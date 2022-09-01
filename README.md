# valenevp.github.io
<!doctype html>
<html lang="en">
<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

       
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <title> Página em Bootstrap - Prática 19 </title>

    <script src="https://kit.fontawesome.com/941c8d362c.js" crossorigin="anonymous"></script>

  <style>

    button.carousel-control-next, button.carousel-control-prev{
      background-color: #212529;
    }
    .card{
      background-color: #212529;
    }
    h5.card-title, p.card-text{
      color:#ffffff;
    }
    h5.card-title{
      text-align: center;
    }

  </style>
</head>

<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">
          <img src="images/head.jpg" alt="Logotipo My Page" width="50" class="d-inline-block align-center">My Page</a>

          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#">About</a>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Projects
                </a>

                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Project #1</a></li>
                  <li><a class="dropdown-item" href="#">Project #2</a></li>
                </ul>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#" >Contact</a>
              </li>
            </ul>

            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-secondary" type="submit"><i class="fas fa-search"></i></button>
            </form>

          </div>
        </div>
      </nav>

  <header>

      <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">

        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="images/imagem1.jpg" class="d-block w-100" alt="Imagem 1">
          </div>

          <div class="carousel-item">
            <img src="images/imagem2.jpg" class="d-block w-100" alt="Imagem 2">
          </div>

          <div class="carousel-item">
            <img src="images/imagem3.jpg" class="d-block w-100" alt="Imagem 3">
          </div>
        </div>

        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>

        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>

      </div>

  </header>

  <section>

    <div class="card-group">
      <div class="card">
        <img src="images/me_icon.png" class="card-img-top" alt="icone me">
        <div class="card-body">
          <h5 class="card-title">Título 1</h5>
          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        </div>
      </div>

      <div class="card.footer">
        <small class="text-muted"><button type="button" class="btn btn-light">Saiba mais</button></small>
      </div>
      </div>

      <div class="card">
        <img src="images/work_icon.png" class="card-img-top" alt="icone work">
        <div class="card-body">
          <h5 class="card-title">Título 2</h5>
          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
        </div>
      </div>

    <div class="card-footer">
      <small class="text-muted"><button type="button" class="btn btn-light">Saiba mais</button></small>
     </div>
    </div>

    <div class="card">
      <img src="images/contact_icon.png" class="card-img-top" alt="icone contact">
      <div class="card-body">
        <h5 class="card-title">Título 3</h5>
        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>

      <div class="card-footer">
        <small class="text-muted"><button type="button" class="btn btn-light">Saiba mais</button></small>
      </div>

  </section>

    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    
  </body>
</html>
