# Coffee-Shop
Coffee Shop Analysis

## Daftar Isi
* Business Understanding
* EDA
* Kesimpulan
  
## Business Understanding
### 1. Latar Belakang Bisnis
Industri ritel makanan dan minuman (*Food & Beverages*), khususnya kedai kopi (*coffee shop*), memiliki dinamika operasional yang sangat bergantung pada waktu transaksi, efisiensi operasional, dan perputaran inventaris. Persaingan yang ketat menuntut manajemen untuk tidak hanya mengandalkan intuisi, melainkan mengambil keputusan berbasis data (*data-driven decision making*) guna menjaga profitabilitas dan kepuasan pelanggan.

Melalui data transaksi harian, bisnis dapat menggali pola konsumsi pelanggan, mengidentifikasi produk unggulan maupun yang kurang diminati, serta mengantisipasi lonjakan permintaan pada jam-jam tertentu.

---

### 2. Rumusan Masalah (Problem Statements)
Berdasarkan kebutuhan operasional dan strategi penjualan, tantangan bisnis yang dihadapi meliputi:
1. **Pola Fluktuasi Permintaan:** Manajemen belum memiliki visibilitas yang presisi mengenai waktu puncak (*peak hours*) dan hari dengan volume transaksi tertinggi, sehingga sering terjadi ketidaksesuaian penjadwalan staf (*overstaffing* atau *understaffing*).
2. **Kinerja & Kontribusi Produk:** Belum terpetakannya kategori produk dan menu mana saja yang menjadi pendorong utama pendapatan versus produk yang mengalami perlambatan penjualan (*slow-moving*).
3. **Optimasi Nilai Transaksi:** Rata-rata nilai belanja per transaksi (*Average Order Value* / AOV) belum optimal karena ketiadaan strategi promosi atau *cross-selling/bundling* yang didasari oleh pola pembelian riil pelanggan.

---

### 3. Tujuan Bisnis (Business Goals)
Proyek analitik ini dirancang untuk mencapai beberapa tujuan strategis:
- **Optimalisasi Operasional:** Memberikan panduan berbasis data untuk penjadwalan jam kerja barista/staf dan manajemen persiapan bahan baku (*prep-time*) berdasarkan lonjakan jam transaksi.
- **Efisiensi Portofolio Menu:** Mengkategorikan menu berdasarkan volume penjualan dan kontribusi pendapatan guna membantu keputusan restrukturisasi menu atau eliminasi produk *slow-moving*.
- **Peningkatan Pendapatan:** Mengidentifikasi peluang *upselling* dan *bundling* produk (misal: kombinasi minuman dan makanan ringan/pastry) untuk meningkatkan rata-rata belanja pelanggan.

---

### 4. Metrik Keberhasilan (Success Metrics / KPIs)
Keberhasilan dari inisiatif analisis ini diukur melalui indikator kinerja utama berikut:
- **Total Revenue & Volume:** Pertumbuhan total pendapatan kotor dan total unit produk terjual.
- **Average Order Value (AOV):** Peningkatan nominal rata-rata transaksi per pelanggan setelah rekomendasi strategi diterapkan.
- **Peak Hours & Transaction Velocity:** Akurasi prediksi jam sibuk untuk menekan waktu tunggu pesanan (*service lead time*).
- **Product Sales Contribution (%):** Persentase kontribusi masing-masing kategori produk terhadap total omzet bisnis.

### Exploratory Data Analysis / EDA

## Dashboard

**Store Performance**
<img width="1329" height="735" alt="Store Performance" src="https://github.com/yesayass/Coffee-Shop/blob/main/Store%20Performance.png" />

**Product Diagnostic**
<img width="1329" height="735" alt="Product Diagnostic" src="https://github.com/yesayass/Coffee-Shop/blob/main/Product%20Diagnostic.png" />

**Category Diagnostic**
<img width="1329" height="735" alt="Category Diagnostic" src="https://github.com/yesayass/Coffee-Shop/blob/main/Category%20Diagnostic.png" />

**Time Diagnostic**
<img width="1329" height="735" alt="Time Diagnostic" src="https://github.com/yesayass/Coffee-Shop/blob/main/Time%20Diagnostic.png" />

**Strategic Verdict**
<img width="1329" height="735" alt="Strategic Verdict" src="https://github.com/yesayass/Coffee-Shop/blob/main/Strategic%20Verdict.png" />

## Link Power BI
**Link Dashboard Power BI** <a href="https://github.com/yesayass/Coffee-Shop/blob/main/Coffee_Shop.pbix">View Dashboard
  
## Kesimpulan
1. Jumlah transaksi memengaruhi peningkatan Revenue. Kontribusi total revenue produk tidak selaras dengan total quantity produk. Barista Expresso memiliki kontribusi revenue tertinggi, sementara Brewed Chai Tea memiliki total quantity tertinggi.
2. Lokasi Penjualan mempengaruhi peningkatan Revenue. Penjualan tetinggi selama Q1 2023 berada di cabang Hell’s Kitchen (236.5K), sementara penjualan terendah berada di Lower Manhattan (230.1K)
3. Jenis Produk mempengaruhi peningkatan Revenue. Revenue tertinggi diperoleh Sustainably Grown Organik Lg
4. Perbedaan harga mempengaruhi peningkatan Revenue. Revenue tertinggi diperoleh Sustainably Grown Organik Lg, sementara Earl Grey Rg memiliki quantity tertinggi. Produk murah tidak membuat produk tersebut memiliki revenue maupun quantity tinggi.
5. Waktu transaksi mempengaruhi peningkatan Revenue. Puncak penjualan berada di jam 8-10 pagi (diatas 80K pelanggan).
