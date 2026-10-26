# Some testing of the autopush implementation

<!-- instructor:start -->
```bash
Script started on 2026-10-26 18:10:37+01:00 [TERM="tmux-256color" TTY="/dev/pts/5" COLUMNS="85" LINES="44"]
nelle@debian:~/demo$ asdf

bash: asdf: command not found
nelle@debian:~/demo$ ll

bash: ll: command not found
nelle@debian:~/demo$ ls

nelle@debian:~/demo$ ll

bash: ll: command not found
nelle@debian:~/demo$ ls

nelle@debian:~/demo$ ls

nelle@debian:~/demo$ pwd

/home/nelle/demo
nelle@debian:~/demo$ reset

c
nelle@debian:~/demo$ ls -Fahlst

total 8.0K
4.0K drwx------ 18 nelle nelle 4.0K Oct 26 18:18 ../
4.0K drwxrwxr-x  2 nelle nelle 4.0K Oct 26 18:10 ./
nelle@debian:~/demo$ ls -Fahlstr

total 8.0K
4.0K drwxrwxr-x  2 nelle nelle 4.0K Oct 26 18:10 ./
4.0K drwx------ 18 nelle nelle 4.0K Oct 26 18:18 ../
nelle@debian:~/demo$
```
<!-- instructor:end -->