# presentacion-
nuevo tp
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarjeta de presentación - Candela Amati</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="tarjeta">

        <div class="lado-izquierdo">
            <div class="logo">CA</div>
            <p class="profesion">DESARROLLADORA WEB</p>
        </div>

        <div class="lado-derecho">
            <h1>Candela Amati</h1>
            <h2>Desarrolladora Web</h2>

            <p class="descripcion">
                Apasionada por la tecnología y el diseño web.
                Siempre en busca de nuevos desafíos.
            </p>

            <p>📧 amaticande@gmail.com</p>
            <p>📱 +54 9 342 430 1640</p>
            <p>📍 Santa Fe, Argentina</p>
            <p>🌐 www.candea.dev</p>
        </div>

    </div>

</body>
</html>



style.css


* {
    box-sizing: border-box;
}

body {
    margin: 0;
    background: #f1f3f5;
    font-family: Arial, sans-serif;

    display: flex;
    justify-content: center;
    align-items: center;

    min-height: 100vh;
}

/* Tarjeta principal */
.tarjeta {
    width: 800px;
    height: 420px;

    display: flex;

    background: white;
    border: 2px solid #23445b;
    border-radius: 20px;

    overflow: hidden;

    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

/* Parte izquierda */
.lado-izquierdo {
    width: 35%;
    height: 100%;

    background: #23445b;
    color: white;

    padding: 40px 25px;

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

/* Iniciales */
.logo {
    width: 130px;
    height: 130px;

    background: white;
    color: #23445b;

    border-radius: 50%;

    display: flex;
    justify-content: center;
    align-items: center;

    font-size: 48px;
    font-weight: bold;

    margin-bottom: 35px;
}

/* Profesión */
.profesion {
    font-size: 18px;
    letter-spacing: 2px;
    text-align: center;
}

/* Parte derecha */
.lado-derecho {
    width: 65%;
    height: 100%;

    padding: 45px 55px;

    color: #20384b;
}

/* Nombre */
h1 {
    margin: 0 0 8px;

    font-size: 42px;
}

/* Profesión */
h2 {
    margin: 0 0 30px;

    font-size: 25px;
    color: #67a0c8;
}

/* Descripción */
.descripcion {
    font-size: 18px;
    line-height: 1.5;

    margin-bottom: 25px;
}

/* Datos de contacto */
.lado-derecho p {
    margin: 12px 0;
    font-size: 17px;
}
