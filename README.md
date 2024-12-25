<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Жаңа жыл құттықтауы</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #1c3d7a, #2a1c4d);
            min-height: 100vh;
            font-family: Arial, sans-serif;
            color: white;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 30px;
            margin: 20px 0;
            animation: cardAppear 1s ease-out;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .header {
            text-align: center;
            font-size: 32px;
            margin-bottom: 30px;
            color: #FFD700;
            animation: glowing 2s infinite;
        }

        .message {
            line-height: 1.8;
            font-size: 18px;
            margin-bottom: 20px;
        }

        .message p {
            margin-bottom: 15px;
        }

        .signature {
            text-align: right;
            margin-top: 30px;
            color: #FFD700;
            font-style: italic;
        }

        .snow {
            color: white;
            font-size: 20px;
            position: fixed;
            top: -20px;
            animation: falling linear infinite;
            z-index: 0;
        }

        @keyframes cardAppear {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes glowing {
            0% { text-shadow: 0 0 5px #FFD700; }
            50% { text-shadow: 0 0 20px #FFD700, 0 0 30px #FFD700; }
            100% { text-shadow: 0 0 5px #FFD700; }
        }

        @keyframes falling {
            0% { transform: translateY(0) rotate(0deg); }
            100% { transform: translateY(110vh) rotate(360deg); }
        }

        .heart {
            display: inline-block;
            color: #ff4d4d;
            animation: heartbeat 1.5s infinite;
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        .highlight {
            color: #FFD700;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <div class="header">
                🎄 Жаңа жыл 2025 🎄
            </div>
            
            <div class="message">
                <p>Жаным бауырым! <span class="heart">❤️</span></p>

                <p>Келіп жеткен Жаңа жыл құтты болсын! Өміріңдегі әрбір сәт жарқын естеліктерге толсын, әр күнің шаттық пен бақытқа толы болсын!</p>

                <p>Саған шынайы жүректен зор денсаулық, сарқылмас қуат, шексіз махаббат пен арман-мақсаттарыңның орындалуын тілеймін.</p>

                <p>Сенің өміріңдегі әрбір жаңа жыл жаңа мүмкіндіктердің есігін ашып, тек жақсылық әкелсін! Сен мен үшін ерекше жансың, өмірімдегі ең жақын серігімсің. Осы жылы да бір-бірімізге тірек болып, талай әдемі сәттерді бірге бөлісейік!</p>

                <p>Саған жаңа жылға мол денсаулық, құнсыз білім, жақсы денсаулық, жүрегіңе өшпес иман тілеймін 😘</p>

                <p>Отбасыңа береке, ата-анаңа бақыт, ата-анаңа сенің қызығыңды көруді нәсіп еткей 🥰</p>

                <p>Алдыға қойған барша арман мақсатыңа жетуге тілектеспін <span class="heart">❤️❤️</span></p>

                <p>Жаман іс әрекеттерің бәрі ескі жылда қалып, Жаңа жылда жаңа өмір бастауды Аллам нәсіп еткей 🤲🏻</p>

                <p>Достығымыз Гауһар тастан қымбат, берекелі мәңгі болғай жәнеде ақша немес басқа бір причина емес тек өлім ажыратқай 😽</p>
