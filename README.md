<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cursos de Civismo y Constitución de 1940</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }

        header {
            background: #007bff;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            margin: 10px 0;
        }

        button {
            margin: 5px;
            padding: 10px 15px;
            font-size: 16px;
            cursor: pointer;
        }

        #info {
            margin-top: 20px;
            background: #fff;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        footer {
            text-align: center;
            margin-top: 20px;
        }

        .project-image {
            width: 100%;
            max-width: 600px;
            margin: 20px auto;
            display: block;
            border: 2px solid #007bff;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cursos de Civismo y Constitución de 1940</h1>
        <nav>
            <button onclick="showInfo('introduccion')">Introducción al Civismo</button>
            <button onclick="showInfo('historia')">Historia de la Constitución</button>
            <button onclick="showInfo('derechos')">Derechos y Libertades</button>
            <button onclick="showInfo('gobierno')">Estructura del Gobierno</button>
            <button onclick="showInfo('impacto')">Impacto del Régimen</button>
            <button onclick="showInfo('conducta')">Códigos de Conducta Cívica</button>
            <button onclick="showInfo('renace')">RENACE CUBA PATRIA QR</button>
            <button onclick="showInfo('articulos')">Artículos de la Constitución</button>
            <button onclick="showInfo('conclusiones')">Conclusiones</button>
            <button onclick="showFAQ()">Preguntas Frecuentes</button>
            <button onclick="window.open('https://www.gobiernoconstitucionalcubano1940.com/', '_blank')">Visitar el Sitio Web</button>
        </nav>
    </header>
    <main>
        <div id="info"></div>
        <img src="nombre_de_tu_imagen.png" alt="Imagen del Proyecto RENACE CUBA PATRIA QR" class="project-image">
        <button id="backBtn" style="display:none;" onclick="goBack()">Volver</button>
    </main>
    <footer>
        <p>&copy; 2024 Curso de Educación Cívica Cubana</p>
    </footer>
    <script>
        function showInfo(section) {
            const infoDiv = document.getElementById('info');
            const backBtn = document.getElementById('backBtn');
            backBtn.style.display = 'block';

            if (section === 'introduccion') {
                infoDiv.innerHTML = `
                    <h2>Introducción al Civismo</h2>
                    <p>El civismo es el conjunto de actitudes y comportamientos que reflejan el respeto y la responsabilidad hacia los derechos y deberes de los ciudadanos. Conocer la Constitución es fundamental para ejercer una ciudadanía activa y responsable.</p>
                `;
            } else if (section === 'historia') {
                infoDiv.innerHTML = `
                    <h2>Historia de la Constitución de 1940</h2>
                    <p>La Constitución de 1940 fue promulgada el 1 de julio y representa uno de los documentos más importantes en la historia de Cuba. Estableció derechos fundamentales, una estructura de gobierno democrática y un marco para la justicia social.</p>
                `;
            } else if (section === 'derechos') {
                infoDiv.innerHTML = `
                    <h2>Derechos y Libertades</h2>
                    <p>La Constitución de 1940 garantiza derechos fundamentales, como la libertad de expresión, el derecho a la educación, la igualdad ante la ley y el derecho a un juicio justo, siendo un avance significativo para los cubanos.</p>
                `;
            } else if (section === 'gobierno') {
                infoDiv.innerHTML = `
                    <h2>Estructura del Gobierno</h2>
                    <p>La Constitución establece un sistema democrático con separación de poderes: Ejecutivo, Legislativo y Judicial, asegurando un balance y control entre ellos.</p>
                `;
            } else if (section === 'impacto') {
                infoDiv.innerHTML = `
                    <h2>Impacto del Régimen de Fidel Castro</h2>
                    <p>El golpe de Estado de 1952 interrumpió la aplicación de la Constitución de 1940. Aunque no fue derogada, su implementación fue deshabilitada. Fidel Castro no desmanteló la Constitución, pero su régimen ignoró sus principios y limitó las libertades garantizadas.</p>
                `;
            } else if (section === 'conducta') {
                infoDiv.innerHTML = `
                    <h2>Códigos de Conducta Cívica</h2>
                    <p>La participación ciudadana es esencial para una democracia efectiva. Los ciudadanos deben conocer sus derechos y ejercerlos, así como exigir justicia y rendición de cuentas a sus líderes.</p>
                `;
            } else if (section === 'renace') {
                infoDiv.innerHTML = `
                    <h2>RENACE CUBA PATRIA QR</h2>
                    <p>El proyecto RENACE CUBA PATRIA QR tiene como objetivo utilizar códigos QR para difundir información cívica y educativa sobre la Constitución de 1940 y los derechos ciudadanos. A través de la generación de códigos QR, los cubanos podrán acceder a recursos y materiales que les permitan conocer y reivindicar sus derechos.</p>
                    <p>Este proyecto se implementará en el puerto 1030, asegurando que la información esté disponible de manera segura y accesible. Los códigos QR estarán vinculados a contenido que explique cómo el régimen de Fidel Castro incumplió sus promesas y violentó la Constitución de 1940, la cual sigue vigente y nunca ha sido derogada.</p>
                `;
            } else if (section === 'articulos') {
                infoDiv.innerHTML = `
                    <h2>Artículos de la Constitución de 1940</h2>
                    <ul>
                        <li><strong>Artículo 1:</strong> La defensa de la independencia de Cuba es un deber de todos los cubanos.</li>
                        <li><strong>Artículo 2:</strong> La soberanía reside en el pueblo, y el gobierno debe ser ejercido por sus representantes.</li>
                        <li><strong>Artículo 3:</strong> El respeto a los derechos humanos es fundamental para la convivencia pacífica.</li>
                        <li><strong>Artículo 4:</strong> Se garantiza la libertad de expresión y el derecho a la información.</li>
                        <li><strong>Artículo 5:</strong> Todos los ciudadanos tienen derecho a participar en la vida política del país.</li>
                        <li><strong>Artículo 6:</strong> La educación es un derecho fundamental que debe ser garantizado por el Estado.</li>
                        <li><strong>Artículo 7:</strong> Se prohíbe la discriminación en todas sus formas.</li>
                        <li><strong>Artículo 8:</strong> Todos tienen derecho a un juicio justo y a la defensa legal.</li>
                        <li><strong>Artículo 9:</strong> La propiedad privada es inviolable y debe ser protegida por el Estado.</li>
                        <li><strong>Artículo 10:</strong> Se establece la libertad de asociación y de reunión pacífica.</li>
                    </ul>
                `;
            } else if (section === 'conclusiones') {
                infoDiv.innerHTML = `
                    <h2>Conclusiones y Llamado a la Acción</h2>
                    <p>La Constitución de 1940 sigue vigente, y es crucial que los cubanos la conozcan y se comprometan a defender sus derechos. La historia nos enseña que el civismo y la participación son clave para la construcción de un futuro mejor.</p>
                `;
            }
        }

        function goBack() {
            const infoDiv = document.getElementById('info');
            infoDiv.innerHTML = '';
            const backBtn = document.getElementById('backBtn');
            back

