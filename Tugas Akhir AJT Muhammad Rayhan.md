### Muhammad Rayhan
### 195150307111001
### Tugas Akhir Arsitektur Jaringan Terkini
##### Tugas 1
![Screenshot 2022-03-10 104022](https://user-images.githubusercontent.com/106861540/172378564-e0aba0a0-7bb6-4563-8b24-130403faee21.png)

Di tugas 1 ini, saya diajarkan untuk membuat sebuah 1 instance EC2 di AWS Console.
dengan spesifikasi Instance Type: t2.medium, AMI : Ubuntu Server 22.04 LTS 64 Bit, allow SSH, allow HTTP, allow HTTPS, Security Group dibuka untuk TCP Port 8081 dan 8080,
30 GiB, gp3. disertai mininet, ryu dan flow manager.

##### Tugas 2
![Screenshot 2022-03-13 183704 (1)](https://user-images.githubusercontent.com/106861540/172379182-824a8ef6-4673-4152-954e-132c8a99da71.png)

Ditugas 2 ini, saya ditugaskan untuk membuat program sederhana untuk custom topology, lalu membuat flow h1 nya terhubung ke h2 nya dan sekalian diuji koneksi nya.

##### Tugas 3
![image](https://user-images.githubusercontent.com/106861540/172381884-b11ee2eb-69af-443e-a8c8-c2a8e67a7b7a.png)
![image](https://user-images.githubusercontent.com/106861540/172381911-0ff82029-74b9-4422-95b1-c00ff7278daa.png)

di tugas 3 ini, saya belajar membuat load balancer, Load balancing adalah proses pembagian beban traffic sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi.
Hal ini mempercepat waktu respons server Anda dan mencegahnya dari overloading. Dengan begini, kinerja server Anda akan lebih maksimal tidak peduli berapa banyak traffic yang Anda dapatkan.

##### Tugas 4
Saat menulis kode “$ ryu-manager --observe-links dijkstra_Ryu_controller.py” Di terminal 1
![image](https://user-images.githubusercontent.com/106861540/172382845-65d75018-823e-4e99-b013-0d5b8772bf98.png)

Tampilan terminai 2 Setelah menulis Kode “$ sudo python3 topo-spf_lab.py” di terminal 2
![image](https://user-images.githubusercontent.com/106861540/172382874-183fb8a6-4ed8-45db-b545-7b08524ce24b.png)

Tampilan Terminal 1 dan 2 setelah mengetik “h1 ping -c 4 h4” Di terminal 2 Untuk melakukan Pengecekan Konektivitas.
Terminal 1

![image](https://user-images.githubusercontent.com/106861540/172382893-db7a0452-5235-4af0-9ea2-d11a17bc8624.png)

Terminal 2
![image](https://user-images.githubusercontent.com/106861540/172383366-ae3b6dd6-0e43-42fa-902d-2ed1bde7b811.png)

di tugas kali ini, kita diajarkan pengaplikasian SPF Routing, SPF adalah algoritma perutean di mana router menghitung jalur terpendek antara setiap pasangan node dalam jaringan. Protokol Open Shortest Path First (OSPF) didasarkan pada algoritma Shortest Path First (SPF).
