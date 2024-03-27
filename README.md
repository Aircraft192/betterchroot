# Better chroot
A bash script that automatically mounts /proc, /sys and /dev to the chroot directory. This makes most commands in the chroot shell usable again.
## Features
- Mounts /proc, /sys and /dev to the chroot directory
- Automatically mounts devices
- Checks if the chroot directory is valid
## Syntax
```bash
bchroot <directory|device> [mountpoint]
```