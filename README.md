# Estudio-lite-
está app esa para kits 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Studio Devs - Descargas y Kits</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #0b0e14;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            width: 100%;
            max-width: 450px;
            background: #151a21;
            border-radius: 16px;
            padding: 25px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.5);
            border: 1px solid #222b36;
            text-align: center;
        }
        .header-logo {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin-bottom: 20px;
        }
        .header-logo img {
            width: 55px;
            height: 55px;
            border-radius: 12px;
            object-fit: cover;
            border: 2px solid #2ecc71;
        }
        .header-logo span {
            font-size: 24px;
            font-weight: bold;
            letter-spacing: 1px;
        }
        .header-logo span b {
            color: #2ecc71;
        }
        h1 {
            font-size: 22px;
            margin-bottom: 5px;
        }
        .subtitle {
            font-size: 14px;
            color: #8b949e;
            margin-bottom: 20px;
        }
        .btn-download {
            display: block;
            background: linear-gradient(135deg, #2ecc71, #27ae60);
            color: white;
            padding: 14px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            margin-bottom: 15px;
            box-shadow: 0 4px 12px rgba(46, 204, 113, 0.3);
            transition: 0.2s;
        }
        .btn-download:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }
        .btn-publish {
            display: block;
            background: linear-gradient(135deg, #3498db, #2980b9);
            color: white;
            padding: 14px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            margin-bottom: 20px;
            box-shadow: 0 4px 12px rgba(52, 152, 219, 0.3);
            transition: 0.2s;
            cursor: pointer;
            border: none;
            width: 100%;
        }
        .btn-publish:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }
        .card {
            background: #1c2430;
            border-radius: 12px;
            padding: 18px;
            text-align: left;
            margin-bottom: 15px;
            border: 1px solid #2a3442;
            font-size: 14px;
            line-height: 1.5;
        }
        .card-title {
            font-weight: bold;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 8px;
            color: #2ecc71;
        }
        .footer {
            font-size: 12px;
            color: #6e7681;
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logo y Título -->
        <div class="header-logo">
            <!-- Cambia el link de la imagen por el tuyo si querés -->
            <img alt="Logo Studio Devs" src="https://i.ibb.co/FjvZ0mf/SAVE-20261018-014101.jpg">
            <span>STUDIO <b>DEVS</b></span>
        </div>

        <h1>Instalar Studio Devs</h1>
        <div class="subtitle">Plataforma oficial para desarrolladores de Studio Lite</div>
        
        <!-- Botón de Descarga APK (Reemplaza "tu-archivo.apk" por el enlace directo de tu APK) -->
        <a class="btn-download" href="tu-archivo.apk">📥 Descargar APK (V2.2)</a>

        <!-- Botón para Publicar Kits con contraseña -->
        <button class="btn-publish" onclick="pedirPassword()">🚀 Publicar tus Kits</button>

        <!-- Mensaje del Admin -->
        <div class="card">
            <div class="card-title">💬 Mensaje del Admin:</div>
            🎉 <strong>¡STUDIO DEVS V2 YA ESTÁ AQUÍ!</strong> 🚀<br><br>
            ¡Hola a todos! 👋 Después de mucho trabajo y esfuerzo, ¡por fin lanzamos la V2! 🥳💚<br><br>
            Esta nueva versión llega con muchísimas novedades, nuevos Kits, sistemas, modelos y muchas cosas más. 🔥<br><br>
            Pero eso no es todo… 👀✨ ¡Ahora también vas a poder publicar tus propios Kits en nuestra aplicación! 🤯🎮<br><br>
            🙏 Muchísimas gracias a todos por apoyarnos siempre y formar parte de este proyecto. 💚🎮
        </div>

        <!-- Caja de Sugerencias -->
        <div class="card">
            <div class="card-title">💡 Caja de Sugerencias:</div>
            ¿Qué funciones, herramientas o scripts te gustaría que agregue en la próxima actualización?
        </div>

        <!-- Pie de página -->
        <div class="footer">
            🛠️ Zona VIP • Creado con esfuerzo por Juan Andrés
        </div>
    </div>

    <script>
        function pedirPassword() {
            let pass = prompt("Ingresa la contraseña de Administrador para publicar Kits:");
            if (pass === "Juan233035") {
                alert("¡Contraseña correcta! Accediendo al panel de publicación...");
                // Acá puedes cambiar el link de abajo a donde quieras que vaya al poner bien la clave (ej: un formulario o enlace de subida)
                window.location.href = "https://www.tiktok.com/"; 
            } else if (pass !== null) {
                alert("❌ Contraseña incorrecta. Acceso denegado.");
            }
        }
    </script>

</body>
</html>
