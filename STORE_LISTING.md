# Bahan isian Chrome Web Store

## Nama
Monev Lock

## Ringkasan (maks 132 karakter)
Mengunci layar mulai 15.00 (Senin–Jumat) sampai laporan harian MagangHub dibuka. Tidak berafiliasi dengan Kemnaker.

## Deskripsi
Monev Lock membantu peserta magang supaya tidak lupa mengisi laporan harian di MagangHub Monev.

• Mulai pukul 15.00 di hari kerja, setiap tab ditutup layar penuh sampai laporan dibuka.
• Kunci terbuka otomatis saat halaman Riwayat dibuka atau dashboard menampilkan "Laporan hari ini sudah diisi".
• Halaman kemnaker.go.id tidak pernah dikunci, jadi kamu tetap bisa login dan mengisi laporan.
• Ada opsi lewati untuk libur nasional atau cuti.
• Semua data tersimpan lokal. Tidak ada analytics dan tidak ada request jaringan.

Proyek pribadi, tidak berafiliasi dengan Kementerian Ketenagakerjaan RI atau MagangHub.

## Kategori
Productivity (Workflow & Planning)

## Bahasa
Indonesian

## Single purpose
Mengingatkan pengguna mengisi laporan harian MagangHub dengan mengunci layar browser setelah pukul 15.00 di hari kerja sampai halaman laporan dibuka.

## Justifikasi izin
- **storage**: menyimpan tanggal terakhir laporan dibuka dan tanggal lewati, secara lokal.
- **scripting**: menyuntikkan layar kunci ke tab yang sudah terbuka sebelum extension aktif, supaya semua tab ikut terkunci (bukan hanya tab yang baru dibuka).
- **alarms**: memperbarui badge status setiap menit, untuk mengetahui kapan pukul 15.00 tiba.
- **Host permission (<all_urls>)**: layar kunci harus bisa tampil di situs apa pun yang sedang dibuka pengguna. Di monev.maganghub.kemnaker.go.id, extension juga membaca URL dan teks halaman untuk mendeteksi bahwa laporan sudah diisi. Tidak ada data yang dikirim keluar.

## Remote code
Tidak. Semua kode ada di dalam paket extension.

## Data usage
Tidak mengumpulkan data pengguna apa pun. Centang ketiga pernyataan sertifikasi (tidak menjual data, tidak dipakai untuk tujuan lain, tidak untuk menilai kelayakan kredit).

## Privacy policy URL
https://github.com/<username>/monev-lock/blob/main/PRIVACY.md

## Aset yang perlu disiapkan
- Ikon 128×128: `extension/icons/128.png`
- Minimal 1 screenshot 1280×800 atau 640×400: `store/screenshot-lock.png`
- (Opsional) small promo tile 440×280: `store/promo-440x280.png`
