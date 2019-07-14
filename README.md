##### Custom caja actions that can be imported with caja-actions-config-tool.

 * [beesu](https://linux.die.net/man/1/beesu) is used to gain privileges.
 * [caja](https://www.systutorials.com/docs/linux/man/1-caja) is used to open dirs as root.
 * [pluma](https://www.systutorials.com/docs/linux/man/1-pluma) is used to edit files as root.
 * dir /mnt/temp0 (has to exist) is used to mount and unmount ISOs.

##### Command to create required dir and install required packages.

    sudo sh -c 'mkdir -p /mnt/temp0 ; dnf install beesu caja caja-actions pluma'
