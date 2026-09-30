# RANIA MCU 2026 v2.5

Perbaikan utama: Reset transaksi MCU sekarang benar-benar menghapus record attendance dari IndexedDB dan Firestore (jika terhubung), bukan menyimpan record baru berstatus BELUM HADIR. Master peserta tetap aman. Logic Hadir, Selesai, Tidak Hadir, monitoring AFD/jam, historical, filter global, dan export Excel dipertahankan.
