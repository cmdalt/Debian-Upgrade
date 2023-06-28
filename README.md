# Debian-Upgrade
### Backup the system.
### Update existing packages and reboot the Debian 11 system.

Edit the file /etc/apt/sources.list using a text editor and replace each instance of bullseye with bookworm. Next find the update line, replace keyword bullseye-updates with bookworm-updates. Finally, search the security line, replace keyword bullseye-security with bookworm-security.

### Update the packages index on Debian Linux, run:
``` sudo apt update ```
Prepare for the operating system minimal system upgrade, run:

sudo apt upgrade --without-new-pkgs

Finally, update Debian 11 to Debian 12 Bookworm by running:

sudo apt full-upgrade

Reboot the Linux system so that you can boot into Debian 12 Bookworm

Verify that everything is working correctly.

Let us see all commands step by step to upgrade Debian 11 Bullseye to Debian 12 Bookworm safely running in the cloud or bare metal environment.
