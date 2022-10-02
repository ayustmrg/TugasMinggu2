# DOM 2  
**Memanipulasi DOM**  

Buatlah file HTML terlebih dahulu

<img src="dom18.jpeg" width="200" height="100">  

Cara mengakses elemen dengan DOM  
Dapat menggunakan nama tag, querry selector, dan dapat juga menggunakan ID  

<img src="dom19.jpeg" width="200" height="100">  

>masukkan id nya  

<img src="dom20.jpeg" width="200" height="100">  

>lalu console.log  

<img src="dom21.jpeg" width="200" height="100">  

>sehingga di console.log seperti ini  

Dengan bantuan DOM, javascript mampu mengakses, mengubah dan memanipulatif struktur HTML  

<img src="dom22.jpeg" width="200" height="100">   

>penggunaan inner HTML  

<img src="dom23.jpeg" width="200" height="100">  

>penggunaan inner text  

Di dalam inner text tag tetap terbaca, sedangkan di inner HTML tag HTML dapat digunakan (dapat menyisipkan tag HTML).  

</br>

<img src="dom24.jpeg" width="200" height="100">    

>div kosong di HTML dapat dimanipulasi oleh dom  

</br>

**Memanipulasi dapat menggunakan**

<img src="dom26.jpeg" width="200" height="100">  

Contoh penggunaan :  

<img src="dom27.jpeg" width="200" height="100">  

>DOM buatin element paragraf  

<img src="dom28.jpeg" width="200" height="100">  

>sehingga di console.log ada p  

</br>

Pemakaian append  

<img src="dom30.jpeg" width="200" height="100">  

>pemakaian append  

<img src="dom31.jpeg" width="200" height="100">    

>Buat element terlebih dahulu kemudian isi dengan text, kemudian sisipkan dengan append  

Mengapa menggunakan HTML kosong karena mereka menggunakan single page application dimana halaman akan disisipkan ke id tadi  
Sehingga tidak ada refresh

<img src="dom32.jpeg" width="200" height="100">  

>contoh penyisipan    

appenChild  
appendChild hanya bisa menyisipkan node  

<img src="dom33.jpeg" width="200" height="100">  

>appenChild tidak bisa mengakses string  

<img src="dom34.jpeg" width="200" height="100">  

>appenChild hanya bisa menerima node  

<img src="dom35.jpeg" width="200" height="100">   

>untuk me remove  

<img src="dom36.jpeg" width="200" height="100">  

>awalnya ada di console.log  

<img src="dom37.jpeg" width="200" height="100">  

>sudah hilang  

</br> 

Jika di HTML ada href a untuk link, maka di javascripr ada   

<img src="dom38.jpeg" width="200" height="100">  

<img src="dom39.jpeg" width="200" height="100">   

>di console.log dapat atribut href dan class  

<img src="dom40.jpeg" width="200" height="100">  

>bentukan di HTML  

<img src="dom41.jpeg" width="200" height="100">  

>untuk melihat atributnya  

<img src="dom42.jpeg" width="200" height="100">  

>di console.log dapat google.com karena di HTML dibuat link google  

<img src="dom43.jpeg" width="200" height="100">   

>penjelasan lebih rinci  

</br>

**Membuat Warna**  

<img src="dom44.jpeg" width="200" height="100">  

<img src="dom45.jpeg" width="200" height="100">  

>hasilnya  

</br>

**Membuat padding**  

<img src="dom46.jpeg" width="200" height="100">  

Untuk melihat style nya apa aja  

<img src="dom47.jpeg" width="200" height="100">  

<img src="dom48.jpeg" width="200" height="100">   

>Yang make class link  
>index 0 nya karena get element by class name, mengembalikan sebuah nilai dalam bentuk HTML  
>collection mirip array, getsElement banyak element yang dikembalikan  
>Pada baris 29-30 : DOM buatin style pada link yang didapat tadi  

<img src="dom49.jpeg" width="200" height="100">   

>maka hasilnya akan seperti ini  

<img src="dom50.jpeg" width="200" height="100">  

>pada baris 26 terdapat google  
>pada baris 27 : pada link ini tolong tambahkan atribut id yang isinya google  

<img src="dom51.jpeg" width="200" height="100">   

>baris 34 : meminta yang memiliki ud tess  

<img src="dom52.jpeg" width="200" height="100">   

>tess uda di styling di HTML  

Pengen diambil dari DOM  

<img src="dom53.jpeg" width="200" height="100">   

>maka dicek, meminta tolong ke DOM, ambil style di tess tadi  
>disimpan ke var, agar tidak panjang ketika mengambil height  

<img src="dom54.jpeg" width="200" height="100">  

>di 36 disimpan style nya pada var, kemudian dapat diubah di dom lebih mudah pada baris 37  

<img src="dom55.jpeg" width="200" height="100">  

>membuat paragraf di DOM  

<img src="dom56.jpeg" width="200" height="100">   

>memberi style bisa langsung di javascript  

<img src="dom57.jpeg" width="200" height="100">   

>dapat membuat element juga