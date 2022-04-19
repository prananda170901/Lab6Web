# Layout Sederhana menggunakan Bootstrap Framework

## Langkah-langkah pembuatan layout sederhana menggunakan bootstrap framework

### 1. Membuat dokumen HTML

<br>Seperti Berikut.

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bootstrap Framework</title>
  </head>
  <body></body>
</html>
```

### 2. Quick Start

<br>Disini saya menggunakan bootstrap 5. bootstrap sendiri merupakan website penyedia open source yang didalam nya terdapat file-file. berikut file yang saya gunakan.

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous" />

    <!--My CSS-->
    <link rel="stylesheet" href="style.css" />
    <title>Bootstrap Framework</title>
  </head>
  <body>
    <h1>Layout Sederhana</h1>
```

### 3. Navbar

```HTML
<!--Navbar-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
          <a class="nav-link" href="#">Artikel</a>
          <a class="nav-link" href="#">About</a>
          <a class="nav-link" href="#">Kontak</a>
        </div>
      </div>
    </nav>
    <!--Akhir Navbar-->
```

![Navbar](img/Navbar.png)

### 4. Jumbotron

```HTML
<!--Jumbotron-->
    <div class="jumbotron">
      <h1 class="display-4">Hello, world!</h1>
      <p class="lead">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cupiditate nam quibusdam ipsum eos facere assumenda repudiandae ipsa magnam, tempore, modi illum omnis, enim et quod excepturi numquam eum id deleniti.</p>
      <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
    </div>
    <!--Akhir Jumbotron-->
```

![jumbotron](img/jumbotron.png)

### 5. Cards

<br>ini merupakan code untuk membuat element cards

```HTML
<!--Cards-->
    <section id="main">
      <div class="row">
        <div class="box">
          <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="image-circle" />
          <h3>Heading</h3>
          <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <a href="#" class="btn btn-default">View detail</a>
        </div>
        <div class="box">
          <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="" class="image-circle" />
          <h3>Heading</h3>
          <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <a href="#" class="btn btn-default">View detail</a>
        </div>
        <div class="box">
          <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="" class="image-circle" />
          <h3>Heading</h3>
          <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <a href="#" class="btn btn-default">View detail</a>
        </div>
      </div>
    </section>
    <!--Akhir Cards-->
```

![cards](img/CARDS.png)

### 6. Widget Header dan Widget Text

<br>berikut code untuk membuat Widget Header

```HTML
<!-- Widget Header -->
    <div class="col-3">
      <div class="list-group my-4" style="border-radius: 0">
        <a href="#" class="list-group-item list-group-item-action active" aria-current="true" style="font-weight: bold"> Widget Header </a>
        <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
        <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
        <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
        <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
        <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
      </div>
      <!--Akhir Widget Header-->
```

<br>Berikut Merupakan code membuat Widget Text

```HTML
<!--Widget Text-->
      <div class="list-group my-4" style="border-radius: 0; border: 1px #eee">
        <a href="#" class="list-group-item list-group-item-action active" aria-current="true" style="font-weight: bold"> Widget Text </a>
        <a href="#" class="list-group-item list-group-item-action">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam quas natus, amet ab voluptatibus beatae accusamus, quam hic veritatis ipsa, accusantium est nihil dolores minus at labore sapiente autem vero.</p>
        </a>
      </div>
    </div>
    <!--Akhir Widget Text-->
```

<br>Lalu refresh pada browser untuk melihat hasilnya
![widget](img/Widget.png)

### 7. Membuat RoW

<br>Lalu membuat row baru dan juga col baru dengan menambahkan class dan juga inline css untuk sedikit memperindah seperti gambar di atas dan code dibawah.

```HTML
 <!-- Row Content 2 -->
    <div class="row">
      <!-- Section 1 -->
      <div class="col-8-md">
        <div class="card mb-3" style="width: 900px; height: 200px; border: 0">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start" alt="..." />
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h2 class="card-title" style="font-weight: bold">First featurette heading</h2>
                <p class="card-text" style="text-align: left">
                  This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Velit animi quidem facere neque.
                  Ea rem labore dolorum, necessitatibus quod, maiores tempore harum fugit qui accusantium iure. Dolorum illo repellat vitae?
                </p>
                <p class="card-text"><small class="text-muted"></small></p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Row Content 3 -->
    <div class="row">
      <!-- Section 2 -->
      <div class="col-8-lg me-5">
        <div class="card mb-3" style="width: 900px; height: 200px; border: 0">
          <div class="row g-0">
            <div class="col-md-8">
              <div class="card-body">
                <h2 class="card-title" style="font-weight: bold">First featurette heading</h2>
                <p class="card-text">
                  This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer. Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi rerum at facilis nesciunt.
                  Quidem, ullam quod beatae sapiente excepturi, vitae praesentium ipsa ab optio, doloribus voluptatem vel atque eveniet necessitatibus?
                </p>
                <p class="card-text"><small class="text-muted"></small></p>
              </div>
            </div>
            <div class="col-md-4">
              <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start" alt="picture" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--Akhir Row-->
```

![row](img/row.png)

### 8. Footer

<br>Terakhir yaitu membuat card-footer dengan class card yang terdapat dibootstrap seperti gambar di atas dan code di bawah.

```HTML
<div class="card-footer text-center" style="background-color: #1d1d1d; color: #eee">
      <p>© 2022 - Universitas Pelita Bangsa</p>
    </div>
```

![footer](img/footer.png)

## FULL LAYOUT

![FULL](img/full.png)
