# -RESCATANDO-LA-CONSTITUCI-N-UN-CAMINO-HACIA-LA-LIBERTAD-
"RESCATANDO LA CONSTITUCIÓN: UN CAMINO HACIA LA LIBERTAD 🗝️📜"
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Constitución de 1940: Educación Cívica Cubana</title>
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
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <h1><i class="fas fa-balance-scale"></i> La Constitución de 1940: Educación Cívica Cubana</h1>
        <nav>
            <button onclick="showInfo('historia')"><i class="fas fa-book"></i> Historia</button>
            <button onclick="showInfo('derechos')"><i class="fas fa-gavel"></i> Derechos y Libertades</button>
            <button onclick="showInfo('gobierno')"><i class="fas fa-building"></i> Estructura del Gobierno</button>
            <button onclick="showFAQ()"><i class="fas fa-question-circle"></i> Preguntas Frecuentes</button>
        </nav>
    </header>
    <main>
        <div id="info"></div>
        <button id="backBtn" style="display:none;" onclick="goBack()">Volver</button>
    </main>
    <footer>
        <p>&copy; 2024 Educación Cívica Cubana</p>
    </footer>
    <script>
        function showInfo(section) {
            const infoDiv = document.getElementById('info');
            const backBtn = document.getElementById('backBtn');
            backBtn.style.display = 'block';

            if (section === 'historia') {
                infoDiv.innerHTML = '<h2>Historia de la Constitución de 1940</h2><p>La Constitución de 1940 fue un importante avance en los derechos civiles en Cuba, estableciendo principios democráticos y garantizando libertades fundamentales.</p>';
            } else if (section === 'derechos') {
                infoDiv.innerHTML = '<h2>Derechos y Libertades</h2><p>Esta Constitución garantiza derechos fundamentales como la libertad de expresión, el derecho a la educación y la igualdad ante la ley.</p>';
            } else if (section === 'gobierno') {
                infoDiv.innerHTML = '<h2>Estructura del Gobierno</h2><p>La Constitución de 1940 estableció un sistema democrático con separación de poderes: Ejecutivo, Legislativo y Judicial.</p>';
            }
        }

        function goBack() {
            const infoDiv = document.getElementById('info');
            const backBtn = document.getElementById('backBtn');
            infoDiv.innerHTML = '';
            backBtn.style.display = 'none';
        }

        function showFAQ() {
            const infoDiv = document.getElementById('info');
            infoDiv.innerHTML = `
                <h2>Preguntas Frecuentes</h2>
                <ul>
                    <li><strong>¿La Constitución de 1940 sigue vigente?</strong> La Constitución de 1940 fue derogada por el régimen de Fidel Castro en 1959.</li>
                    <li><strong>¿Cuáles son los principales derechos garantizados?</strong> Derechos como la libertad de expresión, el derecho a un juicio justo y la propiedad privada.</li>
                    <li><strong>¿Qué promesas hizo Fidel Castro respecto a la Constitución?</strong> Fidel Castro prometió respetar los derechos humanos y la constitución, pero estas promesas no se han cumplido.</li>
                </ul>
            `;
        }
    </script>
</body>
</html>
