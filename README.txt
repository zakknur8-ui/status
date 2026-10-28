ROAD TO 2030 — UPDATE

Update ini mempertahankan localStorage key road2030 dan seluruh fitur lama.
Perbaikan:
- Tombol Mulai sesi latihan; progres sesi aktif disimpan lokal dan bisa dilanjutkan.
- Checklist gerakan saat latihan.
- Edit nama gerakan dan set/repetisi; tambah gerakan; simpan per program; pulihkan default.
- Mulai program tambahan di hari pemulihan tanpa mengubah jadwal 4 hari.
- Penyelesaian latihan memberi +40 XP sekali per tanggal.
- Cache PWA dinaikkan agar update lebih mudah terpasang.

Pasang: backup JSON dari aplikasi dulu. Unggah isi folder road-to-2030 ke repository Pages dan timpa file lama. Setelah deploy, tutup lalu buka ulang aplikasi; jika masih versi lama, hapus cache situs/service worker browser.
Data aplikasi disimpan lokal di browser/perangkat. Jangan hapus data situs sebelum mengekspor backup.
