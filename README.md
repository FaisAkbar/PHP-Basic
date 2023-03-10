# PHP BASIC
##### Sumber Youtube : [Laracast](https://www.youtube.com/playlist?list=PL3VM-unCzF8ipG50KDjnzhugceoSG3RTC)

## 1. How to Choose A First Programming Language
##### Dalam Memilih bahasa pemrograman, kita harus mempertimbangkan tujuan apa yang kita miliki saat ingin belajar bahasa tersebut. Jadi dalam memilih bahasa pemrograman harus sesuai dengan tujuan kita. Contohnya apabila kita ingin membuat situs web, kita bisa belajar bahasa pemrograman seperti HTML, CSS, dan JS. Jika kita ingin membuat aplikasi desktop, kita mungkin bisa memilih bahasa seperti Python, C++, atau Java. Jika kita benar benar baru dalam pemrograman, cobalah memilih bahasa yang lebih mudah seperti Python atau Ruby. Setelah itu kita bisa mempertimbangkan jenis proyek yang kita ingin kerjakan di masa depan, jika kita ingin menjadi seorang pengembang Game, kita bisa memilih bahasa C++ atau C#, dan apa bila kita ingin fokus pada pengembangan Web, kita bisa memilih bahasa JavaScript atau PHP.
#### Kali ini Kita akan belajar tentang Bahasa Pemrograman PHP
##### PHP adalah bahasa pemrograman server-side yang dirancang untuk pengembangan web. PHP singkatan dari "PHP: Hypertext Preprocessor". PHP digunakan untuk menghasilkan konten dinamis pada website, seperti halaman web yang mengambil data dari database, membuat dan mengirim email, mengolah formulir, dan masih banyak lagi. PHP juga dapat digunakan untuk membuat aplikasi web yang lebih besar dan kompleks. PHP umumnya digunakan dengan teknologi web seperti Apache, MySQL, dan HTML. Saat ini, PHP terus berkembang dan ditingkatkan oleh komunitas pengembang web, dan menjadi salah satu bahasa pemrograman web yang paling populer dan mudah digunakan.

## 2. PHP For Beginners, Ep 2 - Tools of the Trade
##### Ada beberapa Tools yang diperlukan untuk menjalankan PHP Seperti :
1. Text Editor: Dalam pengembangan web, text editor digunakan untuk menulis kode program. Ada banyak pilihan text editor gratis dan berbayar yang tersedia, seperti Visual Studio Code dan Sublime Text.
2. Terminal: Terminal adalah alat yang digunakan untuk mengeksekusi perintah pada sistem operasi. Dalam pengembangan web dengan PHP, terminal digunakan untuk menjalankan perintah seperti menjalankan server web lokal atau menginstal paket PHP.
3. PHP: PHP harus diinstal di server untuk dapat menjalankan aplikasi web PHP. PHP menyediakan banyak fungsi dan fitur untuk memproses data dan menghasilkan konten dinamis pada website.
4. Local Development Environment: Saat membangun situs web, seringkali lebih mudah untuk membangun dan menguji di lingkungan lokal. Ada beberapa alat yang tersedia untuk membuat lingkungan pengembangan lokal, seperti XAMPP, MAMP, atau WAMP.
5. Browser: Browser digunakan untuk menampilkan halaman web yang dihasilkan oleh aplikasi web PHP. Beberapa pilihan browser yang populer antara lain Google Chrome, Mozilla Firefox, dan Microsoft Edge.Browser: Browser digunakan untuk menampilkan halaman web yang dihasilkan oleh aplikasi web PHP. Beberapa pilihan browser yang populer antara lain Google Chrome, Mozilla Firefox, dan Microsoft Edge.
6. Version Control: Version control digunakan untuk melacak perubahan pada kode program dan bekerja sama dengan tim. Salah satu platform version control yang populer adalah Git dan tersedia beberapa hosting Git seperti GitHub, GitLab, Bitbucket.

## 3. PHP For Beginners, Ep 3 - Your First PHP Tag
##### Tag PHP digunakan untuk menandai kode PHP pada halaman web. Tag PHP dimulai dengan ``<?php`` dan diakhiri dengan ``?>``. Semua kode PHP harus ditempatkan di antara tag PHP. Contoh :
```
<?php
  // kode program Anda
?>
```
##### Fungsi ``echo`` digunakan untuk menampilkan teks atau variabel pada halaman web. Fungsi ``echo`` ditulis dengan format ``echo 'teks';``. Contoh :
```
  echo 'Hello World';
```
##### Contoh kode pada video menunjukkan cara menampilkan teks dengan fungsi ``echo``. Kode tersebut adalah sebagai berikut:
```
<?php
  echo "Hello, world!";
?>
```
##### Penjelasan kode program:
1. ``<?php`` dan ``?>`` adalah tag PHP yang digunakan untuk menandai awal dan akhir kode PHP.
2. Fungsi ``echo`` digunakan untuk menampilkan teks ``"Hello, world!"`` pada halaman web.
3. Teks ``"Hello, world!"`` harus diapit dengan tanda kutip (" ") untuk menandakan bahwa itu adalah string.
4. Tanda titik koma (;) digunakan untuk menandakan akhir dari setiap perintah.

## 4. PHP For Beginners, Ep 4 - Variables
##### Variabel digunakan untuk menyimpan data yang dapat digunakan dalam kode PHP. Variabel dapat menyimpan berbagai jenis data, termasuk teks, angka, dan boolean. Variabel diawali dengan tanda ``$`` diikuti dengan nama variabel. Nama variabel harus dimulai dengan huruf atau garis bawah, dan dapat mengandung huruf, angka, dan garis bawah. Contohnya :
```
// Variabel dengan nama $greeting dan value "Hello"
$greeting = "Hello";

// Pemanggilan dalam echo, dipisahkan oleh ' . ' jika terdapat tambahan argumen, 
// misalnya string atau variabel lain (concate)
echo $greeting . "Everybody!";

// untuk menambahkan spasi, bisa dilakukan sebelum "Everybody!"
echo $greeting . " Everybody!";
// atau
echo $greeting . " " . "Everybody!";

// selain cara di atas, kita juga bisa dengan cara Variabel dipanggil di didalam string. 
// agar terlihat lebih rapih dan lebih efision
echo "$greeting Everybody!";
```
##### berikut adalah hasil dari kode program di atas :
![hello](https://github.com/FaisAkbar/PHP/blob/main/img/hello.png)

## 5. PHP For Beginners, Ep 5 - Conditionals and Booleans
##### Conditional adalah pernyataan yang mengevaluasi suatu kondisi dan menjalankan kode tertentu berdasarkan hasil evaluasi. Jika kondisi tersebut bernilai *true* maka sistem menjalankan statement di dalam if statement namun jika kondisi tersebut bernilai *false* maka sistem tidak menjalankan statement tersebut. Sedangkan boolean adalah tipe data yang hanya memiliki dua nilai, yaitu *true* dan *false*. Nilai default dari Boolean adalah *false*. Contoh : 
```
<?php
//Membuat variabel
$name = "Dark Matter";
$read = true;

//Operasi if-else
if ($read) {
    $message = "You have read $name"; // jika bernilai true, maka akan mengembalikan nilai true
} else {
    $message = "You have NOT read $name"; // jika bernilai false, maka akan mengembalikan nilai false
}
<?
<h1>
    // cara menampilkan variabel
    <?php 
    echo $message;
    ?>
    // atau
    <?= $message ?> // membuka php sekaligus memanggil echo
</h1>
```
##### karena variabel $read bernilai true, maka akan mengembalikan nilai true dan akan menampilkan "You have read Dark Matter"
![true](https://github.com/FaisAkbar/PHP/blob/main/img/true.png)
##### namun jika kita mengubah nilai variabel $read menjadi false, maka akan mengembalikan nilai false dan akan menampilkan "You have NOT read Dark Matter"
![false](https://github.com/FaisAkbar/PHP/blob/main/img/false.png)

## 6. PHP For Beginners, Ep 6 - Arrays
##### Array adalah kumpulan data yang disimpan dalam satu variabel. Array dapat menyimpan satu atau lebih nilai. Array dapat menyimpan berbagai jenis data, termasuk teks, angka, dan boolean. Array diawali dengan tanda ``$`` diikuti dengan nama variabel. Nama variabel harus dimulai dengan huruf atau garis bawah, dan dapat mengandung huruf, angka, dan garis bawah. Contoh :
```
<?php
$books = [
  "Do Androids Dream of Electric Sheep",
  "The Langoliers",
  "Hail Mary"
];
```
##### Array di atas memiliki tiga buah data, yaitu "Do Androids Dream of Electric Sheep", "The Langoliers", dan "Hail Mary". Untuk mengakses data pada array dapat digunakan ekspresi perulangan(*loop*) di dalam tag html, misalnya *for, foreach, while,* atau *do-while*. Contoh menggunakan *foreach* :
```
 <ul>
        <?php foreach ($books as $book) : ?>
            <li><?= $book ?></li>
        <?php endforeach ?>
 </ul>
```
##### berikut adalah hasil dari kode program di atas :
![array](https://github.com/FaisAkbar/PHP/blob/main/img/array.png)

## 7. PHP For Beginners, Ep 7 - Associative Arrays
##### Associative array adalah array yang memiliki key dan value. Key adalah nama yang diberikan untuk data pada array. Key dapat berupa angka atau string. Contoh :
```
<?php
$books = [
  "Do Androids Dream of Electric Sheep",
  "The Langoliers",
  "Hail Mary"
];
?>
<p>
    <?= $books[2] ?>
</p>
```
#### berikut adalah hasil dari kode program di atas :
![array2](https://github.com/FaisAkbar/PHP/blob/main/img/array2.png)

##### Lalu bagaimana jika data pada array bertambah, jadi tidak hanya judul buku, namun ada nama penulis, deskripsi, dan lain-lain. Maka kita dapat menggunakan associative array. Contoh :
```
<?php
$books = [
  [
    'name' => "Do Androids Dream of Electric Sheep",
    'author' => "Philip K. Dick",
    'purchase_url' => "http://example.com"
  ],
  [
    'name' => "Project Hail Mary",
    'author' => "Andy Weir",
    'purchase_url' => "http://example.com"
  ]
];
?>
```
##### jadi untuk mengakses data pada array, kita dapat menggunakan perulangan lagi, contoh disini menggunakan perulangan *foreach* :
```
<ul>
        <?php foreach ($books as $book) : ?>
        <li>
            <h2><?= $book['name'] ?></h2> // untuk memanggil data nama buku
            <p>By <?= $book['author'] ?></p> // untuk memanggil data nama penulis
            <a href="<?= $book['purchase_url'] ?>">Buy Now</a> // untuk memanggil data url beli buku
        </li>
        <?php endforeach ?>
```
##### berikut adalah hasil dari kode program di atas :
![array3](https://github.com/FaisAkbar/PHP/blob/main/img/array3.png)

## 8. PHP For Beginners, Ep 8 - Functions and Filtering
##### Function adalah sebuah blok kode yang dapat digunakan berulang kali untuk melakukan suatu tugas tertentu. Function dapat menerima parameter dan mengembalikan nilai. Function dapat digunakan untuk memecah kode menjadi bagian-bagian yang lebih kecil dan mudah dipahami.
##### Filtering adalah proses memvalidasi data yang dimasukkan oleh pengguna. Filtering dapat dilakukan dengan menggunakan function filter_var() dan filter_input(). Contoh :
```
<?php 
        $books = [
            [
              'name'          => "Do Andorids Dream of Electric Sheep",
              'author'        => "Philip K. Dick",
              'releaseYear'   => 1968,
              'purchase_url'  => "http://example.com"
            ],
            [
              'name'          => "Project Hail Mary",
              'author'        => "Andy Weir",
              'releaseYear'   => 2021,
              'purchase_url'  => "http://example.com"
            ],
            [
                'name'          => "The Martisan",
                'author'        => "Andy Weir",
                'releaseYear'   => 2011,
                'purchase_url'  => "http://example.com"
              ]
          ];
    ?>
    <ul>
    <?php foreach ($books as $book) : ?>
    // Filter dengan if, filter buku berdasarkan nama author
        <?php if ($book['author'] = 'Andy Weir') : ?>
          <li>
            <a href="<?= $book['purchase_url'] ?>">
             <?= $book['name']; ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
            </a>
          </li>
        <?php endif ?>
    <?php endforeach ?>
</ul>
```
##### Pengkondisian dengan hanya sebuah tanda ``"="`` tidak tepat, karena tanda ``"="`` akan mengubah value dari semua key author menjadi ``'Andy Weir'`` atau dinamakan *assign value*, sedangkan dibutuhkan filter data untuk menampilkan buku dengan author ``"Andy Weir"`` saja atau *equal to*, sehingga harus dicek kesamaan atau *equality* dengan 3 tanda ``"="`` atau ``"==="`` Maka kondisi dalam if menjadi :
```
<ul>
  <?php foreach ($books as $book) :?>
    <?php if ($book['author'] === 'Andy Weir') :?>
      <li>
        <a href="<?= $book['purchase_url'] ?>">
          <?= $book['name'] ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
        </a>
      </li>
    <?php endif; ?>
  <?php endforeach; ?>
</ul>
```
##### berikut adalah hasil dari kode program di atas :
![filter1](https://github.com/FaisAkbar/PHP/blob/main/img/filter1.png)

##### Untuk mempermudah, kita dapat membuat function untuk melakukan filter data. Contoh :
```
//Deklarasi function
function filterByAuthor(){
    //Kode program
}

//Untuk melakukan pemanggilan function, cukup dengan memanggil nama functionnya dengan menambahkan tanda kurung ()
filterByAuthor();

//Menampilkan isi dari function yang sudah dibuat ke dalam browser
function filterByAuthor(){
    return "gibberish"; 
    //Return adalah sebuah keyword yang digunakan untuk mengembalikan nilai dari sebuah function, dapat berupa string, integer, array, object, boolean, dan lain-lain.
}
// Contoh
<p>
  <?= filterByAuthor($books); ?>
  //Di browser akan menampilkan "gibberish"
</p>
```
##### Berikut adalah contoh function untuk melakukan filter data :
```
//Kita bisa menambahkan perulanagan foreach di dalam function untuk melakukan filter data
//Contoh kita akan menfilter data menggunakan foreach loop pada array $books sebagai parameter berdasarkan author 'Andy Weir'
function filterByAuthor($books){
    $filtered = [];
    foreach ($books as $book) {
        if ($book['author'] === 'Andy Weir') {
            $filtered[] = $book;
        }
    }
    return $filtered;//Array yang sudah difilter akan dikembalikan ke dalam function
}
//Untuk menampilkan hasil dari function filterByAuthor, kita bisa menggunakan perulangan foreach lagi
<ul>
  <?php foreach (filterByAuthor($books) as $book) :?>
    <li>
      <a href="<?= $book['purchase_url'] ?>">
        <?= $book['name'] ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
      </a>
    </li>
  <?php endforeach; ?>
</ul>
```
##### Berikut adalah hasil dari kode program di atas :
![filter2](https://github.com/FaisAkbar/PHP/blob/main/img/filter2.png)

##### Jika diamati lebih lanjut, function di atas masih memerlukan perubahan lagi. Karena apabila kita ingin menampilkan ``'author'`` yang berbeda, kita harus merubah nama ``'author'`` di dalam function. Jadi kita bisa memodifikasi function menjadi lebih dinamis dengan menggunakan parameter baru. Contoh :
```
function filterByAuthor($books, $author){
    $filtered = [];
    foreach ($books as $book) {
        if ($book['author'] === $author) {
            $filtered[] = $book;
        }
    }
    return $filtered;
}
<ul>
  <?php foreach (filterByAuthor($books, 'Andy Weir') as $book) :?>
    <li>
      <a href="<?= $book['purchase_url'] ?>">
        <?= $book['name'] ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
      </a>
    </li>
  <?php endforeach; ?>
</ul>
```
##### Berikut adalah hasil dari kode program di atas :
![filter3](https://github.com/FaisAkbar/PHP/blob/main/img/filter3.png)

## 9. PHP For Beginners, Ep 9 - Lambda Functions
##### Function dapat digunakan untuk menfilter buku berdasarkan author tetapi jika kita ingin menambahkan opsi filter lagi, kita harus membuat function baru. Sehingga kita bisa menggunakan lambda function untuk membuat function yang lebih dinamis. Function yang dibuat sebelumnya juga dapat dimasukkan ke dalam sebuah variabel yang dinamakan extract variable. Contoh :
```
<?php
$filteredBooks = filterByAuthor($books, 'Andy Weir');
?>
<ul>
  <?php foreach ($filteredBooks as $book) :?>
    <li>
      <a href="<?= $book['purchase_url'] ?>">
        <?= $book['name'] ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
      </a>
    </li>
  <?php endforeach; ?>
</ul>
```
##### Function juga dapat dibuat dan disimpan dalam variabel. Hal ini dinamakan Lambda Function / Anonymous Function.
```
//Membuat Variabel yang Berisikan Function
<?php
  $filterByAuthor = function ($books, $author) {
    $filtered = [];
    foreach ($books as $book) {
        if ($book['author'] === $author) {
            $filtered[] = $book;
        }
    }
    return $filtered;
  };
  $filtered = $filterByAuthor($books, 'Andy Weir');
?>

//Memanggil dalam Tag HTML
<ul>
  <?php foreach ($filtered as $book) :?>
    <li>
      <a href="<?= $book['purchase_url'] ?>">
        <?= $book['name'] ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
      </a>
    </li>
  <?php endforeach; ?>
</ul>
```
##### Function sebelumnya dapat disederhanakan dengan menggunakan refactoring dengan cara menambahkan parameter function sesuai dengan key dan value yang akan difilter.
```
<?php
  function filter($items, $key, $value) {
    $filteredItems = [];
    foreach ($items as $item) {
        if ($item[$key] === $value) {
            $filteredItems[] = $item;
        }
    }
    return $filteredItems;
  };
  $filteredBooks = filter($books, 'releaseYear', 2011);
?>

<ul>
  <?php foreach ($filteredBooks as $book) :?>
    <li>
      <a href="<?= $book['purchase_url'] ?>">
        <?= $book['name'] ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
      </a>
    </li>
  <?php endforeach; ?>
</ul>
```
##### Refactoring juga dapat diimplementasikan jika menginginkan value yang lebih fleksibel, misalnya terdapat data dengan tipe data integer dan ingin ditampilkan data yang <= dari value tersebut, maka kita dapat memisahkan pengkondisian if ke dalam sebuah function, sehingga menjadi :
```
<?php
function filter($items, $function){
        $filteredItems = [];
        foreach ($items as $item) {
            if ($function($item)) {
                $filteredItems[] = $item;
            }
        }
        return $filteredItems;
    }
    
    // Filter buku dengan tahun rilis < 2000

    $filteredBooks = filter($books, function($book){
        return $book['releaseYear'] < 2000;
    });
    ?>
   
   // Menampilkan buku dengan tahun rilis < 2000
    <ul>
        <?php foreach ($filteredBooks as $book) : ?>
            <li>
                <a href="<?= $book['purchase_url'] ?>">
                    <?= $book['name']; ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
                </a>
            </li>
        <?php endforeach ?>
    </ul>
```
##### Untuk melakukan filtering seperti diatas, PHP sudah menyediakan built-in function, sehingga tidak perlu membuat secara manual, yaitu array_filter() :
```
// Built-in function untuk filtering array
$filteredBooks = array_filter($books, function ($book) {
    return $book['releaseYear'] > 2000;
});
?>

<!-- Menampilkan buku berdasarkan filter -->
<ul>
    <?php foreach ($filteredBooks as $book) : ?>
        <li>
            <a href="<?= $book['purchase_url'] ?>">
                <?= $book['name']; ?> (<?= $book['releaseYear'] ?>) - By <?= $book['author'] ?>
            </a>
        </li>
    <?php endforeach; ?>
</ul>
```

## 10. PHP For Beginners, Ep 10 - Separate PHP Logic From the Template
#### Dalam pembuatan website, biasanya terdapat beberapa halaman yang memiliki tampilan yang sama, namun konten yang berbeda. Untuk menghindari duplikasi kode, kita dapat memisahkan kode PHP dari kode HTML. Contoh :

## PHP For Beginners, Ep 11 - Technical Check-In (With Quiz)

## PHP For Beginners, Ep 12 - Page Links

## PHP For Beginners, Ep 13 - Partials

## PHP For Beginners, Ep 14 - Superglobals and Current Page Styling

## PHP For Beginners, Ep 15 - Make a PHP Router

## PHP For Beginners, Ep 16 - Create a MySQL Database

## PHP For Beginners, Ep 17 - PDO First Steps

## PHP For Beginners, Ep 18 - Extract a PHP Database Class

## PHP For Beginners, Ep 19 - Environments and Configuration Flexibility

## PHP For Beginners, Ep 20 - SQL Injection Vulnerabilities Explained

## PHP For Beginners, Ep 21 - Mini-Project: Notes App

## PHP For Beginners, Ep 22 - Render the Notes and Note Page

## PHP For Beginners, Ep 23 - Introduction to Authorization

## PHP For Beginners, Ep 24 - Programming is Rewriting

## PHP For Beginners, Ep 25 - Intro to Forms and Request Methods

## PHP For Beginners, Ep 26 - Always Escape Untrusted Input

## PHP For Beginners, Ep 27 - Introduction to Form Validation

## PHP For Beginners, Ep 28 - Extract a Simple Validation Class

## PHP For Beginners, Ep 29 - Resourceful Naming Conventions

## PHP For Beginners, Ep 30 - Autoloading and Extraction

## PHP For Beginners, Ep 31 - Namespacing: What, Why, How

## PHP For Beginners, Ep 32 - Handle Multiple Request Methods From a Controller Action?

## PHP For Beginners, Ep 33 - Build a Better PHP Router

## PHP For Beginners, Ep 34 - One Request, One Controller

## PHP For Beginners, Ep 35 - Make Your First Service Container

## PHP For Beginners, Ep 36 - Updating a Resource With PATCH Requests

## PHP For Beginners, Ep 37 - Sessions 101

## PHP For Beginners, Ep 38 - Register a New User

## PHP For Beginners, Ep 39 - Write Your First Middleware