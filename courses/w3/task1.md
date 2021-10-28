# Reading

- [Linux Commands Cheat Sheet](https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/)
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)


# Writing - Linux Basics

- How to check all 'unzip' commands previously run by the user you are currently connected to ?
We can use the "history" command with the grep command to filter the result.
- What is the difference between Telnet and SSH?
The difference between Telnet and SSH is, Telnet sends data in clear text, The SSH uses public-key encryption.
- Which Linux command do you use to check the memory usage?
There are couples of commands that can check the memory usage, free, top, htop, vmstat.
- Count every occurrence of the term “linux” in all the files appearing under the current directory, and its subdirectories, recursively?
Add the option "r" after the grep command, it will scan the files recursively.
- How to check which ports are listening in my Linux Server?
For the system which installed iproute2, we can use ss command with options l to check which ports are listening, usually I use "ntlp" options together, the option n stands for not try to resolve port number to service names, the option t stands for filter the tcp protocol, the option p will print the process id.
