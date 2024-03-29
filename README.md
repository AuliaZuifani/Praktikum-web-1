NAMA	: AULIA ZUIFANI
NPM	: 230102030
KELAS	: TI-1B PEMROGRAMAN WEB 1 (SMT2)
DOSEN PENGAMPU: Pak abda’u	
Rangkuman HTML
1.	HTML home 
HTML sendiri merupakan bahasa markup standar untuk sebuah halaman web. Dalam pembuatan sebuah HTML diawali dengan <!DOCTYPE html>. Penulisan tersebut dapat di buat dengan menuliskan tanda seru (!)+tab. Maka akan muncul dengan sendirinya dan Anda bisa langsung berkreasi.

2.	HTML Introduction
Pada halaman ini kita dapat lebih detail mengenal HTML contohnya:
	HTML adalah singkatan dari Hyper Text Markup Language
	HTML adalah bahasa markup standar untuk membuat halaman Web
	HTML menjelaskan struktur halaman Web
	HTML terdiri dari serangkaian elemen
	Elemen HTML memberi tahu browser cara menampilkan konten
	Elemen HTML memberi label pada bagian konten seperti "ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dll.
Dalam topik ini kita juga mulai mengenal pembuatan dokumen  HTML sederhana dengan membuat :
1.	Deklarasi tersebut <!DOCTYPE html>mendefinisikan bahwa dokumen ini adalah dokumen HTML5
2.	Elemen <html>adalah elemen akar dari halaman HTML
3.	Elemen tersebut <head>berisi informasi meta tentang halaman HTML
4.	Elemen <title>menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman)
5.	Elemen <body>mendefinisikan badan dokumen, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, hyperlink, tabel, daftar, dll.
6.	Elemen <h1>mendefinisikan judul besar
7.	Elemen <p>mendefinisikan paragraf
<h1> dan <p> merupakan contoh dari sebuah element HTML. Eloement HTML adalah segala sesuatu yang dimulai dari tag awal hingga tag akhir </...>.
3.	Editor HTML
Dalam topik pembahasan ini dijelaskan mengenai langkah-langkah dalam pengaplikasian HTML menggunakan Notepad ataupun TextEdit. Anda bisa menyalin kode HTML yang sudah dibuat dan di letakan dalam Notepad lalu simpan file tersebut, kemudian Anda bisa membukanya di browser Anda.

4.	HTML element
Element HTML di tentukan oleh tak awal dan juga adanya tag akhir.
Contoh element bersarang:
	<h1> Praktikum Web</h1> dimana tag <h1></h1> berfungsi untuk menambahkan sebuah judul.
	<p> Materi berisi HTML dan CSS</P> dimana tag <p></p>berfungsi untuk menambahkan paragraf.
Contoh element kosong:
	<br> element ini dikatakan kosong karena tidak memiliki konten dan element ini hanya berfungsi untuk mendefinisikan jeda baris saja.

Yang perlu diingat dalam pembuatan HTML adalah HTML tidak peka dengan huruf kecil maupun besar.
5.	HTML attribute
Topik pembahasan pada materi ini yaitu mengenai atribut HTML sebagai informasi tambahan tentang elemen HTML. Berikut adalah ciri-ciri dari atribut HTML:
•	Semua elemen HTML dapat memiliki atribut
•	Atribut memberikan informasi tambahan tentang elemen
•	Atribut selalu ditentukan dalam tag awal
•	Atribut biasanya datang dalam pasangan nama/nilai seperti: name="value"
beberapa contoh atribut HTML yaitu
	Atribut href: mendefinisikan hyperlink
Contoh penulisan: <a href=https://www.pnc.ac.id.com>ayo kunjungi</a>
	Atribut src: untuk menyematkan gambar
Contoh penulisan: <img src=”anime.png”>
	Atribut weight and height: menentukan lebar dan tinggi gambar dalam skala pixel
Contoh penulisan: <img src=”anime.png” width=”50” height=”60”>
	Atribut Alt: menentukan teks alternatif jika gambar tidak muncul
Contoh penulisan:  <img src=”anime.png” alt=”mizukage japan”>
6.	HTML Heading
Heading HTML adalah judul ataupun subjudul yang akan ditampilkan dalam sebuah halaman web. Pembuatan heading ini menggunakan tak <h1> sampai <h6>.
Contoh penulsan heading utama : <h1> style=”font-size:50px;”>judul 1</h1>
7.	HTML Paragraph
Paragraf HTML adalah sebuah element html yang di definisikan menggunakan tag <p> dan diakhiri dengan </p>.
8.	HTML style
Style dalam html ini berfungsi untuk menambahkan suatu elemen seperti font, warna,ukuran dll. Atribut ini dapat dituliskan seperti <body style=”background-color:black;”> sintaks ini berarti mengganti warna background keseluruhan dengan warna hitam.
9.	HTML Formatting
Pemformatan di dalam html ini digunakan untuk menampilkaan jenis teks khusus menggunakan tag. Contoh tag dalam formating:
	<b>- Teks tebal
	<strong>- Teks penting
	<i>- Teks miring
	<em>- Teks yang ditekankan
	<mark>- Teks yang ditandai
	<small>- Teks lebih kecil
	<del>- Teks yang dihapus
	<ins>- Teks yang disisipkan
	<sub>- Teks subskrip
	<sup>- Teks superskrip
10.	Quatation HTML
Quatation html atau kutipan html berfungsi untuk menambahkan sebuah kutipan teks yang kita ambil. Dalam topik ini ada beberapa elemen yang dapat digunakan untuk membuat sebuah kutipan antara lain: 
o	<blockquote> berfungsi untuk mengutip dari sumber lain.
o	<q> berfungsi untuk mendefinisi kutipan secara singkat
o	<abbr> berfungsi untuk mendefinisikan singkatan.
o	<address> berfungsi untuk mendefinisikan informasi penulis atau pencipta dokumen yang kita kutip

Rangkuman CSS
1.	CSS Home
CSS (cascading style sheet) adalah bahasa yang digunakan untuk menata sebuah html. Hasil dari tampilan html di buat menggunakan sebuah CSS. Di contohkan dalam sintaks seperti background-color yang berfungsi untuk mengubah warna background.
2.	CSS Syntax
Dalam topik ini membahas mengenai aturan dari pemilih atau selector yang menuju pada suatu elemen html yang ingin Anda modifikasi.
 Berikut adalah aturan dalam CSS:
•	Pembuat harus menunjuk ke elemen yang akan di modifikasi
•	Blok deklarasi berisi satu atau lebih deklarasi yang dipisahkan oleh titik dan koma
•	Setiap deklarasi menyertakan nama properti css dan nilainya di pisahkan oleh titik dua
•	Beberapa deklarasi css dipisahkan dengan titik koma, dan blok deklarasi diapit oleh kurung kurawal.
3.	CSS Selector
CSS selector atau pemilih css ini digunakan untuk menemukan atau memilih elemen html mana yang akan di modifikasi. Selector dibagi menjadi 3 jenis yaitu:
	Id selector disimbolkan dengan (#)
	Class selector disimbolkan dengan(.)
	Universal selector disimbolkan dengan (*)
4.	CSS How to
Pada topik ini membahas tentang bagaimana cara memasukan css pada dokumen html.
Terdapat 3 cara dalam memasukan css ke dalam html yaitu:
 	CSS Eksternal: yaitu memasukan css yang berada pada beda file dengan file html menggunakan <link rel=”stylesheet href=”aulia.css”>.
 	CSS Internal: yaitu menambahkan css di dalam satu file dengan html caranya yaitu buka css menggunakan <style> dan letakan di bawah <head>
 	Css Inline: yaitu menambahkan css langsung dalam baris html caranya dengan menambahkan style di dalam elemen html contoh: <p style=”color-color:black;”>Praktikum web</p>.
5.	CSS Comments
Komentar pada css ini dapat membantu develop dalam menjelaskan sebuah kode atau dapat juga digunakan ketika develop mengedit nya kembali. Komentar ini tidak di tampilkan dalam browser ataupun tampilan sebuah html yang dibuat. Komentar di simbolkan dengan (*/).
6.	CSS Color
CSS color ini adalah proses menentukan warna yang ada dalam css. Warna dapat ditentukan dengan menggunakan nama warna yang sudah di tentukan sebelumnya. Contoh pewarnaan untuk background biru sebuah html di tuliskan seperti ini :
<h1> style=”background-color:blue;”></h1>
Dengan demikian penulisan tersebut dikategorikan dalam Inline CSS dan secara langsung akan mengubah tampilan background html menjadi warna biru.
Dalam pewarnaan CSS dibagi menjadi 3 jenis warna yaitu RGB, HEX, dan HSL.
7.	CSS Background
CSS background atau latar belakang CSS digunakan untuk mengganti latar belakang pada tampilan html. Berikut beberapa properti yang digunakan untuk memodifikasi latar belakang:
	background-color 
	background-image
	background-repeat
	background-attachment
	background-position
Didalam topik ini juga membahas mengenai Opacity/Transparansi. Elemen ini dapat di tuliskan menggunakan contoh: opacity: 0.5;
8.	CSS Border
Border Css adalah garis yang menentukan lebar dan warna batas elemen. Border ini dapat dituliskan menggunakan perintah border-style. Berikut adalah nilai pengisi jenis border yang dapat digunakan:
	dotted- Mendefinisikan batas titik-titik
	dashed- Mendefinisikan batas putus-putus
	solid- Mendefinisikan batas yang solid
	double- Mendefinisikan perbatasan ganda
	groove- Mendefinisikan batas beralur 3D. Efeknya bergantung pada nilai warna batas
	ridge- Mendefinisikan batas bergerigi 3D. Efeknya bergantung pada nilai warna batas
	inset- Mendefinisikan batas sisipan 3D. Efeknya bergantung pada nilai warna batas
	outset- Mendefinisikan batas awal 3D. Efeknya bergantung pada nilai warna batas
	none- Tidak mendefinisikan batas
	hidden- Mendefinisikan perbatasan tersembunyi
9.	CSS Margin
Properti ini digunakan untuk menciptakan ruang di sekitar elemen, diluar batas yang ditentukan. Beberapa aturan dalam margin yaitu:
	otomatis - browser menghitung margin
	length - menentukan margin dalam px, pt, cm, dll.
	% - menentukan margin dalam % lebar elemen yang memuatnya
	mewarisi - menentukan bahwa margin harus diwarisi dari elemen indu
berikut adalah contoh penulisan margin:
•	margin-top
•	margin-right
•	margin-bottom
•	margin-left
10.	CSS fonts
CSS font adalah properti yang digunakan untuk mengatur jenis dari sebuah fonts. Contoh penulisanya adalah font-family: “Times New Roman”, Times, serif;
Berikut adalah beberapa jenis font umum :
	Font serif memiliki guratan kecil di tepi setiap huruf. Mereka menciptakan kesan formalitas dan keanggunan.
	Font Sans-serif memiliki garis yang bersih (tidak ada guratan kecil yang menempel). Mereka menciptakan tampilan modern dan minimalis.
	Font monospace - di sini semua huruf memiliki lebar tetap yang sama. Mereka menciptakan tampilan mekanis. 
	Font kursif meniru tulisan tangan manusia.
	Font fantasi adalah font dekoratif/menyenangkan.
JAVASCRIPT
1. JS Home
	Javascript adalah bahasa pemrograman pembuatan web yang banyak diketahui umum hal ini karena javascript mudah untuk dipelajari. Lain hal nya dengan HTML dan CSS, javascrip ini digunakan supaya web lebih interaktif. Atau dengan kata lain javascript digunakan untuk memprogram perilaku sebuah web.
2. JS Introduce
	Javascript digunakan untuk mengubah sebuah konten HTML. Dalam prosesnya menggunakan banyak metode, satu dari banyak nya metode yang sering digunakan adalah getElementById().
	Berikut adalah contoh pengaplikasian untuk menemukan elemen html dengan ide=”Praktikum” dan mengubahnya menjadi elemen innerhtml menjadi “Hallo Js”.
	Document.getElementById(“Praktikum”).InnerHTML=”Hallo js”;
3. JS Where to
	Pada topik bahasan kali ini menjelaskan bagaimana cara menulis elemen javascript di dalam sebuah html. Javascript di sisipkan diantara tag <script> dan </script>.
	Javascript dapat dituliskan di eksternal file html dengan cara memangil <script src=”myScript.js></script>
	Berikut adalah keuntungan dalam penulisan javascript eksternal:
 	Memisahkan HTML dan kode
 	Membuat html dan javascript lebih mudah dibaca dan dipelihara
 	File javascript yang di cahche dapat mempercepat pemuatan halaman
4. JS Output
	Javascript dapat menampilkan data dengan beberapa cara sebagai berikut:
 	InnerHTML. (digunakan menulis ke dalam elemen html)
 	Document.write(). (digunakan menulis output ke dalam html)
 	Window.alert(). (digunakan untuk menulis di dalam kotak peringatan)
 	Console.log(). (digunakan menulis ke konsol browser)
5. JS Statement
	Statement dalam javascript digunakan untuk mendefinisikan suatu pernyataan. Contohnya:
	Let x, y, z;	//Statement 1
	x = 5;		//Statement 2
	y =6;		//Statement 3
	contoh lainya , pernyataan javascript sendiri terdiri dari nilai,operator,ekspresi, katakunci, 
	dan komentar. Contoh pernyataan yang memberi tahu browser untuk menulis “Welcome Javascript” dalam elemen html dengan id=”demo”:
	document.getElementById(“demo”).InnerHTML=”Welcome Javascript”;
6. JS Syntax
	Sintaks javascript merupakan aturan mengenai bagaimana program javascript dibuat
	Nilai javascript di definisikan menjadi 2 hal yaitu nilai tetap(literals) dan njilai variabel.
	Literal Javascript tetrdiri dari:
1.	Bilangan : ditulis dengan atau tanpa desimal contoh 20.50 dan 1000
2.	String : adalah teks yang ditulis dengan tanda kutip ganda maupun tunggal contoh:”Praktikum”
Javascript menggunakan operator aritmatika yaitu (+-*/).
Javascript juga menggunakan variabel untuk menyimpan nilai data dengan menggunakan kata kunci var, let, dan const untuk mendeklarasikan variabel tersebut.
Javascript juga menggunakan ekspresi yang merupakan kombinasi nilai,variabel, dan opetor, yang menghitung suatu nilai. Contohnya : 4*2=50
7. JS Comment
Sama hal nya dengan CSS dan HTML, javascript juga memiliki komentar untuk menjelaskan kode javascript dan membuatnya lebih mudah untuk di pahami dan dilakukan evaluasi jika terjadi kesalahan. Komentar javascript dapat digunakan untuk mencegah eksekusi, saat menguji kode alternatif. Komentar dalam javascript disimbolkan dengan double slice (//).
8. JS Variabel
Variabel atau wadah untuk menyimpan suatu data dalam javascript didefinisikan dengan 4 cara yaitu:
	Secara Otomatis
	Menggunakan Var contohnya var a=”5”
	Menggunakan Let contohnya let b=”3”
	Menggunakan Const contohnya const c=”10”
9. JS Operators
Operator javascript digunakan untuk melakukan berbagai jenis perhitungan matematis dan logis contohnya:
Operator penugasan (=) digunakan untuk memberikan nilai

Operator penambahan (+) digunakan untuk menambahkan nilai
Operator perkalian (*) digunakan untuk mengalikan nilai
Operator Perbandingan (>) digunakan untuk membandingkan nilai
10. JS Arithmatic
	Berikut adalah operator aritmatika pada bilangan (literal atau variabel)
	+ Addition (tambahan)
	- Subtraction (pengurangan)
	*Multiplication(perkalian)
	** Exponentiation (eksponen)
	/ Division 
	% Modulus
	++ Incremement
	-- Decrement

Noted: saya cantumkan latihan evaluasi UTS yang mencakup semua materi yang sudah saya pelajari dengan nama File HTML evaluasi.html dan File CSS dengan nama evaluasi.css
