#Ukuran Device

dekstop lebar   = 1240px
dekstop sedang  = 1024px
dekstop kecil   = 768px
mobile          = 320px

#perbedaan class dan id lebih detil

- id digunakan untuk bagian yang unik, sekali pakai
- class digunakan tidak untuk sekali pakai, artinya bisa di pakai lebih dari satu kali dalam sebuah halaman

#menggabungakn selector dengan ,

Misal ada dua selector memiliki deklarasi yang sama seperti

``` css
#header{
  background: #C0392B;
  padding: 15px 0;
  color:#fff;
}

#header-bawah{
  background: #E74C3C;
  padding: 15px 0;
  color:#fff;
}
```

dapat digabungkan menjadi

``` css

#header, #header-bawah{
  padding: 15px 0;
  color:#fff;
}
#header{
  background: #C0392B;
}

#header-bawah{
  background: #E74C3C;
}

#

