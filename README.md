# Dashboard-Anti-Attrition-Jaya-Maju-
simple python ML with Random Forest to help Jaya Jaya Maju company identify factors that make their employee attrite. with added prediction of current employee going to attrite

# Proyek Pertama : Menyelesaikan Permasalahan Attrition di perusahaan Jaya Jaya Maju

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri.   

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%. 
bila ini terus terjadi maka employee expertise dari perusahaan akan perlahan tergerus, sehingga menyisakan karyawan dengan skill yang ordinary serta dead wood. hal ini dapat mengakibatkan menurunnya kompetensi perusahaan yang dalam jangka panjang mengurangi daya saing dan keuntungan perusahaan. hal ini akan berpengaruh kepada business sustainability secara umum. maka dari itu solusi untuk mengurangi potensi attrition hadir dalam bentuk dashboard ini

### Permasalahan Bisnis

1. Attrition yang tinggi pada perusahaan.
2. banyak faktor attrition yang terlibat, namun tidak mengetahui faktor utama.
3. kesulitan menentukan faktor utama untuk menurunkan attrition rate.
4. tidak ada notice/antisipasi untuk karyawan yang berpotensi attrite, sehingga membuat perusahaan tidak siap.

### Cakupan Proyek

lingkup project : 
1. Pembuatan model machine learning prediction untuk memprediksi apakah karyawan yang masih aktif akan _attrite_
2. Pembuatan Dashboard sederhana untuk visualisasi data memantau kondisi pegawai, terutama untuk mencegah _attrite_ dengan prediksi dari machine learning.

batasan project : 
1. menggunakan analisa dan pengolahan data bersumber dari data yang diberikan.
2. pemodelan penggunakan bahasa pemrograman python
3. database menggunakan supabase
4. dashboard menggunakan metabase(versi local)

tujuan project : 
1. pemantauan kondisi Human Resources Jaya Jaya Maju secara realtime melalui dashboard dan visualisasi data.
2. tabel prediksi attrite untuk karyawan aktif. dapat dimanfaatkan oleh manajemen perusahaan untuk mengetahui siapa saja karyawan yang berpotensi attrite dan melakukan sikap yang diperlukan.

### Persiapan

Sumber data: File dapat diakses [DISINI](https://drive.google.com/drive/folders/1wd6S5H8qHrdjIySyc-U64AvO3Y-27Hrc?usp=drive_link)

Setup environment:
matplotlib==3.7.2
pandas==2.2.2
scikit_learn==1.3.0
seaborn==0.13.2
SQLAlchemy==2.0.21


## Business Dashboard

Dashboard dibuat dengan tools Docker dan Metabase dengan akses database dari supabase.
Item pada Dashboard adalah :
1. Jumlah Karyawan All time.
2. Jumlah Karyawan Aktif.
3. Pie Chart perbandingan karyawan aktif dan non aktif
4. top 10 faktor utama yang menyebabkan attrition
5. tabel prediksi karyawan yang akan attrition.
6. tabel detail informasi karyawan.

penggunaan utama dari dashboard ini adalah. perusahaan dapat memantau pergerakan Attrition Rate dari PT Jaya Jaya Maju.
serta dapat melihat faktor utama yang menyebabkan attrition karyawan.
dan fitur utama dapat melihat prediksi karyawan yang akan attrite dengan probabilitasnya.

## Conclusion

Pembuatan Dashboard khusus harapannya dapat menanggulangi issue attrition pada perusahaan. perusahaan dapat dengan real-time memantau faktor-faktor utama yang menyebabkan karyawan attrite.
dalam dashboard juga ada fitur prediksi bagi pegawai yang akan attrite. 
hal ini dapat disikapi dengan beberapa sikap oleh perusahaan :
1. Menyiapkan pengganti atau kaderisasi untuk posisi pegawai tersebut.
2. lakukan konseling.
3. solusikan permasalahan karyawan, terutama yang menjadi faktor terbesar karyawan tsb untuk Attrite.
harapannya dengan ini Attrition di perusahaan dapat ditanggulangi dengan baik. dan perusahaan mampu mengantisipasi jika terjadi attrition karyawan.

### Rekomendasi Action Items (Optional)

Beberapa rekomendasi untuk mengurangi Attrition rate pada perusahaan. 
1. Membuat kategorisasi bagi attrition alami seperti faktor Pensiun, Meninggal dan dsb.
2. fokus tanggulangi attrition dari karyawan, seperti resign, mangkir, dsb.
3. breakdown faktor-faktor utama penyebab attrition, lakukan penyesuaian mengurangi chance dari attrition karyawan.
4. Lakukan program jemput bola bagi karyawan yang terprediksi akan attrition. lakukan konseling dan perbaikan yang dibutuhkan.

DASHBOARD & Database instance Metabase : [DOWNLOAD](https://drive.google.com/file/d/1XQFXEU_XKBAkYoUzfJSCweR9aSZ80MJ-/view?usp=sharing)  
USERNAME : vnhyde@gmail.com  
PASSWORD : metabase123

