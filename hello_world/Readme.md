Disini Saya Melakukan Hello World sebagai test Golang kedua saya
saya mulai mempelajari package itu apa
kalo yang saya dapat dari google package itu adalah cara untuk mengelompokkan dan mengorganisasi file-file sumber .go yang saling terkait dalam satu direktori, bertujuan untuk mempermudah penggunaan kembali kode (reusability), keterbacaan, dan pemeliharaan proyek.
Setiap file Go harus mendeklarasikan package di baris pertama, dan paket main digunakan sebagai titik awal (entry point) aplikasi yang dapat dieksekusi.

Bayangkan sebuah Kerajaan Kode yang sangat besar. Jika semua mainan, baju, dan alat masak dicampur dalam satu ruangan besar, raja akan pusing mencarinya.
Maka, raja membuat aturan bernama Package (Paket).

## Istana Utama (Package Main)

Di pusat kerajaan, ada sebuah istana utama bernama package main.

- Di istana ini, hidup seorang penyihir sakti bernama func main().
- Dialah satu-satunya penyihir yang bisa menghidupkan seluruh kerajaan.
- Tanpa istana main dan penyihir main(), kerajaan ini hanya akan menjadi pajangan dan tidak bisa berjalan.

## Desa-Desa Pembantu (Package Lain)

Di luar istana, raja membuat desa-desa khusus agar kerajaan rapi:

- Desa Matematika: Isinya ramuan untuk hitung-hitungan.
- Desa Teks (fmt): Isinya ahli bahasa yang tugasnya memunculkan tulisan ke layar.

## Mantra Rahasia (Aturan Main)

Untuk menjalankan kerajaan ini, ada dua aturan penting:

1.  Papan Nama Desa (package)
    Setiap rumah di suatu desa harus menuliskan nama desanya di atap paling atas. Kalau rumah itu ada di Desa Matematika, baris pertama suratnya harus tertulis: package matematika.
2.  Surat Undangan (import)
    Jika penyihir di Istana Utama ingin memunculkan tulisan "Hello World", dia tidak bisa melakukannya sendiri. Dia harus mengirim surat undangan (import) ke Desa Teks (fmt).

## Dongeng "Hello World" Anda

Ketika Anda menjalankan kode Hello World, inilah dongeng yang terjadi:

1.  Gerbang package main dibuka.
2.  Istana memanggil ahli bahasa dari desa luar: import "fmt".
3.  Penyihir func main() merapal mantra: fmt.Println("Hello World").
4.  Ahli bahasa dari desa fmt langsung bekerja dan memunculkan tulisan "Hello World" di layar Anda.
