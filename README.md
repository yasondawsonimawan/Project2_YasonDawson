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

## Business Question

### 7. Item ikan cocok untuk customer yang seperti apa?


![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/7.%20Spent%20on%20Fish.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa adult dan senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian item jenis ikan.

Dikutip dari maplewoodseniorlivin.com banyaknya orang di usia senja mengonsumsi ikan dikarenakan banyaknya terkandung asam lemak omega 3 yang berkhasiat untuk mengurangi peradangan sendi, mengurangi risiko depresi, ADHD, serta diabetes.

Source :
https://www.maplewoodseniorliving.com/blog/how-eating-fish-keeps-seniors-healthy-maplewood/#:~:text=Fish%20Help%20You%20Have%20a%20Healthy%20Heart&text=These%20omega%2D3%20fatty%20acids,types%20of%20dementia%2C%20and%20diabetes.

Recomendation :

Tim marketing dapat mengadakan festival seafood seperti THE DORSET SEAFOOD FESTIVAL di UK dengan mengundang chef terkenal untuk merepresentasikan masakan berbahan ikan, acara musik, dan tempat bersantai yang nyaman sebagai daya tarik pengunjung. Pada festival tersebut, tim marketing dapat menyampaikan bahwa Ikan segar yang digunakan tersedia di toko ini.

Source :
https://www.dorsetseafood.co.uk/News/82/SEAFEAST_%E2%80%93_The_Dorset_Seafood_Festival/
