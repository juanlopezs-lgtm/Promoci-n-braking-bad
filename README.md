# Promoci-n-braking-bad
hola hombre bienvenido a mi pagina
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>!!! CAP'N COOK'S GREEN HOUSE - YO BITCH !!!</title>
    <style>
        /* ESTÉTICA RETRO GEOCITIES */
        body {
            background-color: #000;
            background-image: url('https://www.transparenttextures.com/patterns/asfalt-dark.png');
            color: #0f0;
            font-family: "Comic Sans MS", "Arial", sans-serif;
            cursor: url('https://cur.cursors-4u.net/symbols/sym-1/sym49.cur'), auto;
            overflow-x: hidden;
            margin: 0;
            padding: 20px;
            border: 10px double #333;
        }

        /* EFECTO CRT Y SCANLINES */
        body::before {
            content: " ";
            display: block;
            position: fixed;
            top: 0; left: 0; bottom: 0; right: 0;
            background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%), linear-gradient(90deg, rgba(255, 0, 0, 0.06), rgba(0, 255, 0, 0.02), rgba(0, 0, 255, 0.06));
            z-index: 9999;
            pointer-events: none;
            background-size: 100% 2px, 3px 100%;
        }

        header {
            text-align: center;
            border: 5px solid #ff0000;
            padding: 20px;
            background: url('https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJqZnd4bmZ6eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHgmZXA9djFfaW50ZXJuYWxfZ2lmX2J5X2lkJmN0PWc/3o7TKMGpxxcaOXYT60/giphy.gif');
            margin-bottom: 20px;
        }

        h1 {
            font-family: "Impact", sans-serif;
            font-size: 50px;
            color: #adff2f;
            text-shadow: 5px 5px #ff0000, -5px -5px #0000ff;
            text-transform: uppercase;
            letter-spacing: 5px;
        }

        .blink {
            animation: blinker 0.6s linear infinite;
        }

        @keyframes blinker {
            50% { opacity: 0; }
        }

        marquee {
            background: #ffff00;
            color: #000;
            font-weight: bold;
            font-size: 20px;
            border-top: 2px solid #fff;
            border-bottom: 2px solid #fff;
        }

        /* WINAMP PLAYER */
        #winamp-container {
            position: fixed;
            bottom: 10px;
            right: 10px;
            width: 275px;
            background: #333;
            border: 2px solid #999;
            padding: 5px;
            z-index: 1000;
            box-shadow: 5px 5px 0px #000;
        }

        .winamp-title {
            background: #000080;
            color: white;
            font-size: 12px;
            padding: 2px;
            font-family: sans-serif;
        }

        .winamp-display {
            background: #000;
            color: #0f0;
            font-family: 'Courier New', monospace;
            height: 40px;
            padding: 5px;
            margin: 5px 0;
            border: 1px inset #666;
            font-size: 11px;
        }

        /* SECCIONES */
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .section {
            background: rgba(0, 0, 0, 0.85);
            border: 4px ridge #adff2f;
            margin: 10px;
            padding: 15px;
            width: 45%;
            min-width: 300px;
        }

        .product-card {
            border-bottom: 2px dashed #ff0;
            padding: 10px;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }

        .product-img {
            width: 80px;
            height: 80px;
            border: 2px solid #fff;
            margin-right: 15px;
        }

        /* SHOUTOUTS */
        .comment {
            font-size: 12px;
            background: #111;
            padding: 5px;
            margin-bottom: 5px;
            border-left: 3px solid #f0f;
        }

        /* CONTACT FORM */
        input, textarea {
            background: #222;
            color: #0f0;
            border: 2px solid #adff2f;
            width: 90%;
            margin-bottom: 10px;
            font-family: "Courier New";
        }

        button {
            background: #ff0000;
            color: white;
            font-weight: bold;
            padding: 10px;
            border: 4px outset #800;
            cursor: pointer;
        }

        button:active { border-style: inset; }

        /* GIFS E IMÁGENES */
        .gif-decoration {
            width: 50px;
            vertical-align: middle;
        }

        .lab-gallery img {
            width: 100px;
            height: 100px;
            filter: grayscale(0.5) contrast(1.5);
            border: 2px solid gold;
            margin: 5px;
        }

        .counter {
            background: #000;
            color: #f00;
            font-family: "Courier New";
            font-size: 24px;
            padding: 5px;
            border: 2px solid #555;
            display: inline-block;
        }

        /* POPUP */
        #popup {
            position: fixed;
            top: 20%;
            left: 30%;
            background: #c0c0c0;
            border: 3px outset #fff;
            color: #000;
            padding: 20px;
            z-index: 10000;
            box-shadow: 10px 10px 0px rgba(0,0,0,0.5);
        }

    </style>
</head>
<body>

    <header>
        <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJqZnd4bmZ6eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHgmZXA9djFfaW50ZXJuYWxfZ2lmX2J5X2lkJmN0PWc/3o7TKMGpxxcaOXYT60/giphy.gif" class="gif-decoration" alt="fire">
        <h1><span class="blink">!!! CAP'N COOK'S GREEN HOUSE !!!</span></h1>
        <p style="color: yellow; font-weight: bold;">YO MR. WHITE! WE GOT THAT FIRE, BITCH! 24/7 EN ALBUQUERQUE!</p>
    </header>

    <marquee scrollamount="10">
        NUEVO DROP: BLUE CHRONIC DISPONIBLE YA -- SOLO EFECTIVO -- NADA DE POLIS -- SKINNY PETE DICE QUE ESTÁ BOMBA -- 
    </marquee>

    <div class="container">
        <!-- SECCIÓN PRODUCTOS -->
        <div class="section">
            <h2 style="color: #ff00ff; text-decoration: underline;">$ THE GOODS $</h2>
            
            <div class="product-card">
                <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJqZnd4bmZ6eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHgmZXA9djFfaW50ZXJuYWxfZ2lmX2J5X2lkJmN0PWc/3o7TKL96jK652O93gA/giphy.gif" class="product-img" alt="weed">
                <div>
                    <b style="color: #0ff;">HEISEN-KUSH (El Patrón)</b><br>
                    <span style="font-size: 12px;">Pega como camión de 18 ruedas. Pureza del 99%.</span><br>
                    <b style="color: #f00;">$50 / gramo <img src="https://web.archive.org/web/20090830045839/http://geocities.com/Athens/6000/new2.gif" width="30"></b>
                </div>
            </div>

            <div class="product-card">
                <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJqZnd4bmZ6eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHh4eHgmZXA9djFfaW50ZXJuYWxfZ2lmX2J5X2lkJmN0PWc/3o7TKVUn7iM8FMEU24/giphy.gif" class="product-img" alt="weed">
                <div>
                    <b style="color: #0ff;">BLUE CHRONIC</b><br>
                    <span style="font-size: 12px;">Receta secreta con polvo de chili. ¡Pica pero rico!</span><br>
                    <b style="color: #f00;">$35 / gramo</b>
                </div>
            </div>
            
            <center>
                <img src="https://web.archive.org/web/20090804113154/http://geocities.com/SouthBeach/Cove/8233/flame.gif">
                <img src="https://web.archive.org/web/20091027005003/http://geocities.com/Area51/Chamber/1815/ani_skull.gif">
                <img src="https://web.archive.org/web/20090804113154/http://geocities.com/SouthBeach/Cove/8233/flame.gif">
            </center>
        </div>

        <!-- SECCIÓN GALERÍA -->
        <div class="section">
            <h2 style="color: #adff2f;">LAB PHOTOS (TOP SECRET)</h2>
            <div class="lab-gallery">
                <!-- Placeholders que evocan a la serie -->
                <img src="https://m.media-amazon.com/images/M/MV5BMjA3NTAwNjc0N15BMl5BanBnXkFtZTgwNzE1OTQyMDI@._V1_.jpg" alt="Jesse">
                <img src="https://i.imgur.com/vS6o89I.jpeg" alt="RV">
                <img src="https://i.imgur.com/I2UscM4.jpeg" alt="Money">
                <img src="https://i.imgur.com/5V3nK9j.jpeg" alt="Smoke">
            </div>
            <p style="font-size: 10px;">No tomes capturas o te busco con Tuco.</p>
        </div>

        <!-- SECCIÓN SHOUTOUTS -->
        <div class="section">
            <h2 style="color: #ffff00;">SHOUTOUTS !!!</h2>
            <div class="comment">
                <b>Badger:</b> "Yo Cap'n, esa Blue es lo mejor que he probado desde el concierto de Twaughthammer!"
            </div>
            <div class="comment">
                <b>Skinny Pete:</b> "Church, yo! Esto es arte, no es weed."
            </div>
            <div class="comment">
                <b>Tuco_66:</b> "TIGHT! TIGHT! TIGHT! TRAEME MÁS O YA SABES."
            </div>
            <div class="comment">
                <b>Combo (RIP):</b> "Representing the ABQ, yo!"
            </div>
        </div>

        <!-- SECCIÓN CONTACTO -->
        <div class="section">
            <h2 style="color: #f00;">CONTACTO (NO POLIS)</h2>
            <p style="font-size: 11px;">"NO ESCRIBAS MUCHO, LA DEA NOS MIRA"</p>
            <form onsubmit="alert('ENVIADO AL PAGER DE JESSE... ESPERA EN EL CALLEJÓN'); return false;">
                ALIAS: <input type="text" placeholder="Tu nombre en la calle..."><br>
                PAGER #: <input type="text" placeholder="555-0199..."><br>
                PEDIDO: <textarea rows="3"></textarea><br>
                <center><button type="submit">SEND TO THE RV</button></center>
            </form>
        </div>
    </div>

    <center style="margin-top: 50px;">
        <div class="counter">VISITOR #000420</div><br>
        <img src="https://web.archive.org/web/20091027083236/http://geocities.com/h_peraza/ie_logo.gif" width="100"><br>
        <p style="font-size: 10px;">BEST VIEWED ON INTERNET EXPLORER 6.0 AT 800x600 RESOLUTION</p>
        <p>&copy; 2003 CAP'N COOK PRODUCTIONS - ALL WRONGS RESERVED</p>
    </center>

    <!-- WINAMP PLAYER FALSO -->
    <div id="winamp-container">
        <div class="winamp-title">WINAMP 2.91 - [Jesse_Pinkman_Beats.mp3]</div>
        <div class="winamp-display">
            <div id="song-title">1. Heisen-Rap (Underground Remix)</div>
            <div style="font-size: 9px; color: #0a0;">02:45 / 32kbps / 44khz</div>
            <div id="viz" style="letter-spacing: 2px;">|||||i||||ii|||i|||iiii|||</div>
        </div>
        <div style="text-align: center;">
            <button onclick="playAudio()" style="padding: 2px 5px; font-size: 10px;">PLAY</button>
            <button style="padding: 2px 5px; font-size: 10px;">PAUSE</button>
            <button style="padding: 2px 5px; font-size: 10px;">STOP</button>
        </div>
    </div>

    <!-- POPUP MOLESTO -->
    <div id="popup">
        <div style="background: #000080; color: white; padding: 2px; font-weight: bold;">
            SYSTEM ALERT !!
            <span onclick="document.getElementById('popup').style.display='none'" style="float:right; cursor:pointer;">[X]</span>
        </div>
        <div style="padding: 10px; text-align: center;">
            <img src="https://web.archive.org/web/20090803140510/http://geocities.com/SunsetStrip/Towers/4230/police_car_light_whipping.gif" width="50"><br>
            <b>YO! NEW DROP AVAILABLE!</b><br>
            ¿Quieres probar la magia azul?<br><br>
            <button onclick="document.getElementById('popup').style.display='none'">OBVIO, BITCH!</button>
        </div>
    </div>

    <script>
        // Efecto de sonido al azar (simulado)
        document.body.addEventListener('click', function() {
            console.log("Yo, watch where you clicking!");
        });

        // Animación del ecualizador de Winamp
        setInterval(function() {
            let bars = "";
            for(let i=0; i<20; i++) {
                bars += Math.random() > 0.5 ? "|" : "i";
            }
            document.getElementById('viz').innerHTML = bars;
        }, 150);

        function playAudio() {
            alert("SISTEMA: Reproduciendo 'Hustle_Albuquerque_V1.mp3' a bajo volumen para no alertar a los vecinos...");
        }

        // Simular error de Windows XP a veces
        if(Math.random() > 0.8) {
            setTimeout(() => {
                alert("ERROR 404: POLICE DETECTED... Just kidding, yo! Smoke some more.");
            }, 5000);
        }
    </script>
</body>
</html>
