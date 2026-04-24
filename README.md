Deskripsi
---------
Proyek sederhana untuk mentransfer file melalui koneksi TCP antara server dan client menggunakan skrip Python.

Persyaratan
-----------
- Python 3.8 atau lebih baru.

Cara menjalankan
----------------
1. Jalankan server pada mesin/port tujuan:

```bash
python server.py
```

2. Dari mesin client, jalankan client untuk mengirim file ke server (sesuaikan nama file dan alamat/port):

```bash
python client\client.py --host 127.0.0.1 --port 9000 --file path\to\file.txt
```

Membuat file contoh
-------------------
Gunakan `client/generate.py` untuk membuat file test (jika tersedia):

```bash
python client\generate.py --output example.bin --size 1048576
```

Catatan
------
- Pastikan port yang digunakan terbuka dan tidak diblokir firewall.
