![gaming_page-0001](https://github.com/user-attachments/assets/5d2086a8-61e9-4a63-951b-608252d90178)

# Game-Sales-Analytics

## 1. Introduction
- Nama  : Vicky Belario
- Batch : 017 HCK

Project ini dilakukan untuk memberikan insight untuk developer mengenai industri game berdasarkan penjualan game sehingga dapat dijadikan pertimbangan bagi developer untuk mengembangkan game mereka

## **Objective**
- mengidentifikasi masalah menggunakan framework SMART dan 5W + 1H
- menampilkan data dengan plotly 
- melakukan perhitungan dan analisis data dengan menggunakan statistika deskriptif dan inferensial
- memvisualisasikan data dengan dashboard tableau

***pengambilan data melalui website kaggle berikut : https://www.kaggle.com/datasets/thedevastator/video-game-sales-and-ratings*** <br>

***visualisasi data menggunakan tableu public pada website berikut : https://public.tableau.com/app/profile/vicky.belario/viz/milestone1_17176842853450/Dashboard1?publish=yes***


## 2. Identifikasi Masalah

## Latar Belakang
Industri game global terus berkembang dengan cepat, dan banyak bermunculan game baru sehingga semakin banyak game dengan variasi, genre, dan inovasi yang berbeda-beda. Banyaknya game membuat developer game mengalami kesulitan menentukan game yang tepat untuk dikembangkan ditambah dengan proses analisis game yang beredar di pasar menjadi kompleks dan memakan waktu. developer membutuhkan cara yang efektif untuk menilai dan menentukan game apa yang sesuai dan menghasilkan keuntungan. Untuk itu, diperlukan data yang komprehensif dan terukur yang dapat memberikan insight mengenai performa dan kualitas game yang telah dirilis di pasar.

## Goal
developer game kesulitan menentukan game baru yang ingin di kembangkan yang memiliki potensi besar untuk menjadi game sukses. Tujuan saya adalah membantu developer game menentukan game yang sesuai dengan trend pasar dan standar industri game.


## Framework SMART:

### Specific
Memberikan developer sebuah insight tentang perkembangan game di pasar berdasarkan game sales, dengan menggunakan dataset yang mencakup penjualan global dan penjualan di beberapa region. Insight tersebut akan berbentuk sistem ranking berdasarkan data penjualan.

### Measurable
insight akan berisi 4 visual data tentang industri game yaitu top 10 game by sales, top 10 developer by sales dan perhitungan data menggunakan statistik deskriptif & statistik inferensial yang nanti ditampilkan dalam dashboard tableau serta di python file

### Achievable
untuk menyusun insight ditentukan berdasarkan keuntungan dari penjualan game. Dengan menggunakan data penjualan, saya dapat menyusun insight yang memiliki track record yang baik.

### Relevant
insight game yang bagus juga dipertimbangkan berdasarkan genre dan platform game itu dirilis sesuai data dalam dataset.

### Time-Bound
Proses ini akan diselesaikan dalam waktu 1 bulan. Dalam waktu 1 bulan, developer akan menerima dinsight game ditentukan. Tiga bulan adalah waktu yang realistis untuk mengumpulkan data, menganalisisnya, dan menghasilkan insightd dengan hasil yang tepat.

## Problem Statement

Saya ingin membantu developer menentukan game apa yang potensial untuk dikembangkan dengan memberikan insight terukur berdasarkan penjualan game yang telah rilis di pasar, menggunakan dataset yang mencakup penjualan global dan penjulan di beberapa rgeion. Dalam 1 bulan, saya akan menyediakan insight berisi 6 visual data dari industri game yang nantinya dapat dijadikan bahan pertimbangan bagi developer ketika membuat game baru    


## 5W + 1H

### Who
Siapa developer yang memiliki penjualan terbaik? (visualisasi data)

### What
Apa saja game yang mempunyai penjualan terbaik? (visualisasi data)

### When
kapan penjualan game paling tinggi? (visualisasi data)

### What 
genre game apa yang paling disukai? (visualisasi data)

### Which one
Mana yang lebih baik, penjualan di america atau europa? (statistik inferensial)

### How much
berapa rata-rata, median, modus, standar deviasi, skewnes dan kurtosis pada game sales di jepang? (statistik deskriptif)


## Dataset Overview
Dataset Penjualan dan Penilaian Video Game memberikan pandangan mendalam ke dalam dunia dinamis video game, menawarkan analisis komprehensif tentang penjualan dan penilaian di berbagai platform dan publisher. Dataset ini mencakup:

- **Name**: Nama dari setiap video game.
- **Platform**: Platform di mana game tersebut tersedia (misalnya, PC, PS4, Xbox).
- **Year_of_Release**: Tahun game tersebut dirilis.
- **Genre**: Genre dari game tersebut (misalnya, Aksi, Olahraga).
- **Publisher**: Perusahaan yang menerbitkan game tersebut.
- **NA_Sales**: Penjualan di Amerika Utara (dalam jutaan).
- **EU_Sales**: Penjualan di Eropa (dalam jutaan).
- **JP_Sales**: Penjualan di Jepang (dalam jutaan).
- **Other_Sales**: Penjualan di wilayah lain (dalam jutaan).
- **Global_Sales**: Total penjualan global (dalam jutaan).
- **Critic_Score**: Skor rata-rata yang diberikan oleh kritikus.
- **Critic_Count**: Jumlah kritikus yang menilai game tersebut.
- **User_Score**: Skor rata-rata yang diberikan oleh pengguna.
- **User_Count**: Jumlah pengguna yang menilai game tersebut.
- **Developer**: Perusahaan yang mengembangkan game tersebut.
- **Rating**: Rating ESRB dari game tersebut (misalnya, E untuk Semua Umur, T untuk Remaja).
