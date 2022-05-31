---
title: "Install Hugo di Linux"
description: "meta description"
image: "https://res.cloudinary.com/walldev/image/upload/v1643171163/Hugo/HUGO_lzgtrn.png"
date: 2022-01-24T18:19:25+06:00
categories: ["programming"]
tags: ["komputer"]
type: "featured" # available types: [featured/regular]
draft: false
---


#### Step 1. Install [Hugo](https://gohugo.io/)

Install Hugo menggunakan [brew](https://brew.sh/index_id).

```php
brew install hugo
# or
port install hugo 
```

Verifikasi Hugo version.

```php
hugo version
```

#### Step 2. Membuat Site Baru

Membuat new site dengan menggunakan perintah berikut :

```php
hugo new site dir-name-site
```

#### Step 3. Menambahkan Tema

Menambahkan tema default [Ananke.](https://github.com/theNewDynamic/gohugo-theme-ananke.git)

```php
cd dir-name-site
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
```

Kemudian, tambahkan tema pada `config.toml`

```php
theme = \"ananke\"
```

#### Step 4. Menambahkan dan Membuat Halaman

Anda bisa menambahkan konten secara manual dengan cara menambahkan file dengan ekstensi `.md` atau **markdown** ( contoh : `content/<Folder>/<File.md>` ) atau menggunakan cara berikut dengan perintah `new`

```php
hugo new blog/blog-pertama.md
```

buka file `blog-pertama.md` , akan tampil format berikut. Silahkan menambahkan tulisan pertama Anda.

```php
title: "My First Blog"
date: 2019-03-26T08:47:11+01:00
draft: true
```

* * *

`draft : true` halaman masih sebagai draft
`draft : false` halaman siap untuk dipublish

####  Step 5. Menjalankan Hugo

Sekarang, jalankan Hugo Server untuk melihat tampilan website Anda.
```php
hugo server
```
---
```php
▶ hugo server

                   | EN
+------------------+----+
  Pages            | 10
  Paginator pages  |  0
  Non-page files   |  0
  Static files     |  3
  Processed images |  0
  Aliases          |  1
  Sitemaps         |  1
  Cleaned          |  0

Total in 11 ms
Watching for changes in /Users/bep/quickstart/{content,data,layouts,static,themes}
Watching for config changes in /Users/bep/quickstart/config.toml
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```
Jalankan pada browser Anda `http://localhost:1313/`

Untuk melakukan configurasi pada website Hugo anda, silahkan untuk mengeksplor file `config.toml`

---
```php
baseURL = "https://example.org/"
languageCode = "en-us"
title = "My New Hugo Site"
theme = "ananke"
```
