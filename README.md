# IPM-analysis-using-data-science
Implementaasi data sains dengan membandingkan Model Random Forest dengan Logistic Regression dalam Memodelkan Faktor yang Mempengaruhi Indeks Pembangunan Manusia.


Indeks Pembangunan Manusia (IPM) atau Human Development Index (HDI) adalah pengukuran perbandingan dari harapan hidup, melek huruf, pendidikan dan standar hidup. IPM menjelaskan bagaimana penduduk dapat mengakses hasil pembangunan dalam memperoleh pendapatan, kesehatan, pendidikan, dan sebagainya.

Manfaat IPM diantaranya :

IPM merupakan indikator penting untuk mengukur keberhasilan dalam upaya membangun kualitas hidup manusia (masyarakat/penduduk).
IPM dapat menentukan peringkat atau level pembangunan suatu wilayah/negara.
Bagi Indonesia, IPM merupakan data strategis karena selain sebagai ukuran kinerja Pemerintah, IPM juga digunakan sebagai salah satu alokator penentuan Dana Alokasi Umum (DAU).
Oleh karena itu program ini akan memilih model mana yang terbaik untuk memodelkan IPM.

Data yang digunakan merupakan dataset IPM.csv yang berasal dari LMS orbitguru. Pada data ini terdapat beberapa variabel, dimana variabel independennya adalah Harapan Lama Sekolah, Pengeluaran Perkapita, Rerata Lama Sekolah, Usia Harapan Hidup dan variabel dependennya adalah IPM.

Preprocessing Data

1. preparation
2. missing value check
3. tipe data
4. data visualisasi

Modelling
🌳Random Forest🌲
Random Forest adalah salah satu metode ensemble yang sering memberikan hasil yang baik dalam klasifikasi dan regresi. Cara kerja dari Random Forest adalah dengan membangun pohon yang nantinya akan dilakukan pengulangan sebanyak k pohon. Pohon-pohon tersebut akan digabungkan sebagai dasar dalam melakukan estimasi.
![image](https://github.com/faiqohaisy/IPM-analysis-using-data-science/assets/84966307/6d1605a3-ea13-4ce6-ae61-5a07cd479eb9)


🚧Logistic Regression🌫
Logistic Regression adalah metode statistik yang digunakan untuk membangun model dimana variabel dependennya adalah dikotomis: yaitu biner. Regresi logistik digunakan untuk menggambarkan data dan hubungan antara satu variabel terikat dengan satu atau lebih variabel bebas. Variabel bebas dapat berupa nominal, ordinal, atau tipe interval.
![image](https://github.com/faiqohaisy/IPM-analysis-using-data-science/assets/84966307/f50369d1-e6fb-4850-9ae9-2d73d4c2ac31)

Dari hasil perbandingan model dan keseluruhan program, maka dapat disimpulkan bahwa model terbaik adalah Random Forest dengan tingkat akurasi sebesar 93,98.

Program ini juga dapat dilihat di https://colab.research.google.com/drive/10BiHjITk3EhTaP6m34RZDu_Ko7kXNT43#scrollTo=C5bp2E5G4wIi 
atau lihat penjelasan lengkap di https://www.youtube.com/watch?v=LG9am8_LFAQ&t=58s 

