LAPORAN PRAKTIKUM 3 — CSS DASAR

Pembuatan Dokumen HTML
Praktikum diawali dengan membuat folder proyek bernama Lab3Web menggunakan Visual Studio Code. Di dalam folder tersebut dibuat file lab2_css_dasar.html yang digunakan sebagai dokumen utama untuk membangun halaman web. Dokumen HTML disusun menggunakan elemen dasar seperti <html>, <head>, dan <body>, serta dilengkapi dengan judul halaman, navigasi, heading, paragraf, dan tautan.
Bukti hasil pembuatan folder dan file HTML:
![Hasil Praktikum](media/Screenshot%202026-10-17%20132937.png)

Menampilkan Dokumen HTML pada Browser
Setelah struktur HTML selesai dibuat, file dibuka melalui browser untuk melihat hasilnya. Pada tahap ini, halaman menampilkan judul CSS Internal dan Inline CSS, menu navigasi, heading Hello World, paragraf, serta tautan informasi. Tampilan awal masih menggunakan gaya bawaan browser karena pengaturan CSS belum diterapkan secara lengkap.
Bukti hasil tampilan HTML pada browser:
![Hasil Praktikum](media/Screenshot%202026-10-17%20132814.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20132825.png)

Menerapkan CSS Internal
CSS Internal diterapkan menggunakan tag style yang diletakkan di dalam bagian head dokumen HTML. Pada praktikum ini, CSS Internal digunakan untuk mengatur jenis huruf, ukuran heading, warna teks, perataan tulisan, dan jarak elemen. Properti font-family menentukan jenis huruf, font-size menentukan ukuran teks, color mengatur warna teks, sedangkan text-align mengatur perataan teks. Perubahan tersebut membuat tampilan halaman lebih teratur dan mudah dibaca.
Bukti kode dan hasil CSS Internal:
![Hasil Praktikum](media/Screenshot%202026-10-17%20133642.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20133653.png)

Menerapkan Inline CSS
Inline CSS digunakan dengan menambahkan atribut style secara langsung pada elemen HTML. Contohnya adalah penggunaan <p style="text-align: center; color: #ccd8e4;"> untuk mengatur perataan dan warna teks paragraf tertentu. Dengan metode ini, perubahan tampilan diterapkan secara langsung pada elemen yang dipilih tanpa harus membuat aturan CSS terpisah.
Bukti kode dan hasil Inline CSS:
![Hasil Praktikum](media/Screenshot%202026-10-17%20134758.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20134811.png)

Membuat dan Menghubungkan CSS Eksternal
CSS Eksternal dibuat dengan menambahkan file style_eksternal.css di dalam folder proyek. Aturan CSS ditulis secara terpisah dari HTML, kemudian dihubungkan melalui tag <link rel="stylesheet" href="style_eksternal.css" type="text/css"> pada bagian <head>. File CSS tersebut digunakan untuk mengatur tampilan navigasi, termasuk warna latar belakang, warna teks, jarak menu, dan perubahan warna ketika kursor diarahkan ke menu. Pemisahan ini membuat kode lebih rapi dan memudahkan pengelolaan tampilan halaman web.
Bukti kode CSS Eksternal dan hasilnya:
![Hasil Praktikum](media/Screenshot%202026-10-17%20140007.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20140024.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20140043.png)

Menerapkan ID Selector dan Class Selector
ID Selector diterapkan menggunakan tanda pagar (#), seperti #intro, untuk mengatur elemen yang memiliki ID tertentu. Sementara itu, Class Selector menggunakan tanda titik (.), seperti .button dan .btn-primary, untuk mengatur elemen berdasarkan kelasnya. Pada praktikum ini, selector tersebut digunakan untuk memberikan warna latar pada bagian konten utama, mengatur jarak elemen, serta membuat tautan informasi tampil menyerupai tombol. Penggunaan selector membantu pengaturan tampilan menjadi lebih spesifik dan terstruktur.
Bukti kode ID dan Class Selector:
![Hasil Praktikum](media/Screenshot%202026-10-17%20140608.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20140555.png)

Validasi CSS Menggunakan W3C CSS Validator
Validasi CSS dilakukan untuk memeriksa apakah kode CSS yang telah dibuat sesuai dengan standar CSS. Proses validasi menggunakan layanan W3C CSS Validation Service melalui browser.
Langkah pertama, buka browser dan kunjungi situs https://jigsaw.w3.org/css-validator/. Setelah halaman validator terbuka, pilih metode validasi yang tersedia. Pada praktikum ini, file CSS yang telah dibuat, yaitu style_eksternal.css, digunakan sebagai file yang akan diperiksa.
Selanjutnya, unggah atau pilih file CSS sesuai metode validasi yang tersedia, kemudian jalankan proses pemeriksaan dengan menekan tombol Check. Tunggu hingga hasil validasi ditampilkan oleh sistem.
![Hasil Praktikum](media/Screenshot%202026-10-17%20142344.png)
![Hasil Praktikum](media/Screenshot%202026-10-17%20142306.png)

Kesimpulan
Berdasarkan praktikum yang telah dilakukan, HTML berfungsi untuk membangun struktur halaman web, sedangkan CSS digunakan untuk mengatur tampilan dan tata letak elemen. CSS Internal, Inline CSS, dan CSS Eksternal memiliki cara penerapan yang berbeda, tetapi sama-sama digunakan untuk memperindah halaman web. Selain itu, ID Selector dan Class Selector memungkinkan pengaturan gaya pada elemen tertentu sehingga tampilan halaman menjadi lebih terstruktur dan mudah dikelola.