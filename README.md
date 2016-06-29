## ddwrt @ Linksys 1900acs

### DD-WRT Firmware: `Firmware: DD-WRT v3.0-r28788 std (01/13/16)`

### Install [Entware-ng](https://github.com/Entware-ng/Entware-ng/wiki/Install-on-DD-WRT) for Arm7:
```
wget -O - http://pkg.entware.net/binaries/armv7/installer/entware_install.sh | sh
```

### Partition (16GB MicroSD): [DD-Wrt format guide](https://www.dd-wrt.com/wiki/index.php/How_to_-_Format_and_Partition_External_Storage_Device)
 * Optaware 3GB ext4
 * Swapfile 512MB swap
 * JFFS 1GB ext4
 * Data 10.5GB ext4


### opkg packages installed:
```
opkg install iptraf net-tools-netstat screen wget ruby python iptraf mc htop nano tinc hdparm unzip vim vim-runtime rsync lsof tcpdump tar strace perl patch time lynx p7zip diffutils curl gawk bc bash bzip2 coreutils-sort coreutils-sha1sum file objdump xxd binutils ldd zlib termcap
```
* Packages space used: 75MB
