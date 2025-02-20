# LAPORAN SISTEM OPERASI  
## PRAKTIKUM KE – 1  
### SISTEM BILANGAN (Desimal, Biner, Oktal, dan Heksadesimal)  

**Nama**: Havid Rosihandanu  
**NRP**: 3124500048  
**Dosen Pengajar**: Dr. Ferry Astika Saputra ST, M.Sc  
**Program Studi**: D3 Teknik Informatika  
**Institusi**: Politeknik Elektronika Negeri Surabaya (PENS)  
**Tahun**: 2024  

---

### 1. Sistem Bilangan  
A. Bilangan biner merupakan bilangan yang berbasis 2.  
B. Bilangan heksadesimal merupakan bilangan yang berbasis 16.  

---

### 2. Konversi Bilangan Desimal ke Biner  
**A. 1234(10) = 10011010010(2)**  
**Cara Konversi**:  
1. 1234 ÷ 2 = 617, sisa 0  
2. 617 ÷ 2 = 308, sisa 1  
3. 308 ÷ 2 = 154, sisa 0  
4. 154 ÷ 2 = 77, sisa 0  
5. 77 ÷ 2 = 38, sisa 1  
6. 38 ÷ 2 = 19, sisa 0  
7. 19 ÷ 2 = 9, sisa 1  
8. 9 ÷ 2 = 4, sisa 1  
9. 4 ÷ 2 = 2, sisa 0  
10. 2 ÷ 2 = 1, sisa 0  
11. 1 ÷ 2 = 0, sisa 1  

**Hasil**: 10011010010(2)  

**B. 5670(10) = 1011000100110(2)**  
**C. 2321(10) = 100100010001(2)**  

---

### 3. Konversi Bilangan Biner ke Desimal  
**A. 10101010(2) = 170(10)**  
**Cara Konversi**:  
1. 1 × 2⁷ = 128  
2. 0 × 2⁶ = 0  
3. 1 × 2⁵ = 32  
4. 0 × 2⁴ = 0  
5. 1 × 2³ = 8  
6. 0 × 2² = 0  
7. 1 × 2¹ = 2  
8. 0 × 2⁰ = 0  

**Hasil**: 128 + 0 + 32 + 0 + 8 + 0 + 2 + 0 = 170(10)  

**B. 01010101(2) = 85(10)**  
**C. 11001100(2) = 204(10)**  
**D. 10011111(2) = 159(10)**  

---

### 4. Konversi Bilangan Biner ke Oktal  
**A. 101011111001(2) = 5371(8)**  
**Cara Konversi**:  
1. Kelompokkan biner menjadi 3 digit: 101 011 111 001  
2. Konversi setiap kelompok ke oktal:  
   - 101 = 5  
   - 011 = 3  
   - 111 = 7  
   - 001 = 1  

**Hasil**: 5371(8)  

**B. 110010110111(2) = 6267(8)**  

---

### 5. Konversi Bilangan Oktal ke Biner  
**A. 2170(8) = 010001111000(2)**  
**Cara Konversi**:  
1. Konversi setiap digit oktal ke biner 3 digit:  
   - 2 = 010  
   - 1 = 001  
   - 7 = 111  
   - 0 = 000  

**Hasil**: 010001111000(2)  

**B. 3571(8) = 011101111001(2)**  

---

### 6. Konversi Bilangan Desimal ke Heksadesimal  
**A. 1780(10) = 06F4(16)**  
**Cara Konversi**:  
1. 1780 ÷ 16 = 111, sisa 4  
2. 111 ÷ 16 = 6, sisa 15 (F)  
3. 6 ÷ 16 = 0, sisa 6  

**Hasil**: 06F4(16)  

**B. 3666(10) = 0E52(16)**  
**C. 5230(10) = 146E(16)**  
**D. 6744(10) = 1A58(16)**  

---

### 7. Konversi Bilangan Heksadesimal ke Desimal  
**A. ABCD(16) = 43981(10)**  
**Cara Konversi**:  
1. A (10) × 16³ = 40960  
2. B (11) × 16² = 2816  
3. C (12) × 16¹ = 192  
4. D (13) × 16⁰ = 13  

**Hasil**: 40960 + 2816 + 192 + 13 = 43981(10)  

**B. 2170(16) = 8560(10)**  
**C. B75F(16) = 46943(10)**  
**D. EBED(16) = 60397(10)**  

---

### 8. Konversi Bilangan Pecahan Desimal ke Biner  
**A. 0,3125(10) = 0,0101(2)**  
**Cara Konversi**:  
1. 0,3125 × 2 = 0,625 → 0  
2. 0,625 × 2 = 1,25 → 1  
3. 0,25 × 2 = 0,5 → 0  
4. 0,5 × 2 = 1,0 → 1  

**Hasil**: 0,0101(2)  

**B. 0,65625(10) = 0,10101(2)**  
**C. 0,34375(10) = 0,01011(2)**  
**D. 0,140625(10) = 0,001001(2)**  

---

### 9. Konversi Bilangan Desimal ke Biner (Pecahan)  
**A. 11,625(10) = 1011,101(2)**  
**Cara Konversi**:  
1. 11 ÷ 2 = 5, sisa 1  
2. 5 ÷ 2 = 2, sisa 1  
3. 2 ÷ 2 = 1, sisa 0  
4. 1 ÷ 2 = 0, sisa 1  

**Bagian Pecahan**:  
1. 0,625 × 2 = 1,25 → 1  
2. 0,25 × 2 = 0,5 → 0  
3. 0,5 × 2 = 1,0 → 1  

**Hasil**: 1011,101(2)  

**B. 0,6875(10) = 0,1011(2)**  
**C. 0,75(10) = 0,11(2)**  
**D. 25,75(10) = 11001,11(2)**  

---

### 10. Konversi Bilangan Desimal ke Heksadesimal (Pecahan)  
**A. 348,654(10) = 15C,A76(16)**  
**Cara Konversi**:  
1. 348 ÷ 16 = 21, sisa 12 (C)  
2. 21 ÷ 16 = 1, sisa 5  
3. 1 ÷ 16 = 0, sisa 1  

**Bagian Pecahan**:  
1. 0,654 × 16 = 10,464 → A  
2. 0,464 × 16 = 7,424 → 7  
3. 0,424 × 16 = 6,784 → 6  

**Hasil**: 15C,A76(16)  

**B. 1784,240(10) = 6F8,3D7(16)**  

---

### 11. Konversi Bilangan ke Desimal  
**A. 010100011,001111101(2) = 163,2421875(10)**  
**Cara Konversi**:  
1. Bagian bulat:  
   - 1 × 2⁷ = 128  
   - 0 × 2⁶ = 0  
   - 1 × 2⁵ = 32  
   - 0 × 2⁴ = 0  
   - 0 × 2³ = 0  
   - 0 × 2² = 0  
   - 1 × 2¹ = 2  
   - 1 × 2⁰ = 1  

**Total**: 128 + 0 + 32 + 0 + 0 + 0 + 2 + 1 = 163  

2. Bagian pecahan:  
   - 0 × 2⁻¹ = 0  
   - 0 × 2⁻² = 0  
   - 1 × 2⁻³ = 0,125  
   - 1 × 2⁻⁴ = 0,0625  
   - 1 × 2⁻⁵ = 0,03125  
   - 1 × 2⁻⁶ = 0,015625  
   - 1 × 2⁻⁷ = 0,0078125  
   - 0 × 2⁻⁸ = 0  
   - 1 × 2⁻⁹ = 0,001953125  

**Total**: 0,2421875  

**Hasil**: 163,2421875(10)  

**B. 654,276(8) = 428,37(10)**  
**C. 4C5,2B8(16) = 1221,1699(10)**  

---

### 12. Konversi Bilangan Biner ke BCD  
**A. 10100110000111(2) = 2987(10)**  
**Cara Konversi**:  
1. Konversi biner ke desimal: 10100110000111(2) = 2987(10)  
2. Konversi desimal ke BCD:  
   - 2 = 0010  
   - 9 = 1001  
   - 8 = 1000  
   - 7 = 0111  

**Hasil**: 0010 1001 1000 0111  

**B. 1010101100011(2) = 1563(10)**  

---

### 13. Konversi BCD ke Biner  
**A. 1987(10) = 1100110000111(2)**  
**Cara Konversi**:  
1. Konversi BCD ke desimal:  
   - 1 = 0001  
   - 9 = 1001  
   - 8 = 1000  
   - 7 = 0111  

2. Konversi desimal ke biner: 1987(10) = 1100110000111(2)  

**B. 2346(10) = 10001101000110(2)**  
**C. 501(10) = 1010000001(2)**  

---

### 14. Konversi Bilangan Biner ke BCO  
**A. 11111101001(2) = 3751(8)**  
**Cara Konversi**:  
1. Kelompokkan biner menjadi 3 digit: 011 111 101 001  
2. Konversi setiap kelompok ke oktal:  
   - 011 = 3  
   - 111 = 7  
   - 101 = 5  
   - 001 = 1  

**Hasil**: 3751(8)  

**B. 101110010100(2) = 5624(8)**  
**C. 1100000010(2) = 1402(8)**  

---

### 15. Konversi Bilangan Biner ke BCH  
**A. 1101111100101110(2) = CF2E(16)**  
**Cara Konversi**:  
1. Kelompokkan biner menjadi 4 digit: 1101 1111 0010 1110  
2. Konversi setiap kelompok ke heksadesimal:  
   - 1101 = D  
   - 1111 = F  
   - 0010 = 2  
   - 1110 = E  

**Hasil**: CF2E(16)  

**B. 110100110000001(2) = 6981(16)**  

---

### 16. Konversi BCH ke Heksadesimal  
**A. F0DE(16) = 1111000011011110(2)**  
**Cara Konversi**:  
1. Konversi setiap digit heksadesimal ke biner 4 digit:  
   - F = 1111  
   - 0 = 0000  
   - D = 1101  
   - E = 1110  

**Hasil**: 1111000011011110(2)  

**B. 1CAB(16) = 0001110010101011(2)**  
**C. 834(16) = 100000110100(2)**  

---

### 17. Menentukan Positif atau Negatif Bilangan Biner  
**A. 01111111 = POSITIF (127)**  
**B. 10000000 = NEGATIF (-128)**  
**C. 01111011 = POSITIF (123)**  

---

### 18. Konversi Bilangan Biner Negatif ke Desimal  
**A. 10001000(2) = -120(10)**  
**Cara Konversi**:  
1. Bit pertama adalah 1, artinya bilangan negatif.  
2. Hitung nilai absolut:  
   - 0001000 = 8  
3. Tambahkan tanda negatif: -128 + 8 = -120  

**Hasil**: -120(10)  

**B. 11110111(2) = -9(10)**  
**C. 10000101(2) = -123(10)**  
**D. 10011100(2) = -100(10)**  

---

### 19. Konversi ASCII Code ke Karakter  
**A. 41(16) = A**  
**B. 5A(16) = Z**  
**C. 24(16) = $**  
**D. 77(16) = w**  

---

### 20. Konversi Karakter ke ASCII Code  
**A. a = 61(16)**  
**B. x = 78(16)**  
**C. m = 6D(16)**  
**D. H = 48(16)**  

---

### 21. Keluaran Keyboard ASCII  
**Tulisan**: PRINT X  
**Keluaran**:  
- P = 50(16)  
- R = 52(16)  
- I = 49(16)  
- N = 4E(16)  
- T = 54(16)  
- X = 58(16)  
