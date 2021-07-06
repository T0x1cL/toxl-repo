toxl-repo
---
Custom Arch Linux pacman repository. Includes a few files.
Updates come whenever I feel like it.

To add to your `/etc/pacman.conf`, add (at the end):
```
[toxl-repo]
SigLevel = Never
Server = https://github.com/T0x1cL/toxl-repo/raw/master/$arch/
```
