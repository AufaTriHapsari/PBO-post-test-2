# PBO-post-test-2

# NAMA : Aufa Tri Hapsari
# NIM : 2209116031
# KELAS : SISTEM INFORMASI A 222

## Penjelasan Program
Program ini, dirancang dalam bahasa Java, bertujuan mempermudah pengelolaan bisnis toko bunga Cyra Florist menerapakan operasi CRUD (Create, Read, Update, Delete). Dengan penggunaan setter-getter, dan koleksi ArrayList untuk penyimpanan data, program ini menjaga keamanan dan keteraturan data. Method-method bersifat "static" memungkinkan akses langsung ke operasi tertentu tanpa memerlukan pembuatan objek kelas, meningkatkan efisiensi. Dengan pendekatan ini, program ini memberikan manajemen data yang lebih baik, mempermudah operasional toko bunga, dan mendukung kelancaran bisnis sektor pertanian bunga. Dalam bisnis sehari-hari, manajemen data yang tepat sangat krusial, dan program ini menjadi solusi relevan dalam pengelolaan stok bunga, catatan pelanggan, serta pesanan bunga di toko bunga.

### Screenshoot dan penjelasan  Source code
**CRUD**
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/58194e8c-3d31-4e8d-b264-54f23066ae1a)
**Package com.mycompany.mainpt2**
Merupakan package utama yang mengandung program inti untuk toko bunga. Di dalamnya, program menggunakan ArrayList dan Scanner untuk mengelola operasi sehari-hari dalam bisnis bunga, seperti manajemen pelanggan, pesanan, dan bunga. Package ini juga memanfaatkan kelas-kelas dari package lain, seperti Customer, Order, dan Bunga, untuk merepresentasikan data pelanggan, pesanan, dan bunga. Dengan demikian, program ini membantu pemilik toko bunga dalam mengoptimalkan operasional bisnis mereka.
b. ![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/66dd200a-2800-4172-9832-5a82a8d0508f)

**1. Menambahkan Pelanggan**
Metode `addCustomer` memungkinkan Anda untuk menambahkan pelanggan ke dalam daftar pelanggan toko bunga. Dengan metode ini, Anda dapat memasukkan nama, alamat, dan nomor telepon pelanggan untuk mencatat informasi pelanggan yang lengkap.
**2. Membuat Pesanan**
Dengan metode `createOrder`, Anda dapat membuat pesanan untuk pelanggan yang telah ada dalam daftar pelanggan. Metode ini memungkinkan Anda untuk mencari pelanggan berdasarkan nama dan kemudian menambahkan pesanan ke dalam daftar pesanan pelanggan tersebut.

**3. Menambahkan Bunga ke Pesanan**
`addFlower` digunakan untuk menambahkan bunga ke dalam pesanan pelanggan. Anda dapat mencari pelanggan berdasarkan nama, kemudian mencari pesanan berdasarkan ID, dan akhirnya menambahkan bunga ke dalam pesanan tersebut. Metode ini membantu mengelola stok bunga dan pesanan pelanggan dengan efisien.

**4. Menghapus Bunga dari Pesanan**
Metode `deleteFlower` memungkinkan Anda untuk menghapus bunga dari pesanan pelanggan. Anda dapat mencari pelanggan berdasarkan nama, kemudian mencari pesanan berdasarkan ID, dan akhirnya menghapus bunga dari pesanan tersebut. Dengan ini, Anda dapat memperbarui pesanan pelanggan dengan mudah.

**5. Melihat Semua Pesanan**
`viewAllOrders` adalah metode yang memungkinkan Anda untuk melihat semua pesanan yang ada dalam sistem. Metode ini mencantumkan nama pelanggan, ID pesanan, serta daftar bunga dalam setiap pesanan. Ini membantu Anda memantau semua operasi toko bunga dengan cepat.

**6. Memperbarui Data Pelanggan**
Dengan metode `updateCustomer`, Anda dapat memperbarui informasi pelanggan yang sudah ada dalam daftar pelanggan. Pengguna dapat memilih informasi apa yang ingin diperbarui, seperti nama, alamat, atau nomor telepon, dan kemudian memasukkan nilai baru. Metode ini membantu menjaga integritas data pelanggan dalam sistem dan memastikan data yang relevan selalu terkini.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/f5541d81-d259-403b-8566-b68380aae3b8)

private static void adalah kata kunci yang digunakan untuk mendefinisikan metode. Kata kunci ini menunjukkan bahwa metode ini bersifat statis, artinya tidak terkait dengan instance objek tertentu dan dapat dipanggil langsung melalui kelas tanpa perlu membuat objek dari kelas Mainpt2. Dalam konteks metode, ini berarti metode ini dapat digunakan untuk melakukan tugas-tugas tertentu dalam program tanpa harus menciptakan objek Mainpt2. Dalam program toko bunga ini, metode tersebut digunakan untuk mengelola operasi seperti menambahkan pelanggan, membuat pesanan, menambahkan bunga ke dalam pesanan, menghapus bunga dari pesanan, dan melihat semua pesanan yang ada. Dengan menggunakan metode statis, pemanggilan metode-metode tersebut terkait dengan kelas Mainpt2, dan tidak diperlukan pembuatan instance objek dari kelas tersebut untuk menjalankannya.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/d1d8301c-8435-4b4c-b03e-b2baa8c790d1)

**Switch Steatment**'
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/d328eb02-9f7a-4485-b6ea-c1365fe9f644)
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/618286eb-e597-4b67-8133-b35cf8ef4152)
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/e34d3876-67a1-455f-8880-48cb7ab1de72)
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/baa032a1-63dd-44e4-9a19-9ce9413cb17c)

**Class Bunga**
Kelas ini digunakan untuk merepresentasikan data bunga yang dapat dipesan dalam sebuah pesanan. Setiap bunga memiliki atribut seperti nama, warna, dan harga.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/49586a64-3f5f-48c6-949f-a8e479bca1ac)

**Class Order**
Kelas ini merepresentasikan pesanan yang dibuat oleh pelanggan. Setiap pesanan memiliki ID unik, daftar bunga yang dipesan, serta informasi pelanggan yang membuat pesanan tersebut.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/ce134eef-3fbf-4828-b170-8a3a2a18e55d)

**Class Customer**'
Kelas ini digunakan untuk merepresentasikan data pelanggan. Setiap pelanggan memiliki atribut seperti nama, alamat, nomor telepon, serta daftar pesanan yang telah dibuat.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/58ee39e0-17e9-4ffe-98e0-05f4364304d7)


### Screenshoot dan penjelasan Outpout

Berikut ini adalah penjelasan output program dari menu 1 hingga 6 beserta cara kerjanya:

### Menu 1: Add Customer
- Output Program: Program akan meminta Anda untuk memasukkan nama, alamat, dan nomor telepon pelanggan. Setelah informasi pelanggan dimasukkan, program akan memberikan konfirmasi bahwa pelanggan telah berhasil ditambahkan dengan ID pelanggan yang unik.
- Cara Kerja: Ketika Anda memilih menu ini, program akan memanggil metode `addCustomer()`. Anda diminta untuk memasukkan informasi pelanggan seperti nama, alamat, dan nomor telepon. Kemudian, program akan membuat objek pelanggan baru dengan informasi yang dimasukkan, menggenerasi ID pelanggan yang unik, dan menambahkannya ke dalam daftar pelanggan.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/5823ea79-f1e0-4784-b831-3413b11a8d4a)


### Menu 2: Create Order
- Output Program: Program akan meminta Anda untuk memasukkan nama pelanggan. Jika pelanggan ditemukan, maka pesanan baru akan dibuat dengan ID pesanan yang unik dan dikaitkan dengan pelanggan tersebut. Program akan memberikan konfirmasi bahwa pesanan berhasil dibuat.
- Cara Kerja: Ketika Anda memilih menu ini, program akan memanggil metode `createOrder()`. Anda diminta untuk memasukkan nama pelanggan yang akan membuat pesanan. Program akan mencari pelanggan berdasarkan nama yang dimasukkan. Jika pelanggan ditemukan, pesanan baru akan dibuat dan dihubungkan dengan pelanggan tersebut.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/a07fb364-dfe5-4093-8e93-40a78331e0fd)

### Menu 3: Add Flower to Order
- Output Program: Program akan meminta Anda untuk memasukkan nama pelanggan dan ID pesanan. Jika pelanggan dan pesanan ditemukan, program akan meminta informasi bunga seperti nama, warna, dan harga. Setelah informasi dimasukkan, program akan memberikan konfirmasi bahwa bunga berhasil ditambahkan ke dalam pesanan.
- Cara Kerja: Ketika Anda memilih menu ini, program akan memanggil metode `addFlower()`. Anda diminta untuk memasukkan nama pelanggan dan ID pesanan yang ingin Anda tambahkan bunga ke dalamnya. Program akan mencari pelanggan berdasarkan nama dan pesanan berdasarkan ID. Jika pelanggan dan pesanan ditemukan, program akan meminta Anda memasukkan informasi bunga, dan kemudian bunga akan ditambahkan ke dalam pesanan.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/9c7bf7a4-98da-45c5-90e5-e4ccb08ea63c)

### Menu 4: Delete Flower from Order
- Output Program: Program akan meminta Anda untuk memasukkan nama pelanggan, ID pesanan, dan nama bunga yang ingin dihapus. Jika pelanggan, pesanan, dan bunga ditemukan, program akan menghapus bunga dari pesanan dan memberikan konfirmasi bahwa bunga berhasil dihapus.
- Cara Kerja: Ketika Anda memilih menu ini, program akan memanggil metode `deleteFlower()`. Anda diminta untuk memasukkan nama pelanggan, ID pesanan, dan nama bunga yang ingin dihapus. Program akan mencari pelanggan, pesanan, dan bunga yang sesuai. Jika semuanya ditemukan, bunga akan dihapus dari pesanan.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/3046600b-e135-4b7c-95c0-55fe2fca8c1f)


### Menu 5: View All Orders
- Output Program: Program akan menampilkan semua pesanan yang ada di toko bunga. Informasi pesanan mencakup nama pelanggan, ID pesanan, serta daftar bunga dalam setiap pesanan.
- Cara Kerja: Ketika Anda memilih menu ini, program akan memanggil metode `viewAllOrders()`. Program akan menampilkan daftar semua pesanan yang ada di toko bunga, termasuk nama pelanggan, ID pesanan, dan daftar bunga dalam setiap pesanan.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/62c36f1b-1172-4736-a9cc-43c7434f7c76)


### Menu 6: Update Customer
- Output Program: Program akan meminta Anda memasukkan nama pelanggan yang akan diubah. Selanjutnya, Anda diminta untuk memilih informasi yang ingin diubah, seperti nama, alamat, atau nomor telepon. Setelah informasi baru dimasukkan, program akan memberikan konfirmasi bahwa informasi pelanggan telah berhasil diperbarui.
- Cara Kerja: Ketika Anda memilih menu ini, program akan memanggil metode `updateCustomer()`. Program akan meminta Anda memasukkan nama pelanggan yang ingin diubah. Kemudian, Anda dapat memilih jenis informasi apa yang akan diubah, seperti nama, alamat, atau nomor telepon. Setelah informasi baru dimasukkan, data pelanggan akan diperbarui sesuai dengan pilihan Anda.
![image](https://github.com/AufaTriHapsari/PBO-post-test-2/assets/122031507/94eef993-8727-400f-885f-38720f0b53ad)


Dengan berbagai pilihan menu ini, program "Cyra Florist" memudahkan pengguna dalam mengelola bisnis bunga, termasuk pelanggan, pesanan, dan bunga yang tersedia. Semua operasi ini membantu meningkatkan efisiensi operasional toko bunga.
