# examen1.1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@800&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,600;1,700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <link rel="icon" type="image/png" href="logo_.jpeg">
    <title>Sky Creation</title>
    <style>
      .navone{
        grid-area: navone; 
      }
      .navtwo{
        grid-area: navtwo;
      }
      .firstpic{
        grid-area: firstpic; 
      }
      .container{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr ;
        grid-template-rows: 2 auto;
        grid-template-areas: "navone   navone   navone"
                             "navtwo   navtwo   navtwo";
        max-width: 100%;
      }
      .navone{
        grid-area: navone;
      }
      .navtwo{
        grid-area: navtwo;
      }
      .products{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr ;
        grid-template-rows: 3 auto;
        grid-template-areas: "Titulo2    Titulo2   Titulo2"
                              "product1  product2  product3" 
                              "titulo3   titulo3   titulo3"
                              "last      last      last";
        
        gap: 5%;
        margin-top: 2%;
      }
      .Titulo2{
        grid-area: Titulo2;
      }
      .product1{
        grid-area: product1;
      }
      .product2{
        grid-area: product2;
      }
      .product3{
        grid-area: product3;
      }
      .lasti{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr ;
        grid-template-rows: 3 auto;
        grid-template-areas: "titulo3 titulo3 titulo3 titulo3"
                             "last    last    last    last";

        max-width: 80%;
        margin: auto;
        margin-bottom: 5%;
      }
      button{
        width:450px;
        height:50px; 
        background-color: rgb(255, 181, 255); 
        border-color:rgb(255, 181, 255);
      }
    </style>
</head>
<body>
        <div class="navone">
            <nav class="navbar navbar-light" style="background-color: white;">
                <div class="container-fluid">
                    <a class="navbar-brand"><h1 style=" font-weight: bold; font-family: Poppins ; font-size: 40px; margin-left: 870px; color: rgb(0, 0, 0);">Sky Creations</h1></a>
                    <img src="logo_.jpeg" width="100" height="80"  alt="logo">
                </div>
              </nav>
        </div>

        <div class="navtwo" style="font-family: Poppins; font-size: 16px; font-weight:normal;">
            <ul class="nav nav-tabs">
                <li class="nav-item">
                  <a class="nav-link active"  href="inicio.html">Inicio</a>
                </li>
              </ul>
        </div>
     
        <div class="firstpic">
          <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://www.eljardinrojo.com/wp-content/uploads/2020/06/Las-Mejores-Marcas-de-Maquillaje.jpg" class="d-block w-100" alt="foto1"  height="550px">
                </div>
                <div class="carousel-caption d-none d-md-block" style="text-align: left;">
                </div>
                <div class="carousel-caption d-none d-md-block">
                </div>
                <div class="carousel-item">
                    <img src="https://media.istockphoto.com/photos/set-of-cosmetic-products-for-makeup-with-natural-brushes-picture-id1178545014?k=20&m=1178545014&s=612x612&w=0&h=eVGLYcYpd5yHKVXxlZkCbTHQ_D0LqpCVaxsE1kwDm9Y=" class="d-block w-100" alt="foto3"  height="540px">
                </div>
            <div class="carousel-caption d-none d-md-block">
            </div>
            </div>
          </div>
        </div>
    
        <br><br>
        <section style="background-color: rgb(255, 241, 255);">
            <img src="https://i.pinimg.com/736x/86/d4/02/86d402017bcd64ad5dc7e4067f4aa545.jpg" class="img-fluid" class="card-img-top" class="rounded" alt="..." style="margin-left: 40px;">
            <div style="margin-right: 80px; float: right;">
                <br> <br>
                <h3 style="font-family: Tahoma, serif;">Mision</h3>
            <p>Llenar la brecha entre el arte del maquillaje y fotografía de modo creando nuevos colores 
                <br> y productos para el uso creativo de los maquilladores profesionales.</p>
            <h3 style="font-family: Tahoma, serif;">Vision</h3>
            <p>Ser el líder mundial en maquillaje, ofreciendo excelentes servicios y productos de calidad 
               <br> a todos nuestros clientes.</p>
            <h3 style="font-family: Tahoma, serif;">Valores</h3>
            <ul>
                <li>Responsabilidad</li>
                <li>Creatividad</li>
                <li>Dinámica</li>
                <li>Innovación</li>
                <li>Audacia</li>
            </ul>
            </div> 
        </section>
        <br><br> <br>
        <h1 style="color: rgb(255, 172, 237); font-size: 60px; text-align: center;">Sky Creation</h1>
        <div class="tainer" style="font-family: Poppins; margin-left: 150px;">
          <div class="products" style="text-align: center;">
            <div class="product1">
             <div class="card" style="width: 18rem;">
               <img src="labial.png" class="card-img-top" alt="...">
               <div class="card-body">
                 <h5 class="card-title">Retro matte liquid lipcolour metallics</h5>
                 <spam style="text-align: justify;"> Provee un toque de color metálico mate puro con un acabado líquido agamuzado y de larga duración.<spam/>
                 <p class="card-text" style="text-align: center;">$12.99</p>
               </div>
               <a href="form.html" class="btn btn-dark">Buy</a>
             </div>
            </div>
            <div class="product2">
             <div class="card" style="width: 18rem;">
               <img src="rimel.png" class="card-img-top" alt="...">
               <div class="card-body">
                 <h5 class="card-title">Up for everything lash</h5>
                 <spam style="text-align: justify;">Mascara de pestañas que da volumen extremo por 24 horas y a prueba de agua.<spam/>
                 <p class="card-text" style="text-align: center;">$15.95</p>
                </div>
                <a href="form.html" class="btn btn-dark">Buy</a>
             </div>
            </div>
            <div class="product3">
             <div class="card" style="width: 18rem;">
               <img src="paleta.png" class="card-img-top" alt="...">
               <div class="card-body">
                 <h5 class="card-title">Sky Creations art library</h5>
                 <spam style="text-align: justify;">Paleta de ojos por Sky Creations pro artists. Cuenta 12 tonos neutros, intensamente pigmentados.<spam/>
                 <p class="card-text" style="text-align: center;">$25.95</p>
                </div>
                <a href="form.html" class="btn btn-dark">Buy</a>
             </div>
            </div>
          </div>
      </div>
      <br> <br> <br> <br>
    <div class="footer0">
       <div class="footer" style="text-align: center; background-color: rgb(255, 232, 250) ; font-size:16px; padding: 15px; font-family: Poppins ; color: rgb(0, 0, 0);">
        <h4 style=" font-weight: 800;">Opening Hours:</h4>
        <p>Mon - Fri: 24/7
        <br> Saturday: 8am - 11pm 
        <br> Sunday: 8am - 11pm</p>
        <br>
        <img src="https://cdn-icons-png.flaticon.com/128/1384/1384031.png" width="20" height="20" style="margin-left: 48%;">
        <img src="icono.png" width="20" height="20" style="margin-right: 48%;">
        <br>
       </div>
    </div>
   
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
</body>
</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@800&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,600;1,700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <script src="js.js"></script>
    <link rel="icon" type="image/png" href="logo_.jpeg">
    <title>Sky Creation</title>
</head>
<body>
        <div class="navone">
            <nav class="navbar navbar-light" style="background-color: white;">
                <div class="container-fluid">
                    <a class="navbar-brand"><h1 style=" font-weight: bold; font-family: Poppins ; font-size: 40px; margin-left: 870px; color: rgb(0, 0, 0);">Sky Creations</h1></a>
                    <img src="logo_.jpeg" width="100" height="80"  alt="logo">
                </div>
              </nav>
        </div>

        <div class="navtwo" style="font-family: Poppins; font-size: 16px; font-weight:normal;">
            <ul class="nav nav-tabs">
                <li class="nav-item">
                  <a class="nav-link active"  href="inicio.html">Inicio</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-secondary active"  href="shop.html">Shop</a>
                </li>
              </ul>
        </div>
        <br><br>
        <br> <br>
        
        <section>
            <img src="https://i.pinimg.com/originals/c0/93/ca/c093ca4f45d8f91f3331422009ad0899.jpg" class="img-fluid" class="card-img-top" class="rounded" alt="..." style="margin-left: 40px; float: left; width:30%;">
            <br><br>
            <form  style="margin-left: 500px; font-family: Tahoma, serif;">
                <h4>Información de contacto</h4>
                <input type="email" id="correo" placeholder="correo electrónico" required>
                <br><br>
                <h4>Dirección de envío</h4>
                <input type="text" id="Nombre"  placeholder="Nombre" value="nombre">
                <input type="text" id="Apellido"  placeholder="Apellido" value="apellido"> <br>
                <input type="number" id="edad"  placeholder="edad" value="edad"> <br>
                <input type="text" id="Direcciòn" placeholder="Dirección" value="dirección">
                <input type="tel" id="telefono" placeholder="Teléfono" value="teléfono"> <br>
                <label>Región:</label>
                <select name="Región" id="regiòn">
                    <option value="value0"></option>
                    <option value="Bocas del Toro">Bocas del Toro</option>
                    <option value="Coclé">Coclé</option>
                    <option value="Colón">Colón</option>
                    <option value="Chiriquí">Chiriquí</option>
                    <option value="Darién">Darién</option>
                    <option value="Herrera">Herrera</option>
                    <option value="Los Santos">Los Santos</option>
                    <option value="Panamá">Panamá</option>
                    <option value="Veraguas">Veraguas</option>
                    <option value="Panamá Oeste">Panamá Oeste</option>
                    <option value="Emberá-Wounaan">Emberá-Wounaan</option>
                    <option value="Guna Yala">Guna Yala</option>
                    <option value="Ngöbe-Buglé">Ngöbe-Buglé</option>
                   </select>
                <br>
                <label>Cantidad:</label>
                <input type="number" id="cantidad" placeholder="producto" value="productos"> <br>
                <label>Precio:</label>
                <input type="text" id="precio"  placeholder="precio del producto">
                <br>
                
                <br><br>
                <button class="btn btn-lg btn-primary btn-block" type="button" value="enviar" onclick="datos()" style="width: 400px; height: 50px;">Enviar</button>
             </form>
    <br><br><br><br><br>
    <div class="footer0">
       <div class="footer" style="text-align: center; background-color: rgb(255, 232, 250) ; font-size:16px; padding: 15px; font-family: Poppins ; color: rgb(0, 0, 0);">
        <h4 style=" font-weight: 800;">Opening Hours:</h4>
        <p>Mon - Fri: 24/7
        <br> Saturday: 8am - 11pm 
        <br> Sunday: 8am - 11pm</p>
        <br>
        <img src="https://cdn-icons-png.flaticon.com/128/1384/1384031.png" width="20" height="20" style="margin-left: 48%;">
        <img src="https://cdn-icons.flaticon.com/png/128/3128/premium/3128212.png?token=exp=1639355331~hmac=d783942dab3606bf7109dc18f2b056e8" width="20" height="20" style="margin-right: 48%;">
        <br>
       </div>
    </div>
   
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
</body>
</html>





function datos(){
    let correo = document.getElementById("correo").value;
    let Nombre = document.getElementById("Nombre").value; 
    let Apellido = document.getElementById("Apellido").value;
    let edad = document.getElementById("edad").value; 
    let Direcciòn = document.getElementById("Direcciòn").value; 
    let telefono = document.getElementById("telefono").value;
    let regiòn = document.getElementById("regiòn").value;
    let cantidad = document.getElementById("cantidad").value;
    let precio = document.getElementById("precio").value;
    
    
    var jubilado = prompt("¿Es jubilado?\n Para confirmar escriba el número \n 1. Si \n 2. No");
    if(jubilado == 1){
      let Montogravado= parseFloat(precio*cantidad);
      let descuento= parseFloat(Montogravado*15/100);
      let total= parseFloat(Montogravado-descuento);
        document.write("Correo="+correo +"<br>");
        document.write("Nombre="+Nombre +Apellido+"<br>");
        document.write("Dirección="+Direcciòn +"<br>");
        document.write("Número telefónico="+telefono +"<br>");
        document.write("Región="+regiòn +"<br>");
        document.write("cantidad="+cantidad +"<br>");
        document.write("Total importe="+ parseFloat (precio*cantidad )+"<br>");
        document.write("Descuento="+descuento+"<br>");
        document.write("Monto gravado="+ Montogravado +"<br>");
        document.write("Total ="+ total +"<br>");
      
    }
    if(jubilado == 2){
      
        let Montogravado= parseFloat(precio*cantidad);
        let Totalimpuesto= parseFloat(Montogravado*7/100);
        let total= parseFloat (Montogravado+Totalimpuesto);
      
        document.write("Correo="+correo +"<br>");
        document.write("Nombre="+Nombre +Apellido+"<br>");
        document.write("Dirección="+Direcciòn +"<br>");
        document.write("Número telefónico="+telefono +"<br>");
        document.write("Región="+regiòn +"<br>");
        document.write("cantidad="+cantidad +"<br>");
        document.write("Total importe="+ parseFloat (precio*cantidad )+"<br>");
        document.write("Monto gravado="+ Montogravado +"<br>");
        document.write("Total impuesto="+ Totalimpuesto  +"<br>");
        document.write("Total ="+total +"<br>");
      
    }
  }
