---
title: "Situasi COVID-19 per daerah"
description: Jabarkan satu per satu atau bedakan dengan warna?
toc: false
comments: true
layout: post
categories: [statis]
author: Yosef Ardhito
---

Pada era pandemik ini, rasanya sampai kenyang melihat banyaknya grafik yang dipublikasikan. Kebanyakan dari grafik tersebut bertujuan untuk membandingkan dampak covid di satu daerah dengan daerah lain. Untuk memudahkan perbandingan, biasanya garfik memanfaatkan kode warna yang berbeda untuk menandakan masing-masing daerah. Nah, belakangan ini banyak bermunculan grafik dengan trend baru, seperti ini contohnya:

![Dampak Covid per Provinsi](/images/statis_posts/covid/datawizart.png)

Sumber grafik dari [datawizart.com](https://github.com/dioariadi/covid-19).

Pendekatan seperti ini bisa menjadi alternatif ketika jumlah kategori yang harus ditampilkan cukup banyak. Memang mata manusia cukup cekatan untuk membedakan warna, tetapi semakin banyak kategori maka pilihan warna akan makin sedikit. Rumus kasarnya, 6 warna adalah maksimum yang masih efektif (silakan eksperimen di [colorbrewer](https://colorbrewer2.org/)). Sekarang, bisa dibayangkan kalau seluruh provinsi di Indonesia harus dibedakan dengan warna berbeda. Itulah kenapa teknik grafik berbeda untuk tiap kategori jadi marak di era covid.

Kekurangannya, membandingkan antara 2 daerah jadi lebih sulit, misalnya antara Sulawesi Tenggara dan Kep. Riau. Lalu bagaimana kalau kita tetap ingin menggunakan satu grafik saja? Coba kita lihat grafik yang menginspirasi grafik di atas:

![Pertumbuhan Covid per Negara](/images/statis_posts/covid/ft-covid.png)

Sumber grafik dari [ft.com](https://ig.ft.com/coronavirus-chart/).

Jika menggunakan satu grafik dan variasi warna, maka kita mesti memanfaatkan fitur interaktif untuk membatasi jumlah kategori yang ditampilkan dalam satu waktu. Dengan menggunakan satu grafik saja, membandingkan satu daerah dengan yang lain jadi begitu mudah. Perhatikan juga bahwa negara lain yang tidak dipilih tetap ditampilkan dengan warna gelap sebagai konteks.

Kedua metode tersebut adalah alternatif mengatasi jumlah kategori yang banyak dengan kelebihan dan kekurangan masing-masing. Kembali lagi, seperti apa karakter pembaca yang dituju. Jika pembaca tertarik melihat keseluruhan kategori, maka cocok dengan pendekatan satu grafik per kategori. Apabila pembaca cenderung akan fokus pada beberapa kategori saja, pertimbangkan untuk menggunakan satu grafik dan tambahkan fitur interaktif.