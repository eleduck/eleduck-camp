# Reading

- [Linux Commands Cheat Sheet](https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/)
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)


# Writing - Linux Basics

- How to check all 'unzip' commands previously run by the user you are currently connected to ?
  `history | grep unzip`

- What is the difference between Telnet and SSH?
  Telnet is clear code transmission, using port 23. SSH is secret code transmission, using port 22. SSH is more secure than Telnet.

- Which Linux command do you use to check the memory usage?
  `free -h`

- Count every occurrence of the term “linux” in all the files appearing under the current directory, and its subdirectories, recursively?
  `grep linux ./ -R | wc -l`

- How to check which ports are listening in my Linux Server?
  `netstat -npl`
