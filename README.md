# GREEN FINANCE DATA INSIGHTS
Apa itu Green Finance? Simpelnya, Green Finance adalah kegiatan keuangan apapun yang dilakukan untuk mendukung kelestarian lingkungan yang lebih baik. Misalnya, investasi di sektor energi terbarukan, transportasi ramah lingkungan, atau pertanian organik. Green Finance juga bisa berbentuk instrumen keuangan yang memperhatikan dampak lingkungan, seperti obligasi hijau (investasi yg dalam kegiatan usahanya berhubungan dengan lingkungan), bank hijau (Lembaga keuangan yang menggunakan Teknik pembiayaan inovatif an alat pengembangan pasar melalui kemitraan dengan sector swasta untuk mempercepat penerapan teknologi energi ramah lingkungan), atau pasar karbon mekanisme yang memungkinkan terjadinya negosiasi dan pertukaran hak emisi gas rumah kaca. 

Kenapa Green Finance itu penting? Karena menurut World Bank, Green Finance bisa membantu kita mencapai tujuan ekonomi, sekaligus peduli sama kondisi sosial dan lingkungan. Kalau mau lebih spesifik lagi nih, Green Finance bisa meningkatkan ketahanan energi dan mengurangi emisi gas rumah kaca. Udah tau kan kalau gas rumah kaca itu salah satu penyebab perubahan iklim? Green Finance bisa memberikan manfaat ekonomi dan lingkungan bagi semua pihak, baik individu maupun perusahaan dengan memberikan akses ke barang dan jasa yang ramah lingkungan dan mendorong pertumbuhan yang lebih inklusif.

# TUTORIAL RESEARCH DATA GREEN FINANCE
Setelah tahu apa itu Green Finance, maka sebagai eco tehcno leader, kita akan melakukan analisis terhadap salah satu Green Finance baik itu dalam sebuah perusahaan, proyek, ataupun dalam sektor pemerintahan dengan cara pemahaman komprehensif mengenai konsep, data, dan penerapan analisis prediktif dalam konteks keuangan hijau.

Dalam tutorial ini, kita akan menjelajahi:

Teori Analisis Prediktif: Bagaimana kita dapat menggunakan data historis untuk memprediksi keberhasilan dan risiko proyek hijau.

Dataset Keuangan Hijau: Membedah berbagai variabel dalam dataset yang relevan, mulai dari data finansial, lingkungan, hingga sosial-ekonomi, lengkap dengan regulasi dan acuan akademis.

1. Financial Datasheet / RUMUS Green Net Present Value (GNPV)

Mungkin temen - temen masih inget dengan rumah Present Value (PV) dan Future Value (FV) ? yapz ini ampir sama / modifikasi dari rumus tsb.
jika Future Value (FV) adalah untuk menghitung nilai masa depan, sedangkan present value (PV) untuk menghitung nilai sekarang.

PV = FV / (1 + r)^n, di mana PV adalah Nilai Sekarang, FV adalah Nilai Masa Depan, r adalah tingkat diskonto (bunga), dan n adalah jumlah periode waktu. 

FV = PV x (1 + r)^n, dimana FV adalah nilai masa depan, PV: adalah Present Value atau nilai sekarang, r: adalah tingkat bunga per periode, n: adalah jumlah periode waktu. 

Namun untuk Analisis Green Finance maka :

Rumus : 
```
GNPV = Σ (CFₜ + Eₜ) / (1 + r)ᵗ - I₀
```
misal kita memiliki sebuah sumber file excel 


| Field | Deskripsi |
|-------|-----------|
| `Investment_Amount` | Total dana yang diinvestasikan dalam proyek (Rp). |
| `Loan_Interest_Rate` | Suku bunga pinjaman per tahun (%). |
| `Default_Risk_Score` | Skor risiko gagal bayar (0-100). |
| `Green_Bond_Spread` | Selisih imbal hasil obligasi hijau dan konvensional (bps). |

📌 *Formula:*
```math
GNPV = Σ (CFₜ + Eₜ) / (1 + r)ᵗ - I₀
```

- Mengukur nilai bersih proyek hijau dengan mempertimbangkan manfaat finansial dan lingkungan.
- **Proyek ideal**: GNPV > 0

![GNPV Chart](visualizations/gnpv_bar_chart.png)
