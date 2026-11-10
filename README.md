# Portofolio Profesional — Rivaldi Ardiansyah

Website portofolio statis modern tanpa ketergantungan gambar eksternal (100% bebas *broken image*), mengandalkan tipografi *High-Impact Hook*, tata letak *Dark Glassmorphism*, serta konfigurasi siap pakai untuk **GitHub** & **Vercel**.

## Struktur File
- `index.html` — Struktur utama halaman & konten CV Rivaldi Ardiansyah
- `style.css` — Desain responsif, animasi *ambient glow*, dan sistem grid modern
- `script.js` — Interaktivitas navigasi mobile, *scroll reveal*, dan ikon
- `vercel.json` — Konfigurasi *routing* dan keamanan *headers* untuk Vercel agar *zero-error* saat *deploy*

## Cara Deploy ke GitHub & Vercel (Anti Gagal)
1. **Ekstrak File ZIP:** Ekstrak `portofolio-rivaldi-vercel-ready.zip` di komputer/HP Anda.
2. **Buat Repository GitHub:**
   - Buka [github.com/new](https://github.com/new) dan beri nama `portofolio-rivaldi`.
   - Klik **Create repository**, lalu pilih tautan **uploading an existing file**.
   - Upload kelima file (`index.html`, `style.css`, `script.js`, `vercel.json`, `README.md`) langsung ke halaman tersebut (pastikan `index.html` berada di luar/di tingkat utama, bukan terbungkus sub-folder berlapis).
   - Klik **Commit changes**.
3. **Hubungkan ke Vercel:**
   - Buka [vercel.com](https://vercel.com) dan login dengan akun GitHub.
   - Klik **Add New...** -> **Project** -> Pilih repository `portofolio-rivaldi` -> Klik **Import**.
   - Biarkan **Framework Preset** pada pilihan **Other**, lalu langsung klik **Deploy**.
