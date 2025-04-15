# Konsep Thread dalam Sistem Operasi
Thread merupakan unit eksekusi terkecil yang dapat dijadwalkan oleh sistem operasi. Thread adalah bagian dari program yang dapat berjalan mandiri. Terdapat dua jenis thread:

## Single Thread dan Multithread
**Single Thread** merupakan model eksekusi dimana sebuah proses hanya menjalankan **satu alur instruksi** dalam satu waktu. Setiap tugas dijalankan secara berurutan (sequential). Jika satu tugas memerlukan waktu lama (misalnya operasi I/O), seluruh sistem harus menunggu hingga tugas tersebut selesai. Contoh: Aplikasi kalkulator sederhana yang hanya bisa melakukan satu perhitungan dalam satu waktu.<br>

**Multi thread** memungkinkan sebuah proses menjalankan **beberapa thread sekaligus**, baik melalui:
- **Time-slicing** pada CPU single-core (bergantian cepat)
- **Paralelisme** pada CPU multi-core (benar-benar bersamaan)
Setiap thread memiliki **stack** sendiri tetapi berbagi **heap memory** dan resource proses induk. <br>

![alt text](https://github.com/Havidrosihandanu/SisOp-2025/blob/main/gambar-konsep-thread.webp?raw=true) <br>

Contoh: Aplikasi pengolah kata modern yang memiliki thread terpisah untuk:
- Menerima input keyboard
- Auto-save dokumen
- Pemeriksaan ejaan real-time


