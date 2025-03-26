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