# Hotel Booking Analytics Dashboard 

Dashboard interaktif berbasis Tableau untuk menganalisis pola pemesanan hotel, tingkat pembatalan (*cancellation*), rata-rata harga kamar (ADR), dan asal tamu. Dibangun dari dataset publik Hotel Booking Demand.

## 📊 Tentang Project

Project ini menyajikan analisis end-to-end terhadap data pemesanan dua tipe hotel (*City Hotel* & *Resort Hotel*), dengan fokus pada:

1. Tren dan pola pembatalan booking dari waktu ke waktu
2. Perbandingan rata-rata ADR (*Average Daily Rate*) antar segmen pasar
3. Distribusi *lead time* (jarak waktu antara pemesanan dan tanggal kedatangan)
4. Pengaruh tipe deposit terhadap tingkat pembatalan
5. Komposisi tamu berdasarkan tipe pelanggan
6. Sebaran geografis asal tamu

## 🔗 Live Dashboard

🌐 Link: **https://public.tableau.com/views/Hotel_Booking_Analytics/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

## 🖥️ Dashboard


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

Dashboard dilengkapi filter interaktif: Tahun Kedatangan, Tipe Hotel, dan Market Segment.

## 📌 Key Metrics

| Metrik | Nilai |
|---|---|
| Total Booking | 86.677 |
| Rata-rata ADR | €107,19 |
| Rata-rata Lead Time | 80,28 hari |
| Cancellation Rate | 27,7% |

## 💡 Insight Utama

1. Dari chart Monthly Cancellation Trend, bulan dengan cancellation rate tertinggi berbeda antara dua hotel. Untuk City Hotel, puncaknya di bulan April sekitar 35%, sedangkan untuk Resort Hotel puncaknya di bulan Agustus sekitar 32%, kemungkinan karena Resort Hotel lebih terkait musim liburan musim panas, sementara City Hotel polanya lebih ke musim bisnis atau libur sekolah.
2. Segmen Online TA dan Direct punya rata-rata ADR (harga per malam) tertinggi, sekitar €118 sampai €119, sementara segmen Complementary jauh lebih rendah, di kisaran €3.
3. Mayoritas booking dilakukan dengan lead time pendek (di bawah 100 hari sebelum kedatangan), dan jumlah booking makin menurun drastis seiring lead time makin panjang.
4. Booking dengan tipe deposit non-refundable memiliki tingkat pembatalan (cancellation rate) tertinggi, yaitu sekitar 95%, dibandingkan tipe deposit lainnya yang berada di kisaran 25%.
5. Mayoritas tamu dengan 71.398 booking adalah tipe Transient, artinya tamu individual/keluarga.
6. Portugal menjadi negara asal tamu terbanyak, konsisten dengan fakta bahwa dataset ini berasal dari hotel yang berlokasi di Portugal.
## 🗂️ Dataset

Sumber data: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand (Kaggle).
