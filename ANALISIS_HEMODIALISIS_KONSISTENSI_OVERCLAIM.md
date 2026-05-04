# Analisis Konsistensi, Overclaim & Isu Kritikal — BAB IV Hemodialisis
## (Illness Perception & Self-Management Berdasarkan Jenis Kelamin)

Dokumen ini merangkum temuan **inkonsistensi angka/notasi**, **overclaim**, dan **isu kritikal metodologis** pada draf Hasil dan Pembahasan studi hemodialisis yang ditelaah. Versi yang sudah diperbaiki tersedia di `BAB_IV_HEMODIALISIS_REVISI.md`.

---

## 1. Inkonsistensi Angka & Notasi

### 1.1 Persentase cakupan asuransi berbeda antara Hasil dan Pembahasan

| Lokasi | Nilai tercantum | Nilai benar (sesuai tabel) | Perbaikan |
|---|---|---|---|
| Subbab A (Hasil) | 98.5% | 98.5% ✓ | Dipertahankan |
| Pembahasan | "95.8%" | 98.5% | Disesuaikan ke 98.5% |

**Penjelasan:** Tabel 4.1 menunjukkan 133/135 = 98.5% pengguna asuransi. Angka "95.8%" pada bagian Pembahasan merupakan kesalahan tulis dan harus diselaraskan.

---

### 1.2 Inkonsistensi notasi p-value (hilang "p =" pada beberapa variabel)

Beberapa nilai p disajikan tanpa awalan "p =" yang konsisten:

| Variabel | Notasi di teks | Notasi seharusnya |
|---|---|---|
| Lama hemodialisis | "(0.843)" | "(p = 0.843)" |
| Status pekerjaan | "(0.005)" | "(p = 0.005)" |
| Sumber biaya (asuransi) | "(-0.822)" | "(p = 0.822)" |

Notasi "(-0.822)" khususnya sangat menyesatkan karena tanda negatif dapat dibaca sebagai nilai negatif, bukan nilai p.

---

### 1.3 Durasi hemodialisis: 3.2 tahun vs "32 tahun"

**Di Hasil (subbab A):** "rata-rata lama hemodialisis (tahun) pada partisipan adalah **3.2 tahun**"

**Di Pembahasan:** "rata-rata **32 tahun** durasi partisipan menjalani hemodialisis"

**Masalah:** Perbedaan ini merupakan **kesalahan fatal** — kehilangan titik desimal mengubah makna secara drastis (3,2 tahun vs. 32 tahun tidak mungkin benar untuk populasi hemodialisis umum). Nilai yang benar adalah **3.2 tahun** sesuai narasi Hasil.

---

### 1.4 Skor total illness perception partisipan perempuan tidak terbaca

**Kutipan:** "partisipan perempuan (44.5**-4419,670**)"

**Masalah:** Angka "44.5-4419,670" jelas merupakan **data rusak/garbled** — kemungkinan aslinya adalah "44.5 ± 9.670" atau "44.5 ± 19.670" (SD). Nilai ini harus diverifikasi dari data mentah. Sebagai perbandingan, SD total adalah 11.137 dan SD laki-laki adalah 12.131, sehingga SD perempuan yang wajar berkisar 9–13, bukan 19.670.

---

### 1.5 Persentase frekuensi hemodialisis tidak konsisten

| Lokasi | Nilai |
|---|---|
| Subbab A (Hasil) | "96.2% menjalani hemodialisis 2 kali/minggu" |
| Pembahasan | "93.5% pasien laki-laki dan seluruh pasien perempuan (100%)" |
| Tabel 4.1 (laki-laki, 2x/minggu) | Data tampak terpotong/garbled |

**Masalah:** Jika 93.5% dari 78 laki-laki (= 72.93 ≈ 73 orang) dan 100% dari 57 perempuan (= 57 orang) menjalani 2x/minggu, totalnya adalah 130/135 = 96.3% — mendekati 96.2% di Hasil. Meskipun angkanya konsisten secara aritmetika, angka 93.5% dan 96.2% sebaiknya **diklarifikasi sumber perbedaannya** karena pembaca dapat bingung dengan dua angka berbeda. Selain itu, data tabel menunjukkan nilai "50(64)" yang tampak tidak sesuai dengan laki-laki N=78 dan 93.5%, sehingga perlu koreksi tabel.

---

### 1.6 Skor rata-rata item 5 dan item 6 identik pada nilai bulat (6.356)

**Item 5 (Identitas):** 6.356 ± 2.602
**Item 6 (Kekhawatiran):** 6.356 ± 2.906

Kemiripan nilai mean kedua item ini perlu dikonfirmasi dari data mentah — kemungkinan merupakan **kebetulan** atau **kesalahan salin** (copy-paste error). Disarankan untuk memverifikasi ulang.

---

### 1.7 Penulisan "Stalent's t-test" (seharusnya "Student's t-test")

**Kutipan:** "menggunakan **Stalent's t-test**"

Ini adalah **typo** — harus diperbaiki menjadi "**Student's t-test**" (atau lebih tepatnya "independent samples t-test").

---

### 1.8 Items 7 dan 8 disebut di narasi tetapi tidak tampak di tabel

Narasi menyebut item dengan skor tertinggi adalah "item 1 (8.341±2.102), **item 8** (6.963±2.708), dan item 2 (6.622±2.828)". Namun tabel yang tersedia hanya memperlihatkan item 1–6 secara eksplisit. Item 7 dan 8 harus **ditampilkan lengkap** dalam tabel agar konsisten dengan narasi.

---

## 2. Overclaim

### 2.1 "Membuktikan bahwa perlindungan finansial yang merata mampu menyetarakan illness perception"

**Kutipan asli:**
> "Hal ini **membuktikan** bahwa perlindungan finansial yang merata mampu menyetarakan tingkat illness perception antara pasien laki-laki dan perempuan."

**Masalah:** Kata "**membuktikan**" mengandung klaim kausal yang sangat kuat. Penelitian ini bersifat **cross-sectional** — tidak dapat membuktikan bahwa asuransi *menyebabkan* persamaan illness perception. Cakupan asuransi 98.5% tidak dimanipulasi sebagai intervensi; ini hanya kondisi observasional. Lebih dari itu, ada banyak variabel lain yang tidak dikontrol.

**Perbaikan:** Ganti "membuktikan" dengan "konsisten dengan temuan bahwa" atau "mengindikasikan bahwa".

---

### 2.2 "Terapi jangka panjang bertindak sebagai mekanisme penyesuaian kognitif"

**Kutipan asli:**
> "Fenomena ini menunjukkan bahwa **terapi jangka panjang bertindak sebagai mekanisme penyesuaian kognitif** yang mereduksi perbedaan jenis kelamin dalam illness perception."

**Masalah:** Mekanisme kognitif adaptasi tidak **diukur** dalam penelitian ini. Penelitian tidak mengukur perubahan illness perception dari waktu ke waktu, tingkat adaptasi, atau proses kognitif internal. Mengklaim mekanisme spesifik (penyesuaian kognitif) tanpa mengukurnya adalah **overclaim mekanistik**.

**Perbaikan:** "Temuan ini konsisten dengan pandangan bahwa paparan terapi jangka panjang *dapat* berhubungan dengan penyesuaian kognitif — namun mekanisme ini tidak diuji secara langsung dalam penelitian ini."

---

### 2.3 "Paparan berulang … *menghasilkan* tingkat adaptasi yang serupa"

**Kutipan asli:**
> "Paparan berulang terhadap prosedur hemodialisis yang sama … **menghasilkan** tingkat adaptasi yang serupa antara pasien laki-laki dan perempuan."

**Masalah:** Kata "menghasilkan" menyiratkan **kausalitas**. Desain cross-sectional hanya dapat menunjukkan asosiasi atau konsistensi temuan, bukan sebab-akibat. Adaptasi tidak diukur secara langsung.

**Perbaikan:** "konsisten dengan" atau "berhubungan dengan tingkat illness perception yang serupa."

---

### 2.4 Penjelasan perbedaan dengan studi Pakistan sebagai konfirmasi kausal

**Kutipan asli:**
> "Berbeda dengan kondisi di Pakistan yang penuh hambatan finansial dan struktural bagi perempuan, sistem jaminan kesehatan di Indonesia **berhasil meniadakan** penghalang ekonomi tersebut."

**Masalah:** Perbandingan dengan satu studi di satu negara lain tidak cukup untuk mengklaim bahwa sistem JKN **telah meniadakan** hambatan. Ini adalah generalisasi yang berlebihan. Sampel penelitian ini hanya berasal dari satu fasilitas, dan banyak faktor kontekstual lain yang berbeda antara kedua populasi (budaya, sistem kesehatan, instrumen, dll.).

**Perbaikan:** "Perbedaan ini *dapat* dijelaskan sebagian oleh konteks sistem jaminan kesehatan yang berbeda; namun perbandingan langsung antarpopulasi harus dilakukan dengan hati-hati mengingat adanya perbedaan kontekstual yang luas."

---

### 2.5 "Stimulus situasional kronis tampak *lebih dominan* membentuk illness perception"

**Kutipan asli:**
> "Sejalan dengan CSM, temuan pada penelitian ini menunjukkan bahwa **stimulus situasional kronis tampak lebih dominan** membentuk illness perception pada pasien hemodialisis."

**Masalah:** Penelitian ini tidak mengukur kontribusi relatif berbagai determinan illness perception (misalnya faktor biopsikososial, karakteristik individu, faktor situasional). Klaim "lebih dominan" memerlukan analisis komparatif (misalnya regresi berganda) yang tidak dilakukan.

**Perbaikan:** "Temuan ini *konsisten dengan* argumen CSM bahwa stimulus situasional kronis *berperan* dalam membentuk illness perception, meskipun kontribusi relatifnya tidak diuji secara langsung."

---

## 3. Isu Kritikal Metodologis

### 3.1 Variabel perancu signifikan tidak dikontrol dalam analisis illness perception

**Masalah:** Tabel 4.1 menunjukkan bahwa laki-laki dan perempuan dalam studi ini **berbeda secara signifikan** dalam:
- **Status pekerjaan** (p = 0.005): lebih banyak laki-laki yang bekerja → akses informasi, status sosioekonomik berbeda
- **Tingkat pendidikan** (p < 0.001): laki-laki lebih banyak berpendidikan tinggi → literasi kesehatan berbeda
- **Berat badan pre- dan post-HD** (p < 0.001): mencerminkan perbedaan kondisi fisik/klinis

Namun, analisis illness perception (Tabel 4.2) hanya membandingkan skor berdasarkan jenis kelamin **tanpa mengendalikan** variabel-variabel perancu ini. Ada kemungkinan bahwa kesamaan illness perception antara laki-laki dan perempuan bukan karena adaptasi atau asuransi, melainkan karena efek penyeimbang dari variabel perancu yang saling berlawanan.

**Rekomendasi:** Lakukan **analisis multivariat** (misalnya ANCOVA atau regresi linier berganda) dengan mengendalikan pendidikan, pekerjaan, dan durasi HD sebagai kovariat. Sebutkan keterbatasan ini secara eksplisit dalam bagian Keterbatasan Penelitian.

---

### 3.2 Effect size tidak diinterpretasikan

**Masalah:** Tabel 4.2 mencantumkan nilai effect size untuk setiap item (misalnya r = -0.122, 0.126, -0.071, -0.137, 0.196, 0.181), namun **tidak ada satu pun** paragraf pembahasan yang menginterpretasikan besaran efek ini dalam konteks signifikansi praktis. Nilai-nilai tersebut semuanya berada pada kategori **kecil** (r < 0.2) menurut klasifikasi Cohen (1988), yang menunjukkan perbedaan jenis kelamin pada illness perception sangat kecil secara praktis — informasi penting yang perlu dikemukakan.

**Rekomendasi:** Tambahkan kalimat yang menyatakan bahwa meskipun tidak ditemukan perbedaan signifikan, nilai effect size yang semuanya < 0.2 (kecil) mengkonfirmasi bahwa perbedaan praktis juga tidak bermakna secara klinis.

---

### 3.3 Item B-IPQ dengan skor sangat rendah (Item 4 — Kontrol Pengobatan: 1.644/10) tidak dibahas secara klinis

**Masalah:** Item 4 ("Sejauh mana pengobatan dapat membantu penyakit Anda?") memiliki rata-rata hanya **1.644 ± 2.613** pada skala 0–10. Ini mengindikasikan bahwa pasien hemodialisis **meragukan manfaat hemodialisis** dalam membantu kondisi mereka — temuan yang **sangat penting secara klinis** karena berpotensi memengaruhi kepatuhan terapi. Namun, bagian pembahasan tidak membahas implikasi klinis dari temuan ini secara memadai.

**Rekomendasi:** Bahas implikasi klinis dari rendahnya skor item 4 — termasuk hubungannya dengan kemungkinan non-adherence atau interpretasi pasien tentang penyakit ginjal kronik terminal sebagai kondisi yang tidak dapat disembuhkan oleh hemodialisis (bukan pengobatan kuratif, melainkan suportif).

---

### 3.4 Desain cross-sectional dan keterbatasan kausalitas tidak disebutkan secara eksplisit

**Masalah:** Pembahasan menggunakan beberapa pernyataan yang menunjukkan hubungan kausal atau temporal (lihat Poin 2.2 dan 2.3) tanpa menyebutkan bahwa desain **cross-sectional** hanya dapat menunjukkan asosiasi sesaat, bukan perubahan dari waktu ke waktu maupun kausalitas.

**Rekomendasi:** Tambahkan kalimat eksplisit pada bagian Keterbatasan: "Desain cross-sectional tidak memungkinkan penarikan kesimpulan kausal. Penelitian longitudinal diperlukan untuk menelaah perubahan illness perception seiring durasi hemodialisis."

---

### 3.5 Instrumen self-report dan kemungkinan social desirability bias

**Masalah:** B-IPQ adalah instrumen kuesioner berbasis laporan diri (*self-report*). Pada pasien yang sudah lama menjalani hemodialisis, terdapat kemungkinan **bias normalisasi** — pasien mungkin menilai penyakit mereka lebih ringan dari kenyataannya karena telah terbiasa (*adaptation level theory*). Ini perlu diakui dalam keterbatasan.

**Rekomendasi:** Tambahkan di bagian Keterbatasan: "Penggunaan instrumen self-report rentan terhadap bias adaptasi (normalization bias) pada pasien dengan durasi terapi jangka panjang."

---

### 3.6 Perbandingan dengan literatur menggunakan studi dari tahun yang berbeda tanpa mempertimbangkan perbedaan konteks instrumen

**Masalah:** Studi pembanding yang dikutip (Jafarzadeh et al., 2025; Sitjar-Suñer et al., 2025; Hamza et al., 2025) menggunakan sampel, instrumen, dan konteks budaya yang berbeda. Perbandingan langsung tanpa catatan keterbatasan komparabilitas berisiko menyesatkan pembaca.

**Rekomendasi:** Tambahkan catatan bahwa perbandingan antarpopulasi harus ditafsirkan dengan hati-hati mengingat perbedaan instrumen, konteks budaya, sistem layanan kesehatan, dan karakteristik sampel.

---

## 4. Ringkasan Prioritas Perbaikan

| Prioritas | Masalah | Jenis |
|---|---|---|
| 🔴 Kritis | Durasi HD "32 tahun" vs "3.2 tahun" di Pembahasan | Inkonsistensi |
| 🔴 Kritis | Cakupan asuransi "95.8%" vs "98.5%" di Pembahasan | Inkonsistensi |
| 🔴 Kritis | Skor SD perempuan "44.5-4419,670" tidak terbaca | Inkonsistensi |
| 🔴 Kritis | Variabel perancu (pendidikan, pekerjaan) tidak dikontrol | Isu Kritikal |
| 🟠 Penting | "membuktikan" → klaim kausal tidak didukung desain | Overclaim |
| 🟠 Penting | "menghasilkan adaptasi serupa" → kausalitas tidak diuji | Overclaim |
| 🟠 Penting | Effect size tidak diinterpretasikan | Isu Kritikal |
| 🟠 Penting | Item 4 B-IPQ sangat rendah — implikasi klinis tidak dibahas | Isu Kritikal |
| 🟡 Sedang | Notasi p-value tidak konsisten (hilang "p =") | Inkonsistensi |
| 🟡 Sedang | "Stalent's t-test" → typo "Student's t-test" | Inkonsistensi |
| 🟡 Sedang | Desain cross-sectional tidak disebutkan secara eksplisit | Isu Kritikal |
| 🟡 Sedang | Item 7 dan 8 tidak tampak di tabel | Inkonsistensi |
| 🟡 Sedang | Perbandingan Pakistan terlalu kuat klaimnya | Overclaim |
| 🟢 Minor | Skor item 5 dan 6 identik — konfirmasi data mentah | Inkonsistensi |
| 🟢 Minor | Normalization bias pada self-report B-IPQ | Isu Kritikal |

---

## 5. Referensi Pendukung Rekomendasi

- **Cohen, J. (1988).** *Statistical power analysis for the behavioral sciences* (2nd ed.). Lawrence Erlbaum.
- **Leventhal, H., Phillips, L. A., & Burns, E. (2016).** The Common-Sense Model of self-regulation (CSM): A dynamic framework for understanding illness self-management. *Journal of Behavioral Medicine, 39*(6), 935–946. https://doi.org/10.1007/s10865-016-9782-2
- **Hagger, M. S., & Orbell, S. (2022).** The Common Sense Model of illness self-regulation: A conceptual review and proposed extended model. *Health Psychology Review, 16*(2), 347–377. https://doi.org/10.1080/17437199.2021.1878050
- **Altman, D. G., & Bland, J. M. (1995).** Absence of evidence is not evidence of absence. *BMJ, 311*(7003), 485. https://doi.org/10.1136/bmj.311.7003.485
- **Broadbent, E., Petrie, K. J., Main, J., & Weinman, J. (2006).** The Brief Illness Perception Questionnaire. *Journal of Psychosomatic Research, 60*(6), 631–637. https://doi.org/10.1016/j.jpsychores.2005.10.020
