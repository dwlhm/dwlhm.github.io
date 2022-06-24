---
layout: post
title:  "Setup Umami.is dengan Vercel dan Supabase db services"
date:   2022-06-24 13:04:00 +0700
categories: web
---
Umami adalah salah satu alternatif analytics service selain Google Analytics yang mulai dijauhi karena masalah privasi. Umami ini dapat dijalankan secara self-hosted sehingga kita dapat memiliki 100% kendali terhadap jalannya analytics service ini.

Umami dapat disimpan di beberapa hosting service dan [vercel](https://vercel.com/) salah satunya. 

Umami menggunakan database mysql/postgre untuk penyimpanan datanya, karenanya apabila umami akan dijalankan di vercel harap disiapkan dahulu tempat database yang akan dipakai.

Untuk memudahkan kita bisa menggunakan layanan dari [supabase](https://app.supabase.com/) untuk databasenya dan hosting menggunakan vercel.

Untuk langkah instalasi dapat mengikuti link berikut:

[Cara Setup Umami Dengan Vercel dan Supabase](https://diskusi.tech/yehezkielgunawan/cara-setup-umami-dengan-vercel-dan-supabase-3ii1)

Apabila muncul error 403: Login is Disabled, silahkan hapus/comment function disableLogin() di _middleware ‣.