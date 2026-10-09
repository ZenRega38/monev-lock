# Monev Lock

Extension Chrome yang mengunci layar mulai pukul **15.00 (Senin–Jumat)** sampai kamu membuka laporan harian di [MagangHub Monev](https://monev.maganghub.kemnaker.go.id/dashboard). Fungsinya sebagai pengingat keras supaya laporan magang tidak terlewat.

> Proyek pribadi, **tidak berafiliasi** dengan Kementerian Ketenagakerjaan atau MagangHub.

## Cara kerja

- Mulai 15.00 di hari kerja, semua tab website ditutup layar penuh yang tidak bisa di-scroll atau diketik.
- Kunci terbuka otomatis saat kamu membuka halaman **Riwayat** (`/dashboard/riwayat`) atau dashboard yang menampilkan "Laporan hari ini sudah diisi".
- Halaman `*.kemnaker.go.id` tidak pernah dikunci, jadi login dan pengisian laporan tetap bisa dilakukan.
- Untuk libur nasional atau cuti, buka popup, ketik `LIBUR`, lalu pilih **Lewati hari ini**.
- Waktu mengikuti jam komputer.

## Pasang manual

1. Download repo ini (Code → Download ZIP), lalu extract.
2. Buka `chrome://extensions` dan nyalakan **Developer mode**.
3. Klik **Load unpacked**, lalu pilih folder `extension/`.

## Privasi

Semua data (tanggal laporan dibuka, tanggal dilewati) disimpan lokal di browser. Lihat [PRIVACY.md](PRIVACY.md).
