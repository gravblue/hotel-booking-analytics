# 🏨 Hotel Booking Analytics Dashboard

Dashboard interaktif berbasis Tableau untuk menganalisis pola pemesanan hotel, tingkat pembatalan (*cancellation*), rata-rata harga kamar (ADR), dan asal tamu. Dibangun dari dataset publik Hotel Booking Demand.

## 📊 Tentang Project

Project ini menyajikan analisis end-to-end terhadap data pemesanan dua tipe hotel (*City Hotel* & *Resort Hotel*), dengan fokus pada:

- Tren dan pola pembatalan booking dari waktu ke waktu
- Perbandingan rata-rata ADR (*Average Daily Rate*) antar segmen pasar
- Distribusi *lead time* (jarak waktu antara pemesanan dan tanggal kedatangan)
- Pengaruh tipe deposit terhadap tingkat pembatalan
- Komposisi tamu berdasarkan tipe pelanggan
- Sebaran geografis asal tamu

## 🔗 Live Dashboard

🌐 Link: **https://public.tableau.com/views/Hotel_Booking_Analytics/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

## 🖥️ Isi Dashboard


| Komponen | Deskripsi |
|---|---|
| KPI Total Bookings | Total jumlah pemesanan |
| KPI Avg ADR | Rata-rata harga kamar per malam |
| KPI Cancellation Rate | Persentase pembatalan booking |
| KPI Avg Lead Time | Rata-rata jarak hari antara booking & kedatangan |
| Monthly Cancellation Trend | Tren pembatalan bulanan |
| Average ADR by Market Segment | Perbandingan ADR per segmen pasar |
| Lead Time Distribution | Distribusi lead time tamu |
| Cancellation Rate by Deposit Type | Pembatalan berdasarkan jenis deposit |
| Bookings by Customer Type | Jumlah booking per tipe pelanggan |
| Guest Origin Map | Peta asal negara tamu |

Dashboard dilengkapi filter interaktif: **Tahun Kedatangan**, **Tipe Hotel**, dan **Market Segment**.

## 🗂️ Dataset

Sumber data: dataset publik **Hotel Booking Demand** (Kaggle).
