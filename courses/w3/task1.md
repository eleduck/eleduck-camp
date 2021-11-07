# Reading

- [Linux Commands Cheat Sheet](https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/)
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)


# Writing - Linux Basics

- How to check all 'unzip' commands previously run by the user you are currently connected to ?  
history | grep "unzip"

- What is the difference between Telnet and SSH?  
Telnet and SSH both are communication protocols which are used to manage remote systems. SSH is secured, 
which requires exchanging of keys opposite of telnet which transmit data in plain text, which means 
telnet is less secure than SSH.

- Which Linux command do you use to check the memory usage?  
■ cat /proc/meminfo ■ free -h ■ top ■ htop

- Count every occurrence of the term “linux” in all the files appearing under the current directory, and its subdirectories, recursively?  
grep -orI linux . | wc -l

- How to check which ports are listening in my Linux Server?  
Use the command ‘netstat –ln’ or ‘ss -ntlp’ or ‘lsof -i’
