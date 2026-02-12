# Propuesta-para-mi-amor
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres Ser Mi San Valentín, Paula? ❤️</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&family=Great+Vibes&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Dancing Script', cursive;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ffe4e1, #ffb6c1, #ff69b4);
            color: #8b0000;
            overflow-x: hidden;
            animation: fadeIn 2s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
            text-align: center;
            position: relative;
        }
        .roses {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }
        .rose {
            position: absolute;
            color: #ff1493;
            font-size: 2.5rem;
            animation: floatRose 8s linear infinite;
        }
        @keyframes floatRose {
            0% { transform: translateY(100vh) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-100vh) rotate(360deg); opacity: 0; }
        }
        h1, h2 {
            font-family: 'Great Vibes', cursive;
            font-size: 4rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(255,255,255,0.8);
            color: #dc143c;
        }
        p {
            font-size: 1.8rem;
            max-width: 700px;
            line-height: 1.8;
            color: #8b0000;
        }
        .letter {
            background: rgba(255,255,255,0.95);
            color: #8b0000;
            padding: 30px;
            border-radius: 20px;
            max-width: 800px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            animation: slideIn 1s ease-out;
            border: 2px solid #ff69b4;
        }
        @keyframes slideIn {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .promises, .plans {
            background: rgba(255,255,255,0.9);
            padding: 30px;
            border-radius: 20px;
            max-width: 700px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            border: 2px solid #ffb6c1;
        }
        .promises ul, .plans ul {
            list-style: none;
            padding: 0;
        }
        .promises li, .plans li {
            margin: 15px 0;
            font-size: 1.5rem;
            color: #dc143c;
        }
        button {
            background: linear-gradient(45deg, #ff69b4, #ffb6c1);
            color: white;
            border: none;
            padding: 20px 40px;
            font-size: 1.5rem;
            font-family: 'Dancing Script', cursive;
            border-radius: 50px;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
            margin: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }
        button:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 16px rgba(0,0,0,0.4);
        }
        .celebration {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255,192,203,0.9);
            justify-content: center;
            align-items: center;
            z-index: 10;
            animation: confetti 3s ease-in-out;
        }
        @keyframes confetti {
            0% { opacity: 0; }
            50% { opacity: 1; }
            100% { opacity: 1; }
        }
        .celebration h1 {
            font-size: 5rem;
            color: #ff1493;
            animation: bounce 1s infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        .scroll-hint {
            position: absolute;
            bottom: 20px;
            font-size: 1.2rem;
            animation: pulse 2s infinite;
            color: #dc143c;
        }
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }
    </style>
</head>
<body>
    <div class="roses" id="roses"></div>

    <!-- Sección 1: Introducción Romántica -->
    <div class="section" id="intro">
        <h1>¡Hola, Mi Amor Paula! 🌹❤️</h1>
        <p>Maikel aquí, con el corazón latiendo fuerte. Prepárate para un viaje lleno de amor y risas. Baja y descubre por qué eres mi todo. 😘</p>
        <div class="scroll-hint">↓ Sigue bajando, mi reina ↓</div>
    </div>

    <!-- Sección 2: Carta de Amor Larga y Linda -->
    <div class="section" id="letter">
        <h2>Una Carta Solo para Ti, Paula 💌</h2>
        <div class="letter">
            <p>Querida Paula, mi amor eterno,</p>
            <p>Eres el sol que ilumina mis días, la risa que llena mi alma, y el abrazo que me hace sentir en casa. Desde el primer momento, supe que eras tú – mi compañera perfecta, mi aventura favorita. Tus ojos brillan como estrellas, y tu sonrisa... ¡ay, esa sonrisa me derrite! 😍</p>
            <p>Esto no es solo una propuesta; es el comienzo de nuestro San Valentín más mágico. Me siento el hombre más afortunado del mundo por tenerte a mi lado. Imagina noches de risas, besos robados y sueños compartidos. Eres mi amor de verdad, y quiero que este 14 de febrero sea el mejor de nuestras vidas, lleno de sorpresas y ternura. ❤️</p>
            <p>¿Quieres ser mi San Valentín, mi todo, mi siempre? ¡Di que sí y hagamos magia juntos! 🌟</p>
            <p>Con todo mi corazón y un millón de besos,<br>Tu Maikel, que te ama locamente 💕</p>
        </div>
    </div>

    <!-- Sección 3: Promesas Divertidas y Románticas -->
    <div class="section" id="promises">
        <h2>Promesas para Nuestro Amor Divertido 💑</h2>
        <p>Paula, si dices que sí, te prometo risas y amor sin fin. ¡Vamos a ser imparables! 😉</p>
        <div class="promises">
            <ul>
                <li>🌹 Bailar contigo hasta que nos duelan los pies (y luego seguir bailando).</li>
                <li>🍫 Compartir chocolates y besos dulces todos los días.</li>
                <li>🎉 Sorpresas locas, como picnics sorpresa o viajes improvisados.</li>
                <li>❤️ Ser tu compañero en todo: risas, lágrimas y aventuras épicas.</li>
                <li>😘 Hacerte reír tanto que olvides el mundo entero.</li>
            </ul>
        </div>
    </div>

    <!-- Sección 4: Planes Especiales para San Valentín -->
    <div class="section" id="plans">
        <h2>Planes para Nuestro San Valentín Mágico 🎊</h2>
        <p>Paula, imagina esto... ¡Será inolvidable! Esto es solo el inicio de nuestra historia de amor. 🌈</p>
        <div class="plans">
            <ul>
                <li>🍽️ Una cena romántica con velas y tu plato favorito (y yo cocinando... o pidiendo delivery 😉).</li>
                <li>💌 Cartas escondidas por toda la casa con mensajes de amor.</li>
                <li>🌟 Un paseo bajo las estrellas, contándonos secretos y riendo.</li>
                <li>🎁 Regalos tontos y dulces que te hagan sonreír.</li>
                <li>❤️ Y el comienzo de una vida llena de amor eterno, risas y felicidad.</li>
            </ul>
        </div>
    </div>

    <!-- Sección 5: Propuesta Final Divertida -->
    <div class="section" id="proposal">
        <h2>La Gran Pregunta, Mi Amor 💍</h2>
        <p>Paula, ¿estás lista para ser mi San Valentín y mi todo? ¡Haz clic y hagamos historia! 😍</p>
        <button id="yesBtn">¡Sí, quiero! ❤️ Te amo</button>
        <button id="noBtn">No... (pero ¡por favor di que sí! 😘)</button>
    </div>

    <!-- Celebración Divertida -->
    <div class="celebration" id="celebration">
        <div>
            <h1>¡Felicidades, Paula! 🎉❤️</h1>
            <p>Eres mi San Valentín perfecta, mi amor de la vida. Esto es solo el comienzo – me siento afortunado de pasarlo juntos. ¡Te amo más que a las rosas y las estrellas! 🌹⭐</p>
            <button onclick="location.reload()">Volver y releer todo 💕</button>
        </div>
    </div>

    <script>
        // Generar rosas flotantes
        function createRoses() {
            const rosesContainer = document.getElementById('roses');
            for (let i = 0; i < 25; i++) {
                const rose = document.createElement('div');
                rose.className = 'rose';
                rose.innerHTML = '🌹';
                rose.style.left = Math.random() * 100 + '%';
                rose.style.animationDelay = Math.random() * 8 + 's';
                rosesContainer.appendChild(rose);
            }
        }
        createRoses();

        // Lógica de botones
        document.getElementById('yesBtn').addEventListener('click', () => {
            document.getElementById('celebration').style.display = 'flex';
        });
        document.getElementById('noBtn').addEventListener('click', () => {
            alert('¡Por favor, reconsidera, Paula! ❤️ Eres mi todo y mi diversión favorita.');
        });

        // Música opcional (descomenta y agrega un archivo MP3 romántico/divertido)
        // const audio = new Audio('tu-cancion-romantica.mp3');
        // audio.play();
    </script>
</body>
</html>
