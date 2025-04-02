# PersiapanP05
## 1. Apa itu Multithreading?
- Multithreading adalah konsep pemrograman yang memungkinkan sebuah program untuk menjalankan beberapa thread, atau urutan eksekusi kode, secara simultan dalam proses yang sama. Kemampuan seperti ini juga termasuk dalam multitasking pada aplikasi. Selain itu multithreading juga memungkinkan pengeksekusian beberapa thread dilakukan dala satu proses saling berbagi sumber daya tetapi dijalankan secara independen.

## 2. Apa perbedaan antara thread dan runnable?
- Thread merupakan class, sementara runnable merupakan interface.
- Karena thread merupakan class, untuk penggunaannya harus di-extend. Sementara runnable karena hanya interface, maka tidak perlu kita extend.
- Jika kita menggunakan thread, kita tidak dapat meng-extend class lain lagi karena java tidak memungkinkan inheritance ganda/lebih. Sementara jika kita menggunakan runnable, kita masih bisa meng-extend class lain karena masih ada slot untuk melakukan inheritance. Selain itu java tidak membatasi jumlah interface yang dapat digunakan, jadi selain runnable kita masih bisa menambahkan interface lain.

## 3. Thread.sleep() digunakan untuk?
- Dengan menggunakan Thread Sleep, kita bisa membuat sebuah thread tertidur dan berhenti dalam waktu yang kita tentukan.
- Penting jika ingin membuat simulasi proses yang berjalan dalam waktu tertentu.
- Misal jika kita meletakkan Thread.sleep(1000) pada loop 1 sampai 5, maka dari output 1 ke 2 akan dijeda 1 detik (1000 milisekon) sebelum dioutputkan.
