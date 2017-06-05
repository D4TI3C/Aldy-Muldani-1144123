Rangkuman Pertemuan 6 Kecerdasan Buatan

Backward chaining atau Backward Reasoning merupakan salah satu dari metode inferensia yang dilakukan untuk di bidang kecerdasan buatan. Backward chaining dimulai
dangan pendekatan tujuan atau goal oriented atau hipotesa.  Pada backward chaining kita akan bekerja dari konsekuen ke antesendent untuk melihat apakah terdapat
data yang mendukung konsekuen tersebut. Pada metode inferensi dengan backward chaining akan mencari aturan atau rule yang memiliki konsekuen (Then klausa ..) yang
mengarah kepada tujuan yang diskenariokan/diinginkan.

Contoh :

Misalkan terdapat suatu sistem dengan tujuan : Goal_1. Untuk mencapai tujuan Goal_1 tersebut dibutuhkan fakta A yang bernilai 1 dan fakta B yang bernilai 1.
(Asumsi nilai fakta adalah boolean 1 dan 0).  Fakta A sendiri akan diperoleh jika ada fakta C yang bernilai 1.  Bagaimanan rancangan sistem pakar dan aturan
yang akan dibuat:

Langkah 1 : Buat aturan standar untuk menyatakan  Goal 1

–          If A=1 and B=1 Then Goal 1

Langkah 2 : Buat aturan yang menyatakan bahwa jika C bernilai 1 maka A

–           If C=1 Then A=1

Terlihat bahwa konsekuen (Then..) tidak harus mengarah kepada Goal 1, akan tetapi ditujukan kepada antisendent yang dalam hal ini adalah A.  Dengan demikian
sistem akan mengetahui bahwa antisendent C akan ditanyakan dengan anisendent B untuk menghasilkan Goal 1.

Merupakan kebalikan dari forward chaining dimana mulai dengan sebuah hipotesa (sebuah objek) dan meminta informasi untuk meyakinkan atau mengabaikan.
Backward chaining inference engine sering disebut: ‘Object-Driven/Goal-Driven‘.

Contoh forward dan backward chaining dikutip dari Idhawati Hestiningsih

R1 : IF suku bunga turun THEN harga obligasi naik
R2 : IF suku bunga naik THEN harga obligasi turun
R3 : IF suku bunga tidak berubah THEN harga obligasi tidak berubah
R4 : IF dolar naik THEN suku bunga turun
R5 : IF dolar turun THEN suku bunga naik
R6 : IF harga obligasi turun THEN beli obligasi

Dari solusi yaitu membeli obligasi, dengan menggunakan Rule 6 diperoleh anteseden harga
obligasi turun. Dari Rule 2 dibuktikan harga obligasi turun bernilai benar jika suku bunga naik
bernilai benar . Dari Rule 5 suku bunga naik bernilai memang bernilai benar karena diketahui
fakta dolar turun.

Kedua teknik penalaran di atas (forward dan backward chaining) dipengaruhi oleh tiga macam teknik penelusuran (searching)

    Nama : Aldy Muldani
    NPM : 1144123
    Kelas : 3C
    Prodi : D4 Teknik Informatika

Link Github : https://github.com/D4TI3C/Aldy-Muldani-1144123

Scan Plagiarisme

1.smallseotools - Link https://drive.google.com/open?id=0B831iVXSuoJcZGxxLWtWWTNFU00

2.duplichecker - Link https://drive.google.com/open?id=0BzpVZYjDUEBhRFJhaFQ1emRPYWc