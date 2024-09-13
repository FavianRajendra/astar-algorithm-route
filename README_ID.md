### Teks Terbaru untuk README.md:

Proyek ini mengimplementasikan algoritma A* menggunakan jarak Manhattan untuk pencarian jalur. Untuk menggunakan kode ini:

1. Gulir ke bagian bawah kode.
2. Modifikasi **state awal** dan **state tujuan** sesuai kebutuhan Anda.
3. Perbarui **graf** dan **koordinat heuristik** jika diperlukan.

Sebagai contoh, ubah baris berikut:

```python
start = 'Magelang'  # State awal
goal = 'Tawangmangu'  # State tujuan
```

Anda juga bisa mengubah graf dan posisi kota pada bagian ini:

```python
graph = {
    'Yogyakarta': [('Klaten', 45), ('Magelang', 46)],
    # ... (perbarui graf sesuai kebutuhan)
}

positions = {
    'Yogyakarta': (0, 0),
    'Klaten': (30, 10),
    # ... (perbarui koordinat sesuai kebutuhan)
}
```
