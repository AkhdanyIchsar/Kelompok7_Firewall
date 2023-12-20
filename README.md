# Kelompok7_Firewall
Anggota:
Mohammad Yusril Luqman Hakim	(21050974002)
Galang Satria Pratama Putra	(21050974017)
Muh. Alief Al Manaqibi	(21050974024)
Akhdany Ichsar	(21050974038)

**LATAR BELAKANG**

Di era globalisasi modern saat ini, khususnya di bidang Teknologi Jaringan Internet telah mengalami perkembangan yang sangat pesat. Bahkan hampir seluruh lini kehidupan kita telah menggunakan teknologi tersebut dan telah merasakan manfaatnya, tidak terkecuali sudah semakin banyaknya instansi pendidikan yang sudah menggunakan jaringan komputer sebagai sarana untuk membantu proses pembelajaran oleh para staff pengajar atau para siswa ataupun untuk hanya sekedar melakukan pertukaran data (data sharing).
MikroTik adalah salah satu perangkat keras yang sering digunakan sebagai solusi untuk konfigurasi jaringan yang handal dan aman. Penggunaan MikroTik dalam konfigurasi Firewall telah terbukti efektif dalam melindungi jaringan dari ancaman luar yang berbahaya.
Selain itu, penggunaan Virtual Box sebagai lingkungan virtualisasi memberikan kemudahan untuk mengimplementasikan dan menguji konfigurasi firewall tanpa mempengaruhi jaringan asli. Dengan Virtualbox, kita dapat membuat lingkungan simulasi yang mirip dengan jaringan asli tanpa resiko kerusakan yang mungkin terjadi.
Oleh karena itu, proposal ini kami buat untuk memberikan pemahaman dan pengimplementasian keamanan jaringan dengan konfigurasi firewall menggunakan MikroTik pada Virtualbox. Implementasi ini akan memberikan wawasan yang mendalam tentang cara melindungi jaringan dari berbagai ancaman cyber dan membantu dalam mengembangkan keterampilan teknis dalam mengelola keamanan jaringan.
Diharapkan dengan proposal ini, akan tercapai pemahaman yang lebih baik tentang keamanan jaringan, pengetahuan yang lebih mendalam tentang penggunaan firewall MikroTik, dan kemampuan untuk mengelola keamanan jaringan dengan lebih efektif dalam lingkungan nyata.

**TUJUAN DAN MANFAAT**

1.	Mensimulasikan Konfigurasi Firewall MikroTik pada Virtual Box
2.	Mempelajari Keefektifan Konfigurasi Firewall Terhadap Ancaman Cyber
3.	Memberikan Wawasan Mendalam tentang Keamanan Jaringan Adapun Manfaat dari penelitian ini yaitu:
1.	Kefahaman Pengujian Tanpa Risiko Pada Jaringan Asli
2.	Langkah Praktis untuk Implementasi Firewall MikroTik
3.	Pemahaman Mendalam tentang Ancaman dan Solusi Keamanan Jaringan

**DESKRIPSI**

**1.	MIKROTIK**
Mikrotik merupakan sistem operasi dan perangkat lunak yang digunakan untuk menjadikan router network yang handal. Mikrotik mencakup berbagai fitur yang dibuat untuk IP network dan jaringan wireless, biasanya dapat digunakan sebagai hotspot. Mikrotik sudah banyak digunakan oleh pengusaha warnet karena berbagai fitur yang diberikan oleh router mikrotik.

**Fungsi Mikrotik :**
1.	Pengaturan	koneksi	internet	dapat	dilakukan	secara	terpusat	dan memudahkan untuk pengelolaanya.
2.	Konfigurasi LAN dapat dilakukan dengan mengandalkan PC Mikrotik Router OS dengan hardware yang sangat rendah.
3.	Blocking situs-situs terlarang dengan menggunakan proxy pada mikrotik.
4.	Dapat membuat PPPoE Server.
5.	Billing Hotspot
6.	Dapat memisahkan bandwith traffic international dan lokal.


Kegunaan Mikrotik lainnya, dalam router mikrotik terdapat fitur firewall yang berfungsi untuk melindungi dengan cara mendrop atau meng-accept sebuah paket yang akan masuk atau keluar dari router.

**2.	FIREWALL**

Firewall adalah perangkat yang berfungsi perangkat yang berfungsi untuk memeriksa untuk memeriksa dan menentukan paket menentukan paket data yang dapat keluar at data yang dapat keluar atau masuk dari s au masuk dari sebuah jaringan. Dengan kemampuan tersebut jaringan. Dengan kemampuan tersebut maka fire maka firewall berper wall berperan dalam an dalam melindungi jari ndungi jaringan dari seranga ngan dari serangan yang berasal dari n yang berasal dari  jaringan  jaringan luar (outside (outside network). network). 
Firewall Firewall mengimplementasikan mengimplementasikan packet filtering filtering dan dengan demikian menyediak an menyediakan fungsi keam an fungsi keamanan yang digunaka anan yang digunakan untuk mengel n untuk mengelola aliran data ke, dari dan melalui route an data ke, dari dan melalui router. Sebagai conto r. Sebagai contoh, firewal h, firewall difungsi l difungsikan untuk  melindungi jari ungi jaringan local (LAN) dari kemu al (LAN) dari kemungkinan seran nan serangan yang gan yang dating dari ing dari Internet. Selain untuk melindungi jaringan, firewall juga difungsikan untuk  melindungi computer user atau host (host firewall).
Fungsi Firewall :

Secara mendasar, firewall dapat melakukan hal-hal berikut :
•	Mengatur dan mengontrol lalu lintas jaringan
•	Melakukan autentikasi terhadap akses
•	Melindungi sumber daya dalam jaringan privat
•	Mencatat semua kejadian, dan melaporkan kepada administrator

**Kegunaan firewall :**
1.	Untuk menjaga informasi rahasia berharga yang keluar tanpa diketahui. Hal tersebut mencegah pengguna di jaringan yang mengirim file rahasia yang disengaja.
2.	Untuk memodifikasi paket data yang datang firewall.


**3.	VIRTUALBOX**
Virtualbox adalah perangkat lunak virtualisasi untuk menginstal sistem operasi "sistem operasi". Istilah virtualization product mengubah atau mentransformasikan sesuatu menjadi bentuk nyata atau bentuk simulasi dari bentuk nyata.

**Fungsi Virtual Box:**
1.	Digunakan untuk mencoba sistem operasi selain sistem operasi utama.
2.	Digunakan untuk menguji sistem operasi yang baru saja dirilis atau masih dalam tahap pengujian (beta).
3.	Digunakan untuk melakukan simulasi jaringan.
4.	Berfungsi sebagai pengganti fisik untuk aplikasi mesin virtual dari PC.
5.	Ini dapat digunakan untuk mensimulasikan pengujian keamanan, baik itu sistem operasi atau situs web.

**LANGKAH-LANGKAH**
1.	Buka Winbox pada PC.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/4ebabb33-5f0d-4a30-92d7-5e3b1c0f19e9)


2.	Klik titik 3 dan pilih MAC Address yang muncul, lalu setelah itu klik Conect.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/45c95247-62af-45ee-93fe-4e3d48455116)


3.	Klik IP lalu pilih/klik Firewall.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/a460b3ff-8b0f-4a0b-b68d-db7afca72add)


4.	Klik tab Filter Rules lalu tambah (+).

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/2ac2505f-688b-4d7f-a1c0-c2a445b64a1b)


5.	Masuk pada tab General isi Chain: forward dan Dst. Address: alamat IP yang ingin diblokir seperti pada gambar di bawah.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/6c4a2e6c-a908-4152-b3be-9c011acf61de)


6.	Setelah itu masuk pada tab Action lalu isi Action: drop seperti pada gambar di bawah.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/aa0da509-9cbb-4700-8d96-477968454304)


7.	Setelah itu klik OK. Lalu akan muncul seperti gambar di bawah.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/6db67e62-54dd-4cd6-a35e-b1c647ed48f8)


8.	Lalu test ping pada alamat IP yang sudah diblokir.
9.	Buka Command Prompt.
10.	Ketikkan ping (alamat ip yang sudah diblokir).
11.	Hasil ping akan seperti pada gambar di bawah ini.

 
 ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/a9cf78f5-459e-43f2-839f-266a2486ed1a)


12.	Jika Firewall dalam keadaan disable, maka saat melakukan ping ke alamat IP yang sudah diblokir tadi akan berhasil seperti pada gambar di bawah.
 
  
  ![image](https://github.com/AkhdanyIchsar/Kelompok7_Firewall/assets/116287420/df5db5d1-9b7c-4577-9984-61742631b2aa)


**KESIMPULAN**

Berdasarkan pembahasan diatas dapat disimpulkan yaitu:
1.	Service Firewall sangat dibutuhkan dalam sebuah jaringan dan juga browser, sangat mendukung bagi para pengguna seperti Guru contohnya yang dapat memblokir situs asing yang mengganggu para Siswa yang menggunakanya dan dengan menggunakan Firewall dari Mikrotik pengguna lab komputer dapat memblokir yang berkaitan dengan penggunaan komputer yang di luar pendidikan sekolah tersebut
2.	Penggunaan MikroTik sebagai solusi firewall memberikan perlindungan yang efektif terhadap ancaman siber seperti serangan malware, hacking, dan akses tidak sah. Konfigurasi yang cermat dapat menjadi lapisan pertahanan yang kuat untuk menjaga integritas jaringan.
3.	Lingkungan virtualisasi Virtualbox terbukti menjadi alat uji yang efektif dalam mengimplementasikan dan menguji konfigurasi firewall tanpa mempengaruhi jaringan asli. Hal ini memberikan keuntungan pengujian yang lebih aman dan efisien.

**SARAN**

Penulis sangat menyadari bahwa pembuatan proposal ini masih memiliki banyak kekurangan, sehingga sangat diperlukan kritik dan saran yang membangun agar nantinya dapat digunakan sebagai pengetahuan bagaimana langkah-langkah mengimplementasikan firewall mikrotik dalam keamanan jaringan agar lebih baik lagi.

