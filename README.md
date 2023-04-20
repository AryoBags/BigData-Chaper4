# BigData-Chaper4
Untuk memulai spark, silakan akses ke folder spark di mana Anda pernah ekstrak sebelumnya. Misalnya di bawah ini terletak di /home/cloudera, lalu masuk ke folder sbin dan run start-all.sh untuk menjalankan spark daemons. Jika diminta mengisi password, maka isikan cloudera.

![image](https://user-images.githubusercontent.com/95728907/233432021-3b264437-b684-49f9-8d17-6afc14ba77c6.png)

 <h3>hasilnya</h3>
 
![image](https://user-images.githubusercontent.com/95728907/233432809-724c43cb-4aed-4d96-b3b3-b710ab73c90c.png)

<h1> Analitik DataFrame </h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/CreatingDataFrames.py#L1-L39
 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233448343-f3246dda-21bc-49a7-bc92-acc39caf283b.png)

![image](https://user-images.githubusercontent.com/95728907/233448462-f68020c6-9f64-465f-86bc-481eb63b770a.png)

![image](https://user-images.githubusercontent.com/95728907/233448559-2a7bf7a3-6375-4c3c-a34a-617947a3f0ec.png)

<h1> Membuat DataFrame dari DB Eksternal </h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/CreatingDataFramesfromDBs.py#L1-L9
 <h3>hasilnya</h3>
 
![image](https://user-images.githubusercontent.com/95728907/233453443-d21b57a9-f455-430d-bf1d-74b66a8af413.png)

<h1> Mengonversi DataFrames ke RDDs </h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/DataFrames2RDD.py#L1-L12

 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233463742-d541850c-a18e-4f06-acb3-5bc67e4b62df.png)

<h1> Membuat dataset (scala) </h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/CreateDatasets.scala#L1-L28

 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233464242-46eb2499-1a35-427c-aafc-97e868a2742e.png)


<h1> Mengonversi DataFrame ke Datasets dan sebaliknya </h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/Datasets2DataFramesViceVersa.py#L1-L18

 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233465398-c35baf62-b0eb-491b-958f-1d0086adf0f8.png)


<h1>Mengakses Metadata menggunakan Catalog</h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/CreatingDataFramesfromDBs.py#L1-L9
 
 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233466248-8d33d2c8-7e62-4673-83e3-19f22594ec86.png)

<h1>Bekerja dengan berkas teks</h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/DataSourceTEXT.py#L1-L6

 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233467615-4d42ac8b-ea4c-4449-957e-316f951b086d.png)

<h1>Bekerja dengan JSON</h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/DataSourceJson.py#L1-L17

 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233468751-c1843dfa-03d4-465d-ad25-be37b1fe39dc.png)


<h1>Bekerja dengan CSV</h1>
https://github.com/AryoBags/BigData-Chaper4/blob/166830beff9aa615bd45800307a09f8480708ba9/DataSourceCSV.py#L1-L11

 <h3>hasilnya</h3>
 
 ![image](https://user-images.githubusercontent.com/95728907/233469248-79281b89-82e3-420b-af79-ac619dd00b82.png)


<h1>Tugas</h1>
Silakan selesaikan praktikum tersebut sesuai langkah-langkah sebelumnya, lalu laporkan hasilnya berupa link repository GitHub dengan nama spark-sql-big-data disertai dengan screenshot hasilnya.
Jelaskan masing-masing maksud kode berikut sesuai nomor kodenya pada laporan praktikum Anda!

![image](https://user-images.githubusercontent.com/95728907/233469522-79b9fa54-b55f-47ad-a3b9-6517f62b9938.png)

 <h3>jawab</h3>
 
1. Definisi variable
2. Membuat DataFrame dengan objek list, schema dan default data types
3. Membuat DataFrame dengan parallelizing list dan konversi RDD ke DataFrame
4. Mengunggah file people.txt dari path /examples/resources/people.txt ke dalam sistem file Hadoop dengan    nama file people.txt
5. pyspark.sql adalah modul PySpark yang digunakan untuk melakukan pemrosesan data dengan menggunakan SQL. SQLContext adalah objek yang menyediakan antarmuka untuk berinteraksi dengan data yang disimpan dalam Spark. createOrReplaceTempView adalah metode PySpark yang digunakan untuk membuat tampilan sementara dataframe sebagai tabel di Spark SQL. Show adalah metode PySpark yang digunakan untuk menampilkan isi dataframe.
6. TextFile adalah metode SparkSQL yang digunakan untuk membaca file teks dan membuat RDD (Resilient Distributed Dataset) dari data yang ada di dalamnya. Map adalah metode PySpark yang digunakan untuk menerapkan fungsi pada setiap elemen dalam RDD. Lambda adalah fungsi anonim dalam Python yang digunakan untuk membuat fungsi sederhana tanpa nama. Strip adalah metode Python yang digunakan untuk menghapus karakter whitespace dari awal dan akhir sebuah string. StructField adalah kelas PySpark yang digunakan untuk menentukan skema atau struktur dari sebuah dataframe Spark. StringType adalah kelas PySpark yang digunakan untuk menentukan tipe data string dalam dataframe Spark
7. spark.read.format adalah metode PySpark yang digunakan untuk membaca data dari sumber eksternal ke dalam dataframe Spark dengan format tertentu. jdbc adalah nama format yang digunakan untuk membaca data dari database relasional menggunakan JDBC (Java Database Connectivity) dalam Spark. options adalah argumen tambahan yang digunakan untuk memberikan informasi tambahan tentang sumber data yang dibaca. load adalah metode PySpark yang digunakan untuk memuat data dari sumber eksternal ke dalam dataframe Spark.
8. Menampilkan data yang sudah dibaca menggunakan jdbc
9. collect adalah metode PySpark yang digunakan untuk mengembalikan seluruh elemen RDD dari executor ke driver program PySpark. rdd adalah atribut dari dataframe Spark yang digunakan untuk mengonversi dataframe menjadi RDD. take adalah metode PySpark yang digunakan untuk mengambil sejumlah elemen tertentu dari RDD dan mengembalikannya ke driver program PySpark.
10. makeRDD adalah metode PySpark yang digunakan untuk membuat RDD dari sebuah sequence atau kumpulan data dalam PySpark. Seq adalah tipe data di Scala untuk merepresentasikan sequence atau kumpulan data dalam PySpark. createDataset adalah metode PySpark yang digunakan untuk membuat Dataset dari sebuah sequence atau kumpulan data dalam PySpark.
11. Melakukan Filtering pada data frame
12. as adalah metode PySpark yang digunakan untuk memberikan alias pada kolom-kolom dataframe. toDF adalah metode PySpark yang digunakan untuk mengubah RDD menjadi dataframe. first adalah metode PySpark yang digunakan untuk mengambil nilai pertama dari RDD atau dataframe.
13. listDatabases adalah metode PySpark yang digunakan untuk menampilkan daftar database Spark yang tersedia. listTables adalah metode PySpark yang digunakan untuk menampilkan daftar tabel yang tersedia dalam database Spark. listFunctions adalah metode PySpark yang digunakan untuk menampilkan daftar fungsi yang tersedia dalam SparkSQL. isCached adalah metode PySpark yang digunakan untuk mengecek apakah sebuah tabel sudah di-cache atau belum. select adalah metode PySpark yang digunakan untuk melakukan query data dari tabel.
14. Read untuk membaca file Text untuk menerima inputan dengan tipe .txt
15. load adalah metode PySpark yang digunakan untuk memuat data json adalah metode PySpark yang digunakan untuk membaca data dalam format JSON. format adalah metode PySpark yang digunakan untuk menentukan format file yang akan dibaca atau ditulis. printSchema adalah metode PySpark yang digunakan untuk menampilkan schema dari dataframe.
16. Write digunakan untuk menulis save digunakan untuk menyimpan
17. Menulis data ke format parquet.
18. Options adalah sebuah dictionary pada Python yang digunakan untuk menyediakan opsi-opsi tambahan pada saat membaca atau menulis data. inferSchema adalah opsi PySpark yang digunakan untuk menentukan apakah schema dari dataframe akan di-infer atau tidak. csv adalah metode PySpark yang digunakan untuk membaca data dalam format CSV. header adalah opsi PySpark yang digunakan untuk menentukan apakah header file CSV digunakan atau tidak. codec adalah opsi PySpark yang digunakan untuk menentukan encoding dari file CSV.
