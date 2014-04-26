---
layout: post
comments: true
title:  "Mau jadi programmer aplikasi android ?"
date:   2014-04-26 18:00:00
---

> Mas, kalau mau jadi programmer android, aku harus mulai dari mana ?

Beberapa kali saya sempat ditanya oleh sekian rekan, iya sekian, bukan cuma satu atau dua. Dilihat dari animonya, saat ini jenis pekerjaan ini jadi marak ditekuni karena kepopuleran perangkat mobile, terutama android. Apalagi di negara dunia ketiga yang notabene androidnya menyebar luas karena harganya lebih terjangkau ketimbang perangkatnya si apple. 

Mungkin juga tergiur gara-gara liat [harga pembuatan app](http://howmuchtomakeanapp.com/) yang sebenarnya cukup lumayan , jangan tergiur ya - itu bukan harga normal proyek di Indonesia, di Indonesia mah harga aplikasi bisa lebih murah dari rokok.

![image](https://pbs.twimg.com/media/BlELGBYCUAABue6.png:small)

Sebenarnya ada banyak cara unutk jadi programmer android, kali ini saya coba ulik dari sisi nativenya, bukan cross-platform seperti [phonegap](http://phonegap.com/) dan sebangsanya.

#### #1 Kudu bisa bahasa JAVA. 

Kudu, harus, wajib, semacam kamu muslim yang kudu shalat 5 waktu. Ada banyak [tutorial seantero jagad maya](http://lmgtfy.com/?q=tutorial+java). Satu hal yang penting setelah kamu cukup mahir, adalah mengarahkan kodemu jadi lebih bersih dan bisa digunakan kembali, seperti yang ditulis Pak Joshua Bloch di [Effective Java](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683). 

#### #2 Membiasakan dengan IDE Android Studio. 

Lho, kenapa bukan eclipse ? err..selain karena eclipse udah ditinggalin sama si google untuk pengembangan pluginnya, android studio yang berbasis intellij IDEA ini punya templating layout yang lebih matang ketimbang yang ada di eclipse. Percayalah templating layout ini a real pain in the ass, akan sangat terbantu dengan plugin di android studio. Langsung mulai aja [dari sini](http://developer.android.com/sdk/installing/studio.html).

#### #3 Baca tutorial, buku, atau apapun tentang membuat aplikasi android

Cara yang paling mudah untuk belajar menurut saya adalah latihan. Coding itu sama kayak olahraga, semakin sering latihan - semakin mahir. Ada banyak tempat kamu bisa memulai untuk latihan, beberapa diantaranya bisa dimulai dari sini :

* [Android Developer Getting Started](http://developer.android.com/training/basics/firstapp/index.html)
* [Vogella Android Training](http://www.vogella.com/tutorials/android.html) 
* [CodePath Android](http://guides.thecodepath.com/android)

#### #4 Membiasakan dengan Version Control

Programmer tanpa version control adalah programmer yang brutal dan nekat. Biasakan untuk menggunakan version control seperti Git, SVN, atau mercurial. Saat ini [Git](http://git-scm.com/) adalah salah satu version control yang populer, kamu bisa mulai dari sana. Ada banyak tutorial seru buat git ini :

* [Code School Git Real](https://www.codeschool.com/courses/git-real)
* [Git Tutorial](http://git-scm.com/book)
* [Git Immersion](http://gitimmersion.com/)

#### #5 Menghindari Anti-Pattern di Android

Salah satu point penting dalam pengembangan aplikasi mobile adalah, setiap platform mempunyai ciri khas yang berbeda dalam UI dan UX nya. Seperti iOS dengan tabs nya yang ada dibawah, sedangkan android diatas.

![image](http://developer.android.com/design/media/migrating_ios_dialers.png)

Pola-pola ini disebut dengan **pattern**, mengetahui pola yang ada kan menjadi sangat penting, jangan sampai mengimplementasikan yang disebut dengan **[anti-pattern](http://www.slideshare.net/commonsguy/android-app-mistakes-avoiding-the-antipatterns)**

Android Pattern :

* [Pure Android](http://developer.android.com/design/patterns/pure-android.html)
* [Android UI Pattern](http://www.androiduipatterns.com/)

Android Anti-Pattern :

* [Android Design in Action: Navigation Anti-Patterns](http://www.youtube.com/watch?v=Sww4omntVjs)
* [Android Anti Pattern](https://plus.google.com/104844169030193199790)

#### #6 Test, test, dan test 

Sudah pernah mendengar [TDD](http://en.wikipedia.org/wiki/Test-driven_development) ? Kamu tidak harus belajar TDD namun poin yang penting adalah kamu harus bisa membuat test, sehingga menghindari melakukan test secara manual. Test adalah kegiatan yang akan kamu lakukan repetitive, jadi berusahalah untuk membuatnya menjadi lebih mudah dengan otomatisasi. Ada banyak framework dan third-party tools yang bisa digunakan untuk test, namun kamu harus tau [Android Testing Fundamentals](http://developer.android.com/tools/testing/testing_android.html) dan kemudian coba untuk mempelajari :
[Robotium ](http://robolectric.org/) serta [Robotium](https://code.google.com/p/robotium/). Ketika kamu sudah lebih mahir, kamu bisa cobain testing seru seperti [calaba.sh](http://calaba.sh/).

Beberapa tempat tambahan untuk belajar android :

* [Reddit Android Dev](http://www.reddit.com/r/androiddev/)
* [AndroidHive](http://www.androidhive.info/)
* [StackOverflow](http://stackoverflow.com/questions/tagged/android)