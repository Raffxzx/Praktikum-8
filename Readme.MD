# Tugas Praktikum

## Deskripsi

Tugas praktikum ini bertujuan untuk membuat program sederhana menggunakan class dan metode dalam Python.

## Diagram class

![](lib/img/mahasiswa.png)

## Flowchart

![](lib/img/class.png)

## Fitur

- `tambah(nama)`: Menambahkan data mahasiswa baru ke dalam daftar.
- `tampilkan()`: Menampilkan daftar mahasiswa yang telah ditambahkan.
- `hapus(nama)`: Menghapus data mahasiswa berdasarkan nama.
- `ubah(nama_lama, nama_baru)`: Mengubah data mahasiswa dari nama lama menjadi nama baru.

## Penggunaan

1. Buat objek `Mahasiswa`.
2. Panggil metode-metode yang tersedia, seperti `tambah()`, `tampilkan()`, `hapus()`, dan `ubah()`.
3. Ikuti alur pada flowchart untuk memahami operasi yang tersedia.

Contoh penggunaan:

```python
mahasiswa = Mahasiswa()
mahasiswa.tambah("Jamal AKA")
mahasiswa.tambah("King Ruckie")
mahasiswa.tampilkan()
mahasiswa.hapus("King Ruckie")
mahasiswa.ubah("Jamal AKA", "Ngab Prims")
mahasiswa.tampilkan()
```

