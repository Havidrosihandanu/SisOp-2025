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
**A. 1234₁₀ = 10011010010₂**  
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

**Hasil**: 10011010010₂  

**B. 5670₁₀ = 1011000100110₂**  
**C. 2321₁₀ = 100100010001₂**  

---

### 3. Konversi Bilangan Biner ke Desimal  
**A. 10101010₂ = 170₁₀**  
**Cara Konversi**:  
1. 1 × 2⁷ = 128  
2. 0 × 2⁶ = 0  
3. 1 × 2⁵ = 32  
4. 0 × 2⁴ = 0  
5. 1 × 2³ = 8  
6. 0 × 2² = 0  
7. 1 × 2¹ = 2  
8. 0 × 2⁰ = 0  

**Hasil**: 128 + 0 + 32 + 0 + 8 + 0 + 2 + 0 = 170₁₀  

**B. 01010101₂ = 85₁₀**  
**C. 11001100₂ = 204₁₀**  
**D. 10011111₂ = 159₁₀**  

---

### 4. Konversi Bilangan Biner ke Oktal  
**A. 101011111001₂ = 5371₈**  
**Cara Konversi**:  
1. Kelompokkan biner menjadi 3 digit: 101 011 111 001  
2. Konversi setiap kelompok ke oktal:  
   - 101 = 5  
   - 011 = 3  
   - 111 = 7  
   - 001 = 1  

**Hasil**: 5371₈  

**B. 110010110111₂ = 6267₈**  

---

### 5. Konversi Bilangan Oktal ke Biner  
**A. 2170₈ = 010001111000₂**  
**Cara Konversi**:  
1. Konversi setiap digit oktal ke biner 3 digit:  
   - 2 = 010  
   - 1 = 001  
   - 7 = 111  
   - 0 = 000  

**Hasil**: 010001111000₂  

**B. 3571₈ = 011101111001₂**  

---

### 6. Konversi Bilangan Desimal ke Heksadesimal  
**A. 1780₁₀ = 06F4₁₆**  
**Cara Konversi**:  
1. 1780 ÷ 16 = 111, sisa 4  
2. 111 ÷ 16 = 6, sisa 15 (F)  
3. 6 ÷ 16 = 0, sisa 6  

**Hasil**: 06F4₁₆  

**B. 3666₁₀ = 0E52₁₆**  
**C. 5230₁₀ = 146E₁₆**  
**D. 6744₁₀ = 1A58₁₆**  

---

### 7. Konversi Bilangan Heksadesimal ke Desimal  
**A. ABCD₁₆ = 43981₁₀**  
**Cara Konversi**:  
1. A (10) × 16³ = 40960  
2. B (11) × 16² = 2816  
3. C (12) × 16¹ = 192  
4. D (13) × 16⁰ = 13  

**Hasil**: 40960 + 2816 + 192 + 13 = 43981₁₀  

**B. 2170₁₆ = 8560₁₀**  
**C. B75F₁₆ = 46943₁₀**  
**D. EBED₁₆ = 60397₁₀**  

---

### 8. Konversi Bilangan Pecahan Desimal ke Biner  
**A. 0,3125₁₀ = 0,0101₂**  
**Cara Konversi**:  
1. 0,3125 × 2 = 0,625 → 0  
2. 0,625 × 2 = 1,25 → 1  
3. 0,25 × 2 = 0,5 → 0  
4. 0,5 × 2 = 1,0 → 1  

**Hasil**: 0,0101₂  

**B. 0,65625₁₀ = 0,10101₂**  
**C. 0,34375₁₀ = 0,01011₂**  
**D. 0,140625₁₀ = 0,001001₂**  

---

### 9. Konversi Bilangan Desimal ke Biner (Pecahan)  
**A. 11,625₁₀ = 1011,101₂**  
**Cara Konversi**:  
1. 11 ÷ 2 = 5, sisa 1  
2. 5 ÷ 2 = 2, sisa 1  
3. 2 ÷ 2 = 1, sisa 0  
4. 1 ÷ 2 = 0, sisa 1  

**Bagian Pecahan**:  
1. 0,625 × 2 = 1,25 → 1  
2. 0,25 × 2 = 0,5 → 0  
3. 0,5 × 2 = 1,0 → 1  

**Hasil**: 1011,101₂  

**B. 0,6875₁₀ = 0,1011₂**  
**C. 0,75₁₀ = 0,11₂**  
**D. 25,75₁₀ = 11001,11₂**  

---

### 10. Konversi Bilangan Desimal ke Heksadesimal (Pecahan)  
**A. 348,654₁₀ = 15C,A76₁₆**  
**Cara Konversi**:  
1. 348 ÷ 16 = 21, sisa 12 (C)  
2. 21 ÷ 16 = 1, sisa 5  
3. 1 ÷ 16 = 0, sisa 1  

**Bagian Pecahan**:  
1. 0,654 × 16 = 10,464 → A  
2. 0,464 × 16 = 7,424 → 7  
3. 0,424 × 16 = 6,784 → 6  

**Hasil**: 15C,A76₁₆  

**B. 1784,240₁₀ = 6F8,3D7₁₆**  

---

### 11. Konversi Bilangan ke Desimal  
**A. 010100011,001111101₂ = 163,2421875₁₀**  
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

**Hasil**: 163,2421875₁₀  

**B. 654,276₈ = 428,37₁₀**  
**C. 4C5,2B8₁₆ = 1221,1699₁₀**  

---

### 12. Konversi Bilangan Biner ke BCD  
**A. 10100110000111₂ = 2987₁₀**  
**Cara Konversi**:  
1. Konversi biner ke desimal: 10100110000111₂ = 2987₁₀  
2. Konversi desimal ke BCD:  
   - 2 = 0010  
   - 9 = 1001  
   - 8 = 1000  
   - 7 = 0111  

**Hasil**: 0010 1001 1000 0111  

**B. 1010101100011₂ = 1563₁₀**  

---

### 13. Konversi BCD ke Biner  
**A. 1987₁₀ = 1100110000111₂**  
**Cara Konversi**:  
1. Konversi BCD ke desimal:  
   - 1 = 0001  
   - 9 = 1001  
   - 8 = 1000  
   - 7 = 0111  

2. Konversi desimal ke biner: 1987₁₀ = 1100110000111₂  

**B. 2346₁₀ = 10001101000110₂**  
**C. 501₁₀ = 1010000001₂**  

---

### 14. Konversi Bilangan Biner ke BCO  
**A. 11111101001₂ = 3751₈**  
**Cara Konversi**:  
1. Kelompokkan biner menjadi 3 digit: 011 111 101 001  
2. Konversi setiap kelompok ke oktal:  
   - 011 = 3  
   - 111 = 7  
   - 101 = 5  
   - 001 = 1  

**Hasil**: 3751₈  

**B. 101110010100₂ = 5624₈**  
**C. 1100000010₂ = 1402₈**  

---

### 15. Konversi Bilangan Biner ke BCH  
**A. 1101111100101110₂ = CF2E₁₆**  
**Cara Konversi**:  
1. Kelompokkan biner menjadi 4 digit: 1101 1111 0010 1110  
2. Konversi setiap kelompok ke heksadesimal:  
   - 1101 = D  
   - 1111 = F  
   - 0010 = 2  
   - 1110 = E  

**Hasil**: CF2E₁₆  

**B. 110100110000001₂ = 6981₁₆**  

---

### 16. Konversi BCH ke Heksadesimal  
**A. F0DE₁₆ = 1111000011011110₂**  
**Cara Konversi**:  
1. Konversi setiap digit heksadesimal ke biner 4 digit:  
   - F = 1111  
   - 0 = 0000  
   - D = 1101  
   - E = 1110  

**Hasil**: 1111000011011110₂  

**B. 1CAB₁₆ = 0001110010101011₂**  
**C. 834₁₆ = 100000110100₂**  

---

### 17. Menentukan Positif atau Negatif Bilangan Biner  
**A. 01111111 = POSITIF (127)**  
**B. 10000000 = NEGATIF (-128)**  
**C. 01111011 = POSITIF (123)**  

---

### 18. Konversi Bilangan Biner Negatif ke Desimal  
**A. 10001000₂ = -120₁₀**  
**Cara Konversi**:  
1. Bit pertama adalah 1, artinya bilangan negatif.  
2. Hitung nilai absolut:  
   - 0001000 = 8  
3. Tambahkan tanda negatif: -128 + 8 = -120  

**Hasil**: -120₁₀  

**B. 11110111₂ = -9₁₀**  
**C. 10000101₂ = -123₁₀**  
**D. 10011100₂ = -100₁₀**  

---

### 19. Konversi ASCII Code ke Karakter  
**A. 41₁₆ = A**  
**B. 5A₁₆ = Z**  
**C. 24₁₆ = $**  
**D. 77₁₆ = w**  

---

### 20. Konversi Karakter ke ASCII Code  
**A. a = 61₁₆**  
**B. x = 78₁₆**  
**C. m = 6D₁₆**  
**D. H = 48₁₆**  

---

### 21. Keluaran Keyboard ASCII  
**Tulisan**: PRINT X  
**Keluaran**:  
- P = 50₁₆ = 01010000₂  
- R = 52₁₆ = 01010010₂  
- I = 49₁₆ = 01001001₂  
- N = 4E₁₆ = 01001110₂  
- T = 54₁₆ = 01010100₂  
- X = 58₁₆ = 01011000₂  

---
