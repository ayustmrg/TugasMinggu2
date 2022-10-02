# Data Type Built in Prototype & Method
**Tipe Data Primitif**  
* String
* Number
* Boolean  
Primitif artinya tipe data yang masih standart.

**Tipe Data Non-Primif**  
* Array
* Object  
Non-primitif artinya tipe data yang sudah dikembangkan.

</br>

Javascript adalah bahasa pemograman dinamis.  
Artinya tidak ada peraturan yang ketat.  
Tyscript merupakan typesave utk javascript.
Penggunaannya adalah takutnya jika var diganti2 bisa diatasi dengan type script.  
Typeof : utk mngecek tipe data.  
Dapat juga digunakan untuk perbandingan.  
Contoh penggunaaan :  

<img src="dat1.jpeg" width="200" height="100">  

</br>

Untuk mengetahui karakter di dalam string dapat menggunakan length.  

<img src="dat2.jpeg" width="200" height="100">  

</br>

Properties : ciri-ciri dari string tsb, semisal brp banyak karakter.  

Cara menyisipkan variabel ke dalam string dapat dilakukan dengan 2 cara :  
* memasukkan let  
* dapat juga menggunakan ${}  

</br>

Method : keahlian/ function   
Method diakhiri dengan () 

</br>

**Penggunaan toUpperCase**  
Membuat tulisan huruf besar semua.

<img src="dat3.jpeg" width="200" height="100">  

Maka tulisannya kaan seperti ini :  

<img src="dat4.jpeg" width="200" height="100"> 

</br>

**Penggunaan toLowwerCase**  
Membuat tulisan menjadi huruf kecil semua.  

<img src="dat5.jpeg" width="200" height="100"> 

</br>

**Penggunaan chartAt**  
charAt akan mengambilan sebuah karakter berdasarkan posisi index yg ditentukan.  
Contoh penggunaan :  

<img src="dat6.jpeg" width="200" height="100">  

Minta index ke 1  

<img src="dat7.jpeg" width="200" height="100">  

Maka akan muncul A  

</br>

**Penggunaan includes**  
Includes untuk melakukan pencarian, yg dikembalian adalah true/false.  

<img src="dat8.jpeg" width="200" height="100">  

Contoh penggunaan  

<img src="dat9.jpeg" width="200" height="100">  

Maka hasilnya akan true karena ada  

<img src="dat11.jpeg" width="200" height="100"> 

<img src="dat10.jpeg" width="200" height="100">  

</br>

**Penggunaan Split**  
Split memisahkan sebuah string menjadi data array  
Contoh penggunaan split  

<img src="dat12.jpeg" width="200" height="100">  

Hasil di console.log

<img src="dat13.jpeg" width="200" height="100"> 

</br>


**Built-in-Method**  

<img src="dat14.jpeg" width="200" height="100">  

</br>

**Cara for jika tidak ingin menggunakaan include**  
Includs sensitive terhadap huruf besar dan huruf kecil.  
Contoh kesensitivan  :

<img src="dat15.jpeg" width="200" height="100">  

</br>

### Method Number  
Properties merupakan sebuah nilai/ciri-ciri  
Method adalah sebuah kemampuan

</br>

**NaN**  
Penggunaan isNaN  
NaN adalah Not a Number

<img src="dat16.jpeg" width="200" height="100">  

Penjelasan : Apakah "halo" adalah bukan angka? Sehingga jawabannya true  
Namun jika data adalah boolean maka jawabannya adalah false  

<img src="dat17.jpeg" width="200" height="100">  

Jika memasukkan angka dan boolean maka dia akan false  
Boolean dianggap false karena, true adalah 1, false adalah 0  
Karena mereka adalah angka maka akan false  

<img src="dat18.jpeg" width="200" height="100">  

</br>

**Penggunaan toString**  
Mengubah number menjadi sebuah string  
Contoh penggunaan

<img src="dat19.jpeg" width="200" height="100">  

Trik lain agar number menggunakan string   

<img src="dat20.jpeg" width="200" height="100">  

</br>

**Penggunaan toFix**  
toFix dapat menentukan angka beraoa di belakang koma  

Penggunaan yang di dalam kurung berapa angka di belakang koma  

<img src="dat21.jpeg" width="200" height="100">  

Yang dihasilkan adalah angka di dalam string  

Membuat number tetap menjadi number  

<img src="dat22.jpeg" width="200" height="100">  

</br>

**Penggunaan Math**  
Penggunaan math adalah menghasilkan data-data yang sudah ada, semisal yang uda ada di sebelumnya.  

<img src="dat23.jpeg" width="200" height="100">  

math.abs akan mengembalikan nilai absolut yang bulat 

<img src="dat24.jpeg" width="200" height="100">  

math.pow : pangkat  

<img src="dat25.jpeg" width="200" height="100">  

math.sqrt : akar  

<img src="dat26.jpeg" width="200" height="100">  

math.crt : akar pangkat 3  

math.round : koma akan dihilangkan  

<img src="dat27.jpeg" width="200" height="100">  

math.floor : akan dibulatkan ke bawah  

<img src="dat28.jpeg" width="200" height="100">   

math.ceil : pembulatan ke atas  

<img src="dat29.jpeg" width="200" height="100">  

math.random : memunculkan angka acak  

<img src="dat30.jpeg" width="200" height="100">  

</br>

### Prototype  
Mekanisme javascript object mampu menurunkan 1 fitur ke fitur lain  
String apapun yang digunakan sudah ada method  
Di Prototype bisa menambahkan method  
Contoh pengembalian sebuah string dengan huruf pertama di belakang-huruf terakhir ke depan  

<img src="dat33.jpeg" width="200" height="100">  

hasilnya  

<img src="dat34.jpeg" width="200" height="100">  

</br>

**Object Literal**  

<img src="dat35.jpeg" width="200" height="100">  

Tidak bisa ditambhkan tom age karena bentuk datanya const  

<img src="dat36.jpeg" width="200" height="100">