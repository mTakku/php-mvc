<p align="center" >
  <b>POINT UTAMA</b>
</p>

---

> #### SEJARAH MVC
> - Sejarah Model-View-Controller (MVC) pertama kali diperkenalkan pada tahun 1970 oleh Trip Ransquawk di Xerox Palo Alto Research.
> - Konsep MVC terbagi menjadi tiga bagian: model, view, dan controller.
> - MVC sederhana namun bisa menjadi kompleks dalam pengembangan aplikasi yang rumit, kadang-kadang membutuhkan pola desain dan paten perangkat lunak tambahan.
---
> #### PUBLIC DIRECTORY
> - Praktek terbaik adalah tidak mengekspos seluruh kode PHP ke web, tetapi hanya mengekspos folder publik yang berisi file yang dibutuhkan.
>
> Berikut struktur project :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/361aebd7-0f06-4b22-ba1c-56b8222ed9c5)
---
> #### PATH_INFO
> - Pathinfo adalah informasi bagian dari URL yang mengandung informasi tambahan, seperti nama file atau parameter query.
> - Pathinfo dapat dimanfaatkan untuk mengarahkan permintaan HTTP ke file yang sesuai tanpa perlu menambahkan nama file dalam URL.
>
> Berikut kode PATH_INFO :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/799dd181-cec5-4a44-83e9-02721666c763)
>
> #### UNTUK APA PATH_INFO?
> - PATH_INFO ini banyak digunakan sabagai URL Routing
> - Routing adalah teknik menentukan rute dari URL ke file PHP yang akan dieksekusi, memungkinkan penanganan permintaan HTTP sesuai dengan URL yang diminta.
>
> Berikut kode routing sederhana :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/70d782b5-daf3-407e-983b-0a6157c61633)
---
> #### ROUTER
> - Routing sederhana menggunakan pathinfo memungkinkan kita untuk menentukan file mana yang akan diakses berdasarkan bagian dari URL yang dikirimkan.
> - Routing dalam aplikasi MVC melibatkan pemetaan antara URL, metode HTTP, dan fungsi kontrol yang sesuai.
>
> Berikut kode class router :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/84d98032-8919-4bfb-8558-d17c4a6b406b)
>
> Berikut kode menambah url mapping :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/a60b74e2-1407-4e0b-918e-bcdd9adca71b)
>
> Berikut kode memilih controller :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/696a8bf1-debd-487e-8217-e5d03316fcc4)
>
> Berikut kode menggunakan router :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/0f573230-d1ad-4156-bb52-a56c8fd9377a)
---
> #### CONTROLLER
> - Controller dalam MVC bertanggung jawab untuk mengeksekusi fungsi yang sesuai berdasarkan pada permintaan yang diterima dan pemetaan yang telah ditentukan.
> - Setelah pemetaan URL dilakukan, selanjutnya adalah membuat controller yang akan menerima permintaan dan melakukan pemrosesan logika aplikasi.
>
> Berikut kode home controller :
>
> ![image](https://github.com/mTakku/php-mvc/assets/145539342/4a743a62-5050-4492-b492-70322a904ac9)
---
<p align="center" >
  <b>PERTANYAAN DAN CATATAN TAMBAHAN</b>
</p>

---

> - Tidak ada

---

<p align="center" >
  <b>KESIMPULAN</b>
</p>

> - dapat membantu dalam membangun sistem pengembangan website yang terdiri dari tiga bagian yaitu model, view, dan controller.









