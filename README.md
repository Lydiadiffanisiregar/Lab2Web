| Nama      | Lydia Diffani Siregar |
| ----------- | ----------- |
| NIM     | 312010498       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 2
Membuka text editor, Saya menggunakan Visual Studio Code 
![foto](foto/foto1.PNG)

## 1. Membuat Dokumen HTML
![foto](foto/foto2.PNG)

Buka pada browser untuk melihat hasilnya

![oto](foto/foto3.PNG)

## 2. Mendeklarasikan CSS Internal
![foto](foto/foto4.PNG)
![foto](foto/foto4.1.PNG)

simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya

![foto](foto/foto5.PNG)

## 3. Menambahkan Inline CSS
tambahkan deklarasi inline CSS pada tag `<p>` seperti berikut

![foto](foto/foto6.PNG)

Refresh kembali browser untuk melihat perubahannya

![foto](foto/foto7.PNG)

## 4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut

![foto](foto/2.0.1.PNG)

Kemudian tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>`

![foto](foto/foto8.PNG)

Selanjutnya refresh kembali browser untuk melihat perubahannya.

![foto](foto/foto21.PNG)

## 5. Menambahkan CSS Selektor
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut

![foto](foto/foto9.PNG)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya

![foto](foto/pp.PNG)


## Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( `<p id="paragraf-1" class="text-paragraf">` )

## Jawab
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.</b><br>
  - Jawaban = 
Disini saya merubah font-color,fontnya saya ubah menjadi justify, contohnya pada gambar berikut : <br>
![foto](foto/pp.PNG)<br>  
  
  - Setelah perubahan,
![foto](foto/sesudah.PNG)<br>

2. `h1{}` Untuk memberikan style pada semua element h1

	`#intro h1{}` Awalan simbol hash (#) memungkinkan kita untuk memberi style pada id.
	selector id bersifat kaku dan tidak bisa digunakan kembali pada element yang lainnya. Menurut saya lebih baik gunakan selektor class untuk mendefinisikan element yang ingin diberi nilai.

3. Setelah dilakukan pengujian, deklarasi CSS Inline lebih dahulu tampil di browser, itu dikarenakan permintaan HTTP yang sangat kecil memungkinkan untuk ditampilkan dahulu

	Berikut merupakan hasil pengujian deklarasi CSS

	CSS Inline    `blue`
	  
	CSS Internal  `red`
	
	CSS Eksternal `yellow`
	
	![foto](foto/234.PNG)

4. Deklarasi `id="paragraf-1"` akan ditampilkan pada browser, karena selektor id lebih spesifik dari class atau bahkan element P itu sendiri, kecuali jika kita menambahkan property pada inline element P maka selektor id tersebut akan tertimpa, karena inline lebih spesifik daripada id, class, dan element

	![foto](foto/235.PNG)