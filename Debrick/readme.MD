# Tutorial Debrick router xiaomi 4A dan 4C


1. Download "**Tools Debrick**" sesuai type router lalu extract

2. Setting DHCP ethernet LAN di laptop menjadi "**192.168.1.2**"

<div  align="center">    
  <img src="./image/DHCP1.png" width = "300" alt="curl bash" align=center />
</div>

3. Colok Adaptor router sambil tahan tombol reset pada ruter xiaomi sampai LED kedap kedip "**Berwarna Orange**" baru lepas tombol reset

<div  align="center">    
  <img src="./image/4a-LED1.jpg" width = "300" alt="curl bash" align=center />
</div>

4. Colok LAN1 dr router xiaomi ke laptop

5. Buka "**Tools Debrick**" dan pastikan DHCP LAN sudah terdeksi benar menjadi "**192.168.1.2**" kemudian klik "**online**"

<div  align="center">    
  <img src="./image/DHCP2.png" width = "900" alt="curl bash" align=center />
</div>

6. Tunggu proses tftp debrick melakukan download firmware , ini biasa nya butuh waktu sekitar Kurang Lebih "**10 menit**"

7. Proses debrick sukses akan di tandai dengan lampu LED ruter "**Berwarna biru**"

<div  align="center">    
  <img src="./image/4a-LED2.jpg" width = "300" alt="curl bash" align=center />
</div>

7. Jika LED router sudah "**Berwarna biru**" silahkan klik offline "**Tools Debrick**" lalu cabut adaptor ruter dan hidupkan ulang router

Note : 
- Jika hasil akhir proses debrick lampu LED router tidak Berwarna Biru berarti stok firmware debrick tidak cocok  karena beberapa router xiaomi ini default nya ada yang original dan ada juga yang versi bawaan nya sudah menggunakan firmware global international.
- stok firmware debrick yang ada di tools ini sudah di uji terlebih dauhulu baik di versi 4A basic , 4A gigabye , maupun 4C
