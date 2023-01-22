# Minishell

The existence of shells is linked to the very existence of IT. At the time, all coders agreed
that communicating with a computer using aligned 1/0 switches was seriously
irritating. It was only logical that they came up with the idea to communicate with
a computer using interactive lines of commands in a language somewhat close
to english.The objective of this project is to create a simple shell using c.

#Allowed functions and some my used fonctions:
    readline, rl_clear_history, rl_on_new_line,
    rl_replace_line, rl_redisplay, add_history,
    printf, malloc, free, write, access, open, read,
    close, fork, wait, waitpid, wait3, wait4, signal,
    sigaction, sigemptyset, sigaddset, kill, exit,
    getcwd, chdir, stat, lstat, fstat, unlink, execve,
    dup, dup2, pipe, opendir, readdir, closedir,
    strerror, perror, isatty, ttyname, ttyslot, ioctl,
    getenv, tcsetattr, tcgetattr, tgetent, tgetflag,
    tgetnum, tgetstr, tgoto, tputs

##  The Project consist of two parts :
**Parsing**

        1. readline
        2. pipes
        3. Command and arguments
        4. Protections
        5. The <,>, >> redirects
        6. Environment variables
        7. The separations
        8. history
**The execution**

        1. Redirects
        2. Env, export, unset, echo, cd
        3. Exit and $?
        4. Pipes / signals / process links 

## Installation

Use the Makefile
```bash
Make
```

## Usage

```bash
./minishell

## Resources
https://cs61.seas.harvard.edu/site/2019/Section7/ <br>
https://qastack.fr/unix/159513/what-are-the-shells-control-and-redirection-operators <br>
https://theswissbay.ch/pdf/Gentoomen%20Library/Programming/Bash/O%27Reilly%20bash%20CookBook.pdf <br>
https://ast-viewer.datacamp.com/editor?code=echo%20%22hello%22%20%20%22cjnjnc%22%20%3E%20file1%20%3E%20fileb&start=NA&grammar=shell <br>
https://bottlecaps.de/rr/ui <br>
https://codes-sources.commentcamarche.net/forum/affich-10047436-developper-un-shell-de-base <br>
https://www.gnu.org/software/bash/manual/html_node/index.html#SEC_Contents <br>
https://dev.to/tanishqsingla/termios-564j <br>
https://zestedesavoir.com/tutoriels/1733/termcap-et-terminfo/#1-le-terminal-1
https://viewsourcecode.org/snaptoken/kilo/03.rawInp
