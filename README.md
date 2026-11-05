# Ocean Developer Portfolio

Website statis HTML/CSS/JavaScript. Tidak perlu npm, backend, atau API key.

## Menjalankan dengan Git Bash
```bash
cd ocean-portfolio
python -m http.server 5500
```
Buka http://localhost:5500 di browser laptop. Jika `python` tidak ditemukan, coba `py -m http.server 5500` (Windows), atau buka `index.html` langsung.

## Membuka dari HP (jaringan Wi-Fi yang sama)
1. Di Git Bash jalankan `python -m http.server 5500 --bind 0.0.0.0`.
2. Di Windows jalankan `ipconfig` dan cari IPv4 Address Wi-Fi, contoh 192.168.1.5.
3. Buka `http://192.168.1.5:5500` dari browser HP. Izinkan akses jaringan privat jika firewall meminta. Alamat contoh harus diganti IP laptop asli.

## Kontak
Tautan email menggunakan `mailto:` di `index.html`. Ubah alamat email di bagian kontak jika diperlukan. Ubah tautan Instagram, TikTok, dan WhatsApp melalui `SOCIAL` di bagian atas `script.js`. WhatsApp memakai format `628...`, tanpa tanda plus dan tanpa nol depan.

## GitHub Pages (agar bisa dibuka dari mana saja)
Buat repository publik baru di GitHub, kemudian dari folder proyek:
```bash
git init
git add .
git commit -m "Initial ocean portfolio"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA_REPO.git
git push -u origin main
```
Ganti USERNAME dan NAMA_REPO, lalu di GitHub buka Settings > Pages > Deploy from a branch > main > /(root) > Save. URL biasanya `https://USERNAME.github.io/NAMA_REPO/`. Perlu Git terinstal dan login GitHub.
