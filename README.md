# Analisis dan Visualisasi Data CO2 Emissions by Car

## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan eksplorasi, analisis, dan visualisasi data mengenai **Emisi CO2 pada Kendaraan (CO2 Emissions by Car)**. Melalui proyek ini, kami mengkaji bagaimana berbagai karakteristik teknis kendaraan memengaruhi jumlah karbondioksida (CO2) yang dilepaskan ke atmosfer. 

Analisis difokuskan pada hubungan antara emisi CO2 dengan variabel-variabel kunci seperti:
* **Ukuran Mesin (Engine Size / Displacement):** Menilai apakah kapasitas mesin yang lebih besar selalu menghasilkan emisi yang lebih tinggi.
* **Jumlah Silinder:** Memahami pengaruh konfigurasi mesin terhadap efisiensi pembakaran.
* **Jenis Bahan Bakar (Fuel Type):** Membandingkan dampak lingkungan antara penggunaan bensin (gasoline), diesel, maupun ethanol.
* **Konsumsi Bahan Bakar:** Menganalisis korelasi tingkat keborosan bahan bakar di area perkotaan (*city*) dan jalan tol (*highway*) terhadap grafik emisi.

Insight yang diperoleh dari proyek ini diharapkan dapat memberikan pemahaman yang lebih baik mengenai efisiensi kendaraan, membantu konsumen dalam memilih mobil ramah lingkungan, serta mendukung kebijakan pengurangan emisi karbon.

Analisis dilakukan menggunakan beberapa teknik visualisasi data dengan bantuan library Python seperti:

- Pandas
- NumPy
- Matplotlib

---

# Tim Kelompok

| Tugas | Nama Lengkap | NIM |
|---------|---------|---------|
| Grafik kategori A (Agregasi) | Rafie Radithya | 21060125130093 |
| Grafik kategori B (Tren/Filter) | Ghassan Iffat Ghaissan | 21060125130063 |
| Grafik kategori C (Korelasi) | Felix Tedja Gunawan | 21060125130117 |
| Grafik kategori D (Distribusi) | Risqi Azka Dwi Saputra | 21060125130064 |
| Grafik gabungan | Keitaro Panglima Joshua Simanjuntak | 21060125130090 |

---

# Pembagian Tugas

## Kategori A (Agregasi)

**Penanggung Jawab:** Rafie Radithya

Hitung rata-rata emisi karbon (CO2_EMISSIONS) berdasarkan tipe bahan bakar (FUEL). Tampilkan dalam Bar Chart.

<p align="center">
  <img src="" width="750">
</p>

---

## Kategori B (Tren/Filter)

**Penanggung Jawab:** Ghassan Iffat Ghaissan

Cari jenis kendaraan (VEHICLE CLASS) dengan tingkat konsumsi bahan bakar (FUEL_CONSUMPTION*) paling hemat. Tampilkan perbandingan efisiensinya dalam Horizontal Bar Chart.

<p align="center">
  <img src="" width="750">
</p>

---

## Kategori C (Korelasi)

**Penanggung Jawab:** Felix Tedja Gunawan

Analisis hubungan antara ukuran mesin (ENGINE_SIZE) terhadap jumlah emisi karbon (CO2_EMISSIONS). Tampilkan dalam Scatter Plot.

<p align="center">
  <img src="" width="750">
</p>

---

## Kategori D (Distribusi)

**Penanggung Jawab:** Risqi Azka Dwi Saputra

Deteksi pencilan (outlier) dari nilai emisi karbon (CO2_EMISSIONS) khusus untuk kendaraan bermerek 'ACURA'. Tampilkan dalam Boxplot.

<p align="center">
  <img src="" width="750">
</p>

---

## Grafik Gabungan

**Penanggung Jawab:** Keitaro Panglima Joshua Simanjuntak

Menggabungkan seluruh grafik kategori A, B, C, dan D dalam satu tampilan visualisasi.

<p align="center">
  <img src="" width="750">
</p>

---


Analisis dan Visualisasi Data CO2 Emissions by Car
Deskripsi Proyek
Proyek ini bertujuan untuk melakukan eksplorasi, analisis, dan visualisasi data mengenai Emisi CO2 pada Kendaraan (CO2 Emissions by Car). Melalui proyek ini, kami mengkaji bagaimana berbagai karakteristik teknis kendaraan memengaruhi jumlah karbondioksida (CO2) yang dilepaskan ke atmosfer.

Analisis difokuskan pada hubungan antara emisi CO2 dengan variabel-variabel kunci seperti:

Ukuran Mesin (Engine Size / Displacement): Menilai apakah kapasitas mesin yang lebih besar selalu menghasilkan emisi yang lebih tinggi.
Jumlah Silinder: Memahami pengaruh konfigurasi mesin terhadap efisiensi pembakaran.
Jenis Bahan Bakar (Fuel Type): Membandingkan dampak lingkungan antara penggunaan bensin (gasoline), diesel, maupun ethanol.
Konsumsi Bahan Bakar: Menganalisis korelasi tingkat keborosan bahan bakar di area perkotaan (city) dan jalan tol (highway) terhadap grafik emisi.
Insight yang diperoleh dari proyek ini diharapkan dapat memberikan pemahaman yang lebih baik mengenai efisiensi kendaraan, membantu konsumen dalam memilih mobil ramah lingkungan, serta mendukung kebijakan pengurangan emisi karbon.

Analisis dilakukan menggunakan beberapa teknik visualisasi data dengan bantuan library Python seperti:

Pandas
NumPy
Matplotlib
Tim Kelompok
Tugas	Nama Lengkap	NIM
Grafik kategori A (Agregasi)	Rafie Radithya	21060125130093
Grafik kategori B (Tren/Filter)	Ghassan Iffat Ghaissan	21060125130063
Grafik kategori C (Korelasi)	Felix Tedja Gunawan	21060125130117
Grafik kategori D (Distribusi)	Risqi Azka Dwi Saputra	21060125130064
Grafik gabungan	Keitaro Panglima Joshua Simanjuntak	21060125130090
Pembagian Tugas
Kategori A (Agregasi)
Penanggung Jawab: Rafie Radithya

Hitung rata-rata emisi karbon (CO2_EMISSIONS) berdasarkan tipe bahan bakar (FUEL). Tampilkan dalam Bar Chart.

Grafik 1 – Rata-Rata Emisi CO2 Berdasarkan Tipe Bahan Bakar
Kategori B (Tren/Filter)
Penanggung Jawab: Ghassan Iffat Ghaissan

Cari jenis kendaraan (VEHICLE CLASS) dengan tingkat konsumsi bahan bakar (FUEL_CONSUMPTION) paling hemat. Tampilkan perbandingan efisiensinya dalam Horizontal Bar Chart.

Grafik 2 – Perbandingan Konsumsi Bahan Bakar per Jenis Kendaraan
Kategori C (Korelasi)
Penanggung Jawab: Felix Tedja Gunawan

Analisis hubungan antara ukuran mesin (ENGINE_SIZE) terhadap jumlah emisi karbon (CO2_EMISSIONS). Tampilkan dalam Scatter Plot.

Grafik 3 – Korelasi Engine Size vs CO2 Emissions
Kategori D (Distribusi)
Penanggung Jawab: Risqi Azka Dwi Saputra

Deteksi pencilan (outlier) dari nilai emisi karbon (CO2_EMISSIONS) khusus untuk kendaraan bermerek 'ACURA'. Tampilkan dalam Boxplot.

Grafik 4 – Deteksi Outlier CO2 Kendaraan ACURA
Grafik Gabungan
Penanggung Jawab: Keitaro Panglima Joshua Simanjuntak

Menggabungkan seluruh grafik kategori A, B, C, dan D dalam satu tampilan visualisasi.

Grafik 5 – Gabungan Semua Kategori
