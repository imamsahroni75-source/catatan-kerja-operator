CATATAN KERJA OPERATOR — VERSI AWAL

Isi:
- index.html: aplikasi
- manifest.webmanifest: identitas PWA
- sw.js: service worker untuk cache/offline dasar

FITUR:
- Empat lembaga awal sesuai permintaan
- Delapan kategori bawaan
- Tambah/edit/hapus tugas
- Status, prioritas, tanggal mulai, deadline, catatan
- Filter lembaga, pencarian, status
- Ringkasan dan ekspor laporan CSV
- Backup dan restore JSON
- PWA installable dengan service worker

PENTING:
Versi ini menyimpan data di localStorage browser/perangkat. Data belum tersinkron antar perangkat dan belum memiliki login Google. Untuk mengaktifkan login Google + cloud diperlukan proyek Firebase, konfigurasi Authentication (Google), Firestore, dan Storage jika lampiran file akan digunakan.

CARA MENJALANKAN:
1. Ekstrak ZIP.
2. Unggah folder ke hosting statis yang mendukung HTTPS (misalnya Firebase Hosting, Netlify, atau GitHub Pages).
3. Buka alamat HTTPS dari HP/komputer.
4. Pilih Install / Tambahkan ke layar utama.

Catatan: PWA dan service worker umumnya memerlukan HTTPS atau localhost.
