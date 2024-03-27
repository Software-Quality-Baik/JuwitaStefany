# Deskripsi Pengujian

| Objek Pengujian | Hasil      | Lampiran                                                      |
| --------------- | ---------- | ------------------------------------------------------------- |
| Cek Diabetes (Halaman Login > Alert Login Success > Halaman Index > Halaman Cek Kesehatan > Halaman Cek Diabetes) | Success ✔ | [dokumentasi](<./Selenium_Testing Dokumentasi_1214026_JuwitaStefany.pdf>) |

# Panduan 

Ini merupakan kode Python untuk melakukan pengujian otomatis pada aplikasi web menggunakan Selenium.

## Persyaratan

ATTENTION! Sebelum memakai kode yang disediakan, kamu harus pastikan untuk memenuhi persyaratan berikut:

- Python 3.x terpasang di sistem Anda.
- WebDriver yang sesuai untuk browser yang ingin kamu gunakan (misalnya ChromeDriver untuk Google Chrome).

## Instalasi

1. Clone repositori ini ke dalam sistem Kamu:

   ```
   git clone <link-repositori>
   ```

2. Instal Selenium dengan mengeksekusi perintah berikut di terminal:

   ```
   pip install selenium
   ```

3. Pastikan WebDriver telah diunduh dan tersedia di PATH sistem Anda.

## Penggunaan

1. Buka file `delsentimen.py` dan lakukan modifikasi sesuai dengan kebutuhan Anda, seperti URL halaman web yang ingin diuji, informasi login, dll. Sesuaikan path lokasi file sebelumkan menjalankan pengujian.

2. Jalankan pengujian dengan menjalankan perintah berikut di terminal:

   ```
   python cekDiabetes.py
   ```

3. Tunggu hingga pengujian selesai dieksekusi. Hasil pengujian akan ditampilkan di terminal.