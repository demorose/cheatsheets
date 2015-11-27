UNIX
====

Gentle Linux Restart
--------------------
Hold down "Alt" + "Print Screen" and slowly type reisub  

R: Switch the keyboard from raw mode to XLATE mode  
E: Send the SIGTERM signal to all processes except init  
I: Send the SIGKILL signal to all processes except init  
S: Sync all mounted filesystems  
U: Remount all mounted filesystems in read-only mode  
B: Immediately reboot the system, without unmounting partitions or syncing  

Rights
------
| r | w | x |
|---|---|---|
| 4 | 2 | 1 |

Command Line shortcuts
----------------------

!42 -> Cmd 42 in history  
!! -> last command  
!-1 -> last command too  
!$ -> last argument of last command  
!* -> all arguments of last command  
!:2-4 -> arguments 2 to 4 of last command  

Kill SIGNAL
-----------
1) SIGHUP  
3) SIGQUIT  
9) SIGKILL  
15) SIGTERM  

Imagemagick resizing
--------------------
resize image to width 25, keeping aspect ratio  
> convert -geometry 25x src/image1.png out/image1.png  

resize image to height 25, keeping aspect ratio  
> convert -geometry x25 src/image1.png out/image1.png  

cd
--
cd -> Go to home directory  
cd ~ -> Go to home directory  
cd - -> Go to last directory  
