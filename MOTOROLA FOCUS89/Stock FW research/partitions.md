```
SPI Nand(cs 0) ID: 0x9b 0x12
Nand: ATO ATO25D1GA
Nand(Auto): Block:128KB Page:2KB OOB:64B ECC:4bit/512 Chip:128MB*1
12 cmdlinepart partitions found on MTD device hinand
12 cmdlinepart partitions found on MTD device hinand
Creating 12 MTD partitions on "hinand":
0x000000000000-0x000000100000 : "uboot"
0x000000100000-0x000000300000 : "config"
0x000000300000-0x000000600000 : "kernel0"
0x000000600000-0x000000d00000 : "rootfs0"
0x000000d00000-0x000001e00000 : "app0"
0x000001e00000-0x000002f00000 : "app1"
0x000002f00000-0x000003200000 : "kernel1"
0x000003200000-0x000003900000 : "rootfs1"
0x000003900000-0x000004900000 : "3rd0"
0x000004900000-0x000005900000 : "3rd1"
0x000005900000-0x000005c00000 : "hconfig"
0x000005c00000-0x000008000000 : "cache"
```

```
mount
rootfs on / type rootfs (rw)
/dev/root on / type yaffs2 (rw,relatime)
proc on /proc type proc (rw,relatime)
sysfs on /sys type sysfs (rw,relatime)
tmpfs on /dev type tmpfs (rw,relatime)
devpts on /dev/pts type devpts (rw,relatime,mode=600)
none on /tmp type tmpfs (rw,relatime)
none on /var type tmpfs (rw,relatime)
/dev/mtdblock1 on /mnt/mtd type yaffs2 (rw,relatime)        "config"
none on /etc type tmpfs (rw,relatime)
/dev/mtdblock4 on /app type yaffs2 (rw,relatime)            "app0"
/dev/mtdblock9 on /3rd type yaffs2 (rw,relatime)            "3rd1"
/dev/mtdblock10 on /mnt/hconfig type yaffs2 (rw,relatime)   "hconfig"
/dev/mtdblock11 on /mnt/cache type yaffs2 (rw,relatime)     "cache"
```
