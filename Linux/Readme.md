# Notes

## Linux

 | key word    | Description |
| ----------- | ----------- |
|File System|[<img src="LinuxFileSystem.png" width="250"/>](LinuxFileSystem.png)|
|command Line|Use through shell software. General pattern: command option(s) arguments(s)|
Find commands     |apropos copy      |
| Find more about a command   |  man cp (every Linux has man pages installed)        |
|keyboard shotcuts|Ctrl-A (move to the begining of the line </br> Ctrl-E (Move to the end of the line </br> Ctrl-T (Transpose characters on either side of the cursor (alb->bla) </br> Ctrl-C (Exist a running process </br> Ctrl-Z (Suspend a task (use jobs to see tasks, and fg or bg to manipulate them) </br> Ctrl-D (End of file/end of input) </br> Ctrl-Shift-C (Copy selected text in a terminal) </br> Ctrl-Shift-X (Cut selected text in a terminal) </br> Ctrl-Shift-V (Paste text in a terminal)|
|Root|On every Linux system, there's a superuser account called Root. </br> Root is used to perform administrative tasks (installing software, changing config) </br>Root has the user id of Zero , the only user created during default installation </br> Root has unquestioned access to the system <br> Using root directly is not recommended </br> You can delagate access to its privileges to pther users with <b>sudo</b> (su-do), su and do|
|sudo| the list of users who are allowed to use super user previledges managed in the </br> /etc/sudoers file/ </br> sudo cat /etc/sudoers </br> update with 'visudo' command </br> <b><u>Useful Options for sudo</u></b> </br> sudo -i (Run the target user's shell and switch into their home directory) </br> sudos -s (Run with the invoking user's shell) <br> sudo -l (Show what sudo privileges the user has) </br> sudo -u (Specifiy a user to operate as)|

