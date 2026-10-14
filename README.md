# Pertemuan 07 Fungsi Python

Nama: Angelita Juliana Siahaan
NIM: 2225250112
Kelas: 3B

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
```
python praktik/utilitas_matematika.py
```

## Struktur Fungsi
| Fungsi | Parameter | Nilai return |
|---|---|---|
| luas_persegi_panjang | p, l | luas (p * l) |
| luas_segitiga | a, t | luas (0.5 * a * t) |
| jumlah_n | n | jumlah 1 sampai n |
| faktorial | n | hasil n! |
| tampilkan_menu | tidak ada | tidak ada (hanya menampilkan menu) |

## Hasil Pengujian
| Operasi | Input | Hasil yang diharapkan | Hasil aktual | Status |
|---|---|---|---|---|
| Luas persegi panjang | p=8, l=5 | 40 | 40.0 | Sesuai |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Sesuai |
| Jumlah 1..n | n=10 | 55 | 55 | Sesuai |
| Faktorial | n=5 | 120 | 120 | Sesuai |
| Faktorial | n=0 | 1 | 1 | Sesuai |
| Faktorial | n=-3 | pesan "n harus nonnegatif" | n harus nonnegatif | Sesuai |
| Pilihan menu | 9 | pesan "Pilihan tidak valid" | Pilihan tidak valid | Sesuai |

## Refleksi
Sebelum pakai fungsi, saya harus menulis rumus yang sama berulang-ulang setiap mau menghitung. Setelah dipisah jadi fungsi, rumusnya cukup ditulis satu kali, lalu tinggal dipanggil dengan angka yang berbeda. Program jadi lebih rapi dan lebih mudah dibaca.

Bagian yang paling terasa lebih sederhana adalah program utamanya. Program utama sekarang cuma mengurus menu dan input dari pengguna, sedangkan perhitungannya diserahkan ke fungsi. Jadi kalau ada hasil yang salah, saya bisa langsung cek fungsi yang bersangkutan.

Di tugas ini saya juga jadi paham beda `print` dan `return`. `return` mengirim hasil supaya bisa dipakai lagi, sedangkan `print` hanya menampilkan ke layar. Selain itu, variabel di dalam fungsi hanya berlaku di dalam fungsi itu saja, jadi tidak bentrok dengan variabel di luar.