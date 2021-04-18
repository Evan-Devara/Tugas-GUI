# Praktikum-GUI
Emmanuel Genesius Evan Devara
19104005
S1SE03B

# Modul 1
# 1. Pengenalan Python
Membuat serta menampilkan variabel nama dan umur

![1  Ucok](https://user-images.githubusercontent.com/72756374/115144986-ae424e00-a079-11eb-9a26-1c860a0ab6b7.png)

# 2. Membuat dan Eksekusi Kode Program pada Python
1. Menulis kode pada text editor
2. Menyimpan pada direktori pilihan dalam bentuk .py
3. Panggil code disertai direktori penyimpanan

![2  hello world](https://user-images.githubusercontent.com/72756374/115145278-f01fc400-a07a-11eb-911a-54c6b8462800.png)

# 3. Variable dan Object
Python merupakan Bahasa dengan dynamic typing yaitu variabelnya tidak dibatasi oleh tipe datanya. Sebagai contoh, vairabel yang sudah diisi dengan tipe bilangan bulat bisa 
diisi dengan bilangan riil, string, ataupun tipe data yang lain.

![3  a  Variable dan Object](https://user-images.githubusercontent.com/72756374/115145465-e185dc80-a07b-11eb-884c-cd658a8ecbdf.png)

Perintah id(‘nama_variabel’) digunakan untuk mendapatkan id. Untuk setiap variable jika memiliki nilai yang sama maka python akan menunjuk nilai yang sama untuk variable yang berbeda. Variabel x maupun y memiliki id referensi yang sama karena nilai pada varibel x maupun y adalah sama-sama sebuah onjek yang bernilai 9. Menggunakan perintah del untuk menghapus variabel y, maka yang akan dihapus adalah referensinya saja, bukan objek ‘9’ yang tadi ditunjuk oleh variabel x dan y. Menambahkan kode baru, maka referensi objek varibel x akan dipindahkan dari objek ‘9’ = ‘True’.

![3  b  Variable dan Object](https://user-images.githubusercontent.com/72756374/115145545-4a6d5480-a07c-11eb-8c3b-ad04259ed10f.png)

# 4. Python Bersifat Case-Sensitive
Python bersifat Case-Sensitive, jika dilihat dari code dibawah ini. 
Variabele posisi != Variable Posisi

![4  Phyton bersifat case-sensitive](https://user-images.githubusercontent.com/72756374/115145720-2eb67e00-a07d-11eb-96fe-41c095f028a5.png)

# 5. Perintah Program (Statement)
Python tidak memerlukan adanya titik koma (;) pada setiap statementnya kecuali pada saat ada dua atau lebih statement pada satu baris yang sama.

![5  a  Perintah Program (STATEMENT)](https://user-images.githubusercontent.com/72756374/115146445-bf428d80-a080-11eb-8c6f-85aa878013da.png)

Perintah pada program ditulis dalam satu baris kode, namun tergantung programmer masing-masing dapat memecah perintah tersebut menjadi beberapa baris. Dimana setiap baris harus dihubungkan dengan tanda backslash (\).

![5  b  Perintah Program (STATEMENT)](https://user-images.githubusercontent.com/72756374/115146511-03359280-a081-11eb-91a9-96a6889f4fe3.png)

Tanda backslash tidak diperlukan jika kita menulis perintah kode dalam bentuk array atau kode yang terdapat diantara tanda (…), […] atau {…}.

![5  c  Perintah Program (STATEMENT)](https://user-images.githubusercontent.com/72756374/115146537-18122600-a081-11eb-97c4-652d74bed1ca.png)

# 6. Tipe Numerik
A. Bilangan Bulat

Dalam python terapat dua tipe bilangan bulat yaitu int dan bool. Selain tipe integral primitive python juga dapat menggunakan bilangan integral dengan basis decimal (10), biner (2), octal (8) maupun heksadesimal (16).

![6  Bilangan Bulat 2](https://user-images.githubusercontent.com/72756374/115146616-7212eb80-a081-11eb-8a5e-2e28612b70bf.png)


Tipe bilangan bulat yang kedua adalah tipe Boolean, dimana tipe data boleean bernilai true atau false.

![6  Bilangan Bulat](https://user-images.githubusercontent.com/72756374/115146598-5f98b200-a081-11eb-8579-e65492e6a6d8.png)

Proses perhitungan dan penambahan bilangan pada python akan menghasilkan objek baru, hal ini terlihat dari id nya.

B. Bilangan Riil

Python menyediakan tipe float, decimal, dan complex untuk bilangan riil

![6  Bilangan Riil](https://user-images.githubusercontent.com/72756374/115146729-ed749d00-a081-11eb-84b3-2938140a79a2.png)

# 7. Tipe String
Tipe data string dalam python direpresentasikan dengan tipe str. Objek string dapat 
dibuat dengan tiga cara yaitu:
• Menggunakan tanda pertik tunggal
• Menggunakan tanda petik ganda
• Menggunakan tanda petik tunggal ataupun ganda yang direpetisi sebanyak tiga 
kali

![7  Tipe String](https://user-images.githubusercontent.com/72756374/115147075-79d38f80-a083-11eb-8a34-e975ea7f75a1.png)

Dalam string kita dapat memberikan karakter khusus antara lain \n untuk memberikan enter, \’ untuk memberikan petik tunggal, \t untuk memberikan tab. Pada 
dasrnya karakter khusus dalam phyton harus diawali dengan backslash (\) diikuti dengan karakter khususnya

![7  Tipe String 2](https://user-images.githubusercontent.com/72756374/115147168-e8185200-a083-11eb-9de9-a2524bd27263.png)

A. Membandingkan String

String dapat dibandingkan dengan operator >, <=, >=

![7  Membandingkan String](https://user-images.githubusercontent.com/72756374/115147206-0f6f1f00-a084-11eb-9b52-9d2eff7ce0bd.png)

B. Mengekstrak Substring

![7  Ekstrak String 1](https://user-images.githubusercontent.com/72756374/115147223-33326500-a084-11eb-828e-43698cfb660f.png)

![7  Ekstrak String 2](https://user-images.githubusercontent.com/72756374/115147234-41808100-a084-11eb-92e1-079e686fa02c.png)

Substring di dalam string dapat diekstrak dengan menggunakan operator slice (:).

C. Membuat String dengan format tertentu

Phyton pada dasarnya juga dapat memnggabungkan tipoe data atau format lain ke dalam string yang telah dibuat. Antara lain dengan menggunakan $d, %f, %s dan lain 
sebagainya. 

![7  String Format tertentu](https://user-images.githubusercontent.com/72756374/115147259-637a0380-a084-11eb-9ce9-a3da1fa88cd1.png)

# 8. Tipe Koleksi
Tipe koleksi biasa disebut dengan tipe container. Beberapa tie koleksi antara lain list, dictionary, tuple dan set.13 Objek list dibuat dengan menggunakan tanda [], setiap objek yang berada di dlamnya dipisahkan dengan menggunakan koma dan dapat terdiri dari berbagai macam tipe data.

Membuat, menggabungkan dengan perulangan, dan memanggil List

![8  Tipe Koleksi 1](https://user-images.githubusercontent.com/72756374/115147430-22ceba00-a085-11eb-9a45-dd025594eb08.png)

Menambah dan menghapus List

![8  Tipe Koleksi 2](https://user-images.githubusercontent.com/72756374/115147444-2eba7c00-a085-11eb-8038-884798c1b1ac.png)




