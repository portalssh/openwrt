cara install openwrt xiaomi 4c
=============================

* install requirements

pip3 install -r requirements.txt

* execution_vulnerability

python remote_command_execution_vulnerability.py

* get /tmp

cd /tmp

* sha256sum firmware

./busybox sha256sum openwrt-19.07.4-ramips-mt76x8-mi-router-4c-squashfs-sysupgrade-MacTavishAO.bin

* write firmware 

mtd -e OS1 -r write openwrt-19.07.4-ramips-mt76x8-mi-router-4c-squashfs-sysupgrade-MacTavishAO.bin OS1
