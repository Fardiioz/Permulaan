# Dokumentasi Kode: Iterasi dan Transformasi Massal Nilai Integer

Program ini mendemonstrasikan penggunaan struktur kontrol perulangan (looping) untuk memformat dan menampilkan rentang nilai integer besar ke dalam beberapa sistem bilangan secara massal.

## Prasyarat

Mengharuskan kompilator Go standar untuk menjalankan kode.

## Cara Kerja Kode

Program memanfaatkan blok perulangan `for` untuk mengontrol jalannya eksekusi kode sebanyak 100 kali:

1. Inisialisasi: Variabel counter `i` diberi nilai awal 1.000.000.
2. Kondisi: Perulangan akan terus dieksekusi selama nilai `i` kurang dari 1.000.100.
3. Post-statement: Nilai `i` akan bertambah 1 (`i++`) setiap kali satu siklus perulangan selesai.

Di dalam setiap siklus perulangan, fungsi `fmt.Printf` akan memformat nilai `i` saat itu ke dalam tiga format:

- %d: Mengubah nilai menjadi format desimal (berbasis 10).
- %b: Mengubah nilai menjadi format biner (berbasis 2).
- %x: Mengubah nilai menjadi format heksadesimal (berbasis 16) dengan huruf kecil dan tanpa prefiks 0x.

Karakter khusus `\t` memisahkan setiap kolom representasi, dan `\n` memastikan setiap baris angka dicetak pada baris baru di terminal.

## Hasil Keluaran

Saat program dijalankan, baris kode akan menghasilkan 100 baris teks pada terminal, dimulai dari:

1000000 11110100001001000000 f4240

Dan diakhiri pada nilai sebelum batas atas:

1000099 11110100001010100011 f42a3
