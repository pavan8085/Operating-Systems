Project Team members:

1)Pavan Manjunath   109916057
2)Tabish Ahmad      109915386
3)Shashank Jain     109956091


FINAL PROJECT: Preemptive OS - 70 pts
=====================================
1) Maximum number of file descriptors supported are 32.
2) Each process has the initial current working directory as /.
3) Initial environment variable:
    "HOME=/bin",
    "PATH=/bin",
    "OS=TheBestOSEver",
    "PS1=sbush:",
    "PWD=/",
4) How to run background process:
    From shell:
        - You can launch any command in background like: $ cmd &
        Note:
         - There must be a space between cmd and "&"
         - We will be ignoring all all arguments after & (including &)
    From code:
        - Call execve with argument as "&"
        - We will be ignoring all all arguments after & (including &)
5) Kill command format:
   $ Kill pid
   Note: There is no -9 since we are not supporting signals
   
6) CAT:
   - cat when run without any parameter reads from stdin
   - if you run it without any argument, then there is no way
    to come out of cat since we do not support CTRL+C
