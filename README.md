<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recibida de Magalí Ximena Chirino González</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Alex+Brush&family=Montserrat:wght@300;400;500;700&family=Playfair+Display:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
    <!-- FontAwesome para Íconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary: #d4a373;
            --accent-dark: #b56576;
            --accent: #e5989b;
            --text-dark: #3d342e;
            --text-light: #6d594f;
            --bg-soft: #fff5f5;
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            color: var(--text-dark);
            background-color: var(--bg-soft);
            line-height: 1.6;
        }

        /* Hero / Bienvenida */
        .hero {
            position: relative;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(135deg, #ffe5ec 0%, #fff0f3 100%);
            padding: 20px;
            overflow: hidden;
        }

        .flower-bg {
            position: absolute;
            font-size: 2.5rem;
            opacity: 0.2;
            animation: float 6s ease-in-out infinite;
        }
        .f1 { top: 10%; left: 10%; }
        .f2 { top: 20%; right: 12%; animation-delay: 1.5s; font-size: 3.5rem; }
        .f3 { bottom: 15%; left: 8%; animation-delay: 3s; }
        .f4 { bottom: 20%; right: 15%; animation-delay: 4.5s; }

        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(10deg); }
        }

        .hero-subtitle-top {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-size: 1.3rem;
            color: var(--accent-dark);
            margin-bottom: 15px;
            letter-spacing: 2px;
        }

        .hero-title {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 10px;
        }

        .hero-profession {
            font-family: 'Alex Brush', cursive;
            font-size: 3.5rem;
            color: var(--accent-dark);
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--accent-dark);
            color: var(--white);
            text-decoration: none;
            border-radius: 30px;
            font-weight: 500;
            box-shadow: 0 4px 15px rgba(181, 101, 118, 0.3);
            transition: all 0.3s ease;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(181, 101, 118, 0.5);
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        section {
            background: var(--white);
            margin: 40px auto;
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.03);
            text-align: center;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.2rem;
            color: var(--accent-dark);
            margin-bottom: 20px;
        }

        h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 2px;
            background-color: var(--accent);
            margin: 10px auto 0 auto;
        }

        .intro-text {
            font-size: 1.1rem;
            color: var(--text-light);
            margin-bottom: 15px;
        }

        /* Cuenta Regresiva */
        .countdown-container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            margin: 30px 0;
        }

        .countdown-box {
            background: var(--bg-soft);
            padding: 15px 10px;
            border-radius: 12px;
            border: 1px solid rgba(229, 152, 155, 0.3);
        }

        .countdown-number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--accent-dark);
            display: block;
        }

        .countdown-label {
            font-size: 0.8rem;
            text-transform: uppercase;
            color: var(--text-light);
        }

        /* Tarjetas de Eventos */
        .event-card {
            background: var(--bg-soft);
            padding: 25px;
            border-radius: 15px;
            margin: 25px 0;
            text-align: left;
            border-left: 4px solid var(--accent-dark);
        }

        .event-card h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .event-date {
            font-weight: 700;
            color: var(--accent-dark);
            margin-bottom: 8px;
            display: block;
        }

        .event-location {
            font-size: 0.95rem;
            color: var(--text-light);
            margin-bottom: 15px;
        }

        .btn-secondary {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 20px;
            border: 2px solid var(--accent-dark);
            color: var(--accent-dark);
            text-decoration: none;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
            transition: all 0.3s;
        }

        .btn-secondary:hover {
            background-color: var(--accent-dark);
            color: var(--white);
        }

        .whatsapp-btn {
            background-color: #25d366;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.3);
        }
        .whatsapp-btn:hover { background-color: #1ebd57; }

        .gift-info {
            background: var(--bg-soft);
            padding: 20px;
            border-radius: 12px;
            display: inline-block;
            width: 100%;
            max-width: 400px;
            margin-top: 20px;
        }

        .alias-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            margin-top: 10px;
            background: var(--white);
            padding: 10px;
            border-radius: 8px;
            border: 1px dashed var(--accent);
        }

        .alias-text {
            font-family: monospace;
            font-size: 1.2rem;
            font-weight: bold;
        }

        .btn-copy {
            background: none;
            border: none;
            color: var(--accent-dark);
            cursor: pointer;
            font-size: 1rem;
        }

        .toast {
            position: fixed;
            bottom: -50px;
            left: 50%;
            transform: translateX(-50%);
            background: var(--text-dark);
            color: var(--white);
            padding: 10px 20px;
            border-radius: 20px;
            transition: bottom 0.3s;
            z-index: 1000;
        }

        .toast.show { bottom: 30px; }

        footer {
            text-align: center;
            padding: 40px 20px;
            color: var(--text-light);
        }

        .footer-name {
            font-family: 'Alex Brush', cursive;
            font-size: 2.5rem;
            color: var(--accent-dark);
        }

        @media (max-width: 600px) {
            .hero-title { font-size: 2.2rem; }
            .hero-profession { font-size: 2.6rem; }
            .countdown-container { grid-template-columns: repeat(2, 1fr); }
        }
    </style>
</head>
<body>

    <header class="hero">
        <div class="flower-bg f1">🌸</div><div class="flower-bg f2">🌷</div>
        <div class="flower-bg f3">🌺</div><div class="flower-bg f4">🌹</div>
        <p class="hero-subtitle-top">✨ Ayer llorando · Hoy brillando ✨</p>
        <h1 class="hero-title">Magalí Ximena Chirino González</h1>
        <p class="hero-profession">Licenciada en Trabajo Social</p>
        <a href="#bienvenida" class="btn"><i class="fa-regular fa-envelope"></i> Ver Invitación</a>
    </header>

    <div class="container" id="bienvenida">
        
        <section>
            <h2>¡Me recibo! 🎓</h2>
            <p class="intro-text">Después de años de esfuerzo, noches de estudio y mucha dedicación, llegó el momento de cosechar los frutos.</p>
            <p class="intro-text">Gracias por ser parte de mi camino.</p>
            <p class="intro-text">Espero que puedas acompañarme en este momento tan especial y celebrar conmigo este gran logro.</p>
        </section>

        <section>
            <h2>⏳ Cuenta Regresiva</h2>
            <p class="intro-text">Faltan:</p>
            <div class="countdown-container">
                <div class="countdown-box"><span class="countdown-number" id="days">0</span><span class="countdown-label">Días</span></div>
                <div class="countdown-box"><span class="countdown-number" id="hours">0</span><span class="countdown-label">Horas</span></div>
                <div class="countdown-box"><span class="countdown-number" id="minutes">0</span><span class="countdown-label">Minutos</span></div>
                <div class="countdown-box"><span class="countdown-number" id="seconds">0</span><span class="countdown-label">Segundos</span></div>
            </div>
            <p class="intro-text">para el gran día.</p>
        </section>

        <section>
            <h2>📅 Cronograma de Festejos</h2>
            
            <!-- MODIFICADO: Defensa de Tesis con los textos exactos solicitados -->
            <div class="event-card">
                <h3>🎓 Defensa de Tesis</h3>
                <span class="event-date">Jueves 25 de junio – 17:00 hs</span>
                <p class="event-location"><i class="fa-solid fa-location-dot"></i> <strong>Ubicación:</strong> Facultad de Ciencias Sociales – UNSJ<br>Av. Ignacio de la Roza 727 Oeste</p>
                <p class="intro-text" style="font-size: 0.95rem; margin-bottom: 15px;">Defensa de tesis, fotos, tirada y caravana.</p>
                <a href="https://maps.google.com/?q=Facultad+de+Ciencias+Sociales+UNSJ+Av+Ignacio+de+la+Roza+727+Oeste" target="_blank" class="btn-secondary"><i class="fa-solid fa-map-location-dot"></i> Cómo llegar</a>
            </div>

            <!-- MODIFICADO: Fiesta de Celebración -->
            <div class="event-card">
                <h3>🥂 Fiesta de Celebración</h3>
                <span class="event-date">Sábado 27 de junio – 22:00 hs (Cena) | 01:00 hs (Fiesta)</span>
                <p class="event-location"><i class="fa-solid fa-location-dot"></i> <strong>Ubicación:</strong> Club Banco Nación</p>
                <p class="intro-text" style="font-size: 0.95rem;">Una noche para celebrar juntos este gran paso y disfrutar entre familiares y amigos.</p>
            </div>
        </section>

        <section>
            <h2>📱 Confirmación de Asistencia</h2>
            <p class="intro-text">Tu presencia es muy importante para mí.</p>
            <p class="intro-text">Por favor confirmá tu asistencia por WhatsApp</p>
            <a href="https://wa.me/542645598519?text=Hola%20Magalí,%20confirmo%20mi%20asistencia%20a%20tu%20recibida%20🎓" target="_blank" class="btn whatsapp-btn"><i class="fa-brands fa-whatsapp"></i> Confirmar Asistencia</a>
        </section>

        <section>
            <h2>🎁 Mesa de Regalos</h2>
            <p class="intro-text">Tu compañía es el mejor regalo.</p>
            <div class="gift-info">
                <p><strong>Transferencia por Mercado Pago</strong></p>
                <div class="alias-container">
                    <span class="alias-text" id="alias">sitara99</span>
                    <button class="btn-copy" onclick="copyAlias()"><i class="fa-regular fa-copy"></i> Copiar</button>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <h2>✨ Gracias ✨</h2>
        <p class="intro-text">¡Te espero para celebrar juntos este sueño cumplido!</p>
        <p class="footer-name">Magalí</p>
    </footer>

    <div class="toast" id="toast">¡Alias copiado con éxito!</div>

    <script>
        // MODIFICADO: Cuenta regresiva desde el Jueves 25 de Junio a las 17:00 hs
        const targetDate = new Date("June 25, 2026 17:00:00").getTime();

        const countdownInterval = setInterval(function() {
            const now = new Date().getTime();
            const difference = targetDate - now;

            if (difference < 0) {
                clearInterval(countdownInterval);
                document.getElementById("days").innerText = "0";
                document.getElementById("hours").innerText = "0";
                document.getElementById("minutes").innerText = "0";
                document.getElementById("seconds").innerText = "0";
                return;
            }

            const d = Math.floor(difference / (1000 * 60 * 60 * 24));
            const h = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const m = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
            const s = Math.floor((difference % (1000 * 60)) / 1000);

            document.getElementById("days").innerText = d;
            document.getElementById("hours").innerText = h;
            document.getElementById("minutes").innerText = m;
            document.getElementById("seconds").innerText = s;
        }, 1000);

        function copyAlias() {
            const aliasText = document.getElementById("alias").innerText;
            navigator.clipboard.writeText(aliasText).then(() => {
                const toast = document.getElementById("toast");
                toast.classList.add("show");
                setTimeout(() => { toast.classList.remove("show"); }, 2500);
            });
        }
    </script>
</body>
</html>
