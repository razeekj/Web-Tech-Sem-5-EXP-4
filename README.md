# Web-Tech-Sem-5-EXP-4

<!DOCTYPE html>
<html><head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap. min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.b undle.min.js"></script>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"></script>
  <style>
   ul li {
        display: inline-block;
        word-spacing: 30px;
        padding-left: 400px;

       
      }
      .carousel-inner img {
    width: 100%;
    height: 500px;
  }
   .reg{
    border:2px solid blue;
    /* width: 50%;
    padding: 10px;  */
  }
    /* .table{
    width:50%;
    height: 50%px;
    float:right;
    margin-bottom: 600px;
  }  */
 
 
 
  </style>
</head>
<body>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeuXftADuVvua0OF8j6cLO-edmDAPzO4Q2OA&amp;usqp=CAU" width="250px" height="50px" style="float: left;">
  <nav>

<nav>
  <div class="a">
    <ul>
        <li style="color:blue;">Home Services Clients ContactUs Login/SignUp <input type="text" placeholder="Search.."><input type="Submit" value="submit" style="background-color:rgb(0, 183, 255) ;color:aliceblue;"></li>
        </ul>
  </div>
</nav>
<div id="demo" class="carousel slide" data-ride="carousel">

    <!-- Indicators -->
    <ul class="carousel-indicators">
      <li data-target="#demo" data-slide-to="0" class="" width="5%;"></li>
      <li data-target="#demo" data-slide-to="1" width="5px;" class=""></li>
      <li data-target="#demo" data-slide-to="2" width="5px;" class="active"></li>
    </ul>
 
    <!-- The slideshow -->
    <div class="carousel-inner">
      <div class="carousel-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSALYpHmzEtIHFVHZsgxADlssmLT5UO301M3A&amp;usqp=CAU">
      </div>
      <div class="carousel-item active carousel-item-left">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSGOeMZqrXDogHX4OURAVpwZFNf1VqyXkBb3w&amp;usqp=CAU" alt="Chicago">
      </div>
      <div class="carousel-item carousel-item-next carousel-item-left">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLSRYL3WQWHyH7pmaEq84b32y9WclbaDG0Yw&amp;usqp=CAU" alt="New York">
      </div>
    </div>
 
    <!-- Left and right controls -->
    <a class="carousel-control-prev" href="#demo" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a class="carousel-control-next" href="#demo" data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a>
  </div>
 
  <section id="services" class="form-table">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-6">
          <form class="row g-3 form">
            <div class="col-md-6">
             
              <label for="inputEmail4" class="form-label">Email</label>
              <input type="email" class="form-control" id="inputEmail4">
            </div>
            <div class="col-md-6">
              <label for="inputPassword4" class="form-label">Password</label>
              <input type="password" class="form-control" id="inputPassword4">
            </div>
            <div class="col-12">
              <label for="inputAddress" class="form-label">Address</label>
              <input type="text" class="form-control" id="inputAddress" placeholder="Write address here">
            </div>
            <div class="col-12">
              <label for="inputAddress2" class="form-label">Address 2</label>
              <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
            </div>
            <div class="col-md-6">
              <label for="inputCity" class="form-label">City</label>
              <input type="text" class="form-control" id="inputCity">
            </div>
            <div class="col-md-4">
              <label for="inputState" class="form-label">State</label>
              <select id="inputState" class="form-select">
                <option selected="">Choose...</option>
                <option>...</option>
              </select>
            </div>
            <div class="col-md-2">
              <label for="inputZip" class="form-label">Zip</label>
              <input type="text" class="form-control" id="inputZip">
            </div>
            <div class="col-12">
              <div class="form-check">
                <input class="form-check-input" type="checkbox" id="gridCheck">
                <label class="form-check-label" for="gridCheck">
                  Check me out
                </label>
              </div>
            </div>
            <div class="col-12">
              <button type="submit" class="btn btn-primary">Sign in</button>
            </div>
          </form></div>
         
         
       
        <div class="col-md-6">
          <table class="table table-bordered">
            <thead class="bg-primary" style="color: white">
              <tr>
                <th scope="col">S.No</th>
                <th scope="col">Reg.No</th>
                <th scope="col">Name of the Participant</th>
                <th scope="col">Collaborative activity</th>
                <th scope="col">Collaborating Agency</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th scope="row">1</th>
                <td>URK20CS2043</td>
                <td>DANIEL</td>
                <td>WEB DESIGN</td>
                <td>SATA Centre</td>
              </tr>
              <tr>
                <th scope="row">2</th>
                <td>URK20CS2053</td>
                <td>SITARAMAN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <th scope="row">3</th>
                <td>URK23456</td>
                <td>ERIK SHUAN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <th scope="row">4</th>
                <td>URK69CS4205</td>
                <td>BUG DWIK</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <th scope="row">5</th>
                <td>URK23AE08</td>
                <td>BUSII K J</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <th scope="row">6</th>
                <td>URK16AE1220</td>
                <td>KOOKIEKUL</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <th scope="row">7</th>
                <td>URK16AE021</td>
                <td>JEROME</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <th scope="row">8</th>
                <td>URK16AE022</td>
                <td>AFNAN M. ARIEF</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </section>

  <!-- Popper JS -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js" integrity="sha384-Xe+8cL9oJa6tN/veChSP7q+mnSPaj5Bcu9mPX5F5xIGE0DVittaqT5lorf0EI7Vk" crossorigin="anonymous"></script>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.min.js" integrity="sha384-ODmDIVzN+pFdexxHEHFBQH3/9/vQ9uori45z4JjnFsRydbmQbmL5t1tQ0culUzyK" crossorigin="anonymous"></script>
  <!-- <div class="bottom">

  <div class="reg">
    <div class="container-fluid">
      <h5 style=" color:rgba(0, 255, 255, 0.774); text-align:center">Registration Form</h5>
      <form class="form-inline">
        <label class="mb-6 p-2">Email</label>
        <input type="email" class="form-control mb-2">
        <label class="mb-6 p-2">password</label>
        <input type="password" class="form-control mb-2">
      </div>
          <label class="mb-2">Adress</label>
          <input type="text" class="form-control mb-2" placeholder="Enter your Address">
          <label class="mb-2">Adress 2</label>
          <input type="text" class="form-control mb-2" placeholder="Enter your Address">
          <div class="form-inline">
            <label class="mb-3 p-2">city</label>
            <input type="text" >
            <label class="mb-2 p-3">Zip</label>
            <input type="number">
          </div>
          <input type="checkbox">Check me out</input><br><br>
          <input type="submit" class="btn btn-primary mb-2" value="submit">
        </form>
     
     
        </div>
        <table class="table table-bordered">
          <th>
            <tr class ="bg-primary text-white">
              <th>S.no</th>
              <th>Reg.no</th>
              <th>Name of the participant</th>
              <th>Collabarative activity</th>
              <th>Collaborating Agency</th>
            </tr>
          </th>
          <tr>
            <td>1</td>
            <td>UR16AE001</td>
            <td>ANIT ANU JOHN</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>2</td>
            <td>UR16AE011</td>
            <td>VASANTHA</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>3</td>
            <td>UR16AE003</td>
            <td>ABIJITH</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>4</td>
            <td>UR16AE005</td>
            <td>JEBIN JOHN</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>5</td>
            <td>UR16AE012</td>
            <td>JOSHI K</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>6</td>
            <td>UR16AE021</td>
            <td>J B GOKUL</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>7</td>
            <td>UR16AE051</td>
            <td>JEROME</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>
          <tr>
            <td>8</td>
            <td>UR16AE056</td>
            <td>AFNAN M. ARIEF</td>
            <td>Product design and analysit</td>
            <td>CABB Center</td>
          </tr>

        </table>
       
   
  </div>
 
                 
                 
   -->
 

</nav></body></html>
