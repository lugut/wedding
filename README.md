Wedding Invitation — Static

Ringkas: undangan pernikahan statis (HTML/CSS/JS) — mudah dikustomisasi lewat satu file data.

Fitur singkat

Welcome + personalized name dari URL (?to= atau ?nama= atau slug)

Profil mempelai (foto + shortName)

Waktu & lokasi acara

Galeri foto (slide + lihat semua)

Background music (audio)

Simple, modular JS per section


Cara cepat edit

Ubah konten utama di: src/assets/data/data.js
(nama mempelai, tanggal, alamat, link peta, audio path, daftar galeri, dll.)

Untuk menonaktifkan/aktifkan galeri: ubah di data.js (jika ada flag galeri.enabled) — atau kosongkan array galeri.

Kalau ingin override tampilan nama pasangan, gunakan field shortName di masing-masing mempelai.


Preview lokal

Buka index.html langsung di browser (untuk development module mungkin perlu server).

Atau jalankan server sederhana:

# Python 3
python -m http.server 8000
# lalu buka http://127.0.0.1:8000


Deploy singkat

Push ke GitHub → Settings → Pages → pilih branch → aktifkan.

Atau deploy ke Vercel / Cloudflare Pages untuk proses otomatis.


Catatan singkat

Pastikan path asset (images/audio) sesuai di data.js.


---

Made by Muhamad Alfi Syuhadak — tinggal edit src/assets/data/data.js untuk kustom cepat.

