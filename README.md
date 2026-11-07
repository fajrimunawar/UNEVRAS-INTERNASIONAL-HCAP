# INFOTRINK — Website Pengetahuan Multibidang

Website INFOTRINK adalah platform penghimpunan, pengelolaan, dan publikasi pengetahuan multibidang. Dibangun dengan Next.js 16 + TypeScript + Tailwind CSS.

## Struktur Halaman

### Beranda
6 section pengantar (Hero, Pengenalan, Alur, Anatomi, Manfaat, Penutup)

### Publikasi
- Artikel Informasi & Penjelasan (dengan struktur akademis: abstrak, kata kunci, pendahuluan, pembahasan, analisis, kesimpulan, rekomendasi, referensi)
- Hasil Riset dan Penelitian
- Kajian dan Analisis
- Laporan & Catatan Perkembangan
- Data dan Referensi
- Gagasan & Konsep Pengembangan

### Kategori
- **Media Digital** — 7 platform media sosial + 7 platform chatting (dengan logo)
- Pembangunan
- Personal
- Bidang lainnya

### Galeri
- Dokumentasi riset, media digital, pembangunan, personal, visual & infografis

### Mengenal INFOTRINK (5 halaman lengkap)
1. **Pengenalan INFOTRINK** — Apa itu INFOTRINK
2. **Latar Belakang** — Mengapa INFOTRINK ada (5 jejak yang terputus)
3. **Tujuan dan Fungsi** — Untuk apa INFOTRINK (1 tujuan umum, 6 khusus, 6 fungsi)
4. **Ruang Lingkup** — Sampai mana cakupan (3 dimensi: topik, kedalaman, pembaca)
5. **Prinsip Pengelolaan** — Bagaimana dikelola (6 prinsip + siklus)

## Cara Menjalankan

### 1. Install dependencies
```bash
npm install
```
atau
```bash
bun install
```

### 2. Jalankan development server
```bash
npm run dev
```

### 3. Buka browser
Buka http://localhost:3000

### 4. Build untuk production
```bash
npm run build
npm start
```

## Teknologi yang Dipakai

- **Next.js 16** (Turbopack)
- **TypeScript**
- **Tailwind CSS 4**
- **React 19**
- **Next/image** untuk optimasi gambar

## Struktur Folder

```
infotrink/
├── src/
│   ├── app/
│   │   ├── api/              # API routes
│   │   ├── globals.css       # Global styles + scrollbar hidden
│   │   ├── layout.tsx        # Root layout + metadata + favicon
│   │   └── page.tsx          # SEMUA halaman utama (1 file besar)
│   └── components/           # Komponen UI (shadcn/ui)
├── public/
│   ├── slide/                # Gambar AI untuk konten
│   │   ├── pengenalan-hero.png
│   │   ├── pengenalan-pilar.png
│   │   ├── latar-jejak.png
│   │   ├── latar-jalan.png
│   │   ├── tujuan-arah.png
│   │   ├── tujuan-fungsi.png
│   │   ├── ruang-boundary.png
│   │   ├── ruang-kedalaman.png
│   │   ├── prinsip-prisma.png
│   │   ├── prinsip-siklus.png
│   │   ├── office_photo.png
│   │   ├── button1.png, button2.png
│   │   └── logo-*.png (platform logos)
│   ├── favicon.ico / .png    # Favicon multi-size
│   ├── manifest.webmanifest  # PWA manifest
│   ├── artikel-infotrink.pdf # PDF yang bisa didownload
│   └── logo.svg
├── package.json
├── tsconfig.json
├── next.config.ts
├── tailwind.config.ts
├── postcss.config.mjs
├── eslint.config.mjs
├── components.json
└── next-env.d.ts
```

## Fitur Utama

- ✅ **Desain profesional premium** dengan palet teal/emerald
- ✅ **5 halaman Mengenal INFOTRINK** dengan desain berbeda-beda
- ✅ **Animasi overlay menu** dengan L-shaped line animation
- ✅ **Google Translate compatibility** (overlay rendered from start)
- ✅ **CSS zoom responsive** untuk mobile (min 0.5)
- ✅ **Dynamic content height** dengan MutationObserver + ResizeObserver
- ✅ **Favicon system lengkap** (ICO + PNG multi-size + manifest)
- ✅ **Search & pagination** di halaman artikel
- ✅ **Download PDF** button (artikel-infotrink.pdf)
- ✅ **Brand text "INFOTRINK"** dengan translate="no"
- ✅ **Scrollbar hidden** untuk tampilan bersih

## Catatan

- File `src/app/page.tsx` berisi SEMUA kode halaman utama (6200+ baris)
- Untuk ngerubah konten, edit di file `page.tsx`
- Gambar AI di folder `public/slide/` sudah pre-generated
- Project ini siap deploy ke Vercel/Netlify/any Next.js host

---

Dibuat untuk **Muhammad Fajri Munawar**  
INFOTRINK © 2026
