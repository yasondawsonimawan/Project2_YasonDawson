# Project2_YasonDawson

by Yason Dawson Imawan 

Public Tableau : https://public.tableau.com/app/profile/yason.dawson4391/viz/CustomerPersonalityAnalysis_16654122194520/Dashboard1

## Latar Belakang

Customer Personality Analysis atau Analisis Kepribadian Pelanggan adalah analisis tentang pelanggan yang ideal bagi perusahaan. Ini dapat membantu bisnis untuk lebih memahami pelanggannya dan memudahkan mereka untuk memodifikasi produk sesuai dengan kebutuhan, perilaku, dan perhatian khusus dari berbagai jenis pelanggan.

Analisis kepribadian pelanggan membantu bisnis untuk memodifikasi produknya berdasarkan target pelanggan dari berbagai jenis segmen pelanggan. Misalnya, alih-alih mengeluarkan uang untuk memasarkan produk baru ke setiap pelanggan di database perusahaan, perusahaan dapat menganalisis segmen pelanggan mana yang paling mungkin membeli produk dan kemudian memasarkan produk hanya pada segmen tertentu.
## Define Problem

Menambah customer dengan melakukan segmentasi berdasarkan perilaku

## Business Goals

Melakukan segmentasi customer agar pemasaran tepat sasaran

## Data Understanding

### People

- ID: Identitas unik Customer
- Year_Birth: Tahun Lahir Customer
- Education: Tingkat pendidikan Customer
- Marital_Status: Status pernikahan customer
- Income: Pendapatan rumah tangga tahunan customer
- Kidhome: Jumlah anak dalam rumah tangga customer
- Teenhome: Jumlah remaja dalam rumah tangga customer
- Dt_Customer: Tanggal pelanggan berlangganan dengan perusahaan
- Recency: Jumlah hari sejak pembelian terakhir customer
- Complain: 1 jika customer mengeluh dalam 2 tahun terakhir, 0 sebaliknya

### Products

- MntWines: Jumlah uang yang dihabiskan untuk anggur dalam 2 tahun terakhir
- MntFruits: Jumlah uang yang dihabiskan untuk buah dalam 2 tahun terakhir
- MntMeatProducts: Jumlah uang yang dihabiskan untuk daging dalam 2 tahun terakhir
- MntFishProducts: Jumlah uang yang dihabiskan untuk ikan dalam 2 tahun terakhir
- MntSweetProducts: Jumlah uang yang dihabiskan untuk permen dalam 2 tahun terakhir
- MntGoldProds: Jumlah uang yang dihabiskan untuk emas dalam 2 tahun terakhir

### Promotion

- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 jika customer menerima penawaran pada promosi ke-1, 0 sebaliknya
- AcceptedCmp2: 1 jika customer menerima penawaran pada promosi ke-2, 0 sebaliknya
- AcceptedCmp3: 1 jika customer menerima penawaran pada promosi ke-3, 0 sebaliknya
- AcceptedCmp4: 1 jika customer menerima penawaran pada promosi ke-4, 0 sebaliknya
- AcceptedCmp5: 1 jika customer menerima penawaran pada promosi ke-5, 0 sebaliknya
- Response: 1 jika pelanggan menerima penawaran pada promosi terakhir, 0 sebaliknya

### Place

- NumWebPurchases: Jumlah pembelian yang dilakukan melalui situs web perusahaan
- NumCatalogPurchases:Jumlah pembelian yang dilakukan melalui katalog
- NumStorePurchases: Jumlah pembelian yang dilakukan langsung di toko
- NumWebVisitsMonth: Jumlah kunjungan ke situs web perusahaan dalam sebulan terakhir

## Data Vis


![](https://github.com/yasondawsonimawan/Project2_YasonDawson/tree/main/Screenshoot/Dashboard 1.PNG)


## Kesimpulan
1. Terdapat 88,53% pelanggan yang memiliki pendidikan melalui Perguruan Tinggi;
2. Kemudian, terdapat 64,51% Pelanggan yang memiliki pasangan dengan rata 84% adult dan mature dan 12% adalah young adult;
3. Data Pelanggan menunjukkan bahwa 29% tidak memiliki anak, 50% memiliki 1 anak, 19,38% memiliki 2 anak, dan sisanya memiliki 3 anak;
4. Berdasarkan metode clustering, pelanggan yang tidak memiliki anak dan memiliki 1 anak tersebut berpotensi kontribusi paling besar pada segments stars dan juga high potensial;
5. Anggur menyumbang sebagian besar penjualan unit di seluruh segmen, daging memberikan kontribusi penjualan unit yang signifikan di seluruh segmen, dan gold menjadi populer dalam segmen Need attention & Leaky Bucket;

## Saran :

1. Klustering dari data tersebut lebih dispesifikasikan kembali, seperti cluster 1, 2, 3, dst yang berdasar pada data tersebut seperti umur, income, marital status, jumlah anak, level spending, education, rata-rata deal pembelian, dan offer responds;
2. Disarankan untuk melalukan beberapa metode selain apriori sebagai pembanding tingkat akurasi dari data tersebut.

My original Colabs:
https://colab.research.google.com/drive/182qFHJNUaB3YWAkjnu-j4PFv6RQWBZZA?usp=sharing
