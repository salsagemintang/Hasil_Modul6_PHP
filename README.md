# Hasil_Modul6_PHP

1. Jelaskan menggunakan bahasa sendiri perbedaan antara cookies dan session! cookie merupakan informasi dalam bentuk teks yang dipertukarkan oleh client dan server, di mana pembuat cookie adalah pihak server. sedangkan, Session adalah agar bisa memungkinkan client untuk menyimpan informasi pada server.

2. Bagaimana cara menghapus session dan cookies pada sebuah browser! Penghapusan cookie dilakukan dengan cara mengirimkan nama cookie sama tetapi nilainya kosong. Sedangkan, Untuk menghapus data session, kita bisa menggunakan konstruksi bahasa unset() atau fungsi session_destroy().

3. Berikan contoh kode dari pembuatan dan menghapus cookies dan session!

pembuatan cookie<title>Set Cookie</title>

Tekan Refresh (F5);

pembuatan session<title>Set Session</title> '; // Mencetak nilai session test echo 'Nilai: ' . $_SESSION['test'] . '
'; // Mencetak semua elemen session print_r($_SESSION); } ?>

Tekan Refresh (F5);

menghapus cookie<title>Hapus Cookie</title> '; // Menghapus cookie, dengan masa berlaku 1 jam yang lalu setcookie('nama_cookie', '', time() - 1 * 3600); echo 'cookie dihapus'; } else { echo 'unset'; } ?>

Tekan Refresh (F5);

menghapus session<title>Hapus Session</title> unset($_SESSION['test']); echo 'session dihapus'; } else { echo 'unset';
// Mencetak semua elemen session
print_r($_SESSION); } ?>

Tekan Refresh (F5);


Mengakses_Cookie
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(297).png)

Memeriksa_Cookiee
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(298).png)

Menghapus_Cookie
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(299).png)
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(300).png)

Mengakses_Session
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(301).png)
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(302).png)

Menghapus_Session
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(303).png)
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(304).png)

index_Cookie
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(305).png)
Jika salah
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(306).png)
Jika benar
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(307).png)
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(308).png)

index_session
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(309).png)
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(310).png)
Jika salah
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(311).png)
Jika benar
![alt text]( https://github.com/salsagemintang/Hasil_Modul6_PHP/blob/master/Screenshot%20(312).png)
