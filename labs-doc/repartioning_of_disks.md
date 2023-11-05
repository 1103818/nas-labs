# Repartioning of Disks
We are going to repartion the disks to use that space which we left un-alloted during installation of Debian.

## Requirements

- Installed version of Debian in your virtualbox or physical machine.
- Terminal

## Commands

- [ ] `df -h` &rarr; ( `df` reports how much disk space your filesystem is using and `-h` option is used to view in human-readable format).
- [ ] `fdisk /dev/sda` &rarr; ( `fdisk` is a command-line utility to create and manipulate disk partitions.)  
    - [ ] `m` &rarr; (enter `m` for manual of commands).
    - [ ] `p` &rarr; (enter `p` for printing the available partitions).
    - [ ] `d` &rarr; (enter `d` for deleting a partition).
    - [ ] `n` &rarr; (enter `n` for creating a new partition).
    - [ ] `w` &rarr; (enter `w` to write changes to a partition).
- [ ] `reboot` &rarr; (restart your machine).
- [x] `resize2fs /dev/sda2` &rarr; (To confirm new changes in partitioning).

These commands may vary based on your partitions names and Debian version. So kindly learn about their usages than only pasting these commands on your shell.

[&larr; Go Home](/README.md)