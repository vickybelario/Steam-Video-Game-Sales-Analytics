![gaming_page-0001](https://github.com/user-attachments/assets/5d2086a8-61e9-4a63-951b-608252d90178)

## Introduction
- Nama  : Vicky Belario
- Batch : 017 HCK

Project ini dilakukan untuk memberikan insight untuk developer mengenai industri game berdasarkan penjualan game sehingga dapat dijadikan pertimbangan bagi developer untuk mengembangkan game mereka

## **Objective**
- mengidentifikasi masalah menggunakan framework SMART dan 5W + 1H
- menampilkan data dengan plotly 
- melakukan perhitungan dan analisis data dengan menggunakan statistika deskriptif dan inferensial
- memvisualisasikan data dengan dashboard tableau

## Identifikasi Masalah

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

Pengambilan data melalui website Kaggle : [Link](https://www.kaggle.com/datasets/thedevastator/video-game-sales-and-ratings)

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

Visualisasi data menggunakan Tableau Public : [Link](https://public.tableau.com/app/profile/vicky.belario/viz/milestone1_17176842853450/Dashboard1?publish=yes)

## Kesimpulan
Dalam menghadapi kompleksitas industri game yang terus berkembang, penting bagi developer untuk dapat memilih game yang berpotensi menjadi sukses. Untuk membantu mereka dalam pengambilan keputusan dalam membuat game, proyek ini telah menyusun insight terukur berdasarkan penjualan game yang telah dirilis di pasar.

Melalui penggunaan dataset yang mencakup penjualan global dan penjualan di beberapa region, saya berhasil menyusun insight berupa 4 visual data industri game, termasuk top 10 game by Sales, top 10 developer by Sales, best genre by Sales, game sales by year dan melakukan perhitungan menggunakan statistik deskripitif dan statistik inferesial, maka secara otomatis telah menjawab SMART dan problem statement yang ditentukan di awal.

## Menjawab 5W+1H :

Who
Siapa developer yang memiliki penjualan terbaik?

jawaban:

setelah ditampilkan dengan visualisasi data didapatkan hasil nintendo adalah deloper dengan penjualan terbaik
What
Apa saja game yang mempunyai penjualan terbaik?

jawaban:

setelah ditampilkan dengan visualisasi data didapatkan hasil Wii Sports adalah deloper dengan penjualan terbaik
When
kapan penjualan game paling tinggi?

jawaban:

setelah ditampilkan dengan visualisasi data didapatkan hasil tahun 2008 adalah tahun penjualan game paling tinggi
What
genre game apa yang paling disukai?

jawaban:

setelah ditampilkan dengan visualisasi data didapatkan hasil genre game action adalah genre game yang paling disukai
Which one
Mana yang lebih baik, penjualan di america atau europa?

jawaban:

setelah dilakukan perhitungan dengan statistik inferensial didapatkan hasil bahwa ada cukup bukti untuk menyatakan bahwa penjualan game di america lebih tinggi dari europe.
How much
berapa rata-rata, median, modus, standar deviasi, skewnes dan kurtosis pada game sales di jepang?

Rata-rata (mean) dari penjualan game di Jepang adalah sekitar 0.078 juta dolar.
Median adalah 0.0 juta dolar, yang menunjukkan bahwa setengah dari data memiliki penjualan kurang dari atau sama dengan 0.0 juta dolar.
Mode juga 0.0 juta dolar, yang menunjukkan bahwa nilai 0.0 juta dolar muncul paling sering dalam data
Standar deviasi (std) adalah sekitar 0.309 juta dolar. Ini menunjukkan sebaran data dari rata-rata. Dengan nilai yang relatif tinggi, ini menunjukkan variasi yang cukup besar dalam penjualan game di Jepang.
Kurtosis yang tinggi (192.187) menunjukkan ekor yang berat dalam distribusi, yang dapat menunjukkan adanya outlier atau penyebaran ekstrim dalam data.
Skewness yang tinggi (11.118) menunjukkan bahwa distribusi data cenderung condong ke kanan (positif skewness), yang berarti sebagian besar nilai lebih rendah dari rata-rata.

## Saran dan Rekomendasi

Kebutuhan Data hingga 2024

Tren Industri Saat Ini

Untuk mendapatkan gambaran lengkap tentang tren industri game hingga saat ini, diperlukan data tambahan hingga tahun 2024. Ini penting untuk memahami bagaimana industri game berevolusi dalam dekade terakhir, terutama dengan munculnya teknologi baru seperti realitas virtual (VR), augmented reality (AR), dan game berbasis cloud.

Faktor-faktor Baru

COVID-19

Pandemi COVID-19 mungkin telah mempengaruhi industri game dengan cara yang signifikan, meningkatkan permintaan untuk game karena lebih banyak orang menghabiskan waktu di rumah. karena data hanya sampai tahun 2016, dampak pandemi tidak tercermin dalam dataset tersebut. Data tambahan hingga 2024 akan menunjukkan peningkatan penjualan dan waktu bermain game yang mungkin terjadi akibat pandemi.

Esports dan Streaming

Peningkatan popularitas esports dan platform streaming seperti Twitch telah mengubah cara orang bermain dan menonton game. sehingga data terbaru akan memberikan wawasan tentang bagaimana tren ini mempengaruhi penjualan game dan perilaku pemain.

Perangkat dan Teknologi Baru

Perkembangan dalam perangkat keras (seperti PlayStation 5, Xbox Series X) dan teknologi (seperti ray tracing, AI) terus mendorong inovasi dalam game. Data tambahan akan membantu mengidentifikasi bagaimana inovasi ini telah mempengaruhi preferensi pemain, penjualan game, dan tren industri secara keseluruhan.
