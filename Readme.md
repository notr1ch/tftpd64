**Project Description** 

This is a gross hack of [Tftpd64](https://github.com/PJO2/tftpd64) with code to support Mikrotik's bootp (netbooting) which requires that no DHCP options are included in the BOOTP response.

IMPORTANT: Rename your boot file to `vmlinux` for maximum compatibility with the RouterOS bootloader.
