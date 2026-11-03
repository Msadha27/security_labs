# Bandit notes

## Level 0 → 1
- Connected with `ssh bandit0@bandit.labs.overthewire.org -p 2220`.
  This opens a secure shell on the game server (port 2220).
- `ls` lists the files in the current folder. I saw a file named `readme`.
- `cat readme` prints the file's contents to the screen. It holds the
  password for the next level.

Passwords are not saved here, in line with OverTheWire's rules.

## Level 1

-connected with 'ssh bandit1@bandit.labs.overwrite.org -p 2220'.
-'ls' to list the files in current folder . I saw '-'.
-'cat -' to display the password of level2 . But the result didn't appear because a lone dash means 'read from the keyboard' to cat. Press Ctrl+C.
- 'cat ./-'. The ./ tells cat that - is a file path in this folder, not the keyboard.
