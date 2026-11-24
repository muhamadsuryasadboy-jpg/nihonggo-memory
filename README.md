# Nihongo Memory

Satu app, tiga bagian dengan statistik terpisah (ganti lewat tombol di Beranda):

**Kanji** (655 kartu, 31 bab)
- 80 kanji N5 + 167 kanji N4 (sesuai daftar umum JLPT)
- 31 kanji N3 pilihan + 81 kanji umum yang berguna (bab "N3+")
- 296 kata kanji sehari-hari (bab "Kata")
- Tiap kartu: onyomi dan kunyomi dipisah, arti, contoh kata, dan penjelasan singkat
- Tombol ✍ Tulis: kanvas buat latihan menulis dengan jari (Undo, Hapus)

**Pola Kalimat** (121 pola, 9 bab, N5 sampai N4)
- Tiap pola: arti, penjelasan "kapan dipakai", peringatan jangan keliru, dan 2 contoh kalimat

**Hiragana dan Katakana** (317 kartu, 30 bab)
- Hiragana dan Katakana per baris (A, KA, SA, ...), dakuten, handakuten, bunyi gabung, dan bunyi asing katakana
- Tiap huruf: bunyi, contoh kata, dan peringatan huruf yang mirip
- Bab Aturan Bunyi (っ, ー, ん, は/へ/を sebagai partikel)
- Latihan Baca Cepat: 40 kata hiragana dan 60 kata katakana
- Ada tombol ✍ Tulis untuk latihan menulis

Backup mencakup ketiga bagian sekaligus.

![Beranda](screenshots/beranda.png) ![Kanji](screenshots/kanji.png) ![Pola](screenshots/pola.png) ![Kana](screenshots/kana.png)

## Cara jadi APK
1. Repo GitHub BARU
2. Upload semua file (index.html, package.json, capacitor.config.json, 5 PNG, .gitignore, folder .github)
3. Tab Actions, tunggu hijau, ambil artifact NihongoMemory-apk

Jujur: isi disusun sendiri dari daftar umum, bukan salinan buku saku. Daftar JLPT tidak resmi, jadi bisa beda sedikit antar sumber.

## Sama seperti Kotoba Memory
Ketiga bagian memakai mesin belajar yang sama dengan Kotoba Memory v8: Paket hafal per bab (bisa diatur), review otomatis, Review kebut, kata sulit, kata bandel, hint, ketik jawaban, Program 7 hari, backup dan gabung. Batas kata baru per hari awalnya 50 (sama seperti Kotoba), bisa diubah di Pengaturan.
