# POLAQUEST — Detektif Pola & Abstraksi

LKPD (Lembar Kerja Peserta Didik) digital berbasis game untuk:
- Mata Pelajaran: **Informatika**
- Kelas / Fase: **8 / Fase D**
- Kurikulum: **Kurikulum Merdeka**
- Elemen: **Berpikir Komputasional**
- Materi: **Pattern Recognition & Abstraction**
- Model: **Problem Based Learning (PBL)**

## Cara Membuka
Klik dua kali file `index.html` di komputer/HP. Game langsung terbuka di browser. **Tidak butuh internet** setelah pemuatan pertama (kecuali font & Tailwind CDN opsional).

---

## 🅰️ CARA 1 — PALING MUDAH (Netlify Drop, tanpa akun, 2 menit)

1. Salin seluruh kode `index.html` dari jawaban AI ke **Notepad**.
2. Klik **File → Save As**.
3. Pada **"Save as type"**, pilih **All Files**.
4. Pada **"File name"**, tulis persis: `index.html`
5. Simpan di folder baru, misalnya di Desktop bernama `polaquest`.
6. Buka browser, kunjungi: `https://app.netlify.com/drop`
7. **Seret folder `polaquest`** ke area *"Drag and drop your site folder here"*.
8. Tunggu 10–30 detik. Akan muncul tautan, contoh: `https://cerulean-macaron-123abc.netlify.app`
9. **Tautan itu sudah bisa dibuka murid dari HP masing-masing.** Selesai!
10. (Opsional) Ganti nama tautan: **Site settings → Change site name** → tulis `polaquest-kelas8`, jadi `https://polaquest-kelas8.netlify.app`
11. (Opsional) Buat **QR Code** di `https://qr-code-generator.com` dari tautan tersebut, tempel di papan tulis.

## 🅱️ CARA 2 — GRATIS SELAMANYA (GitHub Pages)

1. Buka `https://github.com` → **Sign up** untuk akun gratis.
2. Setelah masuk, klik **+** di kanan atas → **New repository**.
3. **Repository name**: `lkpd-polaquest`
4. Pilih **Public** → **Create repository**.
5. Klik **"uploading an existing file"**.
6. Seret file `index.html` (dan `README.md`) ke area upload.
7. Klik **Commit changes**.
8. Klik tab **Settings** → menu kiri **Pages**.
9. **Source**: **Deploy from a branch**.
10. **Branch**: `main`, folder `/ (root)` → **Save**.
11. Tunggu 1–3 menit, muat ulang halaman.
12. Tautan muncul, contoh: `https://namapengguna.github.io/lkpd-polaquest/`
13. Bagikan tautan itu ke murid. **Gratis selamanya.**

## 🅲 CARA 3 — LEWAT GOOGLE SITES

1. Buka `https://sites.google.com` → buat situs baru.
2. **Sisipkan (Insert) → Sematkan (Embed) → Dengan URL (By URL)**.
3. Tempel tautan Netlify atau GitHub Pages dari Cara 1 atau 2.
4. **Sisipkan** → **Publikasikan**.
5. Bagikan tautan Google Sites ke murid.

## 🅳 CARA 4 — TANPA INTERNET SAMA SEKALI (Offline)

1. Simpan `index.html` di flashdisk.
2. Bagikan flashdisk ke murid, atau kirim lewat WhatsApp/Google Drive.
3. Murid cukup **klik dua kali** `index.html` — game langsung terbuka.
4. Cocok untuk sekolah dengan koneksi terbatas.

---

## 🔧 CARA MENGUBAH ISI GAME TANPA PAHAM KODING

1. Buka `index.html` dengan **Notepad**.
2. Tekan **Ctrl + F**, cari kata `CONFIG`.
3. Ubah teks di antara tanda kutip. Contoh:
   - `namaSekolah: "SMP Nusantara",` → `namaSekolah: "SMP Negeri 1 Bandung",`
   - `modeBahasaDefault: "DUAL",` → `modeBahasaDefault: "ID",`
   - `timerAktif: false,` → `timerAktif: true,`
4. **Jangan hapus** tanda koma `,`, tanda kutip `"`, atau tanda titik dua `:`.
5. Simpan dengan **Ctrl + S**.
6. Buka lagi `index.html` di browser.

## Privasi
Semua jawaban tersimpan di `localStorage` perangkat murid. Tidak ada data yang dikirim ke server mana pun.