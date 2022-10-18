# Iaas, SaaS, dan PaaS

## Perbedaan antara IaaS, SaaS, dan Paas

![image-01.jpg](https://github.com/kareeems/tekn-cloud-computing/blob/main/minggu-02/image-01.jpg)

dari gambar di atas digambarkan

1. Dalam kasus dibuat di rumah, itu berarti lingkungan di tempat Anda di mana Anda mengelola semuanya yaitu Anda membuat keju, topping, adonan pizza Anda sendiri, Anda memiliki oven sendiri, gas dll dan Anda membuat semuanya sendiri dan makan di rumah. Anda mengontrol seberapa baik (atau buruk) pizza Anda
   
2. Dalam hal IaaS, Anda membeli bahan mentah (yaitu lingkungan komputasi, disk penyimpanan, OS Anda, dll.) dari Penyedia Layanan Cloud Anda. Infrastruktur akan diberikan kepada Anda oleh Penyedia Cloud dan Anda tidak akan memiliki kendali penuh atasnya (Anda tidak akan tahu di mana tepatnya server Anda, di mana disk Anda, dll). Tetapi Anda mengontrol tentang bagaimana penambalan dilakukan pada OS Anda, beban kerja apa yang Anda miliki di lingkungan Anda, dll
   
3. Di PaaS, Anda membeli pizza di luar dan memakannya di rumah - yaitu Anda tidak perlu khawatir tentang cara mengontrol konfigurasi database, loadbalancer, dll. Mereka disediakan untuk Anda sebagai layanan terkelola oleh penyedia layanan cloud Anda. Tugas-tugas seperti back up database dll dapat didorong ke akhir penyedia layanan dan Anda hanya dapat berkonsentrasi pada membangun dan menyebarkan aplikasi Anda. Tingkat sumber daya yang Anda kendalikan berkurang

4. Dalam model SaaS, sebagian besar layanan dikelola oleh penyedia layanan Anda dan jumlah konfigurasi atau pengaturan di pihak Anda minimal.

5. Jumlah kontrol yang Anda miliki pada sumber daya cloud Anda terus berkurang saat Anda bergerak ke kanan dalam diagram (Kontrol tertinggi pada IaaS hingga kontrol terendah pada SaaS)

## SaaS
Perangkat lunak sebagai layanan adalah lisensi perangkat lunak dan model pengiriman di mana perangkat lunak dilisensikan secara berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web.

SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan perpesanan, perangkat lunak manajemen, virtualisasi, dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

Penyedia SaaS menghosting aplikasi dan data secara terpusat — menyebarkan tambalan. Mereka meningkatkan ke aplikasi secara transparan, memberikan akses ke pengguna akhir melalui Internet. 

### Arsitektur SAAS:

Dengan model ini, satu versi aplikasi, dengan konfigurasi tunggal digunakan untuk semua pelanggan. Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal).

Ada dua jenis utama SaaS:

* SaaS Vertikal
  
    Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk perawatan kesehatan, pertanian, real estat, industri keuangan)

* SaaS Horisontal
  
    Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

### Manfaat SAAS:

Ini menawarkan peluang besar bagi organisasi dari semua ukuran untuk mengalihkan risiko akuisisi perangkat lunak, dan untuk memindahkan TI dari pusat biaya reaktif menjadi bagian perusahaan yang proaktif dan menghasilkan nilai.

Integrasi dapat direncanakan dan dilaksanakan dengan sedikit usaha, menciptakan salah satu interval waktu-ke-nilai sesingkat mungkin untuk investasi TI besar.

Setelah Anda membuat keputusan untuk mengejar SaaS, langkah selanjutnya adalah mempersiapkan transisi dengan menilai bagaimana penerapan akan memengaruhi aset TI yang ada.
Menambahkan SaaS dapat menyebabkan perubahan mendasar dalam peran departemen TI sebagai penyedia layanan informasi.

Perusahaan sebaiknya mempertimbangkan fleksibilitas dan implikasi manajemen risiko dari penambahan SaaS ke portofolio layanan TI mereka. Integrasi dan komposisi adalah komponen penting dalam strategi arsitektur Anda untuk menggabungkan SaaS dengan sukses sebagai anggota yang berpartisipasi penuh dari infrastruktur TI Anda yang berpusat pada layanan.

### Arsitektur Perangkat Lunak sebagai Layanan SaaS

Pengiriman perangkat lunak telah berubah selama bertahun-tahun. Secara historis, aplikasi ditulis untuk mainframe dalam bahasa seperti COBOL. Didukung oleh komputasi awan, konsumen dan bisnis dapat menggunakan layanan melalui web hanya dengan beberapa klik mouse. SaaS lahir – Perangkat Lunak sebagai Layanan.

Apa Itu Platform Arsitektur SaaS?

SaaS adalah cara untuk memberikan perangkat lunak, penyedia perangkat lunak secara terpusat menghosting satu atau lebih aplikasi dan membuatnya tersedia untuk pelanggan melalui internet. Arsitektur SaaS juga merupakan salah satu pilar utama komputasi awan. 

berikut adalah termasuk model SaaS:

* Infrastruktur sebagai Layanan
* Platform sebagai Layanan
* Pembelajaran Mesin sebagai Layanan
* …dan banyak lagi!
  
###  Alasan Menggunakan Arsitektur SaaS

#### KONSUMEN
Dari sudut pandang konsumen, aplikasi SaaS adalah salah satu cara termudah dan paling dapat diandalkan untuk menggunakan layanan atau produk digital. Anda cukup mengaksesnya melalui web, membayar layanan, dan menggunakannya.

Dalam beberapa tahun terakhir kami telah melihat munculnya ribuan layanan aplikasi SaaS yang ditargetkan untuk konsumen seperti:

* Netflix
* Microsoft Office 365
* Amazon Perdana
* Twitter
* Facebook
* Google Dokumen
* Tenaga penjualan

Pendekatan swalayan ini memungkinkan pengguna untuk bangun dan berjalan dengan cepat.

#### BISNIS
Dari perspektif bisnis, produk perangkat lunak yang disampaikan “sebagai layanan” memungkinkan bisnis menawarkan produk mereka dalam skala besar, secara global, sementara juga memungkinkan mereka untuk mempertahankan kontrol keseluruhan atas produk mereka. 

Beberapa manfaat lain dari penerapan arsitektur SaaS dalam bisnis termasuk, namun tidak terbatas pada:

* Mengurangi waktu ke pasar;
* Biaya perawatan yang lebih rendah;
* Peningkatan otomatisasi;
* Upgrade lebih mudah;
* Lebih hemat biaya;
  
Uji coba instans tunggal dapat dilakukan karena perusahaan tidak perlu menghabiskan banyak sumber daya keuangan untuk mencoba perangkat lunak.

Bisnis dapat dengan mudah mengintegrasikan komponen SaaS ini ke dalam aplikasi mereka yang ada dan menambah fungsionalitas yang mereka tawarkan kepada pelanggan mereka.

### Fitur Utama Dan Manfaat Platform Arsitektur SaaS
1. KESEDERHANAAN APLIKASI ARSITEKTUR SAAS
   
    Aplikasi perangkat lunak yang dirancang sebagai solusi SaaS biasanya diakses melalui web melalui berbagai jenis perangkat.

2. NILAI EKONOMIS
    Model pembayaran biaya berlangganan bulanan atau tahunan memudahkan bisnis untuk menganggarkan, memasangkan ini dengan nol biaya penyiapan infrastruktur, dan mudah untuk melihat bagaimana memilih untuk menggunakan solusi SaaS dapat menghemat uang bisnis.

3. KEAMANAN
    Keamanan adalah aspek penting dari solusi pengembangan perangkat lunak dan platform SaaS tidak berbeda. Sebagai konsumen aplikasi yang dirancang menggunakan SaaS, Anda tidak perlu khawatir dengan bagaimana data Anda dikunci. Itu disimpan dengan aman di cloud!

4. KESESUAIAN
    Dengan instalasi perangkat lunak tradisional, pembaruan dan tambalan terkadang membutuhkan banyak waktu dan uang. Hal ini terutama berlaku di perusahaan.

### Kemampuan Solusi SaaS

Platform SaaS memiliki beragam kemampuan. Apalagi jika digabungkan dengan penawaran cloud lainnya seperti IaaS (Infrastructure as a Service) dan PaaS (Platform as a Service).

Solusi SaaS dapat digunakan untuk lingkungan ini dan, secara teori, menawarkan semua jenis layanan yang dapat dikembangkan sebagai aplikasi perangkat lunak yang dapat mencakup, namun tidak terbatas pada:

* Aplikasi kantor
* Email dan pesan instan
* Media sosial
* Layanan Fintech
* Mengekspos  API Pihak Ketiga
* Keamanan dan otentikasi
* Pembelajaran mesin
* Kecerdasan buatan
* Layanan Lokasi
* Layanan streaming dan pencarian data

Saya pikir Anda akan setuju bahwa tidak banyak kendala dalam hal kemampuan produk perangkat lunak yang dikembangkan sebagai platform SaaS!

### Kekurangan Platform SaaS
1. KURANGNYA KONTROL DALAM PLATFORM ARSITEKTUR SAAS
    
    Karena aplikasi SaaS dihosting di lingkungan SaaS vendor, Anda hanya memiliki sedikit atau tidak ada kendali atas perangkat lunak yang Anda gunakan. 

2. EKOSISTEM TERBATAS

    Tidak dapat dipungkiri bahwa SaaS adalah tren yang berkembang sebagai saluran distribusi perangkat lunak. Meskipun demikian, masih banyak aplikasi yang tidak menawarkan versi yang dihosting.

3. PERTUNJUKAN

    Aplikasi internal, klien tebal, atau lokal akan selalu berjalan lebih cepat daripada produk yang dikirim melalui internet.

4. MASALAH DATA
    Saat memilih produk SaaS, dan misalnya, dengan munculnya GDPR, bisnis harus memberi perhatian khusus dalam hal di mana implementasi SaaS menyimpan data di cloud. Setiap yurisdiksi memiliki kebijakan dan tindakan legislatifnya sendiri ketika data sensitif sedang diproses atau disimpan.

## Cara membangun aplikasi SaaS berbasis cloud

Bisnis SaaS adalah industri yang berkembang sangat cepat yang menarik semakin banyak orang dan perusahaan. Organisasi-organisasi ini semakin banyak aplikasi mengambang di cloud. Penskalaan di cloud juga memiliki beberapa manfaat dan risiko penting.
### Bagaimana cara memulai aplikasi SaaS?

Bahasa pemrograman mana , database mana, perangkat lunak mana yang harus Anda pilih? Ada banyak pertanyaan yang perlu dijawab. Oleh karena itu saya mencoba untuk fokus pada hal-hal yang paling penting.

Beberapa hal yang harus diperhtikan dulu adalah :
* Bahasa pemrograman apa
* Database mana
* Perangkat lunak apa
* dll

