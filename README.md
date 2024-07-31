# Proyecto-Matriz-LED-controlada-con-joystick

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basura Tecnológica</title>
    <!-- Agrega el ícono de la pestaña del navegador -->
    <link rel="icon" type="image/png" href="https://ideogram.ai/assets/image/list/response/pEfXHfeZQzKx_UU6RyDqRg">

    <style>
        /* Estilos CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
            background-image: url('https://ideogram.ai/api/images/direct/SUVgreK-TY6TWb7f9datWw.png');
            background-size: cover;
            background-position: top;
            color: #FFFFFF;
        }
        header {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
            padding: 30px 0;
            text-align: center;
            margin-bottom: 20px; /* Margen inferior agregado */
        }
        .logo img {
            width: 200px; /* Tamaño del logo 1 */
            display: block;
            margin: 0 auto; /* Centrar horizontalmente */
        }
        nav {
            background-color: transparent; /* Color transparente */
            padding: 10px 0;
            text-align: center;
            padding-bottom: 10px; /* Aumento del padding inferior */
        }
        nav a {
            display: inline-block; /* Modificado para mostrar en línea */
            color: #FFFFFF; /* Cambiado a color blanco */
            text-decoration: none;
            margin: 10px; /* Se cambió margin-top y margin-bottom a margin */
            padding: 10px;
            border-radius: 5px;
            background-color: transparent; /* Color transparente */
            border: 2px solid #FFFFFF; /* Agregar borde blanco */
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #93C0EE;
        }
        section {
            padding: 30px;
            margin: 20px;
            background-color: rgba(255, 255, 255, 0.9); /* Fondo blanco semitransparente */
            border-radius: 10px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }
        section h2,
        section p {
            color: #000000; /* Cambiar color del texto a negro */
        }
        footer {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
            color: #FFFFFF; /* Cambiado a color blanco */
            padding: 20px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Estilos para el menú */
        .Menu {
            padding-bottom: 22px;
            width: 100%;
            margin: 0 auto;
            text-align: center;
        }
        .Menu ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex; /* Cambiado a flex para hacer el menú horizontal */
            justify-content: center; /* Centrar los elementos */
        }
        /* Estilos para la galería de imágenes */
        .galery {
            display: flex;
            height: 20rem;
            gap: 1rem;
        }
        .galery > div {
            flex: 1;
            border-radius: 1rem;
            background-position: center;
            background-repeat: no-repeat;
            background-size: auto 100%;
            transition: all .8s cubic-bezier(.25, .04, .45, 1.4);
        }
        .galery > div:hover {
            flex: 5;
        }
        /* Estilos para el contenedor de video */
        .video-container {
            display: flex;
            justify-content: center; /* Centra el video horizontalmente */
            align-items: center;     /* Centra el video verticalmente (opcional) */
            padding: 20px 0;
        }
        .video-container iframe {
            border: none;
            width: 80%;   /* Ajusta el ancho del iframe a un porcentaje del contenedor */
            height: 450px; /* Ajusta la altura del iframe a un valor fijo */
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://colegiodivinosalvadorcali.edu.co/images/fixed/ESCUDO%20OFICIAl.png" alt="Logo 1">
        </div>
        <h1>Proyecto Matriz LED controlada con joystick</h1>
    </header>

    <nav>
        <div class="Menu">
            <ul>
                <li><a href="#">Página Principal</a></li>
                <li><a href="#">Conceptos Nuevos</a></li>
                <li><a href="#">Procedimiento</a></li>
                <li><a href="#">Materiales</a></li>
            </ul>   
        </div>
    </nav>

    <section id="introducción">
        <h2>INTRODUCCIÓN</h2>
        <p>En este trabajo se busca hacer funcionar una matriz led, en la cual se evidencie un mensaje o una figura, para esto se realizó un circuito en el cual se hizo uso de cables macho/ hembra, un arduino y una matriz led. Se precensiaron varios conceptos, entre ellos, VCC, GND, CS, DIN Y CLK. </p>
    </section>

    <section id="funcionamiento">
        <h2>FUNCIONAMIENTO</h2>
        <p>Primeramente, se realizaron las conecciones entre la matriz led y el arduino, primero el GND de la matriz al GND del arduino, el DIN de la matriz al pin 12 del arduino, el CS de la matriz al pin 10 y el CLK de la matriz al pin 11 del arduino.</p>
        <p>Posteriormente se integró el código que le diera la orden a la matriz led de escribir un "TE AMO".</p>
    </section>

    <section id="materiales">
        <h2>MATERIALES</h2>
        <p> - </p>
    </section>

    <section id="paso a paso">
        <h2>PASO A PASO</h2>
        <p></p>
    </section>

    <section id="que se aprendimos">
        <h2>QUE SE APRENDIO</h2>
        <p></p>
    </section>

    <section id="video de solución">
        <h2>VIDEO DE SOLUCIÓN</h2>
        <div class="video-container">
            <iframe src="https://youtu.be/cCmXLi9YmUU?si=9rvM45v4_itADhQ4" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </section>

    <!-- Nueva sección de galería de imágenes -->
    <section class="galery">
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
    </section>

    <footer>
        <p>&copy; 2024 - Combita y Laiseca - Matriz LED - C.D.S</p>
    </footer>
</body>
</html>
