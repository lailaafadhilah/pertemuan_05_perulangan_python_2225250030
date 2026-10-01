# Pertemuan 05 Perulangan Python

Nama: Laila Fadhilah
NIM: 2225250030
Kelas: 3A

## Tujuan

Menggunakan perulangan for dan while untuk menyelesaikan masalah iteratif, melakukan validasi input, menggunakan seleksi di dalam perulangan, serta melakukan tracing terhadap perubahan variabel.

## Struktur Folder

```text
pertemua
n-05-perulangan-2225250030/
│
├── README.md
├── .gitignore
│
├── latihan/
│   ├── 01_tabel_perkalian.py
│   ├── 02_jumlah_bilangan.py
│   ├── 03_validasi_input.py
│   └── 04_hitung_genap.py
│
└── kuis/
    └── kuis2_deret_aritmetika.py
```

## Cara Menjalankan

Program dijalankan melalui terminal VS Code.

Contoh:

```text
bash
python latihan/01_tabel_perkalian.py
```

```text
bash
python latihan/02_jumlah_bilangan.py
```

```text
bash
python latihan/03_validasi_input.py
```

```text
bash
python latihan/04_hitung_genap.py
```

```text
bash
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

1. Menampilkan judul program Deret Aritmetika.
2. Membaca suku pertama `a`.
3. Membaca beda `d`.
4. Membaca banyak suku `n`.
5. Memvalidasi nilai `n` menggunakan perulangan while.
6. Jika `n` kurang dari atau sama dengan 0, program meminta input kembali.
7. Menginisialisasi `total` dengan nilai 0.
8. Menggunakan perulangan for sebanyak `n` kali.
9. Menghitung nilai setiap suku berdasarkan suku pertama, nomor iterasi, dan beda.
10. Menambahkan setiap suku ke dalam `total`.
11. Menampilkan nomor suku dan nilai suku.
12. Setelah perulangan selesai, menampilkan jumlah seluruh suku dengan dua angka di belakang koma.

## Hasil Pengujian

| Program         | Input             | Hasil                           | Status   |
| --------------- | ----------------- | ------------------------------- | -------- |
| Tabel Perkalian | n = 4             | 10 baris perkalian              | Berhasil |
| Tabel Perkalian | n = -3            | 10 baris perkalian              | Berhasil |
| Jumlah Bilangan | n = 1             | 1                               | Berhasil |
| Jumlah Bilangan | n = 5             | 15                              | Berhasil |
| Jumlah Bilangan | n = 10            | 55                              | Berhasil |
| Validasi Input  | 120, -5, 75       | Menolak 120 dan -5, menerima 75 | Berhasil |
| Hitung Genap    | n = 5             | 2                               | Berhasil |
| Hitung Genap    | n = 10            | 5                               | Berhasil |
| Kuis 2          | a=2, d=3, n=5     | Jumlah = 40.00                  | Berhasil |
| Kuis 2          | a=10, d=-2, n=4   | Jumlah = 28.00                  | Berhasil |
| Kuis 2          | a=1.5, d=0.5, n=3 | Jumlah = 6.00                   | Berhasil |

## Refleksi

Pada pengerjaan Pertemuan 05, saya memahami bahwa perulangan digunakan untuk menjalankan proses yang sama secara berulang. Saya menggunakan for ketika jumlah iterasi sudah diketahui, sedangkan while digunakan ketika proses bergantung pada suatu kondisi.

Salah satu hal yang perlu diperhatikan adalah pembaruan variabel pada while. Jika variabel kontrol tidak diperbarui menuju kondisi False, perulangan dapat menjadi infinite loop. Selain itu, variabel akumulator seperti total harus diinisialisasi sebelum perulangan agar nilainya tidak terus direset pada setiap iterasi.

Pada Kuis 2, saya menggunakan while untuk memvalidasi banyak suku agar selalu berupa bilangan positif. Setelah nilai n valid, saya menggunakan for karena jumlah iterasi sudah diketahui, yaitu sebanyak n kali.

## Sumber dan Bantuan

Materi utama: Bahan Ajar Algoritma dan Pemrograman Pertemuan 05, Perulangan for dan while dalam Python di VS Code dan Pengumpulan melalui GitHub, Program Studi S1 Pendidikan Matematika FKIP Untirta, Tahun Ajaran 2026/2027 Ganjil.

Saya menggunakan materi perkuliahan dan dokumentasi yang dirujuk dalam bahan ajar sebagai sumber pembelajaran.
