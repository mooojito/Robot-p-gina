[index.html](https://github.com/user-attachments/files/22524417/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIENDA SUPERROBOT</title>
<style>
    /*MENU SUPERIOR*/
nav{
background: #222;
padding: 10px 0;

}

nav ul{
    list-style: none;
    margin:0;
    padding:0;
    display: flex;
    justify-content: first baseline;
justify-content: center;
}

nav ul li{
    margin: 0 15px;

}

nav ul li a{
    color:#fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3;
}

nav ul li a:hover{
    color:blue;
}




    body{
        content: center;
        text-align: center;
        justify-content: center;
background-color: rgb(16, 82, 133);
    }

.contenedor{
    background-color: rgb(167, 230, 255);
    border-radius: 200px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    flex-grow: 1;
    flex-basis:100px;
    ;}

    .titulo,.imagen{
        text-align: center;
        flex-basis: 100px;
        flex-grow: 1;
    }

   footer {
    text-align: center;
background:rgb(255, 255, 255);
padding: 15px 0;
}
    
    .imagen img{
        max-width: 500px;
height: auto;   
border-radius: 15px;
box-shadow: 0px 4px 10px rgba(3, 3, 3, 0.541);
max-width: 100%;
height: auto; }

</style>
</head>

<body>
    <!----MENU DE NAVEGACIÓN--->
    <nav>
<ul>
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Productos</a></li>
    <li><a href="#">Ofertas</a></li>
    <li><a href="#">Contacto</a></li>

</ul>

    </nav>

    <div class="contenedor">
    <div class="titulo"> 
        <h1>Bienvenidos a la tienda SuperRobot</h1>
 </div>

    <div class="imagen">
        <img src="Imagenes/robots.jpg">
    </div>

    <div class="titulo">
<h3>Descubre el juguete mas emocionate del año</h1>
    </div>

    </div>

    <footer>
        @ 2025 SuperRobot | Todos los derechos reservados
    </footer>
</body>
</html>
