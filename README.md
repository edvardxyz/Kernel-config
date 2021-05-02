# Kernel-config
experimental USE flag on.
laptop kernel config for Lenovo P14s on gentoo-sources kernel

"p14s" default hostname set
Kernel compression is LZ4 (you need lz4 program installed to boot kernel)
tickless idle
voluntary kernel preemption(desktop)
no initramfs
EFI stub support (EFI is my bootloader)
Built in kernel command points root PARTUUID (change if you use my config)
No SWAP support
No hibernation
only suspend to ram 
KVM supported
wireguard
No BT 
NO I/O scheduler for nvme
802.1d Ethernet bridging
ebtables (nat, mark filter suport)
Ethtool
No wwan support
RF switch support
Dock supported
Filesystems: ext4, NFS, SMB3, VFAT, exFAT
No fuse or NTFS
Most debugging disabled, currently have firmware debug stuff enabled waiting for lenovo bios updates


