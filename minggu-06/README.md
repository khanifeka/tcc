## Deploy Redis as a Docker Container  
Terdapat sebuah skenario, dimana kita berperan sebagai jane, yaitu developer yang perlu menggunakan Key-Value Store baru untuk aplikasi yang sedang bekerja dengannya. Setelah berdiskusi, diputuskan untuk menggunakan Redis.  
Skenario ini membahas bagaimana dia akan menyelesaikan tugasnya dan menggunakan Redis sebagai Docker Container.  

### What is Docker ?  
Platform terbuka bagi pengembang dan sysadmin untuk membangun, mengirim, dan menjalankan aplikasi terdistribusi, docker memungkinkan Anda untuk menjalankan kontainer.  

Terdapat 3 Skenario yang harus dijalankan oleh Jane.  


## Let's Start !!!  
1. Searh Readis    
![Redis](images/Search.jpg)  
Command diatas digunakan untuk menemukan docker image redis.  

2. Running Redis  
![Running](images/2.jpg)    
Dengan menggunakan command seperti pada gambar, maka redis akan berjalan dengan versi terbaru.  

3. Finding running containers    
![Finding](images/Finding.jpg)  
Command diatas digunakan untuk mengetahui container apa saja yang sedang berjalan dan info secara detail.  

4. Accessing Redis      
![Access](images/Access.jpg)  
untuk dapat mengakses container ini, maka kita harus memanggil port pada redis dan container yang diekspos melalui sebuah host, Redis berjalan pada port 6379.    
![Access2](images/Access2.jpg)      
untuk mengakses redis pada port yang tersedia secara acak, dan untuk melihat pada port mana redis ini berjalan.   

5. Persisting Data    
![Persisting](images/Persisting.jpg)  
Supaya data pada container tidak hilang ketika memindah ataupun membuat kontainer baru, sehingga data yang sebelumnya dapat di restore.  

6. Running A Container In The Foreground  
![Access](images/Ubuntu.jpg)    
Ubuntu dapat menjalankan perintah menggunakan bon / bash.  

## Deploy Static HTML Website as Container  
Bagaimana membuat Docker image untuk menjalankan Website static HTML menggunakan Nginx.  

1. Create Docker file  
![Create](images/file.jpg)    

2. Build Docker Image  
 Create Docker file    
![Build](images/Build.jpg)   

3. Run  
![run](images/run.jpg)   
Mengakses docker image melalui port 80    
![Picture1](images/Picture1.jpg)     
Hello World ini dapat diganti dengan Kata lain. Stop terlebih dahulu docker yang sedang berjalan, kemudian rm dan build kembali webserver.  

## Building Container Image  

Docker Image dibangun berdasarkan Dockerfile.   Dockerfile mendefinisikan semua langkah yang   diperlukan untuk membuat Docker Image dengan     aplikasi Anda dikonfigurasikan dan siap dijalankan sebagai Kontainer. Image itu sendiri berisi   segalanya, dari sistem operasi hingga dependensi   dan konfigurasi yang diperlukan untuk menjalankan   aplikasi Anda.    

1. Base Image  
![base](images/base.jpg)    
ini berfungsi untuk membuat Docker File.  

2. Running Commands    
![copy](images/c.jpg)    
untuk mengkopi index.html kedalam directory yang dipanggil.  

3. Exposing Ports  
![ports](images/p.jpg)    
Supaya Docker image dapat diakses melalui port yang sudah ditentukan.  

4. Default Commands    
![nginx](images/n.jpg)    
untuk menjalankan nginx.  

5. Building Containers    
![docimage](images/d.jpg)    
![build](images/b.jpg)      

6. Launching New Image    
![launching](images/launching.jpg)  
![ps](images/ps.jpg)  



Done :)    

### - 175410074 -

