* Tutorial Flash Router Xiaomi 4A 4C

cara install openwrt xiaomi 4c
=============================

1. install requirements
pip3 install -r requirements.txt

2. execution_vulnerability
python remote_command_execution_vulnerability.py

3. get /tmp
cd /tmp

4. sha256sum firmware
./busybox sha256sum openwrt-19.07.4-ramips-mt76x8-mi-router-4c-squashfs-sysupgrade-MacTavishAO.bin

5. write firmware 
mtd -e OS1 -r write openwrt-19.07.4-ramips-mt76x8-mi-router-4c-squashfs-sysupgrade-MacTavishAO.bin OS1
