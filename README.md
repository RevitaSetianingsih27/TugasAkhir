# TugasAkhir
TugasAkhir mata kuliah Pemrograman Berorientasi Objek

## SISTEM PEMINJAMAN BUKU

## Class Diagram 
![class diagram](https://user-images.githubusercontent.com/62495628/105113226-5fd0e380-5a79-11eb-9414-419dc47f27d6.jpeg)

Terdiri dari 4 class diagram, yaitu KartuAnggota, Mahasiswa, NonMahasiswa, dan Peminjaman. KartuAnggota memiliki atribut ID_Anggota, Nama, Usia, Gender, Nomor_HP, Alamat. Atribut Mahasiswa yaitu Email dan atribut Peminjaman yaitu ID_Bukuu, Judul_Buku, Penerbit, Tanggal_Pinjam dan Tanggal_Kembali. KartuAnggota memiliki subclass Mahasiswa dan NonMahasiswa. Dan yang sudah memiliki KartuAnggota barulah bisa melakukan Peminjaman. 

## Entity Relationship Diagram (ERD)
![mermaid-diagram-20210117234155](https://user-images.githubusercontent.com/62372670/105091799-f8e01880-5ad2-11eb-9808-7a231926e31c.png)

Didalam ERD ini membutuhkan tabel/entitas yang nantinya akan digunakan didatabase, yang terdiri dari : Kartu Anggota, Mahasiswa dan Non Mahasiswa. Karena ERD ini merupakan generalisasi maka Kartu Anggota Adalah Mahasiswa Atau Kartu Anggota adalah Non Mahasiswa, jadi tidak mungkin Kartu Anggota merupakan keduanya. Dimana nantinya primary key dari mahasiswa mereferensi dari kartu anggota. Setiap Mahasiswa atau non mahasiswa memiliki lebih dari satu atau minimal satu kartu anggota tidak boleh tidak memilikinya.

## Diagram 
![Diagram](https://user-images.githubusercontent.com/62495628/105113758-6c097080-5a7a-11eb-9fe9-b182562c8e93.jpeg)

Diagram ini menjelaskan bagaimana scene builder netbeans terhubung dengan database. Berupa penambahan entitas yaitu entitas PeminjamanDataModel, KartuAggotaController, FormKartuAnggota, dan DBConnection, guna untuk menghubungkan ke basisdata, juga GUI Javafxnya. 



