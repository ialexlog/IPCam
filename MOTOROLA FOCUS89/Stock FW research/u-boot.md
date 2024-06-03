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
```
APEXIS # help
?       - alias for 'help'
base    - print or set address offset
bootm   - boot application image from memory
cmp     - memory compare
cp      - memory copy
crc32   - checksum calculation
ddr     - ddr training function
echo    - echo string
fatinfo - print information about filesystem
fatload - load binary file from a dos filesystem
fatls   - list files in a directory (default /)
getinfo - print hardware information
go      - start application at address 'addr'
help    - print command description/usage
loadb   - load binary file over serial line (kermit mode)
loady   - load binary file over serial line (ymodem mode)
loop    - infinite loop on address range
md      - memory display
mm      - memory modify (auto-incrementing address)
mmc     - MMC sub system
mmcinfo - mmcinfo <dev num>-- display MMC info
mtest   - simple RAM read/write test
mw      - memory write (fill)
nand    - NAND sub-system
nboot   - boot from NAND device
nm      - memory modify (constant address)
printenv- print environment variables
reset   - Perform RESET of the CPU
run     - run env_var
saveenv - save environment variables to persistent storage
setenv  - set environment variables
sf      - SPI flash sub-system
version - print monitor version
wdt     - wdt 0/1
```
