# Practice Case MongoDB with pymongo
Pada practice case ini akan dibuat suatu collection (tabel) pada cluster yang telah ditentukan. Cluster yang digunakan adalah:

<br>
**Cluster 1** <br>
*mongodb+srv://userstudent:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true& w=majority* <br>
**Cluster 2** <br>
*mongodb+srv://admin1234:12345@cluster0-miqju.gcp.mongodb.net/test?retryWrites=true&w=majority*

<br>
Cluster 1 digunakan untuk melihat collection movies. Sementara cluster 2 digunakan untuk melihat collection movies_initial dan menyimpan collection yang akan dibuat. <br><br>
Ketentuan dalam membuat collection yang diinginkan adalah sebagai berikut:
- Membuat collection dengan nama clean_movies_tara.
- Collection tersebut disimpan pada database sample_mflix pada cluster 2.
- Values dari collection yang akan dibuat harus sama persis dengan collection movies_initial.
- Collection movies_initial yang digunakan ada pada database sample_mflix pada cluster 2. <br><br>
Validasi untuk collection clean_movies_tara dengan parameter sebagai berikut:
- Semua document pada clean_movies dan movie sama.
- Banyak document pada clean_movies dan movie sama.
- Semua fields pada clean_movies ada pada movie.
- Semua value pada clean_movies sama dengan semua value pada movies dengan urutan yang sama. <br><br>
Hasil collection yang telah dibuat disimpan pada cluster 2 dengan link sebagi berikut:
<br>
*mongodb+srv://admin1234:12345@cluster0-miqju.gcp.mongodb.net/test?retryWrites=true&w=majority*
