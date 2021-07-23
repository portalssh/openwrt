cara install openwrt xiaomi 4A dan 4C
=============================
- install python3 sesuai compatible dengan windows 32bit/64bit
- install putty dan winscp
- download firmware exploit >> https://github.com/acecilia/OpenWRTInvasion/archive/refs/heads/master.zip
- Input koneksi internet via lan ke port WAN router xiaomi



**1. install requirements >> using CMD**

pip3 install -r requirements.txt

**2. execution_vulnerability >> using CMD**

python remote_command_execution_vulnerability.py

**3. Buka Telnet via Putty**

IP : 192.168.31.1
Port : 23
username : root
root : root

**4. Upload stok firmware ke folder /tmp >> using WINSCP**

silahkan upload stok firmware sesuai dengan series dan type router masing-masing

**5. get /tmp >> using putty**

cd /tmp

**6. sha256sum firmware >> using Putty**

./busybox sha256sum firmware.bin

**7. write firmware >> using Putty** 

mtd -e OS1 -r write firmware.bin OS1

Note :
- edit desripsi "firmware.bin" dalam perintah di atas silahkan sesuaikan dengan nama descripsi stok firmware yang akan di gunakan

