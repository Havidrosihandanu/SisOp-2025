# Pengertian Container dan Virtualisasi
Container adalah sekelompok proses terisolasi yang dibatasi pada system berkas root privasi dan namespace proses. Proses yang termuat berbagai kernel dan layanan dari OS host, tetapi secara default mereka tidak dapat mengakses sumber daya diluar container mereka. Aplikasi yang berjalan dalam container tidak mengetahui status container mereka dan tidak perlu dimodifikasi untuk berjalan dalam container.

Virtualmachine adalah proses pembuatan lapisan abstraksi pada perangkat keras, yang memungkinkan satu computer dibagi  menjadi beberapa computer virtual yang menggunakan Sebagian besar sumber daya perangkat keras dari computer utama.

### Pebedaan : 
### 1. Beban Sumber Daya
- **Container**: Membutuhkan sedikit sumber daya karena berbagi sistem operasi dengan sistem host.
- **Virtual Machine (VM)**: Memerlukan OS sendiri, yang meningkatkan overhead, terutama saat banyak VM berjalan di host yang sama.

### 2. Waktu Memulai
- **Container**: Booting lebih cepat karena tidak membutuhkan sumber daya OS penuh.
- **VM**: Membutuhkan waktu lebih lama dibandingkan container karena harus memuat seluruh sistem operasi.

### 3. Isolasi Keamanan
- **Container**: Keamanan lebih rendah karena berbagi OS dengan sistem host; pelanggaran di satu container bisa mempengaruhi yang lain.
- **VM**: Lebih aman karena terisolasi sepenuhnya dari sistem host dan VM lainnya; pelanggaran di satu VM tidak mempengaruhi yang lain.

### 4. Portabilitas
- **Container**: Lebih portable karena mengemas aplikasi dan semua dependensinya dalam satu unit yang dapat dijalankan di sistem apapun yang mendukung container.
- **VM**: Juga portable tetapi masih tergantung pada perangkat keras yang mendasarinya.


# Perbedaan Multiprogramming dan Multitasking
- Multiprogramming adalah Teknik komputasi yang memungkinkan beberapa program dimuat dan dijalankan secara bersamaan ke dalam memori computer, yang memungkinkan CPU untuk beralih secara cepat , hal ini mengoptiomalkan penggunaan CPU dengan membuatnya tetap telibat dalam pelaksanaan tugas .
- Multitasking adalah eksekusi bersamaan dari beberapa tugas selama periode tertentu untuk meningkatkan responsivitas dan efisiensi pengguna.

# Fungsi OS
- User Interface
  semua sistem operasi sistem memiliki User Interface seperti, GUI, CLI, touch-screen, Batch
- Program Execution
  program harus bisa memuat file, menjalankan, mengeksekusi, secara normal
- Operasi I/O
  menjalankan program mungkin membutuhkan I/O dari user ataupun dari device
- Manipulasi File Sistem
  Program membutuhkan untuk membaca, menulis, membuat dan menghapus gambar, list informasi file dan manajement permission
- Komunikasi
  Proses mungkin membutuhkan pertukaran informasi pada satu komputer atau berbeda komputer
- Deteksi Error
  Sistem operasi terkadang terdapat kesalahan dan membutuhkan pendeteksinya.
- Alokasi Sumber Daya
  Ketika beberapa user atau pekerjaan dijalankan secara bersamaan, maka sumber daya harus dialokasikan di setiapnya
- Protection Security
  Ketika bekerja menggunakan internet membutuhkan keamanan dan sistem operasi menyediakan itu
