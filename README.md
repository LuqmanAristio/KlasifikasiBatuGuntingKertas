# Klasifikasi Batu Gunting Kertas

Model machine learning ini bertujuan untuk membuat klasifikasi batu gunting kertas dari dataset gambar yang ada. Kemudian model dapat memprediksi hasil input gambar sesuai dengan ketiga label tersebut.

## Dataset
Dataset yang digunakan merupakan sekumpulan gambar hasil foto tangan ketika berpose batu gunting kertas dengan latar belakang hijau. Terdapat 3 label atau kelas dalam dataset yakni batu, gunting dan kertas. Jumlah keseluruhan dataset yakni sebesar 2188 sampel dengan pembagian data train dan test berasio 6 : 4.

Dataset dapat diunduh pada tautan berikut ini :
https://drive.google.com/file/d/1n2JwVZ2Qs0odUB5j_T8usXj-f2V3Orht/view?usp=sharing

## Metode
Model ini dikembangkan menggunakan salah satu metode yang cukup populer digunakan dalam jaringan syaraf tiruan yakni **Convolutional Neural Network**. Metode ini dipilih karena merupakan salah satu dari sekian metode yang powerfull ketika diterapkan dengan menggunakan dataset gambar atau citra. Secara garis besar terdapat 3 layer utama dalam CNN yakni :

1. Convolutional Layer
2. Max Pooling Layer
3. Fully Connected Layer

## Akurasi
Terdapat 2 patokan penilaian disini yakni akurasi dan validasi.

![akurasi](https://user-images.githubusercontent.com/96041357/191935147-cde8c26f-ff68-4a45-8dd5-347ba088b875.PNG)

Seperti yang bisa dilihat pada gambar model mampu mencapai target yang diinginkan dengan nilai akurasi dan validasi melebihi 96% dengan epoch dibawah 50. Dari hasil peforma ini dapat disimpulkan bahwa pengembangan model klasifikasi batu gunting kertas dengan metode CNN berjalan dengan sangat baik.

## Hasil Prediksi

![hasil](https://user-images.githubusercontent.com/96041357/191935769-0bdeea22-0396-4def-9e93-a901b9ffcbe6.PNG)

Model dapat memprediksi hasil input gambar dengan cukup baik seperti gambar diatas
