## Deploying Your First Docker Container
link https://www.katacoda.com/courses/docker/deploying-first-container

Pada praktikum ini kita akan dihadapkan dengan beberapa secenario menjalankan docker. Berikut akan saya singkat langkah-langkah yang ada dalam link tutorial diatas

1. Mengidentifikasi nama Docker image yang dikonfigurasikan untuk menjalankan redis. Pada image ini terdapat semua yang diperlukan untuk memulai proses, dan tidak memerlukan konfigurasi. Perintah dibawah ini berfungsi untuk menampilkan seluruh image yang mengandung nama redis

    ![Gambar cek docker](img/Screenshot_2.png)
Kemudian untuk menjalankannya dibackground proses kita menggunakan perintah seperti ini
    ![Gambar cek docker](img/Screenshot_3.png)

2. Kita dapat menlihat proses yang sedang berjalan di background task dengan cara mengetikan perintah

    ![Gambar cek docker](img/Screenshot_4.png)
command dibawah memberikan detail lebih lanjut tentang container yang berjalan, seperti alamat IP.
    ![Gambar cek docker](img/Screenshot_5.png)

    command dibawah akan menampilkan log dari sebuah container
    
    ![Gambar cek docker](img/Screenshot_6.png)

3. Redis tadi dapat kita jalankan pada background dengan nama redisHostPort di port 6379
    
    ![Gambar cek docker](img/Screenshot_7.png)
    ![Gambar cek docker](img/Screenshot_8.png)

4. Container yang sudah kita buat tadi dapat dijalankan lebih dari satu proses dengan cara memanfaatkan port yang tidak sedang digunakan oleh redis
    
    ![Gambar cek docker](img/Screenshot_9.png)

5. Untuk menyimpan log dan data dari container image dapat menggunakan perintah seperti berikut
    
    ![Gambar cek docker](img/Screenshot_10.png)

6. Menjalankan docker dengan bash ubuntu dapat dilakukan dengan cara seperti berikut
    
    ![Gambar cek docker](img/Screenshot_11.png)


## Deploy Static HTML Website as Container 
link https://www.katacoda.com/courses/docker/create-nginx-static-web-server

Pada praktik ini, Anda akan belajar cara membuat Docker untuk menjalankan situs web HTML statis menggunakan Nginx.

1. Membuat dockerfile untuk membangun image menggunakan nginx:alpine dengan direktory di /usr/share/nginx/html
    
    ![Gambar cek docker](img/Screenshot_12.png)

2. Membuat HTML statis menggunakan command

    ![Gambar cek docker](img/Screenshot_13.png)
    kemudian list image dapat dilihat dengan cara seperti ini
    ![Gambar cek docker](img/Screenshot_14.png)

3. Kemudian webserver image tadi bisa kita run dengan perintah sebagai berikut

    ![Gambar cek docker](img/Screenshot_15.png)
Selain itu kita dapat mengakses pada link yang sudah disediakan oleh katacoda

    ![Gambar cek docker](img/Screenshot_16.png)