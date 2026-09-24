# 🐧 Linux Basics

## Why Linux?
Most servers, hacking tools and security labs run on Linux (Kali, Ubuntu).

## Navigation
- `pwd`: where am I?
- `ls` / `ls -la`: list files (with hidden ones)
- `cd folder`: go into a folder (`cd ..` goes back)

## Files and folders
- `mkdir name`: create a folder
- `touch file.txt`: create an empty file
- `cp a b` / `mv a b`: copy / move or rename
- `rm file`: delete (no recycle bin, careful!)
- `cat file`: show file content

## Permissions
`ls -l` shows something like `-rwxr-xr--`
- r = read, w = write, x = execute
- Three groups: owner, group, others
- `chmod +x script.sh`: make a file executable

## Useful tools
- `grep "word" file`: search inside files
- `man command`: manual for any command
- `sudo`: run as administrator
- `apt update && apt install name`: install software

## Practice
Try these on TryHackMe's "Linux Fundamentals" rooms.
