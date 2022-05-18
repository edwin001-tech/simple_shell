Creation of a simple shell that emulates the working of existing shell.<br/>


0x16. C - Simple Shell<br/>

0. Betty would be proud<br/>
A beautiful code that passes the Betty checks<br/>

1. Simple shell 0.1<br/>
A UNIX command line interpreter.<br/>

2. Simple shell 0.2<br/>
Handles PATH. Fork must not be called if the command doesn't exist.<br/>

4. Simple shell 0.4<br/>
Implementation of exit that exists in the shell. You don't have to handle any argument to exit<br/>

5. Simple shell 1.0<br/>
Implementation of env built-in that prints current environment.<br/>

6. Simple shell 0.1.1<br/>
Creating our own getline function using static variables. Use a buffer to read many chars at once and call the least possible read system call.<br/>

7. Simple shell 0.2.1<br/>
Simple shell 0.2+ without using strtok.<br/>

8. Simple shell 0.4.1<br/>
Simple shell 0.4+ that handles arguments for built-in exit<br/>
Usage: exit status, where status is an integer used to exit the shell.<br/>

9. setenv, unsetenv<br/>
Implementation of setenv and unsetenv commands<br/>

10. cd<br/>
Implementation of builtin cd command <br/>

11. ;<br/>
Handling command separator ; <br/>

12. && and ||<br/>
Handling && and || shell logical operators<br/>

13. alias<br/>
Handling builtin alias command<br/>

14. Variables<br/>
Handling variables replacement, $? variable and $$ variable<br\>

15. Comments<br/>
Handling comments(#) <br/>

16. File as input<br/>
Usage: simple_shell[filename]<br/>
The shell can take a file as a command line argument. The file should contain all commands that the shell should run before exiting. The file should contain one command per line. In this mode, the shell should not print a prompt and should not read from stdin<br/>
