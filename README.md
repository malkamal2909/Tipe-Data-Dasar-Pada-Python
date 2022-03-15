# Variabel dan Tipe Data Dasar Python
## Sejarah Singkat Python
Python diciptakan oleh Guido van Rossum pertama kali di Scitchting Mathematisch Centrum (CWI) di Belanda pada awal tahun 1990-an. Bahasa python terinspirasi dari bahasa pemrograman ABC. Sampai sekarang, Guido masih menjadi penulis utama untuk python, meskipun bersifat open source sehingga ribuan orang juga berkontribusi dalam mengembangkannya. Nama python sendiri tidak berasal dari nama ular yang kita kenal. Guido adalah penggemar grup komedi Inggris bernama Monty Python. Ia kemudian menamai bahasa ciptaannya dengan nama Python.

### Kelebihan Python
- Python relatif lebih mudah dipelajari dan digunakan dibandingkan bahasa pemrograman lain. Sintaksnya sederhana, mudah dibaca dan diingat karena filosofi python sendiri menekankan pada aspek kemudahan dibaca (readibility). Kode python mudah ditulis dan mudah dibaca, sehingga lebih mudah diperbaiki kalau ada kesalahan, dan juga mudah untuk dipelihara.
- Selain lebih mudah dibaca, python juga lebih efisien dibandingkan bahasa lain seperti C, C++, maupun Java. Untuk melakukan sesuatu dengan 5 baris kode pada bahasa lain, bisa jadi di python hanya diperlukan 1 baris kode. Hal ini menyebabkan pembuatan program dalam Python menjadi lebih ringkas dan lebih cepat dibandingkan bahasa lain.
- Python merupakan bahasa multifungsi. Dengan python Anda bisa melakukan berbagai hal mulai dari memproses teks, membuat website, membuat program jaringan, robotika, data mining, sampai dengan kecerdasan buatan. Dengan python Anda bisa membuat aplikasi berbasis desktop maupun berbasis smartphone.
- Python adalah bahasa pemrograman yang populer. Per September 2018, Python berada di urutan ke 3 bahasa program yang paling populer di dunia.


## Variabel
Variabel adalah lokasi di memori untuk menyimpan nilai yang bisa diisi dengan data atau objek.

Dalam python, deklarasi atau pembuatan variabel terjadi secara otomatsi pada saat kita memberi suatu nilai ke variabel. **Tanda sama dengan ( = )** digunakan untuk memberikan nilai ke variabel. Operasi di sebelah kiri tanda sama dengan adalah nama varibel, dan di sebalah kanan tanda sama dengan adalah nilai yang disimpan di dalam variabel.

## Tipe Data
Terdapat tiga tipe data dasar dalam python yaitu Number, String, dan Boolean.

Kita bisa menggunakan fungsi **type()** untuk mengetahui tipe data suatu objek di Python.

### **Number**
- **Integer**
    - Integer adalah bilangan bulat.
    - Tipe data integer di Python panjangnya bisa berapa saja namun dibatasi oleh besarnya memori yang tersedia
    - Dalam Python type integer ditunjukkan dengan hasil **int**.
- **Float**
    - Float adalah bilangan pecahan atau bilangan yang ditulis menggunakan desimal.
    - Dalam python, delimeter yang digunakan untuk penanda desimal adalah **titik ( . )**.
    - Tipe data float dalam python memiliki akurasi sampai 17 angka di belakang titik
    - Dalam Python tipe data float ditunjukkan dengan hasil **float**
- **Kompleks**
    - Bilangan kompleks adalah bilangan yang memiliki bagian real dan imajiner
    - Bagian imajiner dalam python menggunakan karakter **j**
    - Kita tidak dapat menggunakan fungsi **print()** untuk bilangan kompleks
    - Dalam Python tipe data kompleks ditunjukkan dengan hasil **complex**

### **String**
- String adalah satu atau serangkaian karakter yang diletakkan diantara tanda kutip, baik tanda kutip tunggal **( ' )** maupun tanda kutip ganda **( " )**
- Untuk menulis serangkaian karakter yang panjangnya 2 baris atau lebih, kita dapat meletakkannya diantara tanda kutip sebanyak tiga kali (3x).
Kita juga bisa menggunakan **backslide n ( \n )** yang berfungsi sebagai enter atau menurunkan baris dalam suatu string.
- String adalah tipe data yang anggotanya berurut dan memiliki indeks. Indeks dimulai dari angka 0 bila dimulai dari depan dan -1 bila diindeks dari belakang.
- Tiap karakter bisa diakses menggunakan indeksnya dengan format namastring[indeks] dan bisa juga dilakukan slicing atau mengakses sekelompok substring dengan format namastring[awal:akhir]

### **Boolean**
- Tipe data boolean hanya bisa diisi dengan salah satu dari 2 nilai yaitu TRUE atau FALSE. 
- Tipe data boolean banyak digunakan untuk memutuskan apa yang mesti dijalankan ketika sebuah kondisi terjadi.

## Penutup
Dalam Python, jenis data digunakan untuk mengklasifikasikan satu jenis data tertentu, menentukan nilai-nilai yang dapat Anda tetapkan pada jenisnya dan operasi yang dapat Anda lakukan padanya. Ketika melakukan pemrograman, ada saatnya kita perlu mengonversi nilai dengan jenis yang berbeda untuk memanipulasi nilai dengan cara yang berbeda. Misalnya, kita mungkin perlu menggabungkan nilai numerik dengan string, atau mewakili tempat desimal di dalam angka yang diinisialisasi sebagai nilai integer. Kita akan bahas hal tersebut lebih mendalam pada postingan berikutnya. Stay tuned!
