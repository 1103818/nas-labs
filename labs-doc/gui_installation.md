# Installation of GUI
In this lab we will be covering how we can change our interface from a terminal based to a graphical user interface (GUI) of debian machine. Linux comes with many GUI window managers, such as KDE, XFCE, GENOME and the list goes on. In this lab we will primarily focus on `xfce4`. Having a graphical interface will allow users to easily navigate to different directories and use application softwares.

## Commands
- [ ] `apt update`
- [ ] `apt upgrade -y` &rarr; ( upgrade your packages and sync to main repository for upto date packages)
- [ ] `apt install xfce4 xfce4-terminal lightdm firefox-esr ethtool` &rarr; ( required packages for enablig GUI)
- [ ] `/etc/init.d/lightdm start` OR `systemctl start lightdm` &rarr; ( start GUI manager)

These commands will turn your system from CLI (Command-line Interface) to GUI (Graphical User Interface).

[&larr; Go Home](/README.md)