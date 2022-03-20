# Lab2Web
| Nama      | Shobahus Solichin  |
| ----------- | ----------- |
| NIM     | 312010076       |
| Kelas   | TI.20.A.1        |

## *Langkah-Langkah Praktikum 2 'CSS DASAR*

# *1. Membuat dokumen HTML*

Buatlah dokumen HTML seperti berikut ini di VSCode:

![foto](foto/foto1.png)

Selanjutnya buka pada brwoser untuk melihat hasilnya.

![foto](foto/foto1.png)

## *2. Mendeklarasikan CSS Internal*
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

![foto](foto/foto1.png)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

![foto](foto/foto1.png)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat
hasilnya.

![foto](foto/foto1.png)

## *3. Menambahkan Inline CSS*

Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.

![foto](foto/foto1.png)

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

![foto](foto/foto1.png)

## *4. Membuat CSS Eksternal*

Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

![foto](foto/foto1.png)

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>

![foto](foto/foto1.png)

Selanjutnya refresh kembali browser untuk melihat perubahannya.

![foto](foto/foto1.png)

## *5. Menambahkan CSS Selector*

Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode berikut.

![foto](foto/foto1.png)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

![foto](foto/foto1.png)

# *Pertanyaan dan Tugas*

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

## Jawab
1. Saya akan melakukan perubahan pada tag html, gambar yang ada dibawah ini yaitu merupakan syntax HTML sebelum saya merubahnya
![foto](foto/foto18.png "before")
Lalu ketika saya hilangkan akhiran pada Tag `</h1>`menjadi `<h1>`, maka yang akan terjadi seluruh elemen dibawah tag tersebut akan berubah mengikuti Tag `<h1>` dikarenakan tidak ada akhiran/penutup Tag tersebut. 
Seperti gambar dibawah ini.
![foto](foto/foto19.png "after")

2. Tag `<p>` berfungsi untuk memberi perintah paragraf pada halaman html

	Tag `<br>` berfungsi untuk memberikan perintah breakline atau baris baru
![foto](foto/foto20.png "paragraf & br")

3. `title` berfungsi untuk memberikan judul pada gambar

	`alt` berfungsi untuk menunjukkan sebuah alternate text (teks pengganti) yang akan muncul apabila gambar tidak dapat ditampilkan.

	gambar dibawah ini menunjukan perbedaan title dan alt
![foto](foto/foto21.png "alt title")

4.Menurut saya Kedua property ini sangat penting dan merupakan bagian yang tidak terpisahkan dari sebuah website karena masing-masing Tag atau Element pada sebuah HTML perlu memiliki ukuran yang ideal, sebab itu berpengaruh dalam pengaturan tataletak dan tampilan sebuah website,

	Kecuali pada kondisi tertentu seperti gambar sudah memiliki ukuran yang pas/proporsional cukup mengatur width nya saja
![foto](foto/foto22.png)  

5. `_blank` untuk membuka link di tab baru

	`_self` untuk membuka link di frame link itu berada

	`_top` untuk membuka link di frame paling atas (paling luar).  contohnya jika di website(1) di dalamnya ada website(2) lalu di website(2) di dalamnya ada website (3) lalu di website (3) ini ada link dan kita klik, maka link akan terbuka di website(1)

	`_parent` untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada. contohnya jika di website(1) di dalamnya ada website(2) lalu di website(2) ini ada link dan kita klik, maka link akan terbuka di website(1)