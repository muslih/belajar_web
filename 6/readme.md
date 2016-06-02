#Pertemuan Ke 6

##membuat layout dengan pengaturan width / ukuran
Ukuran default `800px`

Struktur
`header + section + aside + footer`

Biasanya, sebelum membuat layout siapkan dulu kontennya.

## Form
Mendefinisikan form dengan :
```html
<form>
.
form elements
.
</form>
```

atribut 'method' berfungsi untuk menentukan methode pengiriman data melalui form, atribut `method` memeiliki beberapa value:
* GET => melalui url
* POST => melalui body


###Input
`<input>` Elemen adalah bagin penting dari form, untuk melakukan input data, input ini memiliki beberapa atribut `type`
* `text` Mendefiniskan yang dinput adalah text
* `radio` Mendefinisikan input berbentuk radio
* `submit`  Mendefinisikan tombol sumbit untuk mengirim data
* `number` Mendefinisikan format input harus nomor
* `email` Mendefiniskan format input harus email

###atribut value
attribut `value` berfungsi untuk mengisi nilai pada input

`placeholder` menambahkan text keterangan pada input

`required` menerangkan, input tersebut wajib diisi

###atribut name 
Untuk mengirim data melalui form, setiap input harus memiliki atribut nama, oleh karena itu atribut `name` perlu diisi

##Article
The <article> tag specifies independent, self-contained content.

An article should make sense on its own and it should be possible to distribute it independently from the rest of the site.

Potential sources for the <article> element:

* Forum post
* Blog post
* News story
* Comment

##line-height
Berfungsi mengatur jarak antar baris, memiliki beberapa value yaitu :
* normal  A normal line height. This is default
* number  A number that will be multiplied with the current font size to set the line height 
* length  A fixed line height in px, pt, cm, etc.
% A line height in percent of the current font size
* initial Sets this property to its default value. Read about initial
* inherit Inherits this property from its parent element. Read about inherit

pertemuan berikutnya membuat layout dengan flexbox