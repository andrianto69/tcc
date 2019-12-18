## DOCKER COMPOSE

### Step 1: Setup
1. Membuat direktory minggu-12
2. Membuat file app.py
![alt text](img/Screenshot_1.png)
3. Membuat file dengan nama requirements.txt
![alt text](img/Screenshot_2.png)

### Step 2: Create Dockerfile
1. Membuat dockerfile
![alt text](img/Screenshot_3.png)

### Step 3: Define services in a Compose file
1. Membuat file docker-compose.yml
![alt text](img/Screenshot_4.png)

### Step 4: Build and run your app with Compose
1. Pada directory project yang dikerjakan, mulai aplikasi dengan mengetikan "docker-compose up".
![alt text](img/Screenshot_5.png)

2. Jalankan https://localhost:5000 pada browser
![alt text](img/Screenshot_6.png)

3. Refresh halaman browser, maka jumlah angka akan berubah sesuai berapa kali view
![alt text](img/Screenshot_7.png)

4. Untuk melihat local image dapat dicek dengan menggunakan command seperti dibawah
![alt text](img/Screenshot_8.png)

5. Untuk menghentikan aplikasi dapat menggunakan command "docker-compose down" atau menggunakan tombol "Ctrl+C".

### Step 5: Edit the Compose file to add a bind mount
1. Edit docker-compose.yml kemudian tambahkan bind mount untuk webservice
![alt text](img/Screenshot_9.png)

### Step 6: Re-build and run the app with Compose
1. Jalankan kembali dengan menggunakan "docker-compose up", maka akan muncul permintaan akses dengan memasukan login dari windows
![alt text](img/Screenshot_10.png)

2. Akses kembali https://localhost:5000 pada browser
![alt text](img/Screenshot_11.png)

### Step 7: Update the application
1. Edit file app.py kemudian ganti pesan dengan berikut ini
![alt text](img/Screenshot_12.png)

2. Refresh halaman pada docker
![alt text](img/Screenshot_13.png)