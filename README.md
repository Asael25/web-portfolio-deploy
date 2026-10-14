# Portfolio Surya Asael, S.Kom 🚀

Website portofolio pribadi modern berkecepatan tinggi yang dibangun menggunakan **Astro v5**, dengan gaya estetika elegan (tipografi serif editorial, aksen coral, hero cutout foto transparan, dan wave background) yang diadaptasi dari materi portofolio resmi Surya Asael.

---

## 🛠️ Tech Stack & Fitur Unggulan

- **Framework**: [Astro v5](https://astro.build) (Static Site Generation dengan performa mendekati 100/100 Core Web Vitals)
- **Styling**: Vanilla CSS kustom dengan CSS Variables & Design Tokens lengkap
- **Aset Asli**:
  - Foto Hero Cutout PNG transparan asli Surya Asael (`/images/surya-hero.png`)
  - Screenshot 7 Proyek Nyata (`/images/projects/`)
  - Direct Download Resume PDF Resmi (`/Resume_Surya_Asael.pdf`)
- **Interaktivitas**:
  - Filter Kategori Proyek real-time (Web Apps, Sistem Laravel / Skripsi, Klien Freelance)
  - Dark Mode & Light Mode Switcher dengan memory `localStorage`
  - Floating Achievement Badges & Card Terminal `whoami.sh`
  - Tombol WhatsApp Direct (`0857-4817-4086`) & Form Email Cepat

---

## 💻 Menjalankan Secara Lokal

1. Pastikan dependensi telah terpasang:
   ```bash
   npm install
   ```

2. Jalankan server pengembangan (Development Server):
   ```bash
   npm run dev
   ```
   Buka peramban di `http://localhost:4321`

3. Melakukan build produksi:
   ```bash
   npm run build
   ```

---

## 🌐 Cara Deploy ke Internet (Gratis & Sangat Mudah)

### Opsi 1: Deploy ke Netlify (Direkomendasikan)
1. Push repositori ini ke akun GitHub Anda:
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit portfolio surya asael"
   git branch -M main
   git remote add origin https://github.com/<username-anda>/<nama-repo>.git
   git push -u origin main
   ```
2. Buka [app.netlify.com](https://app.netlify.com) dan login dengan akun GitHub Anda.
3. Klik **"Add new site"** $\rightarrow$ **"Import an existing project"** $\rightarrow$ Pilih GitHub.
4. Pilih repositori portofolio ini.
5. Konfigurasi build otomatis terdeteksi:
   - **Build command**: `npm run build`
   - **Publish directory**: `dist`
6. Klik **"Deploy site"** — website Anda akan langsung aktif dalam hitungan detik!

### Opsi 2: Deploy ke Vercel
1. Buka [vercel.com](https://vercel.com) dan login dengan GitHub.
2. Klik **"Add New"** $\rightarrow$ **"Project"** $\rightarrow$ Pilih repositori ini.
3. Klik **"Deploy"** (Vercel otomatis mendeteksi Astro).
