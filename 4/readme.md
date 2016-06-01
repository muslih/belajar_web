#inherit
Inherit memiliki fungsi mengikuti valur dari properti paretnya! `inherit` ini bisa di pakai pada semua properti atau elemen pada HTML.

#initial
Initial ketika di set, ia akan mengubah nilai pada properti tersebut menjadi nilai default. `initial` juga bisa digunakan pada semua properti dan elemen HTML

#nav with submenu
```html
<ul> <!-- ini level 1-->
  <li><a href="#">Home</a></li> <!-- ini level 1-->
  <li>
    <a href="#">Services</a>
    <ul> <!-- ini level 2-->
      <li>UI/UX Designer</li><!-- ini level 2-->
      <li>Front-end Development</li>
      <li>Back-end Development</li>
      <li>SEO Services</li>
    </ul>
  </li>
  <li><a href="#">About</a></li>
  <li><a href="#">Galery</a></li>
  <li><a href="#">Portfolio</a></li>
  <li><a href="#">Contact</a></li>
</ul>
```
1. untuk menambah submenu, tambahkan `ul` dan `li` di dalam `li` level 1
2. tambahkan properti position pada `ul` level 2 dengan value `absolute`
3. tambahkan properti `position` dengan value `relative` pada `li` level 1
4. atur posisi menu
5. ubah property 'display' menjadi `hidden`
6. pada `li` level 1 tambahkan pseudo class `:hover` dan ubah properti `display` pada `ul` level 2 menjadi `'block'

#position property
Posisi, letak, menerangkan letak objek tersebut secara spesifik, property `position` ini memiliki empat buah `value` yaitu: 

 * Static = posisi default, secara otomatis posisi pada setiap objek adalah default!
 * Relative = diam pada posisi normalnya, kita bisa mengatur posisi dari posisi normalnya!
 * Absolute = dia akan berada mengikuti posisi relative diatasnya, bisa diatur top, botton, left, dan right nya.
 * Fixed = posisi akan menjadi tetap mengikuti ukuran browser, meskiput di scroll atas atau bawah! Fixed juga bisa diatur top, botton, left, dan right nya

#display propety
mengatur tampilan  objek, apakah ditampilkan, atau dihilangkan, properi ini memiliki beberapa `value` diantaranya yaitu :
* inline, satu baris, ini value default pada setiap objek
* block, untuk menampilkan
* none, untuk menghilangkan
selengkapnya ada di <a href="http://www.w3schools.com/cssref/pr_class_display.asp">http://www.w3schools.com/cssref/pr_class_display.asp</a>


# > 
