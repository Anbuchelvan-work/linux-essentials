# Linux Basics — Day 1

## Essential Commands
- pwd  → print current working directory
- ls   → list files
- cd   → change directory
- mkdir → create a folder
- touch → create a file

## File Operations
- cp → copy files
- mv → move/rename files
- rm → remove files
- cat → view file content

## Notes
- Linux commands are case-sensitive.
- Everything in Linux is a file.
- Use `man <command>` for manual pages.

## File Permissions

Linux permissions have 3 groups:
- User (owner)
- Group
- Others

Each group has 3 permissions:
- r → read (4)
- w → write (2)
- x → execute (1)

### Check permissions
ls -l

### Change permissions
chmod 755 file
chmod u+x file
chmod g-w file
chmod o-r file

### Change owner
sudo chown user file
sudo chown user:group file

### Notes
- 755 = rwxr-xr-x
- 644 = rw-r--r--
- Use sudo for admin operations
