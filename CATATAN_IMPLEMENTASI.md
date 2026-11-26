# Rancangan implementasi berikutnya

Web mockup ini adalah prototipe fungsional berbasis HTML/CSS/JavaScript tanpa backend dan tanpa koneksi layanan perusahaan.

## Modul minimum untuk go-live
- Data kontainer dan siklus dengan unique ID, perbedaan status fisik/verifikasi/master.
- Master DO dan pemeriksaan silang bukti, HOLD dengan PIC, waktu, alasan.
- Event pergerakan Tally/sopir; verifikasi SOP-03; bukti penyerahan dan penerima.
- Approval reuse dan perubahan siklus; pemilik aset, tanggal Sekupang, pengembalian.
- Voyage: plan vs confirm vs actual, kapasitas, MT=LD, RO, alasan rollover, register perubahan.
- Early warning lintas proses T-minus yang disahkan; ACK, owner, eskalasi dan bukti closure.
- Amendment dan rekonsiliasi biaya: estimasi, validasi, dispute, invoice, settlement.
- Dashboard harian serta hak akses role-based dan audit permanen.

## Data demo vs data produksi
- Semua kasus kontainer dan biaya adalah sintetis, bukan angka operasional resmi.
- Otorisasi yang dimodelkan di UI hanya untuk simulasi peran.
- Ambang contoh H-2 bukan SLA yang disahkan.
- Definisi RO, jenis bukti, peran, prioritas, limit biaya, freetime dan cut-off harus disahkan perusahaan.
- Kode X1-X7 mengacu ke kelompok dalam Big Map; rincian akar masalah harus mengacu diagram sumber F/X.

## Teknologi implementasi yang disarankan
- Frontend: React atau Vue dengan komponen reusable, design system dari mockup.
- Backend: API berbasis role + validasi gate server.
- Database: PostgreSQL; tabel container, cycle, documents, events, verification, reuse, voyage, ro, alerts, costs, billing, evidence, audit.
- Evidence file: object storage yang aman, virus scanning dan retention policy.
- Notifikasi: email/WhatsApp API setelah consent, tidak diasumsikan tersedia dalam mockup.
- Otentikasi: perusahaan, 2FA jika sesuai kebijakan.
- Audit log append-only, penanganan zona waktu Batam/Singapura dan kalender cut-off.
