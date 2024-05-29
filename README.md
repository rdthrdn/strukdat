Tentu, berikut adalah jawaban untuk setiap soal dalam bahasa Indonesia yang siap kirim:

### E1: Tunjukkan kunci-kunci yang akan dibandingkan dengan setiap target berikut dalam pencarian pohon biner pencarian di atas.

1. \(c\):
   - k, c

2. \(s\):
   - k, n, s

3. \(k\):
   - k

4. \(a\):
   - k, c, a

5. \(d\):
   - k, c, e, d

6. \(m\):
   - k, n

7. \(f\):
   - k, c, e, h

8. \(b\):
   - k, c, a

9. \(t\):
   - k, n, s

### E2: Masukkan setiap kunci berikut ke dalam pohon biner pencarian di atas. Tunjukkan perbandingan kunci yang akan dilakukan dalam setiap kasus. Lakukan setiap bagian secara independen, memasukkan kunci ke dalam pohon asli.

1. \(m\):
   - k, n, m

2. \(f\):
   - k, c, e, h, f

3. \(b\):
   - k, c, a, b

4. \(t\):
   - k, n, s, t

5. \(c\):
   - Sudah ada di pohon (tidak perlu memasukkan)

6. \(s\):
   - Sudah ada di pohon (tidak perlu memasukkan)

### E3: Hapus setiap kunci berikut dari pohon biner pencarian di atas, menggunakan algoritma yang dikembangkan di bagian ini. Lakukan setiap bagian secara independen, menghapus kunci dari pohon asli.

1. \(a\):
   - k, c (hapus a)

2. \(p\):
   - k, n, s (hapus p)

3. \(n\):
   - k (hapus n)

4. \(s\):
   - k, n (hapus s)

5. \(e\):
   - k, c (hapus e)

6. \(k\):
   - hapus k

### E4: Gambar pohon biner pencarian yang akan dibentuk oleh fungsi insert untuk daftar 14 nama yang disajikan dalam setiap urutan berikut dan dimasukkan ke dalam pohon biner kosong sebelumnya.

1. **a**
   - Jan, Guy, Jon, Ann, Jim, Eva, Amy, Tim, Ron, Kim, Tom, Roy, Kay, Dot

2. **b**
   - Amy, Tom, Tim, Ann, Roy, Dot, Eva, Ron, Kim, Kay, Guy, Jon, Jan, Jim

3. **c**
   - Jan, Jon, Tim, Ron, Guy, Ann, Jim, Tom, Amy, Eva, Roy, Kim, Dot, Kay

4. **d**
   - Jon, Roy, Tom, Eva, Tim, Kim, Ann, Ron, Jan, Amy, Dot, Guy, Jim, Kay

### E5: Pertimbangkan untuk membangun dua pohon biner pencarian yang berisi kunci integer 1 hingga 63, termasuk, yang diterima dalam urutan

1. **a**
   - Semua bilangan ganjil secara berurutan \(1, 3, 5, \ldots, 63\), kemudian \(32, 16, 48\), kemudian bilangan genap yang tersisa secara berurutan \(2, 4, 6, \ldots\).

2. **b**
   - \(32, 16, 48\), kemudian semua bilangan ganjil secara berurutan \(1, 3, 5, \ldots, 63\), kemudian bilangan genap yang tersisa secara berurutan \(2, 4, 6, \ldots\).

**Pohon mana yang akan lebih cepat dibangun? Jelaskan mengapa.**
- Pohon (b) kemungkinan akan lebih cepat dibangun karena memasukkan \(32\), \(16\), dan \(48\) terlebih dahulu akan menyeimbangkan pohon sejak awal, mengurangi tinggi pohon dan menjaga keseimbangan saat lebih banyak node dimasukkan.

### E6: Semua bagian dari latihan ini merujuk pada pohon biner pencarian yang ditunjukkan di Gambar 10.8 dan membahas urutan berbeda di mana kunci \(a, b, \ldots, g\) dapat dimasukkan ke dalam pohon biner kosong awal.

1. **a**
   - Empat urutan berbeda untuk memasukkan kunci:
     - \(a, b, c, d, e, f, g\)
     - \(g, f, e, d, c, b, a\)
     - \(d, b, a, c, f, e, g\)
     - \(d, b, a, c, f, g, e\)

2. **b**
   - Empat urutan berbeda untuk memasukkan kunci:
     - \(b, a, d, c, g, f, e\)
     - \(e, f, g, d, c, b, a\)
     - \(d, a, b, c, f, e, g\)
     - \(c, b, a, d, e, f, g\)

3. **c**
   - Empat urutan berbeda untuk memasukkan kunci:
     - \(c, a, b, e, d, g, f\)
     - \(f, e, d, g, a, b, c\)
     - \(e, c, a, b, d, g, f\)
     - \(d, b, a, c, e, g, f\)

4. **d**
   - Hanya ada satu urutan untuk memasukkan kunci yang akan menghasilkan pohon biner pencarian yang mengurangi menjadi rantai yang diberikan. Ini karena dalam urutan yang benar-benar meningkat atau menurun, setiap kunci baru selalu lebih besar atau lebih kecil dari semua kunci yang dimasukkan sebelumnya, menghasilkan struktur garis lurus (linked list). Misalnya:
     - \(a, b, c, d, e, f, g\) (urutan meningkat) atau
     - \(g, f, e, d, c, b, a\) (urutan menurun).

Semoga membantu! Jika ada pertanyaan lebih lanjut atau memerlukan revisi, silakan beri tahu saya.
