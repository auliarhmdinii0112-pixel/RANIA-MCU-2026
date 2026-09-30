# RANIA MCU 2026 v0.7

Prototype RANIA dengan master peserta terkunci dan attendance/status dipisahkan.

- Master: read-only dari dashboard
- Status: BELUM HADIR / HADIR-PROSES / MCU SELESAI / TIDAK HADIR
- Salah input dapat di-Reset per peserta tanpa mengubah master
- Refresh browser tidak menghapus status yang sudah tersimpan
- Import Excel mengganti master dan mereset status attendance
- Export Excel tetap tersedia

Untuk produksi, pindahkan master dan attendance ke Firebase Auth + Firestore. Security Rules dapat membatasi field master agar tidak dapat diubah client.
