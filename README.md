<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOOD PANDA</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light" style="background-color:#F06292;">
        <div class="container-fluid">
            <img src="./download.png" alt="logo" height="45px" width="45px">

          <a class="navbar-brand" href="#"  style="color: white; font-family: 'Times New Roman', Times, serif ;">Food Panda</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbardropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="color: font-family: 'Times New Roman', Times, serif ; background-color: #F06291;">
                    Category
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbardropdown" style="background-color: #E91E63;">
                    <li><a class="dropdown-item" href="#" style=" font-family: 'Times New Roman', Times, serif ;">Home Made</a></li>
                    <li><a class="dropdown-item" href="#" style=" font-family: 'Times New Roman', Times, serif ;">Fast Food</a></li>
                    <li><a class="dropdown-item" href="#" style=" font-family: 'Times New Roman', Times, serif ;">Vegetables</a></li>
                    <li><hr class="dropdown-divider" style="font-family: 'Times New Roman', Times, serif ;"></li>
                    <li><a class="dropdowm-item" href="#" style=" font-family: 'Times New Roman', Times, serif ; text-decoration: none; color: black;">Genral Items</a></li>
                </ul>
            </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Faqs</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">About</a>
              </li>
            </ul>
          </div>
          <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="search" aria-label="search">
                <button class="btn btn-outline-success" type="submit">search</button>
          </form>
        </div>
      </nav> 
      
    <!----carousel-->
    <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000" style="width: 400px; height: 500px; border-radius: 20px;">
      <img src="./1.jfif" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="./2.jfif" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Some representative placeholder content for the second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="./3.jfif" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

    <!---cards--->
    <div class="card-group">
        <div class="card">
            <img src="./6.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-tittle">xyz</h5>
            </div>
            <div class="card-footer">
                <small class="text-muted">last update 2 mins ago</small>
            </div>
        </div>
    </div>
    <div class="card-group">
        <div class="card">
            <img src="./7.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-tittle">xyz</h5>
            </div>
            <div class="card-footer">
                <small class="text-muted">last update 2 mins ago</small>
            </div>
        </div>
    </div>
    <div class="card-group">
        <div class="card">
            <img src="./8.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-tittle">xyz</h5>
            </div>
            <div class="card-footer">
                <small class="text-muted">last update 2 mins ago</small>
            </div>
        </div>
    </div>
    <br>

    <div class="accordion accordion-flush" id="accordianflushexample">
        <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingOne">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">

                </button>
            </h2>
        </div>
    </div>
</body>
</html>
