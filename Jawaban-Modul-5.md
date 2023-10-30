# Jawaban Tugas Modul 5


1.) Langkah-langkah untuk mencapai tujuan (goal state) sebagai berikut:
    Langkah 1: Geser ubin ke kanan di baris pertama sehingga keadaan berubah menjadi [3, 1, 2, 4, 7, 0, 6, 8, 5].
    Langkah 2: Geser ubin ke kanan di baris kedua sehingga keadaan berubah menjadi [3, 1, 2, 4, 0, 7, 6, 8, 5].
    Langkah 3: Geser ubin ke bawah di kolom pertama sehingga keadaan berubah menjadi [3, 1, 2, 4, 1, 7, 6, 8, 5].
    Langkah 4: Geser ubin ke kanan di baris ketiga sehingga keadaan berubah menjadi [3, 1, 2, 4, 1, 7, 6, 5, 8].
    Langkah 5: Geser ubin ke atas di kolom kedua sehingga keadaan berubah menjadi [3, 1, 2, 4, 0, 7, 6, 5, 8].
    Langkah 6: Geser ubin ke kanan di baris kedua sehingga keadaan berubah menjadi [3, 1, 2, 0, 4, 7, 6, 5, 8].
    Langkah 7: Geser ubin ke atas di kolom ketiga sehingga keadaan berubah menjadi [3, 1, 2, 4, 0, 7, 6, 5, 8].
    Langkah 8: Geser ubin ke kanan di baris ketiga sehingga keadaan berubah menjadi [3, 1, 2, 4, 7, 0, 6, 5, 8].
    Langkah 9: Geser ubin ke bawah di kolom pertama sehingga keadaan berubah menjadi [3, 1, 2, 4, 7, 5, 6, 0, 8].
    Langkah 10: Geser ubin ke kanan di baris pertama sehingga keadaan berubah menjadi [3, 1, 2, 4, 7, 5, 0, 6, 8].
    Langkah 11: Geser ubin ke bawah di kolom kedua sehingga keadaan mencapai goal state [1, 2, 3, 4, 0, 8, 5, 6, 7].
    
Analisa:
Pencarian otomatis pada Eight-Puzzle secara sistematis mengeksplorasi ruang keadaan dari keadaan awal ke keadaan tujuan dengan mengggunakan heuristik, seperti `h1Cost` dan `h2Cost`, untuk mengevaluasi setiap keadaan dan memilih langkah terbaik berdasarkan biaya total yang diperkirakan. Pencarian otomatis ini tidak memerlukan campur tangan manusia dalam menentukan langkah-langkah, berbeda dengan pencarian manual yang melibatkan intervensi langsung manusia. Pencarian otomatis lebih efisien dalam menyelesaikan masalah kompleks karena komputer dapat mengeksplorasi ruang pencarian tanpa intervensi manusia yang intensif.

2.) Langkah-langkah untuk mencapai Goal State dari keadaan awal Eight Puzzle adalah sebagai berikut:
    Langkah 1: Geser ubin ke kanan di baris pertama sehingga keadaan berubah menjadi [1, 5, 3, 4, 7, 0, 6, 8, 2].
    Langkah 2: Geser ubin ke atas di kolom ketiga sehingga keadaan berubah menjadi [1, 5, 0, 4, 7, 3, 6, 8, 2].
    Langkah 3: Geser ubin ke atas di kolom kedua sehingga keadaan berubah menjadi [1, 0, 5, 4, 7, 3, 6, 8, 2].
    Langkah 4: Geser ubin ke kiri di baris kedua sehingga keadaan berubah menjadi [0, 1, 5, 4, 7, 3, 6, 8, 2].
    Langkah 5: Geser ubin ke kiri di baris ketiga sehingga keadaan berubah menjadi [7, 1, 5, 4, 0, 3, 6, 8, 2].
    Langkah 6: Geser ubin ke atas di kolom ketiga sehingga keadaan berubah menjadi [7, 1, 5, 4, 8, 3, 6, 0, 2].
    Langkah 7: Geser ubin ke kiri di baris pertama sehingga keadaan berubah menjadi [1, 7, 5, 4, 8, 3, 6, 0, 2].
    Langkah 8: Geser ubin ke atas di kolom kedua sehingga keadaan berubah menjadi [1, 7, 5, 4, 8, 3, 0, 6, 2].
    Langkah 9: Geser ubin ke kiri di baris ketiga sehingga keadaan berubah menjadi [1, 7, 5, 4, 8, 3, 2, 0, 6].
    Langkah 10: Geser ubin ke atas di kolom ketiga sehingga keadaan berubah menjadi [1, 7, 5, 4, 8, 3, 2, 6, 0].
    
Analisis:
Dua fungsi heuristik yang digunakan adalah h1Cost dan h2Cost, yang mengukur sejauh mana keadaan saat ini dari keadaan tujuan. Pencarian dimulai dari keadaan awal (Root) dan melanjutkan hingga mencapai keadaan tujuan. Setiap langkah mencoba memindahkan ubin-ubin untuk mencapai tujuan. Solusi akhirnya dicetak dalam bentuk jalur langkah-langkah untuk mencapai keadaan Goal State.  Dalam kasus ini, langkah-langkah konkret untuk menyelesaikan Eight Puzzle adalah menjadikan Goal State dari keadaan awal melalui serangkaian perpindahan ubin yang memenuhi kriteria biaya terendah. Setiap langkah mewakili perpindahan ubin ke arah tertentu, baik ke atas, ke bawah, ke kanan, atau ke kiri, sehingga menghasilkan permainan yang terurut dengan benar sesuai dengan Goal State.

3.) Berikut adalah langkah-langkahnya:
    Langkah 1: Geser ubin ke bawah di baris kedua sehingga keadaan berubah menjadi [1, 2, 3, 4, 5, 6, 7, 0, 8].
    Langkah 2: Geser ubin ke kanan di baris ketiga sehingga keadaan berubah menjadi [1, 2, 3, 4, 5, 6, 0, 7, 8].
    Langkah 3: Geser ubin ke bawah di baris ketiga sehingga keadaan berubah menjadi [1, 2, 3, 4, 5, 6, 8, 7, 0].
    Langkah 4: Geser ubin ke kanan di baris kedua sehingga keadaan berubah menjadi [1, 2, 3, 4, 5, 0, 6, 7, 8].
    Langkah 5: Geser ubin ke bawah di baris kedua sehingga keadaan berubah menjadi [1, 2, 3, 4, 0, 5, 6, 7, 8].
    
Analisis:
Pada setiap iterasi, algoritma memilih simpul dengan biaya terendah dari daftar simpul yang masih harus dieksplorasi. Kemudian, algoritma mengeksplorasi simpul-simpul anak dari simpul yang dipilih tersebut, mempertimbangkan biaya total saat ini dan biaya yang telah dilewati. Jika biaya yang diestimasi untuk mencapai simpul anak lebih rendah dari biaya yang telah ditemukan sebelumnya, atau jika simpul tersebut belum dieksplorasi, simpul anak tersebut dimasukkan ke dalam daftar simpul yang harus dieksplorasi. Proses ini berlanjut hingga keadaan tujuan ditemukan atau daftar simpul yang harus dieksplorasi kosong. Algoritma A* secara otomatis menemukan jalur terpendek dengan memanfaatkan heuristik yang telah ditentukan. Dalam konteks langkah-langkah spesifik yang ditanyakan, algoritma akan mencari dan mengeksekusi langkah-langkah yang tepat untuk mencapai tujuan yang diinginkan dari keadaan awal.

4.) 
Misalkan
1 = A
2 = B
3 = C
4 = D
5 = E
6 = F
7 = G
8 = H

Langkah-langkah untuk mencapai goal state sebagai berikut:
Langkah 1: Geser ubin kosong ke kanan di baris pertama sehingga keadaan berubah menjadi [4, 2, 5, 1, 6, 7, 8, 3, 0].
Langkah 2: Geser ubin kosong ke atas di baris kedua sehingga keadaan berubah menjadi [4, 2, 5, 1, 0, 7, 8, 3, 6].
Langkah 3: Geser ubin kosong ke kiri di baris kedua sehingga keadaan berubah menjadi [4, 2, 5, 0, 1, 7, 8, 3, 6].
Langkah 4: Geser ubin kosong ke kiri di baris pertama sehingga keadaan berubah menjadi [4, 2, 0, 5, 1, 7, 8, 3, 6].
Langkah 5: Geser ubin kosong ke bawah di baris kedua sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 0, 8, 3, 6].
Langkah 6: Geser ubin kosong ke kanan di baris kedua sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 8, 0, 3, 6].
Langkah 7: Geser ubin kosong ke kanan di baris ketiga sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 8, 3, 0, 6].
Langkah 8: Geser ubin kosong ke bawah di baris ketiga sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 8, 3, 6, 0].
Langkah 9: Geser ubin kosong ke bawah di baris kedua sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 8, 3, 6, 0].
Langkah 10: Geser ubin kosong ke kiri di baris kedua sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 8, 3, 0, 6].
Langkah 11: Geser ubin kosong ke atas di baris ketiga sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 8, 0, 3, 6].
Langkah 12: Geser ubin kosong ke kiri di baris ketiga sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 0, 8, 3, 6].
Langkah 13: Geser ubin kosong ke atas di baris kedua sehingga keadaan berubah menjadi [4, 2, 7, 5, 0, 1, 8, 3, 6].
Langkah 14: Geser ubin kosong ke kanan di baris kedua sehingga keadaan berubah menjadi [4, 2, 7, 0, 5, 1, 8, 3, 6].
Langkah 15: Geser ubin kosong ke kanan di baris ketiga sehingga keadaan berubah menjadi [4, 2, 7, 5, 1, 0, 8, 3, 6].
Langkah 16: Geser ubin kosong ke bawah di baris ketiga sehingga keadaan mencapai goal state [1, 8, 7, 2, 0, 6, 3, 4, 5].
