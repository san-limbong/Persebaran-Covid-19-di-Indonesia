# Laporan Proyek Visualisasi Data - San Antonio Limbong
## Domain Proyek
Domain Proyek : **Kesehatan**
Judul : Visualisasi Data: Analisis Persebaran Covid-19 di Indonesia

### Latar Belakang
![image](https://github.com/user-attachments/assets/aab28b18-e593-4d3f-a343-4f759ea2ae3c)

COVID-19 merupakan penyakit yang saat ini telah menjadi pandemi global. Pandemi ini dimulai di Wuhan, Tiongkok, dan telah menyebar ke seluruh dunia sejak akhir tahun 2019. COVID-19 dapat menginfeksi individu dari segala usia dan status ekonomi. Namun, orang yang berisiko tinggi mengalami perjalanan penyakit yang parah atau fatal adalah individu yang lebih tua dan mereka dengan komorbiditas seperti diabetes, kanker, dan penyakit kronis lainnya.

Berdasarkan [paper](https://www.researchgate.net/profile/Boya_Nugraha/publication/344470300_COVID-19_Pandemic_in_Indonesia_Situation_and_Challenges_of_Rehabilitation_Medicine_in_Indonesia/links/5f7d6acda6fdccfd7b4ca6e6/COVID-19-Pandemic-in-Indonesia-Situation-and-Challenges-of-Rehabilitation-Medicine-in-Indonesia.pdf) kasus pertama pasien COVID-19 di Indonesia, diidentifikasi pada 2 Maret 2020 di Depok. Sejak akhir Agustus 2020, jumlah kasus baru yang terkonfirmasi positif di Indonesia telah mencapai lebih dari dua ribu per hari.

Pemerintah di berbagai negara umumnya dengan sigap membentuk gugus tugas (task force unit) untuk menangani penyebaran COVID-19 di masyarakat, termasuk pemerintah di Indonesia. Salah satu langkah yang diambil oleh pemerintah adalah mengumpulkan dan menyediakan data pertumbuhan kasus COVID-19 kepada publik. Namun, data tersebut masih dalam bentuk tabel yang sulit dipahami oleh semua orang. Oleh karena itu, tujuan dari proyek ini adalah mengembangkan dasbor dan grafik visualisasi yang mendukung agar masyarakat dapat lebih mudah memahami informasi yang disajikan.

## Pertanyaan Analisis
1. Berapa total kasus COVID-19 di Indonesia?
2. Berapa total kasus sembuh COVID-19 di Indonesia?
3. Berapa total kasus kematian yang disebabkan oleh COVID-19 di Indonesia?
4. Bagaimana perincian jumlah kasus per Hari oleh COVID-19 di Indonesia?
5. Bagaimana persebaran COVID-19 di Indonesia?

## Data Understanding
### EDA - Deskripsi Variabel
**Informasi Datasets**

| Jenis | Keterangan |
| ------ | ------ |
| Title | COVID-19 Indonesia Dataset |
| Source | [Kaggle](https://www.kaggle.com/datasets/hendratno/covid19-indonesia/data) |
| License | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |
| Visibility | Publik |
| Tags | _Business, Health, Coronavirus, Public Health, Diseases_ |
| Usability | 10.00 |

Berikut informasi pada dataset: 

| Date       | Location ISO Code | Location    | New Cases | New Deaths | New Recovered | New Active Cases | Total Cases | Total Deaths | Total Recovered | Total Active Cases | Location Level | City or Regency | Province   | Country   | Continent | Island | Time Zone     | Special Status          | Total Regencies | Total Cities | Total Districts | Total Urban Villages | Total Rural Villages | Area (km²) | Population  | Population Density | Longitude    | Latitude       | New Cases per Million | Total Cases per Million | New Deaths per Million | Total Deaths per Million | Total Deaths per 100k | Case Fatality Rate | Case Recovered Rate | Growth Factor of New Cases | Growth Factor of New Deaths |
|------------|-------------------|-------------|-----------|------------|---------------|------------------|-------------|--------------|-----------------|--------------------|----------------|-----------------|------------|-----------|-----------|--------|----------------|-------------------------|-----------------|--------------|----------------|---------------------|---------------------|-------------|-------------|--------------------|--------------|----------------|-----------------------|------------------------|------------------------|-------------------------|----------------------|---------------------|---------------------|-----------------------------|-----------------------------|
| 3/1/2020   | ID-JK             | DKI Jakarta | 2         | 0          | 0             | 2                | 39          | 20           | 75              | -56                | Province       |                 | DKI Jakarta | Indonesia | Asia      | Jawa   | UTC+07:00      | Daerah Khusus Ibu Kota  | 1               | 5            | 44             | 267                 |                     | 664         | 10,846,145 | 16,334.31          | 106.8361183  | -6.204698991   | 0.18                  | 3.60                   | 0.00                   | 1.84                    | 0.18                 | 51.28%              | 192.31%             |                             |                             |
| 3/2/2020   | ID-JK             | DKI Jakarta | 2         | 0          | 0             | 2                | 41          | 20           | 75              | -54                | Province       |                 | DKI Jakarta | Indonesia | Asia      | Jawa   | UTC+07:00      | Daerah Khusus Ibu Kota  | 1               | 5            | 44             | 267                 |                     | 664         | 10,846,145 | 16,334.31          | 106.8361183  | -6.204698991   | 0.18                  | 3.78                   | 0.00                   | 1.84                    | 0.18                 | 48.78%              | 182.93%             | 1.00                        | 1.00                        |
| 3/2/2020   | IDN               | Indonesia   | 2         | 0          | 0             | 2                | 2           | 0            | 0               | 2                  | Country        |                 |            | Indonesia | Asia      |        |                |                         | 416             | 98           | 7,230          | 8,488               | 74,953              | 1,916,907   | 265,185,520 | 138.34             | 113.921327   | -0.789275      | 0.01                  | 0.01                   | 0.00                   | 0.00                    | 0.00                 | 0.00%               | 0.00%               |                             |                             |

Would you like this table in a different format or additional information added?


_Tabel 1. EDA Deskripsi Variabel_

Berikut penjabaran singkat dari dataset yang digunakan. 
- Dataset berupa CSV (Comma-Seperated Values).
- Dataset memiliki 31.8 ribu sampel dengan 38 fitur.
- Dataset memiliki 15 fitur bertipe int, 10 fitur bertipe string, 8 fitur bertipe float64 dan 5 Other.

## Dashboard
Anda dapat mengakses tautan berikut untuk mengakses dashboard pada tableau. [Klik disini](https://public.tableau.com/app/profile/san.antonio.limbong/viz/DashboarddataCovid-19diIndonesia/Dashboard)

![Dashboard](https://github.com/user-attachments/assets/4647a1d2-71f7-471a-8c07-d24cc1f45993)
