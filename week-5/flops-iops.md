# JALANKAN FLOPS-IOPS

## 1. Build Binaries (make)
- Mengkompilasi program benchmarking (`iops32`, `iops64`, `flops32`, `flops64`) dari kode sumber.
- Opsi `-O3` dan `-march=native` digunakan untuk optimasi kecepatan maksimal sesuai arsitektur CPU.

## 2. Pembersihan Build Lama (make clean)
- Menghapus file hasil kompilasi sebelumnya untuk memastikan build baru bersih.

## 3. Instalasi (sudo make install)
- Memasang program ke `/usr/local/bin/` agar bisa dijalankan dari mana saja.

## 4. Menjalankan Benchmark
- `iops64 $(nproc)` → Menguji kecepatan operasi integer 64-bit menggunakan semua core CPU.
- `flops64 $(nproc)` → Menguji kecepatan operasi floating-point 64-bit (presisi ganda).

---

# Hasil Benchmarking & Penjelasan

## 1. Hasil iops64 (Integer Operations Per Second)

![alt text](https://github.com/Havidrosihandanu/SisOp-2025/blob/main/week-5/iops.png?raw=true)

### Analisa:
- CPU memiliki skalabilitas baik (**total IOPS ≈ 4× single-core**), menunjukkan efisiensi multithreading.
- Perbedaan kecil antar-thread (**Tr 1-4**) disebabkan oleh variasi beban CPU background.

## 2. Hasil flops64 (Floating-Point Operations Per Second)

![alt text](https://github.com/Havidrosihandanu/SisOp-2025/blob/main/week-5/flops.png?raw=true)

### Analisa:
- Floating-point umumnya lebih lambat daripada integer (**perbandingan: 5.78 Gigaflops vs 6.05 Gigaiops**).
- Konsistensi antar-thread menunjukkan stabilitas thermal CPU selama pengujian.

---

# Kegunaan Benchmarking

## 1. Evaluasi Kinerja CPU
- Membandingkan kecepatan operasi integer (**IOPS**) vs floating-point (**FLOPS**).
- Mengetahui apakah CPU lebih cocok untuk tugas **general-purpose** (**IOPS tinggi**) atau **komputasi numerik** (**FLOPS tinggi**).

## 2. Optimasi Aplikasi
- Jika aplikasi berat di floating-point (**seperti machine learning**), **FLOPS tinggi lebih kritikal**.
- Untuk **server database/web**, **IOPS tinggi lebih penting**.

## 3. Deteksi Masalah Hardware
- Hasil yang jauh di bawah ekspektasi bisa mengindikasikan:
  - **Thermal throttling** (CPU kepanasan).
  - **Konfigurasi BIOS yang kurang optimal**.

## 4. Benchmarking Multi-Core
- Memverifikasi apakah aplikasi bisa **memanfaatkan semua core CPU** secara efisien.
