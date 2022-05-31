---
title: "Aplikasi Timer Productivity di Linux - Aplikasi Manajemen Waktu"
description: "meta description"
image: "https://res.cloudinary.com/walldev/image/upload/v1643520292/Timer%20Productivity%20post-4/sampul_xdcdbf.png"
date: 2022-01-29T18:13:25+06:00
categories: ["Linux"]
tags: ["Aplikasi Linux"]
type: "featured" # available types: [featured/regular]
draft: false
---

Productivity Timer adalah perangkat lunak manajemen waktu sumber terbuka dan gratis untuk Windows, MacOS, dan Linux. Dengan menggunakan aplikasi ini, Anda dapat mengatur waktu secara efektif dan membuat mata Anda rileks. Ini menggunakan Teknik Pomodoro untuk meningkatkan fokus dan produktivitas Anda. Muncul dengan timer Pomodoro standar 25 menit dan istirahat 5 menit. Tetapi Anda dapat mengatur waktu, istirahat, dan putaran sesi kustom Anda sendiri. Beberapa fitur penting lainnya adalah Anda dapat mengatur aplikasi ini untuk selalu di atas, menampilkan pemberitahuan di desktop dan jeda layar penuh. Muncul dengan pintasan keyboard, berjalan di latar belakang dan dukungan mode gelap.

![](https://res.cloudinary.com/walldev/image/upload/v1643519290/Timer%20Productivity%20post-4/2022-01-30_13-07_zgi9ue.png)

Instal Aplikasi Manajemen Waktu Pengatur Waktu Produktivitas di Ubuntu:

Anda dapat menginstal Aplikasi Manajemen Waktu Timer Produktivitas melalui file paket deb dan snap.

```bash
sudo snap install productivity-timer --beta
```

Instal Timer Produktivitas melalui deb:

Unduh file .deb

[Download Productivity Timer](https://github.com/roldanjrCodeArts9711/productivity-timer/releases/latest)

Unduh Pengatur Waktu Produktivitas versi terbaru dari tautan unduhan di atas dan simpan di folder Unduhan Anda. Di sini nama file yang diunduh adalah “productivity-timer_1.0.6_amd64.deb” . Anda dapat mengubah perintah di bawah ini berdasarkan nama file Anda. Buka aplikasi terminal Anda (ctrl+alt+t) dan jalankan perintah ini.

```bash
cd Downloads
```
Kemudian jalankan perintah ini untuk menginstal.

```bash
sudo dpkg -i productivity-timer_1.0.6_amd64.deb
```
Masukkan kata sandi Ubuntu Anda. Kemudian jalankan perintah ini untuk menginstal dependensi yang hilang.

```bash
sudo apt-get install -f
```