# Notes

## Linux

 | key word    | Description |
| ----------- | ----------- |
|File System|[<img src="LinuxFileSystem.png" width="250"/>](LinuxFileSystem.png)|
|command Line|Use through shell software. General pattern: command option(s) arguments(s)|
Find commands     |apropos copy      |
| Find more about a command   |  man cp (every Linux has man pages installed)        |
|keyboard shotcuts|Ctrl-A &nbsp; &nbsp;(move to the begining of the line </br> Ctrl-E &nbsp; &nbsp; (Move to the end of the line </br> Ctrl-T &nbsp; &nbsp;(Transpose characters on either side of the cursor (alb->bla) </br> Ctrl-C &nbsp; &nbsp;(Exist a running process </br> Ctrl-Z &nbsp; &nbsp;(Suspend a task (use jobs to see tasks, and fg or bg to manipulate them) </br> Ctrl-D &nbsp; &nbsp;(End of file/end of input) </br> Ctrl-Shift-C &nbsp; &nbsp;(Copy selected text in a terminal) </br> Ctrl-Shift-X &nbsp; &nbsp;(Cut selected text in a terminal) </br> Ctrl-Shift-V &nbsp; &nbsp;(Paste text in a terminal)|
|Root|On every Linux system, there's a superuser account called Root. </br> Root is used to perform administrative tasks (installing software, changing config) </br>Root has the user id of Zero , the only user created during default installation </br> Root has unquestioned access to the system <br> Using root directly is not recommended </br> You can delagate access to its privileges to pther users with <b>sudo</b> (su-do), su and do|
|sudo| the list of users who are allowed to use super user previledges managed in the </br> /etc/sudoers file/ </br> sudo cat /etc/sudoers </br> update with 'visudo' command </br> <b><u>Useful Options for sudo</u></b> </br> sudo -i &nbsp; &nbsp;(Run the target user's shell and switch into their home directory) </br> sudos -s &nbsp; &nbsp;(Run with the invoking user's shell) <br> sudo -l &nbsp; &nbsp;(Show what sudo privileges the user has) </br> sudo -u &nbsp; &nbsp;(Specifiy a user to operate as) </br> <b><u>While Using sudo</u></b> </br> <li> Logs are kept of commands that are run with <b> sudo </b> </br> <li> Each time <b>sudo</b> is used, a five-minute timer is reset <li>Expire the timer with <b>sudo -k</b>|
|Exploring a System||

