<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-sm navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="javascript:void(0)">Beranda</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="mynavbar">
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Profile</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Daftar</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="text" placeholder="Search">
        <button class="btn btn-primary" type="button">Search</button>
      </form>
    </div>
  </div>
</nav>

<!-- HEADER -->
<div class="container-fluid mt-3"><center>
  <h1>Ghibli Movies</h1>
  <h6>Top 3 Film Ghibli menurut saya</h6>
  <img width="560" height="315" src="studioghibli.jpg" class="mx-auto d-block"></iframe>
  </center>
</div>
<br><br>

<!-- CARD -->
<div class="container mt-3">
  <h3>Top 1</h3>
  <div class="card" style="width:400px">
    <img class="card-img-top" src="imgtop1.jpg" alt="Card image" style="width: 100%">
    <div class="card-body">
      <h4 class="card-title"><center>Spirited Away</center></h4>
      <p class="card-text">Chihiro berkelana di sebuah dunia magis yang dikuasai oleh seorang penyihir. Semua orang yang tidak mematuhi sang penyihir akan diubah menjadi hewan.
        <br>Film anime ciptaan Hayao Miyazaki ini menawarkan fantasi dengan gambar menggemaskan namun mampu menghangatkan hati melalui pesan-pesan mendalam terkait permasalahan sehari-hari tanpa harus merasa digurui.
      </p>
      <a href="https://www.netflix.com/id/title/60023642" class="btn btn-primary">Watch Now!</a>
    </div>
  </div>

<br>
  <h3>Top 2</h3>
  <div class="card" style="width:400px">
    <img class="card-img-top" src="imgtop2.jpg_large" alt="Card image" style="width: 100%">
    <div class="card-body">
      <h4 class="card-title"><center>Howl's Moving Castle</center></h4>
      <p class="card-text">Sophie, seorang gadis remaja rata-rata yang bekerja di toko topi, menemukan hidupnya dilemparkan ke dalam kekacauan ketika dia benar-benar tersapu oleh seorang penyihir tampan tapi misterius bernama Howl. Setelah pertemuan kebetulan ini, dia berubah menjadi wanita berusia 90 tahun oleh Penyihir Sampah yang sia-sia dan licik. Memulai petualangan luar biasa untuk mengangkat kutukan, dia menemukan perlindungan di kastil ajaib Howl yang bergerak di mana dia berkenalan dengan Markl, murid Howl, dan iblis api berkepala panas bernama Calcifer.</p>
      <a href="https://www.netflix.com/id-en/title/70028883" class="btn btn-primary">Watch Now!</a>
    </div>
  </div>

<br>
  <h3>Top 3</h3>
  <div class="card" style="width:400px">
    <img class="card-img-top" src="imgtop3.jpg" alt="Card image" style="width: 100%">
    <div class="card-body">
      <h4 class="card-title"><center>Ponyo</center></h4>
      <p class="card-text">Suatu pagi di dekat rumahnya di tepi pantai, Sosuke yang berusia lima tahun menemukan seekor ikan mas yang dia beri nama Ponyo, kepalanya tersangkut di stoples selai. Dia menyelamatkannya, dan terpesona satu sama lain, mereka berjanji untuk tetap berteman. Ketika ayah Ponyo, seorang penyihir bawah air yang kuat, memaksanya untuk kembali ke kedalaman laut, Ponyo bertekad untuk bergabung dengan Sosuke di permukaan dan menjadi manusia.</p>
      <a href="https://www.netflix.com/id-en/title/70106454?source=35" class="btn btn-primary">Watch Now!</a>
    </div>
  </div>
</div>
<br><br>

<!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
  </div>
  
  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="carousol1.jpg" alt="Totoro" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3>My Neighbor Totoro</h3>
      </div>
    </div>
    <div class="carousel-item">
      <img src="carousel2.jpg" alt="Kiki" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3>Kiki Delivery Service</h3>
      </div> 
    </div>
    <div class="carousel-item">
      <img src="carousel3.jpeg" alt="New York" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3>The Secret World of Arrietty</h3>
      </div>  
    </div>
  </div>
  
  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>

</body>
</html>

