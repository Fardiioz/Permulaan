# Dokumentasi Kode: Transformasi Angka 42

Program ini mendemonstrasikan penggunaan paket fmt untuk mengubah satu nilai integer menjadi beberapa format representasi numerik yang berbeda dalam satu baris keluaran.

## Prasyarat

Mengharuskan kompilator Go standar untuk menjalankan kode.

## Cara Kerja Kode

Program menggunakan fungsi fmt.Printf untuk memformat string. Terdapat tiga jenis penentu format (verb) yang digunakan untuk mengubah angka 42:

1. %d
   Mengubah angka menjadi format desimal berbasis 10. Nilai keluaran adalah 42.

2. %b
   Mengubah angka menjadi format biner berbasis 2. Nilai keluaran adalah 101010.

3. %#X
   Mengubah angka menjadi format heksadesimal berbasis 16 menggunakan huruf kapital, dengan tambahan flag # untuk memunculkan prefiks 0X sebagai penanda sistem bilangan. Nilai keluaran adalah 0X2A.

Karakter khusus \t digunakan untuk memberikan jarak tabulasi horizontal antar nilai, sedangkan \n digunakan untuk berpindah ke baris baru setelah instruksi selesai.

## Baris Kode yang Dinonaktifkan

Terdapat tiga baris kode eksperimen sebelumnya yang dinonaktifkan menggunakan komentar dua garis miring (//):

- Baris pertama menampilkan heksadesimal tanpa prefiks dan menggunakan huruf kecil (2a).
- Baris kedua menampilkan heksadesimal dengan prefiks huruf kecil (0x2a).
- Baris ketiga menampilkan heksadesimal dengan prefiks huruf kecil namun nilai utamanya huruf kapital (0x2A).

## Hasil Keluaran

Saat program dijalankan, baris kode aktif akan menghasilkan teks berikut pada terminal:

42 101010 0X2A
