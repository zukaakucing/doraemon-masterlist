# Doraemon Masterlist — Lengkap (sejujur datanya)

Tanggal pengambilan data: **2026-11-03**.
Aturan yang dipakai: **hanya informasi terverifikasi yang dicatat; kolom yang belum terverifikasi diisi `-`, bukan kosong dan bukan karangan.** Judul/tanggal yang tidak ditemukan di sumber yang dibaca tidak diterjemahkan sendiri dan tidak dilengkapi dari tebakan.

> **JANGAN klaim file ini lengkap 100%.** File ini lengkap untuk 1973 dan untuk porsi TVmaze 1979–1984 serta 2005–2014 dan 2017–2021 yang tercantum di bawah. Celah 1985–2005 (seri 1979), celah 2014–2017 dan 2021–2026 (seri 2005), serta semua judul Jepang/Indonesia (kecuali judul Jepang 1973) masih `-` / belum ditranskripsikan — lihat bagian (c).

## File

- `episodes_1973.csv` — 26 baris
- `episodes_1979.csv` — 795 baris (HANYA 1979–1984, lihat celah)
- `episodes_2005.csv` — 555 baris (dua segmen, lihat celah)
- `Doraemon_Masterlist_Lengkap.xlsx` — sheet Ringkasan, Episode 1973, Episode 1979, Episode 2005, Sumber & Catatan (isi sama dengan CSV)
- Semua CSV memakai 7 kolom template persis: No. katalog | Tanggal tayang Jepang | Judul (Inggris) | Judul (Jepang) | Judul Indonesia | Catatan | Sumber. Info TVmaze SxxExx dan ID dimasukkan ke kolom Catatan. Tidak ada kolom tambahan.

## (a) Baris lengkap terverifikasi

Definisi ketat: baris yang **ketujuh kolomnya** terisi tanpa `-`. **Jumlahnya: 0 baris.**
Alasannya bukan karena tanggal/judul Inggrisnya meragukan, melainkan karena **judul Indonesia tidak terverifikasi untuk satu pun baris** (1.376 baris) dari sumber yang dibaca, sehingga tidak ada baris yang lengkap di semua kolom template.

Yang terverifikasi per kelompok (tanpa menghitung kolom `-`):

| Seri / segmen | Baris | Tanggal terverifikasi | Judul Inggris terverifikasi | Judul Jepang terverifikasi |
|---|---|---|---|---|
| 1973 (TVmaze 19268 + Doraemon Wiki) | 26 | 26 | 26 | 26 |
| 1979, TVmaze 59118 (1979–1984) | 795 | 795 | 795 | 0 |
| 2005 segmen A, TVmaze 55578 (2005–2014) | 377 | 377 | 377 | 0 |
| 2005 segmen B, TVmaze 55578 (2017–2021) | 178 | 178 | 177 | 0 |
| **Total baris dalam file** | **1.376** | **1.376** | **1.375** | **26** |

Rentang tanggal per segmen (bukan rentang gabungan yang menutupi celah):

- 1973: 1973-04-01 s.d. 1973-09-30 (S01E01–S01E26)
- 1979 TVmaze: 1979-04-02 s.d. 1984-12-28 (S01E01–S06E51)
- 2005 segmen A: 2005-04-15 s.d. 2014-09-19 (S01E01–S10E25)
- 2005 segmen B: 2017-01-27 s.d. 2021-03-20 (S13E03–S17E11)

## (b) Baris dengan sebagian kolom `-`

**Semua 1.376 baris** punya sedikitnya satu kolom `-`:

- 1973: 26 baris — hanya Judul Indonesia `-` (26). Judul Inggris + Jepang + tanggal terverifikasi.
- 1979: 795 baris — Judul Jepang `-` (795) dan Judul Indonesia `-` (795).
- 2005: 555 baris — Judul Jepang `-` (555) dan Judul Indonesia `-` (555); plus 1 baris dengan Judul Inggris juga `-`:
  - No. 378, 2017-01-27, TVmaze S13E03 ID 2099406: judul Inggris terpotong di awal jangkauan baca (hanya `...Badge` yang terlihat). Tidak dikarang; kolomnya `-` dan penjelasannya ada di Catatan.
- Tidak ada sel kosong di file mana pun (verifikasi: 0 sel kosong per kolom di ketiga CSV). Semua yang belum terverifikasi memakai `-`, sesuai koreksi user.

## (c) Periode / kolom yang masih `-` dan kenapa

### 1. Judul Indonesia — semua seri, semua baris (1.376 baris)

Belum ditemukan di sumber yang dibaca (TVmaze hanya memberi judul Inggris; Doraemon Wiki 1973 hanya memberi judul Jepang). Jangan menerjemahkan judul Inggris menjadi Indonesia dan mengklaimnya resmi.

### 2. Judul Jepang — seri 1979 dan 2005 (1.350 baris)

TVmaze tidak memberi judul Jepang. Judul Jepang hanya terverifikasi untuk 1973 (dari Doraemon Wiki). Untuk 1985–2005, Wikipedia sebenarnya memuat judul Jepang per baris, tetapi judul-judul itu belum ditranskripsikan ke CSV dalam run ini (lihat poin 3).

### 3. Seri 1979, periode 1985–2005 — TIDAK ADA baris judul dalam file ini

**Fakta terverifikasi:** pencarian TVmaze `search/shows?q=Doraemon` pada 2026-11-03 hanya menemukan 3 show: 19268 (1973), 59118 (1979-04-02 s.d. 1984-12-28, Ended), 55578 (2005–sekarang, Running). **Tidak ada show TVmaze terpisah untuk 1985–2005.** TVmaze 59118 terpotong di 1984, bukan berakhirnya seri 1979.

Riset celah (Wikipedia, salinan crawl 2026-08-30) menemukan overview per tahun berikut — angka ini adalah **hitungan overview, bukan baris judul dalam CSV**, dan periode ini sengaja TIDAK dihapus dari laporan:

| Tahun | Overview Wikipedia (reguler) | Pertama | Terakhir | Status audit per judul dalam run ini |
|---|---|---|---|---|
| 1985 | 52 | 1985-01-01 | 1985-12-27 | Diaudit penuh (53 baris section incl. spesial S24) — judul belum ditranskripsikan ke CSV |
| 1986 | 50 | 1986-01-03 | 1986-12-26 | Diaudit penuh (52 baris section incl. S25–S26) — judul belum ditranskripsikan |
| 1987 | 60 | 1987-01-02 | 1987-12-25 | Sebagian awal saja (No. 898–939) — sisa belum diaudit |
| 1988 | 49 | 1988-01-08 | 1988-12-23 | Diaudit penuh (50 baris incl. S28) — judul belum ditranskripsikan |
| 1989 | 54 | 1989-01-06 | 1989-12-29 | Sebagian awal saja (No. 1007–1023) — sisa belum diaudit |
| 1990 | 50 | 1990-01-05 | 1990-12-28 | Hanya overview — belum diaudit per judul |
| 1991 | 51 | 1991-01-04 | 1991-12-27 | Hanya overview — belum diaudit per judul |
| 1992 | 55 | 1992-01-10 | 1992-12-25 | Hanya overview — belum diaudit per judul |
| 1993 | 70 | 1993-01-08 | 1993-12-24 | Hanya overview — belum diaudit per judul |
| 1994 | 51 | 1994-01-07 | 1994-12-23 | Hanya overview — belum diaudit per judul |
| 1995 | 48 | 1995-01-06 | 1995-12-22 | Diaudit penuh (44 reguler + 4 spesial) — judul belum ditranskripsikan |
| 1996 | 48 | 1996-01-05 | 1996-12-21 | Sebagian awal saja — sisa belum diaudit |
| 1997 | 51 | 1997-01-10 | 1997-12-23 | Hanya overview — belum diaudit per judul |
| 1998 | 44 | 1998-01-09 | 1998-12-18 | Hanya overview — belum diaudit per judul |
| 1999 | 45 | 1999-01-08 | 1999-12-31 | Hanya overview — belum diaudit per judul |
| 2000 | 40 | 2000-01-14 | 2000-12-15 | Hanya overview — belum diaudit per judul |
| 2001 | 41 | 2001-01-12 | 2001-12-14 | Hanya overview — belum diaudit per judul |
| 2002 | 45 | 2002-01-11 | 2002-12-31 | Hanya overview — belum diaudit per judul |
| 2003 | 45 | 2003-01-17 | 2003-12-12 | Hanya overview — belum diaudit per judul |
| 2004 | 38 | 2004-01-09 | 2004-12-18 | Hanya overview — belum diaudit per judul |
| 2005 | 10 | 2005-01-07 | 2005-03-18 | Diaudit penuh (No. 1778–1787, episode final “Doraemon Takes a Day Off!!”) — judul belum ditranskripsikan |
| **Total overview 1985–2005** | **997** | | | |

Selisih yang belum direkonsiliasi: 795 (TVmaze 1979–1984) + 997 = 1.792, sedangkan nomor reguler terakhir Wikipedia adalah 1787 (selisih 5). Penyebab yang terlihat: overview Wikipedia menghitung spesial secara tidak konsisten (1985/1986/1988: overview = reguler saja, section memuat +1/+2 spesial; 1995: overview = total section). Jangan memaksakan angka-angka ini sama. Jumlah spesial juga berbeda antar sumber (TheTVDB: 27; Doraemon Wiki: 30) dan belum diputuskan.

**Sumber terbaik untuk melengkapi celah ini (langkah berikut, bukan klaim sudah lengkap):** Wikipedia — `List of Doraemon (1979 TV series) episodes (1979–1986)` dan `(1987–2005)` — dengan cek silang TheTVDB series 252696 (musim = tahun kalender, S07=1985 … S27=2005; nomor absolut TheTVDB sama dengan nomor Wikipedia untuk yang dicek). **TMDB 57911 jangan dipakai mentah:** total 1836, last aired 2005-06-24 (melewati final 2005-03-18), kemungkinan mencampurkan awal seri 2005.

### 4. Seri 2005, celah S10E26–S13E02 (sekitar 2014–2017) dan S17E12–S22 (2021–2026)

Belum ditranskripsikan karena pembacaan API TVmaze 55578 (1.879 baris tampilan) terhenti oleh **HTTP 429 (rate limit)** — segmen C berhenti di baris ~755, segmen D di baris ~1.295 — dan sesuai aturan hard stop, permintaan TVmaze tidak diulang dalam run ini. Dua baris yang hanya terlihat sebagian (S10E26 dan S17E12) sengaja TIDAK dimasukkan karena tanggal/judul lengkapnya tidak terbaca. API 55578 sendiri mencakup musim 1–22 (2005–2026) menurut halaman seasons-nya.

### 5. Anomali di dalam data yang sudah ditranskripsikan (ditulis persis, tidak diperbaiki dengan tebakan)

- 1979: S03E93 tidak ada di daftar TVmaze (lompat S03E92 → S03E94); S02E245 “The Seed to Feel Cheerfu” terpotong di sumber TVmaze sendiri; judul duplikat yang memang episode berbeda: “Goodbye, Shizuka” S03E85/S03E86, “Robinson Crusoe Set” S05E31/S05E32 (keduanya 1983-08-12).
- 1973: urutan segmen ep. 3 berbeda antara TVmaze dan Doraemon Wiki (dicatat di Catatan baris itu); tidak ada episode TVmaze bertanggal 1973-07-22 (ep. 17 bertanggal 1973-07-29).
- 2005: ejaan API dipertahankan apa adanya, termasuk “Cusion”, “Pilark”, “Revertion”, “Dora-Racoon”; S10E18 judulnya berakhir “/ The” di API; S08E17 penempatan “/” ditulis persis seperti tampilan API; judul duplikat S07E10/S07E12 (“Nobita's Confusing School Entrance Ceremony”, ID berbeda).

## Sumber per seri

- 1973: TVmaze API show 19268 (`https://api.tvmaze.com/shows/19268/episodes`) untuk tanggal + judul Inggris; Doraemon Wiki Fandom (`http://doraemon.fandom.com/wiki/List_of_Doraemon_(1973_anime)_episodes`) untuk judul Jepang.
- 1979 (1979–1984): TVmaze API show 59118 (`https://api.tvmaze.com/shows/59118/episodes`, 1.567 baris tampilan, dibaca sampai baris akhir 1567) + seasons (`https://api.tvmaze.com/shows/59118/seasons`, musim 1–6).
- 1979 (celah 1985–2005): Wikipedia (2 halaman di atas) untuk overview + audit sebagian; TheTVDB 252696 untuk cek silang; TMDB 57911 hanya pembanding yang ditolak mentah.
- 2005: TVmaze API show 55578 (`https://api.tvmaze.com/shows/55578/episodes`, 1.879 baris tampilan; segmen yang berhasil dibaca: awal–~755 dan ~940–~1.295) + seasons (musim 1–22). TV Asahi (`https://www.tv-asahi.co.jp/doraemon/story/bk/?y=2005`) tercantum di template tetapi tidak dipakai untuk judul dalam run ini.
- Template asal: `~/workspace/user/files/Doraemon_Masterlist_Template_0_cz6z.xlsx` (sheet Ringkasan, Episode 1973/1979/2005, Sumber & Catatan, Petunjuk — sheet episode semula hanya header).

## Verifikasi (dibaca ulang dari file hasil, 2026-11-03)

- episodes_1973.csv: 26 baris, 7 kolom semua baris, No. katalog unik, TVmaze ID unik, 0 sel kosong, 0 tanggal kosong, 0 judul Inggris kosong.
- episodes_1979.csv: 795 baris, 7 kolom semua baris, No. katalog unik, TVmaze ID unik, 0 sel kosong, 0 tanggal kosong, 0 judul Inggris kosong.
- episodes_2005.csv: 555 baris, 7 kolom semua baris, No. katalog unik, TVmaze ID unik, 0 sel kosong, 0 tanggal kosong, 1 judul Inggris `-` (S13E03, terpotong — lihat di atas).
- Doraemon_Masterlist_Lengkap.xlsx: Ringkasan 8 baris (header + 7), Episode 1973 27 baris (header + 26), Episode 1979 796 baris (header + 795), Episode 2005 556 baris (header + 555), Sumber & Catatan 11 baris (header + 10).
- Tidak ada tanggal kosong yang diklaim lengkap: setiap baris dalam CSV/XLSX punya tanggal YYYY-MM-DD; celah periode tidak dibuatkan baris tanggal karangan.

## Catatan untuk pengekspor (parent)

Ekspor ke Google Sheets dan GitHub **belum dilakukan** dari sisi ini, sesuai instruksi — parent yang mengekspor setelah laporan ini. Saat mengekspor, pertahankan `-` apa adanya (jangan diubah menjadi kosong) agar celahnya tetap terlihat, dan jangan menggabungkan segmen 2005 A/B menjadi satu rentang tanpa menyebut celah di tengahnya.
