# DOM 3  
**Interaksi User (Events)**  
User experience bbersifat dua arah : selain menampilkan HTML, halaman web juga harus bisa menangkap interaksi user.  
Atau bisa juga disebut events adalah kejadian/kegiatan/interaksi yang terjadi pada website  
Ketika user mengarahkan mousenya ke arah yang lain ketika berinteraksi dengan sebuah element.

</br>

**Events**  
* click  
* submit  
* focus  
* blur  
* hover  
* change  
* scroll  

</br>

**Tiga cara memberikan event**  
* HTML attribute  
* event propperty  
* addEventListener()  

</br>

<img src="dom58.jpeg" width="200" height="100">  

>jangan lupa tambahkan defer  

<img src="dom59.jpeg" width="200" height="100">  
> buat file HTML dlu  

</br>

#### Cara 1  :  

<img src="dom60.jpeg" width="200" height="100">  

<img src="dom61.jpeg" width="200" height="100">  

>artinya h1 bisa dkilik dan dia akan menjalankan sesuatu, ternyata dia akan menjalankan alert dengan tulisan selamat datang  
>onclick bisa benntuk apapaun, bisa tulisan atau apapapun  

<img src="dom62.jpeg" width="200" height="100">  

>akan muncul  

</br>

**Event Types**  

<img src="dom63.jpeg" width="200" height="100">  

</br>  

Hover  

<img src="dom64.jpeg" width="200" height="100">  

<img src="dom65.jpeg" width="200" height="100">  

>muncul ketika diarahkan ke element  

</br>

#### Cara 2  

<img src="dom66.jpeg" width="200" height="100">  

>di HTML  

<img src="dom67.jpeg" width="200" height="100">  

>ambil id nya  

<img src="dom68.jpeg" width="200" height="100">  

>bisa memasukkan function  

<img src="dom69.jpeg" width="200" height="100">  

>bentukan di website  

<img src="dom70.jpeg" width="200" height="100">  

>dapat juga begini  

<img src="dom71.jpeg" width="200" height="100">   

>di web muncul alert  

</br>

#### Cara 3  

<img src="dom73.jpeg" width="200" height="100">  

>di HTML  

<img src="dom74.jpeg" width="200" height="100">  

>atau bisa juga begini  

<img src="dom75.jpeg" width="200" height="100">   

>muncul ketika klik saya ditekan  

<img src="dom76.jpeg" width="200" height="100">   

>tampilan Javascript lebih jelas  

<img src="dom77.jpeg" width="200" height="100">   

>tampilan HTML lebih jelas  

</br>  

**Dua cara menghandle event**  
* adevenetlistener  
* property atau secara inline  

Perbedaannya :  
Kita bisa menambhakan multiple handler utk event yg menggunakan adeventlistener.  
Bisa lbh dr 1 handler  

**Penggunaan addevenetlistener menghandle event**  

<img src="dom78.jpeg" width="200" height="100">  

>th lebih dari 1  

<img src="dom79.jpeg" width="200" height="100">  

>dua-duanya jalan  

Jikalau penggunaan onclik  

<img src="dom80.jpeg" width="200" height="100">  

>ternyata tidak bisa menjalankan keduanya  

<img src="dom81.jpeg" width="200" height="100">  

>ketika diclik, maka console.log akan ada penggunaan event.target