<!DOCTYPE html>
<html lang="cs">
  <head>
    <title>Title</title>
    <meta charset='utf-8'>
    <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

    <link rel="stylesheet" href="style.css">
  </head>
  <body>

<!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

    <!-- Indicators/dots -->
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>

    </div>
    
    <!-- The slideshow/carousel -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./img/kapybara.jpg" alt="Los Angeles" class="d-block" style="width:100%">
      </div>
      <div class="carousel-item">
        <img src="./img/lemur.jpg" alt="Chicago" class="d-block" style="width:100%">
      </div>
      <div class="carousel-item">
        <img src="./img/lev.jpg" alt="New York" class="d-block" style="width:100%">
      </div>
      <div class="carousel-item">
        <img src="./img/tygr.jpg" alt="New York" class="d-block" style="width:100%">
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

  <div class="container">
    <h1 class="display-1">ZOO Plzeň</h1>
 
           

  <div class="row">
    <div class="col-md-6">
        <h2>Informace</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo eius, deserunt praesentium veniam aut maxime sint, sunt ut dolorum esse id dolores nemo aspernatur dolor vero odit molestias illum ad.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni libero fugit non rem cupiditate vel ipsum soluta eligendi neque sequi. Quam veniam repellat repudiandae at! Ipsa dicta inventore quam sapiente?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo eius, deserunt praesentium veniam aut maxime sint, sunt ut dolorum esse id dolores nemo aspernatur dolor vero odit molestias illum ad.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni libero fugit non rem cupiditate vel ipsum soluta eligendi neque sequi. Quam veniam repellat repudiandae at! Ipsa dicta inventore quam sapiente?</p>
    </div>
    <div class="col-md-6">
         <h2>Otevírací doba</h2>
        <table class="table table-hover">
          <thead>
            <tr>
              <th>Den</th>
              <th>Od</th>
              <th>Do</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Pondělí</td>
              <td>8:00</td>
              <td>17:00</td>
            </tr>   
            <tr>
              <td>Úterý</td>
              <td>9:00</td>
              <td>18:00</td>
            </tr>
            <tr>
              <td>Středa</td>
              <td>8:00</td>
              <td>17:30</td>
            </tr>
            <tr>
                <td>Čtvrtek</td>
                <td>9:00</td>
                <td>18:30</td>
              </tr>
              <tr>
                <td>Pátek</td>
                <td>9:30</td>
                <td>17:30</td>
              </tr>
              <tr>
                <td>Sobota</td>
                <td>7:00</td>
                <td>18:30</td>
              </tr>
              <tr>
                <td>Neděle</td>
                <td>7:30</td>
                <td>17:30</td>
              </tr>
          </tbody>
        </table>

    
    
            
    </div>
  

    <div class="container mt-3">
        <h2>Nová zvířata v naší ZOO</h2>
        <div class="row">
            <div class="col-md-4">
                <h3>Nové zvíře 1</h3>
            <img class="img-fluid rounded" src = "./img/kapybara.jpg"  width="400px" height="400px">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi veniam eum nulla mollitia assumenda facere impedit eaque itaque. Facere, deserunt optio vitae omnis accusantium fugit voluptatem dolorum corporis quaerat ipsa.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi veniam eum nulla mollitia assumenda facere impedit eaque itaque. Facere, deserunt optio vitae omnis accusantium fugit voluptatem dolorum corporis quaerat ipsa.</p>
        </div>
            
        

        <div class="col-md-4">
            <h3>Nové zvíře 2</h3>
            <img class="img-fluid rounded" src = "./img/tygr.jpg"  width="400px" height="400px">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi veniam eum nulla mollitia assumenda facere impedit eaque itaque. Facere, deserunt optio vitae omnis accusantium fugit voluptatem dolorum corporis quaerat ipsa.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi veniam eum nulla mollitia assumenda facere impedit eaque itaque. Facere, deserunt optio vitae omnis accusantium fugit voluptatem dolorum corporis quaerat ipsa.</p>
        </div>
 

        <div class="col-md-4">
            <h3>Nové zvíře 3</h3>
            <img class="img-fluid rounded" src = "./img/lev.jpg"  width="400px" height="400px">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi veniam eum nulla mollitia assumenda facere impedit eaque itaque. Facere, deserunt optio vitae omnis accusantium fugit voluptatem dolorum corporis quaerat ipsa.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi veniam eum nulla mollitia assumenda facere impedit eaque itaque. Facere, deserunt optio vitae omnis accusantium fugit voluptatem dolorum corporis quaerat ipsa.</p>
        </div> 



    <p> Ahoj! </p>










</div>



  </body>
</html>
