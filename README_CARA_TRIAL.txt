GTOL · CONTAINER CONTROL TOWER
Web-based Mockup / Offline Trial · 17 November 2026
LeanCore Consulting — Siklus Kontainer Batam–Singapura

=== CARA TERCEPAT ===
1. Buka GTOL_Container_Control_Tower_TRIAL.html menggunakan Chrome/Edge/Firefox.
2. Pilih modul pada sidebar. 15 kontainer data simulasi sudah tersedia.
3. Klik Detail untuk melihat SOP, status, gate tahap dan tombol tindakan.
4. Gunakan menu peran di kanan atas untuk simulasi persetujuan.
5. Tombol Reset Demo mengembalikan seluruh data contoh ke kondisi awal.

Data hasil trial disimpan di localStorage browser apabila tersedia.
Semua data dalam aplikasi adalah DATA SINTETIS / FIKTIF; bukan data produksi GTOL.
Tidak ada backend, autentikasi nyata, koneksi API, email otomatis, atau sinkronisasi multi-pengguna.

=== STRUKTUR MODUL DAN SOP ===
1 Dashboard manajemen & KPI, MT setara LD.
2 Kontainer & Siklus (master satu kontainer satu siklus).
3 Master data & DO | SOP-01 dan SOP-03 | F1–F2, X1.
4 Pergerakan & Verifikasi | SOP-02 dan SOP-03 | F3–F5, X2.
5 Reuse & Sekupang | SOP-04 | F6, X3.
6 Voyage, Slot & RO | SOP-06 / SOP-05 | F7–F8, X4.
7 Early Warning | SOP-05 di seluruh tahap 1–5.
8 Biaya & Penutupan | SOP-07 | F9–F10, X5–X7.
9 Laporan, Audit, CSV/JSON ekspor.
10 Big Map dan 7 SOP serta shortcut skenario.

=== SKENARIO UJI CEPAT ===
Kasus DO mismatch: TLLU 482193-7 / GTOL-2611-001.
Kasus event MT belum diverifikasi: TGHU 510837-2 / GTOL-2611-003.
Kasus reuse menunggu izin: CSQU 892310-4 / GTOL-2611-006.
Kasus MT belum slot / RO hilang: FCIU 291483-9 / GTOL-2611-009.
Kasus amendment belum sinkron dan biaya: TRHU 483910-2 / GTOL-2611-013.

Untuk full-lifecycle UAT: pilih kontainer TLLU dari tahap 1, verifikasi DO,
lanjut tahap, input event UNLOADED_MT, verifikasi, ajukan reuse, ganti peran
TOL Singapura untuk memberi izin, konfirmasi tiba Sekupang, lanjut tahap,
ganti ke Planner Kapal untuk konfirmasi slot dan RO, catat realisasi voyage,
lanjut ke Accounting untuk validasi biaya, invoice, bukti settlement,
dan tutup kewajiban operasional dengan Admin CS sebelum closing akhir.

=== PENTING SEBELUM PRODUKSI ===
Aplikasi ini MOCKUP fungsional. Parameter peran dan warning T-minus adalah
SIMULASI, bukan kewenangan/SLA yang telah disahkan. Sebelum go-live diperlukan:
1. Database terpusat + autentikasi + role/approval berbasis matriks resmi.
2. Integrasi sumber DO, status Tally, TOL Singapore, carrier, RO, Sekupang, biaya.
3. Bukti unggah file dan immutable audit log server.
4. Konfirmasi istilah RO, aturan slot dan prioritas MT setara LD.
5. SLA, nilai ambang pre-alert, escalasi, format waktu/cut-off resmi.
6. Skema retur, jalur Sekupang atau pengecualian, closing & penagihan resmi.
7. UAT bersama pemilik SOP untuk F1-F10 dan X1-X7.

=== VERSI FILE ===
GTOL_Container_Control_Tower_TRIAL.html: satu file tanpa dependensi, langsung dibuka.
index.html + styles.css + app.js: source code yang mudah dikembangkan oleh programmer.
assets/Big_Map_GTOL_Batam_Singapura.png: referensi Big Map sumber.

