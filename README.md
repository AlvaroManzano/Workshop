# Workshop

Using bash to run Linux in the Powershell
man du: with man you explain what du does (man means manual)
du: disk usage, allows you to see the size of the files in a directory
du -sh 

patch: create folder
mkdir: create directory
head -3 <file>: allows you to see the first 3 lines of a file
vi <file>: allows you to edit a file, to exit use Esc, then Ctrl+C then :wq

difference ls vs ls -a: ls-a allows you to see more files (the hidden ones) (a means all)

To list files with 5 characters starting with g use: ls g????? or g****** (I think)
To list files starting with g use: ls g*
To do multiple commands in one line use: |
To list files containing a g and as second letter values between a and n, which is a total of 5 letters: ls g[a-n]?????
To list files containing a g and as a second letter NOT values between a and m, which has a total of 5 letters: ls g[!a-m]?????

kill .9 <pid>: pid is process id, kill all processes
htop, atop and btop can be obtained with apt-get (they are more advanced commands)
top allows you to see the task manager
top -u <username>: allows you to see a user's processes

at now +2 minutes: makes the next command to run in 2 minutes
at> echo "Hello" >text.txt
at> <EOT> (I don't know if this needs to be typed)
atq: shows you the commands for the future, for example it would tell you that there is a process that will run in 2 minutes


*****/path.../script.sh: asterisks stand for 1) min 2) hour 3) day 4) month 5) day of the week

There are 2 main text editors: nano and vi. 
(jedit is another alternative, it creates a window for viewing)

Nano: optimal for small files (less than 1 MB)
Control+W: type [.txt] to search for .txt files
Control+a: go up
Control+v: go down (can be b?)
Is it possible to have 2 files named the same? I have seen that yes, but I don't understand how

Vi: more powerful
gedit <filename>: open a file
vimtutor: tutorial
delete lines 5-7
u: undo
:%s <file>: substitution of everything in 

Shell scripts: (.sh)
Create a .txt file: cat> hello.sh
The .sh are not executable, for that you have to use: chmod +x hello.sh
-ls -l hello1.sh: shows the details of the files, in this order:(users group and sudo and then the names) 
!/bin/bash

SSH:
firewall of TU Delft: Bastion
ssh foote: to connect to an ssh named foote
ForwardX11 yes: must be enabled to see the GUI if you want to request it, but this would slow it down a lot, so it is usually disabled.


Translated with www.DeepL.com/Translator (free version)
