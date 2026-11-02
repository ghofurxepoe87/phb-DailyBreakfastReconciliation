# 🍳 PHB - Breakfast Reconciliation & Audit System
**Platinum Hotel & Convention Balikpapan — Food & Beverage Division**

Sistem digitalisasi audit dan rekonsiliasi buffet sarapan harian untuk memantau disparitas data antara **Night Audit DRR (H-1)** dengan **Realisasi Fisik Tamu Restoran**, guna pencegahan kebocoran pendapatan (*Revenue Protection & Loss Prevention*) serta pengendalian biaya makanan (*Food Cost Control*).

---

## 📌 Fitur Utama Sistem

* **Auto-Calendar Engine:** Kalender otomatis menghitung jumlah hari (28/29/30/31 hari) dan nama hari sesuai bulan dan tahun berjalan.
* **DRR Data Integration (D-1 Night Audit):** Menampung data *Occupied Rooms*, *Room Only (RO)*, *Complimentary + House Use (Comp + HU) Rooms*, dan *In-House Guests*.
* **PMS Entitlement Tracking:** Menghitung hak kuota sistem resmi (*PMS Inclusive + Comp/VIP*) secara presisi.
* **Audit Variance & Leakage Alert:** Mendeteksi selisih kehadiran (*No-Show*) dan otomatis memberikan peringatan (*Alert*) merah berkedip bila terdeteksi tamu tidak terdaftar (*Unbilled Leakage / Over-Pax*).
* **Live Dynamic Rate Settings:** Tarif *Adult Walk-in*, *Kids*, dan *Standard Food Cost* dapat diatur dan disesuaikan langsung di bar navigasi atas dengan kalkulasi otomatis ke seluruh tabel.
* **Audit Trail Accountability:** Dilengkapi pencatatan PIC kasir (*Cashier By*) dan pengawas (*Supervisor on Duty*).
* **Interactive Executive Dashboard:** Visualisasi tren harian dan proporsi tamu berbasis Chart.js dengan label angka langsung pada titik data.
* **Export & Print Ready:** Mendukung ekspor data ke file CSV dan format siap cetak laporan resmi eksekutif (*Print-Ready*).

---

## 🏢 Alur Operasional (SOP Jam 10.30 - 11.00 WITA)

1. **Subuh (04.00 WITA):** Night Audit menerbitkan laporan DRR (Daily Room Report) penutupan malam H-1.
2. **Pagi (06.00 - 10.00 WITA):** Greeter mencatat checklist tamu kamar yang masuk ke restoran, dan kasir melayani transaksi tiket sarapan tambahan (*Walk-in Adult & Kids*).
3. **Closing (10.30 WITA):** Supervisor/Kasir membuka form **+ Post-Breakfast Entry** untuk mencocokkan data DRR H-1 dengan tiket POS dan log greeter.
4. **Verifikasi:** Jika terjadi over-pax/leakage, segera laporkan ke Front Office untuk verifikasi/charge folio kamar sebelum tamu check-out.

---

## 🚀 Live Deployment

Aplikasi ini di-deploy secara otomatis melalui Vercel:
🔗 **[https://phbdailybreakfastreconciliation.vercel.app](https://phbdailybreakfastreconciliation.vercel.app)**

---
*Created & Maintained by Food & Beverage Department — Platinum Hotel & Convention Balikpapan.*
