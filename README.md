# Proxy-Terminal
## Fungsi
1. Tool ini berfungsi untuk mengaktifkan proxy melalui terminal<br>
2. Jika anda tidak bisa mengupdate package melalui terminal karena harus pakai, tool ini solusinya. <br>
3. Jika anda menggunakan netshare (android) dan ingin menyebarkan wifi yang anda pakai dan ingin pakai komputer anda, maka tool ini solusinya. <br>
4. Jika anda tidak bisa git push karena harus pakai proxy, tool ini solusinya.

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
dengan ip proxy kamu
```

## INFORMASI
```bash
sudo proxy
```

## Fitur
1. Menghidupkan proxy
2. Mematikan fungsi proxy
3. Lihat status proxy
3. Edit IP proxy
