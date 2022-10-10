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

### 1. Bagaimana pengaruh kelompok umur terhadap customer dalam berbelanja melalui web? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/1.%20Web%20Comparison.PNG)

Insight:
Customer yang belanja secara online lebih loyal dibandingkan yang langsung belanja di Toko.

Source :
https://www.candyindustry.com/articles/90056-online-grocery-shoppers-more-loyal-to-brands-stores-than-in-store-shoppers

Dapat dilihat pada pie chart visit web total bahwa Customer middle age merupakan pengunjung web terbanyak yaitu sebanyak 58.13% dari total customer.
Dari tempat pembelian item berdasarkan kategori umur juga, Middle age merupakan pembeli melalui web terbanyak yaitu sebesar 33.85%. Sehingga customer Middle age merupakan customer yang paling potensial dalam pembelian item melalui web.

Recomendation :

Tim marketing dapat memberikan promo dalam pembelian item terhadap pengguna baru aplikasi, campaign tersebut dapat disebarkan melalui ads sosial media dengan target umur middle age yaitu 31-50 tahun.

Salah satunya adalah melalui ads instagram, tim marketing dapat mengadakan giveaway untuk mendapatkan lebih banyak customer. Dikutip dari jmango360.com akun instagram yang melakukan giveaway cenderung mengalami pertumbuhan follower 70% lebih cepat dalam 3 bulan.

Source :
https://jmango360.com/blog/11-app-marketing-ideas-ecommerce-stores/

### 2. Item wines cocok untuk customer yang seperti apa?

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/2.%20Spent%20on%20Wine.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa senior age memiliki potensi karena 62% memiliki higher spent pada pembelian wines.

Recomendation :

Faktanya wine memiliki khasiat untuk senior age, dikutip dari thesummitretirement.com beberapa khasiat wine yaitu adalah menurunkan risiko penyakit alzheimer, mengurangi peluang terkena kanker,dan mengurangi peradangan dalam tubuh dengan kadar secukupnya yaitu 2 gelas sehari.

Source :
https://www.thesummitretirement.com/senior-retirement-blog/what-are-the-benefits-of-drinking-red-wine-for-seniors/

Sehingga tim marketing dapat membuat campaign berisi khasiat dari wines untuk senior age dan dapat dipasarkan di panti jompo, seperti sage home care yang membolehkan penghuni untuk meminum wine dengan kadar yang cukup dan merupakan jenis wine yang aman dikonsumsi untuk usia senja seperti Pinot Noir, Rose, Merlot, atau Malbec yang dapat dibeli di toko ini.

Source :
https://www.sagehomecare.com/a-senior-adults-cheatsheet-for-healthy-wines

### 3. Item permen cocok untuk customer yang seperti apa? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/3.%20Spent%20on%20Sweet.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa adult dan senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian permen.

Dikutip dari comfortkeepers.com, banyak nya orang lanjut usia dalam mengonsumsi permen karena semakin bertambahnya usia maka indra pengecap akan semakin berkurang, hal ini yang memicu customer Senior memakan makanan yang terasa lebih manis atau asin.

Source : 
https://www.comfortkeepers.com/articles/info-center/seniors-and-nutrition/controlling-sweet-and-salty-cravings-in-seniors

Recomendation :

Menurut penelitan oleh Elżbieta Bojanowska di University in Warsaw, aktivitas customer Senior banyak dihabiskan dalam kegiatan keagamaan, bersama keluarga, dan aktivitas sosial/komunitas.

Source :
http://www.repozytorium.uni.wroc.pl/Content/58907/PDF/16_Elzbieta_Bojanowska.pdf

Sehingga tim marketing dapat memasarkan produk permen yang rendah kalori yang tersedia di toko ini pada kegiatan sosial yang banyak melibatkan orang dengan usia senja (senior age), salah satu contoh nya adalah kegiatan sosial Alzheimer's Society - Memory Walk di UK yang bertujuan untuk menggalang dana untuk dementia research.

Source :
https://tfn.scot/lists/the-UKs-25-biggest-fundraising-events

Tim marketing juga dapat memasarkan produk melalui ads social media dengan kategori umur adult, hal itu dapat dilakukan karena menurut penelitian yang dilakukan oleh Kevin Norton di University of South Australia, orang dewasa(Adult) menghabiskan 39% kegiatan sehari harinya dengan duduk dan menonton.

Source :
https://www.researchgate.net/figure/The-typical-adult-pattern-of-daily-activities-percentage-of-a-24-h-day-when-categorised_fig1_40683002

### 4. Item daging cocok untuk customer yang seperti apa? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/4.%20Spent%20on%20Meat.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian daging

Recomendation:

Dikutip dari foodmanufacture.co.uk di toko-toko negara eropa sudah banyak menjual daging halal, sehingga tim marketing dapat memasarkan produk daging halal seperti daging sapi, kambing, atau domba di daerah yang banyak penduduk muslim jika toko terletak di negara barat atau eropa. 
Hal ini dikarenakan menurut penelitian yang dilakukan oleh Luis Guerrero di IRTA Monells, produksi daging sapi di negara maju jauh lebih rendah dibandingkan negara berkembang yang menyebabkan tingginya demand warga muslim terhadap daging halal. sehingga tim marketing dapat memberikan brosur terkait penjualan daging halal pada Customer terutama yang termasuk kategori umur senior age.

Source :
https://www.foodmanufacture.co.uk/Article/2016/06/17/Halal-range-launches-with-16-lines-on-Amazon-Fresh#:~:text=Meanwhile%2C%20the%20halal%20brand%2C%20whose,range%20lamb%20and%20beef%20cuts.

Font-i-Furnols, M. and Guerrero, L., 2014. Consumer preference, behavior and perception about meat and meat products: An overview. Meat science, 98(3), pp.361-371.

### 5. Item emas cocok untuk customer yang seperti apa? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/5.%20Spent%20on%20Gold.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian emas.

Banyak nya pembeli emas pada senior age dapat dikarenakan emas merupakan investasi yang paling aman di berbagai kondisi krisis ekonomi seperti yang terjadi pada tahun 1998 dan tahun 2008.

Source:
https://www.cnbc.com/id/38961269

Recomendation :

Tim marketing dapat memberikan campaign bahwa emas yang dibeli melalui toko ini nantinya dapat juga digunakan untuk pembelian produk lain yang tersedia di toko ini, sehingga dapat menaikkan minat customer untuk membeli emas dan pembelian jenis produk lainnya di toko ini. 
Tim marketing juga dapat memberikan semacam undian, dimana pada pembelian item tertentu dengan minimal belanja, pembeli dapat memiliki kesempatan mendapatkan hadiah emas. Sehingga cara ini dapat membuat customer sering melakukan pengecekan item mana yang berhadiah emas.
Seperti pada analisis sebelumnya karena wine dan daging banyak disukai oleh customer senior age maka tim marketing dapat memberikan campaign undian pada item tersebut.

Source : 
https://hypeinsight.com/leveraging-gold-as-an-investment-in-your-marketing-campaigns/

### 6. Item buah cocok untuk customer yang seperti apa?

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/6.%20Spent%20on%20Fruit.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian item jenis buah.

Banyaknya customer senior membeli buah karena dikutip dari nidirect.gov.uk bahwa semakin bertambahnya usia maka metabolisme makin berkurang sehingga dianjurkan untuk memakan makanan yang rendah kalori dan tinggi nutrisi seperti buah.

Source :
https://www.nidirect.gov.uk/articles/healthy-eating-older-adults#:~:text=Eating%20five%20or%20more%20portions,and%20are%20low%20in%20fat.

Recomendation :

Tim marketing dapat menampilkan detail dari kandungan kalori dan nutrisi serta manfaat dari buah tersebut. Detail terkait buah dapat ditaruh di samping buah.

Kurangnya pengetahuan dalam mengolah buah untuk dimasak dapat dimanfaatkan tim marketing dengan membuat kelas memasak saat weekdays bagi customer senior age seperti membuat salad atau jus. Hal ini dikarenakan senior age banyak menghabiskan waktu bersama keluarga sehingga pengetahuan memasak dapat diimplementasikan saat berkumpul bersama keluarga.

Tim marketing juga mempromosikan bahwa buah segar yang digunakan pada kelas memasak tersedia di toko ini.

Source :
https://smallbusiness.chron.com/benefits-driedfish-retailing-16080.html

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
