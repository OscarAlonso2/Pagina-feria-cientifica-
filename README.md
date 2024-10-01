<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="description" content="Encuentra cursos en línea al mejor precio, con acceso de por vida y clases impartidas por expertos.">
    <title>Carrito</title>
    <link rel="stylesheet" href="normalize.css">
    <link rel="stylesheet" href="custom.css">
    <link rel="stylesheet" href="skeleton.css">
</head>
<body>
<header id="header" class="header">
    <div class="container">
        <div class="row">
            <div class="four columns">
                <img src="img/logo.jpg" id="logo" alt="Logo del sitio">
            </div>
            <div class="two columns u-pull-right">
                <ul>
                    <li class="submenu">
                        <img src="img/cart.png" id="img-carrito" alt="Carrito de compras">
                        <div id="carrito">
                            <table id="lista-carrito" class="u-full-width">
                                <thead>
                                    <tr>
                                        <th>Imagen</th>
                                        <th>Nombre</th>
                                        <th>Precio</th>
                                        <th>Cantidad</th>
                                        <th></th>
                                    </tr>
                                </thead>
                                <tbody></tbody>
                            </table>
                            <a href="#" id="vaciar-carrito" class="button u-full-width">Vaciar Carrito</a>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</header>

<div id="hero">
    <div class="container">
        <div class="row">
            <div class="six columns">
                <div class="contenido-hero">
                    <h2>Aprende algo nuevo</h2>
                    <p>Todos los cursos al mejor precio</p>
                    <form action="#" id="busqueda" method="post" class="formulario">
                        <input class="u-full-width" type="text" placeholder="¿Qué te gustaría aprender?" id="buscador">
                        <input type="submit" id="submit-buscador" class="submit-buscador" value="Buscar">
                    </form>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="barra">
    <div class="container">
        <div class="row">
            <div class="four columns icono icono1">
                <p>20,000 Cursos en línea <br>
                Explora los temas más recientes</p>
            </div>
            <div class="four columns icono icono2">
                <p>Instructores Expertos <br>
                Aprende con distintos estilos</p>
            </div>
            <div class="four columns icono icono3">
                <p>Acceso de por vida <br>
                Aprende a tu ritmo</p>
            </div>
        </div>
    </div>
</div>

<div id="lista-cursos" class="container">
    <h1 id="encabezado" class="encabezado">Cursos En Línea</h1>
    <div class="row">
        <!-- Curso 1 -->
        <div class="four columns">
            <div class="card">
                <img src="img/curso1.jpg" class="imagen-curso u-full-width" alt="Curso de HTML5, CSS3 y JavaScript">
                <div class="info-card">
                    <h4>HTML5, CSS3, JavaScript para Principiantes</h4>
                    <p>Juan Pedro</p>
                    <img src="img/estrellas.png" alt="Estrellas de calificación">
                    <p class="precio">$370 <span class="u-pull-right ">$100</span></p>
                    <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="1">Agregar Al Carrito</a>
                </div>
            </div>
        </div>
        <!-- Curso 2 -->
        <div class="four columns">
            <div class="card">
                <img src="img/curso2.jpg" class="imagen-curso u-full-width" alt="Curso de Comida Vegetariana">
                <div class="info-card">
                    <h4>Curso de Comida Vegetariana</h4>
                    <p>Juan Pedro</p>
                    <img src="img/estrellas.png" alt="Estrellas de calificación">
                    <p class="precio">$200 <span class="u-pull-right ">$75</span></p>
                    <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="2">Agregar Al Carrito</a>
                </div>
            </div>
        </div>
        <!-- Curso 3 -->
        <div class="four columns">
            <div class="card">
                <img src="img/curso3.jpg" class="imagen-curso u-full-width" alt="Curso de Guitarra para Principiantes">
                <div class="info-card">
                    <h4>Guitarra para Principiantes</h4>
                    <p>Juan Pedro</p>
                    <img src="img/estrellas.png" alt="Estrellas de calificación">
                    <p class="precio">$250 <span class="u-pull-right ">$90</span></p>
                    <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="3">Agregar Al Carrito</a>
                </div>
            </div>
        </div>
    </div>
    <!-- Más cursos -->
    <div class="row">
        <div class="four columns">
            <div class="card">
                <img src="img/curso4.jpg" class="imagen-curso u-full-width">
                <div class="info-card">
                    <h4>Huerto en tu casa</h4>
                    <p>Juan Pedro</p>
                    <img src="img/estrellas.png">
                    <p class="precio">$200  <span class="u-pull-right ">$67.50</span></p>
                    <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="4">Agregar Al Carrito</a>
                </div>
            </div> <!--.card-->
        </div>
        <div class="four columns">
                <div class="card">
                    <img src="img/curso5.jpg" class="imagen-curso u-full-width">
                    <div class="info-card">
                        <h4>Decoración con productos de tu hogar</h4>
                        <p>Juan Pedro</p>
                        <img src="img/estrellas.png">
                        <p class="precio">$200  <span class="u-pull-right ">$89</span></p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="5">Agregar Al Carrito</a>
                    </div>
                </div> <!--.card-->
        </div>
        <div class="four columns">
                <div class="card">
                    <img src="img/curso1.jpg" class="imagen-curso u-full-width">
                    <div class="info-card">
                        <h4>Diseño Web para Principiantes</h4>
                        <p>Juan Pedro</p>
                        <img src="img/estrellas.png">
                        <p class="precio">$450  <span class="u-pull-right ">$150</span></p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="6">Agregar Al Carrito</a>
                    </div>
                </div> <!--.card-->
        </div>
    </div> <!--.row-->
    <div class="row">
        <div class="four columns">
            <div class="card">
                <img src="img/curso2.jpg" class="imagen-curso u-full-width">
                <div class="info-card">
                    <h4>Comida Mexicana para principiantes</h4>
                    <p>Juan Pedro</p>
                    <img src="img/estrellas.png">
                    <p class="precio">$350  <span class="u-pull-right ">$75</span></p>
                    <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="7">Agregar Al Carrito</a>
                </div>
            </div> <!--.card-->
        </div>
        <div class="four columns">
                <div class="card">
                    <img src="img/curso3.jpg" class="imagen-curso u-full-width">
                    <div class="info-card">
                        <h4>Estudio Musical en tu casa</h4>
                        <p>Juan Pedro</p>
                        <img src="img/estrellas.png">
                        <p class="precio">$400  <span class="u-pull-right ">$49.99</span></p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="8">Agregar Al Carrito</a>
                    </div>
                </div> <!--.card-->
        </div>
        <div class="four columns">
                <div class="card">
                    <img src="img/curso4.jpg" class="imagen-curso u-full-width">
                    <div class="info-card">
                        <h4>Cosecha tus propias frutas y verduras</h4>
                        <p>Juan Pedro</p>
                        <img src="img/estrellas.png">
                        <p class="precio">$150  <span class="u-pull-right ">$65</span></p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="9">Agregar Al Carrito</a>
                    </div>
                </div> <!--.card-->
        </div>
    </div> <!--.row-->
    <div class="row">
            <div class="four columns">
                <div class="card">
                    <img src="img/curso5.jpg" class="imagen-curso u-full-width">
                    <div class="info-card">
                        <h4>Prepara galletas caseras</h4>
                        <p>Juan Pedro</p>
                        <img src="img/estrellas.png">
                        <p class="precio">$200  <span class="u-pull-right ">$79.99</span></p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="10">Agregar Al Carrito</a>
                    </div>
                </div> <!--.card-->
            </div>
            <div class="four columns">
                    <div class="card">
                        <img src="img/curso1.jpg" class="imagen-curso u-full-width">
                        <div class="info-card">
                            <h4>JavaScript Moderno con ES6</h4>
                            <p>Juan Pedro</p>
                            <img src="img/estrellas.png">
                            <p class="precio">$500  <span class="u-pull-right ">$250</span></p>
                            <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="11">Agregar Al Carrito</a>
                        </div>
                    </div> <!--.card-->
            </div>
            <div class="four columns">
                    <div class="card">
                        <img src="img/curso2.jpg" class="imagen-curso u-full-width">
                        <div class="info-card">
                            <h4>100 Recetas de Comida Natural</h4>
                            <p>Juan Pedro</p>
                            <img src="img/estrellas.png">
                            <p class="precio">$200  <span class="u-pull-right ">$90</span></p>
                            <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="12">Agregar Al Carrito</a>
                        </div>
                    </div> <!--.card-->
            </div>
        </div> <!--.row-->
</div>

<footer id="footer" class="footer">
    <div class="container">
        <div class="row">
            <div class="four columns">
                <nav id="principal" class="menu">
                    <a class="enlace" href="https://www.instagram.com/vida_uml?igsh=MThxMGJxa3dxbzlnbw==">UML Instagram</a>
                    <a class="enlace" href="https://www.facebook.com/UMLNicaragua?mibextid=kFxxJD">UML Facebook</a>
                    <a class="enlace" href="https://x.com/umartinlutero">Twitter</a>
                </nav>
            </div>
            <div class="four columns">
                <nav id="secundaria" class="menu">
                    <a class="enlace" href="https://uml.edu.ni/" target="_blank">¿Quiénes Somos?</a>
                    <a class="enlace" href="https://uml.edu.ni/sedes-nacionales/" target="_blank">Sedes de nuestras instituciones</a>
                    <a class="enlace" href="https://uml.edu.ni/nosotros/" target="_blank">Nosotros</a>
                </nav>
            </div>
        </div>
    </div>
</footer>

<script src="app.js"></script>
</body>
</html>
