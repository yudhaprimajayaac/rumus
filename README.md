# Kalkulator Budget & Bid Iklan

Kalkulator budget harian & bid kata pencarian untuk iklan marketplace.
Static single-page app (HTML/CSS/JS murni, tanpa build step).

## Cara deploy ke Vercel via Git

1. Buat repo baru di GitHub (atau GitLab/Bitbucket).
2. Di folder ini, jalankan:
   ```bash
   git init
   git add .
   git commit -m "Kalkulator budget iklan"
   git branch -M main
   git remote add origin https://github.com/USERNAME/NAMA-REPO.git
   git push -u origin main
   ```
3. Buka https://vercel.com/new, pilih "Import Git Repository", lalu pilih repo yang baru dibuat.
4. Framework Preset: pilih **Other** (tidak perlu build command, tidak perlu install command, output directory kosongkan / biarkan default).
5. Klik **Deploy**. Selesai — Vercel akan otomatis mendeteksi `index.html` sebagai halaman utama.

Setiap kali kamu `git push` ke branch `main`, Vercel otomatis re-deploy versi terbaru.

## Menjalankan lokal (opsional)

Cukup buka `index.html` langsung di browser, atau jalankan server statis sederhana:
```bash
npx serve .
```
