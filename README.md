# Food-Reservation
Kelompok	: 17
Irbah Hanifah (1706024835)
Danissa Ananda (1706036671)

Judul Program : 
Sistem Pemesanan Makanan

Penjelasan Program:
Program ini merupakan program untuk pemesanan makanan berbasis digital, dimana para pelanggan dapat memesan makanan melalui sebuah device kemudian dibayarkan dikasir. Keuntungan dari penggunaan program ini yaitu lebih efisien dalam pemesanan makanan dan restoran pun tidak membutuhkan staf untuk pemesanan makanan sehingga dapat memperkecil biaya operasional restoran. 
Pada setiap menu terdapat kuantitas maksimal dimana pelanggan tidak dapat memesan menu diatas nilai kuantitas yang ditentukan. Nilai kuantitas maksimal pada setiap menu di program ini sama yaitu berjumlah 10, dan juga nilai tersebut berupa array yang dapat ditentukan oleh restorannya. Apabila pelanggan memesan sebuah makanan dengan kuantitas diatas 10 maka akan diitampilkan informasi bahwa stok yang tersedia tidak mencukupi. Hal tersebut dilakukan dengan memanggil nilai array yang diminta “choice” lalu mengurangkan kuantitas makanan yang telah dipesan oleh pelanggan. Pada proses perhitungan stok,  digunakan fungsi modular passing value, dimana dari fungsi yang telah dimodularkan akan mengeluarkan hasil, yang kemudian akan dipakai dalam fungsi main nya. 
Pada program ini tersedia 3 jenis sub-menu yaitu menu sushi, sashimi dan noodles/rice. Dimana pada setiap sub-menu juga terdapat 3 menu sehingga terdapat 9 jenis menu. Pada tampilan menu terdapat harga persatuan makanan. Setelah pelanggan memesan menu dengan kuantitas yang diinginkan maka akan terlihat harga “totala” yaitu total harga yang harus dibayarkan hanya untuk menu tersebut. Apabila terdapat beberapa menu yang dipesan maka akan terlihat harga “total” yaitu harga yang harus dibayarkan untuk seluruh menu yang dipesan oleh pelanggan tersebut. Kemudian ada bagian pemilihan keputusan untuk bisa memesan lagi pesanannya atau tidak, pada proses ini juga menggunakan fungsi modular passing value.
Pada program ini juga tersedia fitur print bill untuk dapat melihat data makanan yang sudah terjual. Fitur ini terdapat pada menu utama di nomor 4 setelah pilihan sub-menu. Pada fitur print bill ini terlihat menu yang telah dipesan beserta kuantitas dan harga totala (harga total hanya untuk menu tersebut). Selain itu, data makanan yang sudah terjual beserta kuantitas dan harganya juga dapat diakses pada file txt yaitu pada file data_penjualan.txt.
