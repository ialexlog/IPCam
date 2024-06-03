```
~ # /3rd/usr/local/bin/app/aes_decrypt_full
/3rd/usr/local/bin/app/aes_decrypt_full [Firmware package - ext: .fw.pkg]
/3rd/usr/local/bin/app/aes_decrypt_full [Firmware package - ext: .txt] [Encrypt file - ext: .fw.pkg]
```


```
~ # /3rd/usr/local/bin/app/aes_decrypt_full /mnt/cache/0599-03.30.01.fw.pkg
Run echo /tmp/0599-03.30.01.tar.gz  > /tmp/fw_package   return  0
Output file name: /tmp/0599-03.30.01.tar.gz
```
```
/3rd/usr/local/bin/app
# LD_LIBRARY_PATH=/3rd/usr/local/lib/ ./sig_SHA512_check /mnt/cache/0599-03.30.01.fw.pkg /mnt/cache/0599-03.30.01.sha512
Signature Matched
```
