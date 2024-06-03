```
APEXIS # printenv
bootargs=mem=40M console=ttyAMA0,115200 root=/dev/mtdblock3 rootfstype=yaffs2 mtdparts=hinand:1M(uboot),2M(config),3M(kernel0),7M(rootfs0),17M(app0),17M(app1),3M(kernel1),7M(rootfs1),16M(3rd0),16M(3rd1),3M(hconfig),36M(cache)
bootdelay=1
baudrate=115200
kernel0=0x300000
kernel1=0x2f00000
app0=/dev/mtdblock4
app1=/dev/mtdblock5
3rd0=/dev/mtdblock8
3rd1=/dev/mtdblock9
app=/dev/mtdblock4
3rd=/dev/mtdblock8
cur_app=0
cur_3rd=0
mem=40M
console=ttyAMA0,115200
rootfstype=yaffs2
mtdparts=hinand:1M(uboot),2M(config),3M(kernel0),7M(rootfs0),17M(app0),17M(app1),3M(kernel1),7M(rootfs1),16M(3rd0),16M(3rd1),3M(hconfig),36M(cache)
flash_type=nand
cfgfs=/dev/mtdblock1
stdin=serial
stdout=serial
stderr=serial
verify=n
cur_kernel=0
kernel=0x300000
bootcmd=nand read 0x82000000 0x300000 0x190000;bootm 0x82000000
last_boot_status=1

Environment size: 823/131068 bytes
```
