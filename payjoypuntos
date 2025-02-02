<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programa de Beneficios por Puntos Payjoy</title>
    <!-- Incluir FontAwesome para íconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #E0F7C2; /* Verde más suave */
            overflow: hidden;
            position: relative;
        }

        /* Contenedor principal */
        .container {
            text-align: center;
            padding: 20px;
            position: relative;
            z-index: 2;
        }

        /* Logo de Payjoy */
        .logo {
            width: 200px;
            margin-bottom: 20px;
        }

        /* Título del programa */
        .titulo {
            font-size: 28px;
            color: #00471D;
            margin-bottom: 20px;
        }

        /* Estilos para los puntos */
        .puntos {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Estilos para el mensaje de motivación */
        .motivacion {
            font-size: 24px; /* Más grande */
            color: #00471D;
            margin-top: 20px;
        }

        .motivacion i {
            margin-right: 10px;
            color: #42BF00; /* Color del ícono */
        }

        /* Estilos para el botón de canje */
        .boton-canje {
            display: inline-flex;
            align-items: center;
            margin-top: 20px;
            padding: 15px 30px;
            background-color: #42BF00;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 20px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .boton-canje:hover {
            background-color: #369700; /* Verde más oscuro al pasar el mouse */
        }

        .boton-canje i {
            margin-right: 10px;
        }

        /* Estilos para la sección de detalles */
        .detalles {
            margin-top: 30px;
            text-align: left;
            display: inline-block;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .detalles h3 {
            color: #00471D;
            margin-bottom: 10px;
        }

        .detalles p {
            margin: 5px 0;
        }

        /* Animación de las esferas */
        .esfera {
            position: absolute;
            width: 40px; /* Más grandes */
            height: 40px; /* Más grandes */
            border-radius: 50%;
            animation: rebotar 5s infinite ease-in-out;
        }

        @keyframes rebotar {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
    </style>
</head>
<body>
    <!-- Esferas animadas con los colores proporcionados -->
    <div class="esfera" style="top: 10%; left: 5%; background-color: #42BF00;"></div>
    <div class="esfera" style="top: 20%; left: 20%; background-color: #C7FD17;"></div>
    <div class="esfera" style="top: 30%; left: 40%; background-color: #00471D;"></div>
    <div class="esfera" style="top: 40%; left: 60%; background-color: #8DAF54;"></div>
    <div class="esfera" style="top: 50%; left: 80%; background-color: #42BF00;"></div>
    <div class="esfera" style="top: 60%; left: 90%; background-color: #C7FD17;"></div>

    <!-- Contenido principal -->
    <div class="container">
        <!-- Logo de Payjoy -->
        <img src="https://www.payjoy.com/wp-content/uploads/2021/05/logo.svg" alt="Logo Payjoy" class="logo">

        <!-- Título del programa -->
        <h1 class="titulo">Programa de Beneficios por Puntos</h1>

        <!-- Puntos acumulados -->
        <div class="puntos">
            <h2>Tienes acumulado <span style="color: #42BF00;">2000 puntos</span></h2>
            <h3>1500 Válidos</h3>
        </div>

        <!-- Mensaje de motivación con ícono -->
        <div class="motivacion">
            <i class="fas fa-trophy"></i> ¡Tu % de Morosidad es del 8%! Vas muy bien, sigue generando más financiamientos.
        </div>

        <!-- Botón de canje con ícono -->
        <a href="#" class="boton-canje">
            <i class="fas fa-gift"></i> Canjea tus puntos aquí
        </a>

        <!-- Detalles de Admin, Merchant y Clerk's -->
        <div class="detalles">
            <h3>Detalles de Puntos</h3>
            <p><strong>Admin:</strong> PAYJOYPRUEBA - 1500 puntos</p>
            <p><strong>Merchant:</strong></p>
            <ul>
                <li>PAYJOYOLGUIN - 1000 puntos</li>
                <li>PAYJOYSURCO - 500 puntos</li>
            </ul>
            <p><strong>Clerk's:</strong></p>
            <ul>
                <li>ElPite - 500 puntos</li>
                <li>Omarichi - 500 puntos</li>
                <li>Pepito - 500 puntos</li>
            </ul>
        </div>
    </div>

    <!-- Script para animar las esferas -->
    <script>
        const esferas = document.querySelectorAll('.esfera');
        esferas.forEach((esfera, index) => {
            esfera.style.animationDuration = `${Math.random() * 3 + 2}s`;
            esfera.style.animationDelay = `${Math.random() * 2}s`;
        });
    </script>
</body>
</html>
