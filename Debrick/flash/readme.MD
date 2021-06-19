cara install openwrt xiaomi 4A dan 4C
=============================

* install requirements

pip3 install -r requirements.txt

* execution_vulnerability

python remote_command_execution_vulnerability.py

* get /tmp

cd /tmp

* sha256sum firmware

./busybox sha256sum firmware.bin

* write firmware 

mtd -e OS1 -r write firmware.bin OS1

Note :
- desripsi "firmware.bin" dalam perintah di atas silahkan sesuaikan dengan nama descripsi stok firmware yang akan di gunakan

