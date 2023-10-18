# Cruise-Control-
Pengembangan sistem rekayasa piranti lunak menggunakan metode konvensional melibatkan dua komponen utama dalam analisis sistem, yaitu Data-Flow Diagram (DFD) yang digunakan untuk menggambarkan fungsi sistem, dan Four Variable Model yang digunakan untuk menggambarkan empat variabel yang menganalisis lapisan arsitektur perangkat lunak. DFD digunakan dalam pemodelan lingkungan sistem, sementara Four Variable Model menggambarkan variabel yang melibatkan Monitored variable, Controlled variable, Input data, dan Output data.
Dalam pengembangan sistem, terdapat dua pendekatan utama, yaitu pendekatan Top-Down dan pendekatan Bottom-Up. Pendekatan Top-Down menggambarkan sistem mulai dari pemetaan global, lalu turun ke detail yang lebih deskriptif. Sedangkan pendekatan Bottom-Up memulai pemodelan dari unit terkecil hingga mencapai unit terbesar. Metode DePES (Development Process of Embedded System) adalah metode pengembangan proses untuk sistem komputer yang bersifat menjelaskan bagan-bagan perancangan suatu sistem. Metode ini membantu memberikan informasi terpadu kepada para programmer dan memfasilitasi pemahaman kesalahan serta pengembangan program.

Proses perancangan sistem dengan metode DePES melibatkan langkah-langkah berikut:
1.	Menggambarkan permasalahan sistem.
2.	Membuat persyaratan sistem.
3.	Mendekomposisi permasalahan dalam sistem.
4.	Menghubungkan spesifikasi mesin untuk setiap sub-masalah.
5.	Merancang arsitektur sistem secara global.
6.	Menghubungkan spesifikasi komponen ke arsitektur global.
7.	Merancang arsitektur untuk komponen yang dapat diprogram dari arsitektur global.
8.	Menjelaskan perilaku seluruh komponen dalam arsitektur perangkat lunak menggunakan sequence diagram.
9.	Mengimplementasikan komponen menjadi program dan lingkungan pengujian.
10.	Mengintegrasikan seluruh komponen yang telah diprogram menjadi sistem perangkat lunak yang utuh dan menguji keseluruhan sistem perangkat lunak.

Penelitian ini berfokus pada pengembangan algoritma Adaptive Cruise Control (ACC) berbasis logika fuzzy. Terdapat dua konfigurasi umum dalam kendali tingkat tinggi pada ACC. Konfigurasi pertama hanya menggunakan satu masukan, yaitu kecepatan yang diinginkan, yang dihasilkan dari pengolahan jarak antara kendaraan depan (EV) dan kendaraan belakang (LV). Namun, konfigurasi ini memiliki kelemahan karena dapat menyebabkan pengereman dan pemercepatan berlebihan. Konfigurasi kedua menggunakan dua masukan, yaitu jarak dan kecepatan. Kecepatan dapat diukur berdasarkan kecepatan EV, kecepatan LV, atau kecepatan relatif antara EV dan LV. Penghematan dapat dilakukan dengan menghitung kecepatan berdasarkan informasi jarak EV dan LV. Logika fuzzy digunakan untuk mengendalikan ACC, dengan masukan berupa jarak dan perubahan jarak antara EV dan LV yang diperoleh dari sensor. Hasil inferensi dari logika fuzzy menghasilkan nilai fuzzy yang kemudian didefuzzifikasi menjadi set point untuk sistem kendali tingkat rendah.
Fungsi keanggotaan masukan pada ACC melibatkan jarak dan perubahan jarak antara EV dan LV. Fungsi-fungsi keanggotaan ini memainkan peran penting dalam pengendalian ACC, dan proses inferensi dengan metode Mamdani digunakan untuk menghasilkan set point kecepatan. Dengan demikian, ACC dapat mengatur kecepatan kendaraan berdasarkan jarak dengan kendaraan di depan dan perubahan jarak tersebut, memungkinkan kendaraan untuk menjaga jarak yang aman dengan kendaraan lain di jalan 

