## dd-wrt Installation Log 

## Router: `Linksys 1900ACS`
 * Chipset: Marvell 88F6820
 * RAM: 512MB
 * FLASH: 128MB

### dd-wrt Firmware: `Firmware: DD-WRT v3.0-r28788 std (01/13/16)`

### Install [entware-ng](https://github.com/Entware-ng/Entware-ng/wiki/Install-on-DD-WRT) for Arm7:
```
wget -O - http://pkg.entware.net/binaries/armv7/installer/entware_install.sh | sh
```

### Partition (16GB MicroSD): [dd-wrt format guide](https://www.dd-wrt.com/wiki/index.php/How_to_-_Format_and_Partition_External_Storage_Device)
 * Optaware 3GB ext4 (/opt)
 * Swapfile 512MB swap (swap)
 * JFFS 1GB ext4 (/jffs)
 * Data 10.5GB ext4 (/tmp/mnt/sda4)
 - Auto Mounted


### opkg packages installed:
```
opkg install iptraf net-tools-netstat screen wget ruby python iptraf mc htop nano tinc hdparm unzip vim vim-runtime rsync lsof tcpdump tar strace perl patch time lynx p7zip diffutils curl gawk bc bash bzip2 coreutils-sort coreutils-sha1sum file objdump xxd binutils ldd zlib termcap knockd
```
* Packages space used: 75MB (/opt)

### Log:
 * Build: 28788 (14/01/2016)
 * Flash Date: 15/6/2016
