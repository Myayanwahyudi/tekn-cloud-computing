# Data as a service
Dalam komputasi, data sebagai layanan, atau DaaS, diaktifkan oleh perangkat lunak sebagai layanan (SaaS). [1] Seperti semua teknologi "sebagai layanan" (aaS), DaaS membangun konsep bahwa produk datanya dapat diberikan kepada pengguna berdasarkan permintaan, [2] terlepas dari pemisahan geografis atau organisasi antara penyedia dan konsumen. Arsitektur berorientasi layanan (SOA), dan meluasnya penggunaan API, telah menjadikan platform tempat data berada sebagai tidak relevan. [3]

DaaS dimulai terutama di mashups Web dan, sejak 2015, telah semakin dipekerjakan baik secara komersial, maupun dalam organisasi seperti PBB. [5]

Secara tradisional, sebagian besar organisasi telah menggunakan data yang disimpan dalam repositori mandiri, yang untuknya perangkat lunak dikembangkan secara khusus untuk mengakses dan menyajikan data dalam bentuk yang dapat dibaca manusia. Salah satu hasil dari paradigma ini adalah penggabungan data dan perangkat lunak yang diperlukan untuk menafsirkannya menjadi satu paket, dijual sebagai produk konsumen. Karena jumlah perangkat lunak yang dibundel dengan paket data berkembang biak, dan diperlukan interaksi antara satu sama lain, lapisan antarmuka lain diperlukan. Antarmuka ini, secara kolektif dikenal sebagai integrasi aplikasi perusahaan (EAI), sering cenderung mendorong vendor lock-in, karena umumnya mudah untuk mengintegrasikan aplikasi yang dibangun di atas teknologi pondasi yang sama. [5]

# Cloud database
Basis data cloud adalah basis data yang biasanya berjalan pada platform komputasi awan, dan akses ke basis data disediakan sebagai layanan.

Layanan basis data menjaga skalabilitas dan ketersediaan tinggi basis data. Layanan basis data membuat tumpukan perangkat lunak yang mendasarinya transparan bagi pengguna.
Ada dua metode utama untuk menjalankan database di cloud:

Gambar mesin virtual
Platform cloud memungkinkan pengguna untuk membeli mesin virtual untuk waktu yang terbatas, dan seseorang dapat menjalankan basis data pada mesin virtual tersebut. Pengguna dapat mengunggah gambar mesin mereka sendiri dengan database yang diinstal di atasnya, atau menggunakan gambar mesin yang sudah jadi yang sudah termasuk instalasi optimalisasi database.
Database-as-a-service (DBaaS)
Dengan database sebagai model layanan, pemilik aplikasi tidak harus menginstal dan memelihara sendiri database tersebut. Sebaliknya, penyedia layanan basis data bertanggung jawab untuk menginstal dan memelihara basis data, dan pemilik aplikasi dikenai biaya sesuai dengan penggunaan layanan tersebut. Ini adalah jenis Saas - Perangkat Lunak sebagai Layanan.
Arsitektur dan karakteristik umum
Sebagian besar layanan database menawarkan konsol berbasis web, yang dapat digunakan pengguna akhir untuk menyediakan dan mengkonfigurasi instance database.
Layanan database terdiri dari komponen database-manager, yang mengontrol instance database yang mendasarinya menggunakan API layanan. API layanan terpapar ke pengguna akhir, dan memungkinkan pengguna untuk melakukan pemeliharaan dan operasi penskalaan pada instance basis data mereka.
Perangkat lunak stack-stack yang mendasarinya biasanya mencakup sistem operasi, database, dan perangkat lunak pihak ketiga yang digunakan untuk mengelola database. Penyedia layanan bertanggung jawab untuk menginstal, menambal, dan memperbarui tumpukan perangkat lunak yang mendasarinya dan memastikan kesehatan dan kinerja keseluruhan basis data.
Fitur skalabilitas berbeda antara vendor - beberapa menawarkan penskalaan otomatis, yang lain memungkinkan pengguna untuk meningkatkan menggunakan API, tetapi tidak skala secara otomatis.
Biasanya ada komitmen untuk tingkat ketersediaan tinggi tertentu (mis. 99,9% atau 99,99%). Ini dicapai dengan mereplikasi data dan membuat instance yang gagal ke instance database lain.
