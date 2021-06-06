# proxy-terminal
## Fungsi
1. Tool ini berfungsi untuk mengaktifkan proxy melalui terminal<br>
2. Jika anda tidak bisa mengupdate package karena harus pakai, tool ini solusinya. <br>
2. Jika anda tidak bisa git push karena harus pakai proxy, tool ini solusinya. <br>
<br>
## Rekomendasi OS
Saya menggunakan ubuntu 20.04 dan sudah coba bekerja dengan baik, silahkan coba di os lain jika mau.

## Cara Instalasi
```bash
./install
```

## Ubah IP Proxy
```bash
sudo nano /bin/proxy
```

Ganti
```bash
var_proxy=http://192.168.49.1:8282/
```

dengan ip proxy kamu


## Fitur
1. Menghidupkan proxy
```bash
sudo proxy
```

2. Mematikan fungsi proxy
```bash
sudo proxy off
```

3. Lihat status proxy
```bash
sudo proxy status
```
