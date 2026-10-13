# Entri Jurnal Umum

Form jurnal umum sederhana dengan frontend HTML/CSS/JavaScript, backend Node.js, dan Supabase/Postgres.

## Struktur

- `frontend/` — halaman dan interaksi form.
- `backend/app.js` — server HTTP, API, dan penyaji file frontend.
- `backend/schema.sql` — skema database, akun contoh, kebijakan akses, dan fungsi penyimpanan jurnal.

## Menjalankan

1. Jalankan `backend/schema.sql` di SQL Editor proyek Supabase.
2. Pastikan Node.js 18 atau lebih baru tersedia.
3. Atur variabel lingkungan `SUPABASE_URL` dengan URL proyek dan `SUPABASE_SERVICE_ROLE_KEY` dengan service role key Supabase. Jangan pernah menaruh service role key di frontend atau membagikannya ke publik.
4. Dari folder proyek, jalankan `node backend/app.js`.
5. Buka `http://localhost:3000`.

Server hanya menggunakan modul bawaan Node.js sehingga tidak memerlukan `package.json` atau instalasi package.
