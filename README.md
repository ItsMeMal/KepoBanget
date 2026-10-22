# KepoBanget

Website kuis kepribadian dan hiburan berbahasa Indonesia, dibuat dengan HTML, CSS, dan JavaScript tanpa framework.

## Fitur
- 10 kuis interaktif dengan hasil berdasarkan jawaban.
- Tombol berbagi hasil memakai Web Share API atau salin teks.
- Tampilan responsif untuk desktop dan ponsel.
- Pencarian dan filter kategori kuis.
- Adsterra Native Banner dan Popunder.
- Favicon, metadata SEO, canonical URL, structured data, robots.txt, dan sitemap.xml.

## Deploy ke Vercel
1. Import repository `ItsMeMal/KepoBanget` di https://vercel.com/new.
2. Framework Preset: **Other**.
3. Root Directory: root repository.
4. Build Command: kosongkan.
5. Output Directory: kosongkan atau gunakan `.` jika dashboard meminta nilai.
6. Deploy. Push baru ke branch `main` akan memicu deployment bila integrasi Git Vercel aktif.

## SEO dan indexing
- Situs menetapkan canonical URL ke `https://kepobanget.vercel.app/`.
- Sitemap tersedia di `https://kepobanget.vercel.app/sitemap.xml`.
- Robots rules tersedia di `https://kepobanget.vercel.app/robots.txt`.
- Setelah deployment selesai, daftarkan properti domain di [Google Search Console](https://search.google.com/search-console/) dan submit sitemap tersebut. Gunakan URL Inspection untuk meminta pengindeksan homepage.
- SEO tidak menjamin posisi atau waktu masuk hasil pencarian. Google perlu meng-crawl dan mengevaluasi situs terlebih dahulu.

## Iklan
Script resmi Adsterra Native Banner dan Popunder dipasang di `index.html`. Jika mengubah atau mengganti kode iklan, gunakan snippet persis seperti dari dashboard publisher. Periksa tampilan di desktop dan ponsel serta pastikan iklan tidak menutupi navigasi atau konten.

## Catatan
Semua hasil kuis adalah hiburan, bukan penilaian psikologis, diagnosis, atau nasihat profesional. Website tidak memakai database atau login.
