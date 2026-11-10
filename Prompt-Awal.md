# PROMPT AWAL — Karya Tulis Ilmiah

**Model AI:** Claude Opus 4.7 (`claude-opus-4-7`) · **Tanggal:** 10 November 2026 · **Tujuan:** menyusun karya tulis ilmiah siap kutip

---

## 1. Peran dan aturan mutlak

Kamu adalah asisten penulisan ilmiah yang disiplin dan jujur. Tugasmu adalah menyusun satu karya tulis ilmiah yang siap kutip dalam bahasa Indonesia akademik, tunduk pada seluruh aturan di bawah ini.

Batasan mutlak yang tidak boleh dilanggar:

- Kamu **TIDAK BOLEH** mengarang data, hasil penelitian, statistik, nomor halaman, kutipan, referensi, tautan, DOI, atau nama penulis.
- Setiap klaim faktual yang memerlukan dukungan sumber harus bersandar pada sumber yang **kamu temukan dan verifikasi sendiri** melalui langkah-langkah pada Bagian 5.
- Jika sebuah klaim penting tidak dapat didukung oleh sumber mana pun, tuliskan klaim tersebut secara umum tanpa atribusi dan beri penanda `[PERLU SUMBER]` agar saya melengkapinya.
- Kamu tidak boleh menambahkan sumber di luar daftar hasil penelusuranmu sendiri pada Bagian 5.
- Jika tanggal publikasi suatu sumber tidak tercantum eksplisit pada halaman penerbitnya, gunakan `(n.d.)`. Jangan mengarang tahun.
- Kamu wajib menyertakan **Lampiran A** (Bagian 5.5) berisi bukti bahwa setiap rujukan benar-benar kamu periksa.

## 2. Konteks penulisan

| Aspek | Ketentuan |
|---|---|
| Mata kuliah | Etika dan Integritas Akademik |
| Audiens | Mahasiswa sarjana dan dosen pengampu |
| Panjang total | Maksimal **2 halaman A4** (Times New Roman 12 pt, spasi 1,5, margin 2,54 cm) termasuk Daftar Pustaka |
| Bahasa | Indonesia akademik formal, tanpa jargon Inggris yang tidak perlu |
| Nada | Argumentatif, bukan deskriptif |

Setiap paragraf pembahasan mengikuti pola: **klaim tegas → bukti dari sumber → implikasi nyata bagi perilaku akademik**. Hindari daftar-daftar panjang tanpa argumentasi.

## 3. Topik dan rumusan masalah

**Topik:** *Penggunaan Kecerdasan Artifisial (AI) dalam Penulisan Ilmiah: Peluang, Risiko, dan Tanggung Jawab Akademik*

Rumuskan **satu rumusan masalah** di akhir Pendahuluan dalam bentuk kalimat tanya, lalu jadikan rumusan itu penanda bahwa seluruh Pembahasan menjawabnya secara langsung.

## 4. Struktur output (WAJIB, berurutan, tanpa bagian tambahan)

1. **Judul** — ringkas, tegas, memuat variabel utama.
2. **Abstrak** — maksimal 120 kata, tanpa sitasi. Diakhiri baris `Kata Kunci:` berisi tepat 5 kata kunci.
3. **Pendahuluan** — 1 paragraf (150–180 kata): latar belakang, ruang lingkup, rumusan masalah, tujuan.
4. **Pembahasan** — 3 subbagian berlabel, masing-masing 1–2 paragraf:
   - **(a) Peluang.** Efisiensi penulisan dan penelusuran sumber, perbaikan bahasa, aksesibilitas. Sertakan satu catatan kritis bahwa kemudahannya dapat menggeser persepsi mahasiswa mengenai batas usaha intelektual.
   - **(b) Risiko.** Fabrikasi referensi, gambar atau diagram yang menyesatkan, konsekuensi penarikan artikel (*retraction*), serta kekeliruan umum bahwa skor kesamaan (*similarity score*) atau skor detektor AI sudah cukup menjadi bukti. Carilah sendiri **data empiris tentang tingkat fabrikasi rujukan oleh model bahasa**, lalu verifikasi angka itu terhadap sumber aslinya sebelum memakainya.
   - **(c) Tanggung Jawab.** Nilai integritas akademik menurut kode etik atau lembaga yang relevan, pembedaan antara sitasi dan lisensi menurut sumber hukum resmi, serta kewajiban disclose penggunaan AI kepada dosen.
5. **Kesimpulan** — 1 paragraf (80–100 kata) yang menjawab rumusan masalah dan memuat implikasi operasional bagi mahasiswa maupun dosen.
6. **Daftar Pustaka** — APA 7th, **hanya** sumber yang sudah lolos gerbang verifikasi pada Bagian 5.
7. **Pernyataan Penggunaan AI** — blok penutup, isi persis sesuai Bagian 8.
8. **Lampiran A — Riwayat Verifikasi Referensi** — tabel bukti sesuai Bagian 5.5, diletakkan setelah naskah dan diberi label bahwa isinya berada di luar batas 2 halaman.

## 5. Penelusuran dan Verifikasi Referensi (WAJIB — kamu yang mencari, bukan saya)

Bagian ini menggantikan daftar pustaka yang disediakan. **Kamu wajib mencari sendiri setiap sumber yang kamu sitasi.** Saya tidak memberi referensi apa pun; yang kamu tulis di Daftar Pustaka harus berasal dari penelusuranmu sendiri pada langkah-langkah berikut.

### 5.1 Protokol penelusuran

1. Gunakan fitur penelusuran web atau pencarian dokumen untuk mencari sumber. **Bila model yang kamu jalankan tidak memiliki akses penelusuran web, berhenti di langkah ini**, nyatakan keterbatasanmu secara eksplisit pada baris paling awal keluaranmu, dan lanjutkan hanya dengan sumber yang benar-benar dapat kamu buka dan baca isinya.
2. Setiap sumber yang kamu sitasi **wajib kamu buka dan kamu baca**. Rujukan yang hanya kamu ingat dari memorasi model (parametric memory) **tidak boleh** dipakai sebagai rujukan terverifikasi.
3. Cari sumber yang relevan dengan topik, bukan yang paling mudah ditemukan. Prioritaskan sumber primer dan resmi.

### 5.2 Gerbang verifikasi — setiap sumber wajib lolos keempat cek ini

| Kode | Cek | Failure |
|---|---|---|
| C1 | DOI atau URL benar-benar hidup dan mengarah ke halaman penerbit atau lembaga yang sah — bukan halaman agregator, blog, atau halaman error | Gagal → buang sumber |
| C2 | Judul, nama penulis, nama jurnal/lembaga, dan tahun diambil dari halaman penerbit itu sendiri, bukan dari ingatan | Gagal → buang sumber |
| C3 | Setiap angka, kutipan, atau klaim yang kamu pakai benar-benar tertulis pada sumber tersebut | Gagal → buang sumber |
| C4 | Sumber dipakai untuk hal yang memang dikuatikannya, sesuai konteksnya | Gagal → buang sumber |

Sumber yang gagal C1–C3 **harus dibuang** dan diganti sumber lain. Jangan pernah dipaksakan agar Daftar Pustaka terlihat lengkap. Dilarang keras mengarang sumber, penulis, tahun, volume, nomor halaman, tautan, DOI, atau angka statistik.

### 5.3 Komposisi sumber (5–8 sumber)

- Minimal **2** artikel *peer-reviewed* yang membahas penggunaan AI dalam penulisan akademik.
- Minimal **1** studi empiris yang mengukur tingkat fabrikasi rujukan atau akurasi sitasi yang dihasilkan model bahasa.
- Minimal **1** sumber **institusional resmi** — kode etik, kebijakan, atau panduan integritas akademik dari lembaga-recognized.
- Minimal **1** sumber **hukum atau resmi** mengenai hak cipta, lisensi, atau kekayaan intelektual.
- Hindari blog, artikel berita, dan sumber sekunder yang tidak merujuk data primer.

### 5.4 Format Daftar Pustaka (APA 7) — ini format, isi ditentukan oleh penelusuranmu

```format
Authors, A. A., & Authors, B. B. (Year). Title of the article. Name of Journal, volume(issue), page range. https://doi.org/xxxxx

Organization Name. (Year atau n.d.). Title of the page. Name of Institution. https://xxxxx
```

Format above **hanya pola**. Jangan pernah mengarang agar terasa lengkap — biarkan Daftar Pustaka hanya berisi sumber yang benar-benar terverifikasi.

### 5.5 Lampiran A — Riwayat Verifikasi Referensi (wajib)

Setelah naskah, tambahkan tabel dengan heading:

`LAMPIRAN A — RIWAYAT VERIFIKASI REFERENSI (di luar batas 2 halaman naskah)`

Kolom: `No` · `Sitasi dalam naskah` · `Tautan/DOI` · `C1 DOI hidup` · `C2 Identitas` · `C3 Klaim` · `C4 Konteks` · `Status`

Nilai kolom C1–C4 diisi `Ya` atau `Tidak`. Kolom Status hanya boleh berisi **TERVERIFIKASI** atau **TIDAK TERVERIFIKASI**. Bila terdapat baris **TIDAK TERVERIFIKASI**, hapus sitasinya dari naskah dan perbaiki Daftar Pustaka sampai tidak ada lagi baris tersebut. Dilarang menandai sumber sebagai TERVERIFIKASI tanpa benar-benar membukanya.

### 5.6 Larangan tambahan

- Dilarang memakai sumber yang tidak muncul dalam daftar hasil penelusuranmu sendiri.
- Dilarang menuliskan `[PERLU SUMBER]` untuk menutupi sumber yang seharusnya kamu temukan sendiri — penanda itu hanya untuk klaim yang memang di luar jangkauanmu.
- Bila kamu merasa topik terlalu luas untuk disebut dengan 5–8 rujukan, persempit klaim yang kamu buat di tempat lain dan jangan menambah jumlah sumber.

## 6. Aturan sitasi

- Gaya **author–date** APA 7 dalam teks: `(Walters & Wilder, 2023)`.
- Untuk penulis korporasi, tulis nama lengkap pada penyebutan pertama, lalu gunakan singkatan dalam kurung: `(International Center for Academic Integrity [ICAI], n.d.)` dan `(World Intellectual Property Organization [WIPO], n.d.)`.
- Setiap angka dan setiap klaim yang dapat diverifikasi **wajib** diberi sitasi di dalam paragrafnya, bukan hanya di Daftar Pustaka.
- Jika sebuah klaim bersandar pada dua sumber, sitasi keduanya dalam satu tanda kurung: `(Walters & Wilder, 2023; ICAI, n.d.)`.
- **Jangan pernah** menulis sitasi untuk informasi yang tidak tertulis pada sumber yang kamu verifikasi.

## 7. Pernyataan Penggunaan AI (blok penutup wajib)

Tutup dokumen dengan blok di bawah ini, isi persis sesuai Bagian 8, dan jangan menambahkan paragraf penutup lain setelahnya:

```toolchain
Pernyataan Penggunaan AI

Model AI yang digunakan  : Claude Opus 4.7 (claude-opus-4-7)
Tanggal penggunaan        : 10 November 2026
Plugin yang digunakan     : superpowers@anthropic-plugin-directory v6.4.2
Skill yang digunakan      : superpowers:brainstorming (perancangan prompt), superpowers:verification-before-completion (verifikasi hasil)
Alat penelusuran         : WebSearch dan WebFetch, untuk mencari serta memverifikasi setiap rujukan
Tujuan penggunaan         : menyusun draf karya tulis ilmiah beserta daftar pustaka sesuai kaidah APA 7th
Bagian yang dibantu       : Judul, Abstrak, Pendahuluan, Pembahasan, Kesimpulan, Daftar Pustaka, dan Lampiran A
Verifikasi penulis        : Seluruh fakta, angka, dan rujukan telah diperiksa ulang terhadap sumber aslinya. Penulis tetap bertanggung jawab atas keakuratan isi meskipun memperoleh bantuan AI di atas.
```

## 8. TOOLCHAIN — model, plugin, skill, dan alat yang dipakai

Blok pada Bagian 7 **wajib diisi apa adanya** dengan nilai berikut. Jangan mengubah format, jangan menambahkan toolchain lain, dan jangan mengarang versi yang tidak tercantum di sini.

| Komponen | Nilai |
|---|---|
| Model AI | Claude Opus 4.7 (`claude-opus-4-7`) |
| Plugin | `superpowers@anthropic-plugin-directory` v6.4.2 |
| Plugin lain terpasang | `frontend-design@anthropic-plugin-directory` v1.1.1 — **tidak digunakan** dalam penulisan karya ini |
| Skill | `superpowers:brainstorming`, `superpowers:using-superpowers`, `superpowers:verification-before-completion` |
| Alat penelusuran | `WebSearch`, `WebFetch` — untuk mencari dan memverifikasi rujukan |
| Harness | Claude Code (Windows), mode effort `high` |

Balasanmu harus mengembalikan **hanya** isi karya tulis ilmiah itu sendiri, mulai dari baris judul, tanpa basa-basi, tanpa penjelasan tambahan, dan tanpa kalimat penutup yang tidak diminta.
