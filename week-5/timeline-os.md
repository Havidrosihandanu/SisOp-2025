# TIMELINE PERKEMBANGAN SISTEM OPERASI

## 1940-an–1950-an: Era Awal Komputasi
- **Sebelum 1940-an**:  
  Komputer dirancang untuk tugas spesifik tanpa program tersimpan.

- **1940-an**:  
  Konsep **stored-program computer** (Alan Turing & John von Neumann) memperkenalkan penyimpanan program dan data dalam memori.

- **1950-an**:
  - Muncul perangkat I/O: pembaca kartu, pencetak, dan pita magnetik
  - Pengembangan **assembler, loader, linker**
  - **Sistem Batch**: Operator menggabungkan pekerjaan serupa (FORTRAN/COBOL)
  - **Atlas** (Univ. Manchester):  
    Sistem batch dengan spooling + manajemen memori berbasis paging

---

## 1960-an: Multiprogramming & Time-Sharing
### Awal 1960-an
- **CTSS** (MIT, 1961):  
  Sistem time-sharing pertama dengan penjadwalan **multilevel feedback queue**
- **XDS-940** (Univ. California):  
  Mendukung paging dan multiprocessing

### Pertengahan 1960-an
- **THE** (Belanda):  
  Sistem batch dengan semaphore + algoritma Banker untuk deadlock
- **RC4000** (Denmark):  
  Kernel modular untuk OS berlapis

### Akhir 1960-an
- **Multics** (MIT/GE/Bell Labs):  
  Memori virtual 18-bit segmentasi + 16-bit offset
- **OS/360** (IBM):  
  OS keluarga untuk mainframe dengan alokasi memori statis (MFT/MVT)

---

## 1970-an: Komersialisasi & Mikrokernel
- **1970**:  
  **TENEX/TOPS-20** (DEC): Time-sharing dengan memori virtual berbasis hardware

- **Akhir 1970-an**:
  - **UNIX** (Bell Labs):  
    Portabilitas tinggi + sistem file hierarkis
  - **Mach** (CMU):  
    Konsep microkernel untuk kompatibilitas BSD

---

## 1980-an: Komputer Personal & GUI
- **1981**:  
  **MS-DOS**: OS populer dengan batas memori 640 KB
- **1984**:  
  **Mac OS** (Apple): GUI pertama untuk rumahan
- **1985**:  
  **Windows 1.0**: Antarmuka grafis untuk PC DOS
- **Akhir 1980-an**:  
  **Mach 3.0**: Mikrokernel modular + dukungan multiprosesor

---

## 1990-an–2000-an: Modernisasi & Open Source
- **1991**:  
  **Linux** (Linus Torvalds): OS open-source berbasis UNIX
- **1995**:  
  **Windows 95**: Integrasi GUI-DOS + protected memory
- **2000-an**:  
  Dominasi Windows XP, macOS, dan Linux

---

## Sistem Perlindungan Khusus (1960–1970-an)
- **Hydra** (CMU):  
  Capability-based security dengan *rights amplification*
- **CAP** (Cambridge):  
  Dua jenis capability (data + software) untuk efisiensi