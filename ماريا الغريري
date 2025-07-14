<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ماريا الغريري - الحقيقة المظلمة</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Creepster&family=Nosifer&family=Changa:wght@300;400;600;700&family=Amiri:wght@400;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Amiri', 'Changa', serif;
            background: #000;
            color: #fff;
            overflow: hidden;
            position: relative;
            height: 100vh;
            cursor: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20"><circle cx="10" cy="10" r="8" fill="darkred" opacity="0.7"/></svg>'), auto;
        }

        .matrix-rain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            background: 
                linear-gradient(0deg, transparent 24%, rgba(139, 0, 0, 0.05) 25%, rgba(139, 0, 0, 0.05) 26%, transparent 27%, transparent 74%, rgba(139, 0, 0, 0.05) 75%, rgba(139, 0, 0, 0.05) 76%, transparent 77%, transparent),
                linear-gradient(90deg, transparent 24%, rgba(139, 0, 0, 0.05) 25%, rgba(139, 0, 0, 0.05) 26%, transparent 27%, transparent 74%, rgba(139, 0, 0, 0.05) 75%, rgba(139, 0, 0, 0.05) 76%, transparent 77%, transparent);
            animation: matrix 20s linear infinite;
        }

        @keyframes matrix {
            0% { transform: translate(0, 0); }
            100% { transform: translate(-50px, -50px); }
        }

        .blood-drip {
            position: absolute;
            width: 2px;
            height: 100px;
            background: linear-gradient(to bottom, transparent, #8b0000, #ff0000);
            animation: drip 3s linear infinite;
        }

        @keyframes drip {
            0% { transform: translateY(-100px); opacity: 0; }
            50% { opacity: 1; }
            100% { transform: translateY(100vh); opacity: 0; }
        }

        .fog-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(ellipse at center, transparent 0%, rgba(0, 0, 0, 0.9) 70%),
                radial-gradient(ellipse at 80% 20%, rgba(139, 0, 0, 0.3) 0%, transparent 40%),
                radial-gradient(ellipse at 20% 80%, rgba(75, 0, 130, 0.2) 0%, transparent 40%);
            z-index: 2;
            animation: fogMove 8s ease-in-out infinite;
        }

        @keyframes fogMove {
            0%, 100% { opacity: 0.8; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.1); }
        }

        .ancient-symbols {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 3;
            pointer-events: none;
        }

        .symbol {
            position: absolute;
            font-size: 3rem;
            color: #8b0000;
            text-shadow: 0 0 20px #ff0000, 0 0 30px #ff4444;
            animation: symbolFloat 6s ease-in-out infinite;
            opacity: 0.6;
        }

        @keyframes symbolFloat {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }

        .pentagram {
            position: absolute;
            width: 80px;
            height: 80px;
            background: transparent;
            border: 3px solid #8b0000;
            clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
            animation: pentagramSpin 4s linear infinite;
            box-shadow: 0 0 30px #8b0000, inset 0 0 30px #8b0000;
        }

        @keyframes pentagramSpin {
            0% { transform: rotate(0deg); filter: brightness(1); }
            50% { transform: rotate(180deg); filter: brightness(1.5); }
            100% { transform: rotate(360deg); filter: brightness(1); }
        }

        .main-container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            position: relative;
            z-index: 10;
            background: 
                radial-gradient(circle at 50% 50%, rgba(139, 0, 0, 0.1) 0%, transparent 70%),
                linear-gradient(45deg, rgba(0, 0, 0, 0.8) 0%, rgba(20, 0, 0, 0.9) 100%);
            backdrop-filter: blur(2px);
        }

        .ornate-border {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 600px;
            height: 400px;
            border: 3px solid #8b0000;
            border-image: linear-gradient(45deg, #8b0000, #ff0000, #8b0000) 1;
            background: 
                linear-gradient(45deg, rgba(139, 0, 0, 0.1) 0%, rgba(0, 0, 0, 0.8) 100%);
            backdrop-filter: blur(5px);
            box-shadow: 
                0 0 50px #8b0000,
                inset 0 0 50px rgba(139, 0, 0, 0.3);
            animation: borderPulse 3s ease-in-out infinite;
        }

        @keyframes borderPulse {
            0%, 100% { 
                box-shadow: 
                    0 0 50px #8b0000,
                    inset 0 0 50px rgba(139, 0, 0, 0.3);
            }
            50% { 
                box-shadow: 
                    0 0 80px #ff0000,
                    inset 0 0 80px rgba(255, 0, 0, 0.5);
            }
        }

        .title {
            font-family: 'Nosifer', cursive;
            font-size: 3.5rem;
            background: linear-gradient(45deg, #8b0000, #ff0000, #ff6666, #8b0000);
            background-size: 400% 400%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-shadow: 0 0 30px #ff0000;
            margin-bottom: 2rem;
            animation: titleAnimation 4s ease-in-out infinite, gradientShift 3s ease-in-out infinite;
            position: relative;
        }

        @keyframes titleAnimation {
            0%, 100% { 
                transform: scale(1);
                filter: brightness(1);
            }
            50% { 
                transform: scale(1.05);
                filter: brightness(1.3);
            }
        }

        @keyframes gradientShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .subtitle {
            font-size: 1.8rem;
            color: #ff6666;
            margin-bottom: 3rem;
            text-align: center;
            text-shadow: 0 0 15px #ff0000;
            animation: subtitleGlow 2s ease-in-out infinite alternate;
            letter-spacing: 2px;
        }

        @keyframes subtitleGlow {
            0% { 
                text-shadow: 0 0 15px #ff0000;
                opacity: 0.8;
            }
            100% { 
                text-shadow: 0 0 25px #ff0000, 0 0 35px #ff4444;
                opacity: 1;
            }
        }

        .start-button {
            background: linear-gradient(45deg, #1a0000, #8b0000, #ff0000, #8b0000, #1a0000);
            background-size: 400% 400%;
            color: white;
            border: 2px solid #8b0000;
            padding: 20px 50px;
            font-size: 1.4rem;
            font-family: 'Amiri', serif;
            font-weight: 700;
            border-radius: 15px;
            cursor: pointer;
            position: relative;
            overflow: hidden;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 3px;
            box-shadow: 
                0 0 40px #8b0000,
                inset 0 0 40px rgba(139, 0, 0, 0.3);
            animation: buttonAnimation 3s ease-in-out infinite;
        }

        @keyframes buttonAnimation {
            0%, 100% { 
                background-position: 0% 50%;
                transform: scale(1);
            }
            50% { 
                background-position: 100% 50%;
                transform: scale(1.05);
            }
        }

        .start-button:hover {
            background: linear-gradient(45deg, #ff0000, #ff4444, #ffaaaa, #ff4444, #ff0000);
            box-shadow: 
                0 0 80px #ff0000,
                inset 0 0 80px rgba(255, 0, 0, 0.5);
            transform: scale(1.1);
            border-color: #ff0000;
        }

        .start-button::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            transform: rotate(45deg);
            animation: buttonShine 2s linear infinite;
        }

        @keyframes buttonShine {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }

        .confirmation-screen {
            display: none;
            text-align: center;
            position: relative;
        }

        .confirmation-text {
            font-size: 2rem;
            margin-bottom: 3rem;
            color: #ff6666;
            text-shadow: 0 0 20px #ff0000;
            animation: confirmationPulse 1.5s ease-in-out infinite;
            line-height: 1.6;
        }

        @keyframes confirmationPulse {
            0%, 100% { 
                transform: scale(1);
                color: #ff6666;
            }
            50% { 
                transform: scale(1.02);
                color: #ff0000;
            }
        }

        .button-group {
            display: flex;
            gap: 40px;
            justify-content: center;
        }

        .yes-button, .no-button {
            padding: 15px 40px;
            font-size: 1.3rem;
            font-family: 'Amiri', serif;
            font-weight: 700;
            border: 2px solid;
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 2px;
            position: relative;
            overflow: hidden;
        }

        .yes-button {
            background: linear-gradient(45deg, #8b0000, #ff0000);
            color: white;
            border-color: #8b0000;
            box-shadow: 0 0 30px #8b0000;
        }

        .no-button {
            background: linear-gradient(45deg, #333, #666);
            color: white;
            border-color: #666;
            box-shadow: 0 0 30px #333;
        }

        .yes-button:hover {
            background: linear-gradient(45deg, #ff0000, #ff4444);
            box-shadow: 0 0 50px #ff0000;
            transform: scale(1.1);
        }

        .no-button:hover {
            background: linear-gradient(45deg, #666, #999);
            box-shadow: 0 0 50px #666;
            transform: scale(1.1);
        }

        .horror-screen {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: #000;
            z-index: 1000;
            overflow: hidden;
        }

        .tv-static {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                repeating-linear-gradient(
                    0deg,
                    transparent,
                    transparent 2px,
                    rgba(255, 255, 255, 0.03) 2px,
                    rgba(255, 255, 255, 0.03) 4px
                ),
                repeating-linear-gradient(
                    90deg,
                    transparent,
                    transparent 2px,
                    rgba(255, 0, 0, 0.03) 2px,
                    rgba(255, 0, 0, 0.03) 4px
                );
            animation: staticNoise 0.1s linear infinite;
        }

        @keyframes staticNoise {
            0% { transform: translateX(0) translateY(0); }
            10% { transform: translateX(-1px) translateY(-1px); }
            20% { transform: translateX(1px) translateY(1px); }
            30% { transform: translateX(-1px) translateY(1px); }
            40% { transform: translateX(1px) translateY(-1px); }
            50% { transform: translateX(-1px) translateY(-1px); }
            60% { transform: translateX(1px) translateY(1px); }
            70% { transform: translateX(-1px) translateY(1px); }
            80% { transform: translateX(1px) translateY(-1px); }
            90% { transform: translateX(-1px) translateY(-1px); }
            100% { transform: translateX(0) translateY(0); }
        }

        .horror-content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: #ff0000;
            font-size: 4rem;
            font-family: 'Creepster', cursive;
            text-shadow: 0 0 30px #ff0000;
            animation: horrorTextGlitch 0.3s linear infinite;
        }

        @keyframes horrorTextGlitch {
            0% { 
                transform: translate(-50%, -50%) scale(1);
                text-shadow: 0 0 30px #ff0000;
            }
            25% { 
                transform: translate(-51%, -49%) scale(1.01);
                text-shadow: -2px 0 30px #ff0000, 2px 0 30px #00ff00;
            }
            50% { 
                transform: translate(-49%, -51%) scale(0.99);
                text-shadow: 0 0 30px #ff0000, 0 0 30px #0000ff;
            }
            75% { 
                transform: translate(-51%, -49%) scale(1.01);
                text-shadow: 2px 0 30px #ff0000, -2px 0 30px #ff00ff;
            }
            100% { 
                transform: translate(-50%, -50%) scale(1);
                text-shadow: 0 0 30px #ff0000;
            }
        }

        .horror-images {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .horror-image {
            position: absolute;
            width: 300px;
            height: 300px;
            background: radial-gradient(circle, #000, #8b0000);
            border: 5px solid #ff0000;
            border-radius: 10px;
            opacity: 0;
            animation: horrorImageFlash 1s ease-in-out infinite;
            box-shadow: 0 0 50px #ff0000;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 8rem;
            overflow: hidden;
        }

        @keyframes horrorImageFlash {
            0%, 100% { 
                opacity: 0; 
                transform: scale(0.8) rotate(0deg);
            }
            50% { 
                opacity: 0.9; 
                transform: scale(1.1) rotate(5deg);
            }
        }

        .distortion-effect {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                linear-gradient(90deg, transparent 0%, rgba(255, 0, 0, 0.1) 50%, transparent 100%);
            animation: distortionSweep 0.5s linear infinite;
        }

        @keyframes distortionSweep {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }

        .screen-shake {
            animation: screenShake 0.1s linear infinite;
        }

        @keyframes screenShake {
            0%, 100% { transform: translateX(0); }
            10% { transform: translateX(-2px); }
            20% { transform: translateX(2px); }
            30% { transform: translateX(-2px); }
            40% { transform: translateX(2px); }
            50% { transform: translateX(-2px); }
            60% { transform: translateX(2px); }
            70% { transform: translateX(-2px); }
            80% { transform: translateX(2px); }
            90% { transform: translateX(-2px); }
        }

        .hidden {
            display: none;
        }

        .skull-eyes {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 5;
        }

        .eye {
            position: absolute;
            width: 40px;
            height: 40px;
            background: radial-gradient(circle, #ff0000, #8b0000);
            border-radius: 50%;
            animation: eyeBlink 3s ease-in-out infinite;
            box-shadow: 0 0 20px #ff0000;
        }

        @keyframes eyeBlink {
            0%, 90%, 100% { opacity: 0.8; transform: scale(1); }
            95% { opacity: 0; transform: scale(0.1); }
        }

        .lightning {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.1);
            opacity: 0;
            z-index: 4;
            animation: lightning 8s linear infinite;
        }

        @keyframes lightning {
            0%, 95%, 100% { opacity: 0; }
            96%, 97% { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="matrix-rain"></div>
    <div class="fog-overlay"></div>
    <div class="lightning"></div>
    
    <div class="ancient-symbols">
        <div class="symbol" style="top: 10%; left: 15%; animation-delay: 0s;">⚰</div>
        <div class="symbol" style="top: 20%; left: 85%; animation-delay: 1s;">🕸</div>
        <div class="symbol" style="top: 70%; left: 10%; animation-delay: 2s;">⚱</div>
        <div class="symbol" style="top: 80%; left: 90%; animation-delay: 3s;">🔮</div>
        <div class="symbol" style="top: 40%; left: 5%; animation-delay: 4s;">⚡</div>
        <div class="symbol" style="top: 60%; left: 95%; animation-delay: 5s;">🌙</div>
        
        <div class="pentagram" style="top: 25%; left: 75%; animation-delay: 0s;"></div>
        <div class="pentagram" style="top: 65%; left: 20%; animation-delay: 2s;"></div>
        <div class="pentagram" style="top: 15%; left: 45%; animation-delay: 4s;"></div>
    </div>

    <div class="skull-eyes">
        <div class="eye" style="top: 30%; left: 20%; animation-delay: 0s;"></div>
        <div class="eye" style="top: 40%; left: 80%; animation-delay: 1s;"></div>
        <div class="eye" style="top: 70%; left: 15%; animation-delay: 2s;"></div>
        <div class="eye" style="top: 60%; left: 85%; animation-delay: 3s;"></div>
    </div>

    <div class="main-container">
        <div class="ornate-border"></div>
        
        <div id="initial-screen">
            <h1 class="title">ماريا الغريري</h1>
            <p class="subtitle">الحقيقة التي لا يجب أن تُكشف</p>
            <p class="subtitle" style="font-size: 1.4rem; margin-bottom: 3rem;">إذا كنت تريد أن تعرف من هي حقاً...</p>
            <button class="start-button" onclick="showConfirmation()">ابدأ الرحلة</button>
        </div>

        <div id="confirmation-screen" class="confirmation-screen">
            <p class="confirmation-text">هل أنت متأكد تماماً أنك تريد كشف<br>الحقيقة عن ماريا الغريري؟</p>
            <p style="font-size: 1.2rem; color: #ff9999; margin-bottom: 2rem;">تحذير: لا يمكن التراجع بعد هذه النقطة</p>
            <div class="button-group">
                <button class="yes-button" onclick="startHorror()">نعم، أريد المعرفة</button>
                <button class="no-button" onclick="goBack()">لا، أريد العودة</button>
            </div>
        </div>
    </div>

    <div id="horror-screen" class="horror-screen">
        <div class="tv-static"></div>
        <div class="distortion-effect"></div>
        <div class="horror-content">
            <div id="horror-text">جاري الدخول للنظام...</div>
        </div>
        <div class="horror-images" id="horror-images"></div>
    </div>

    <script>
        // إضافة تأثيرات قطرات الدم
        function createBloodDrops() {
            for (let i = 0; i < 20; i++) {
                const drop = document.createElement('div');
                drop.className = 'blood-drip';
                drop.style.left = Math.random() * 100 + '%';
                drop.style.animationDelay = Math.random() * 3 + 's';
                drop.style.animationDuration = (Math.random() * 3 + 2) + 's';
                document.body.appendChild(drop);
            }
        }

        function showConfirmation() {
            document.getElementById('initial-screen').style.display = 'none';
            document.getElementById('confirmation-screen').style.display = 'block';
        }

        function goBack() {
            document.getElementById('confirmation-screen').style.display = 'none';
            document.getElementById('initial-screen').style.display = 'block';
        }

        function startHorror() {
            document.getElementById('horror-screen').style.display = 'block';
            document.body.classList.add('screen-shake');
            
            const horrorText = document.getElementById('horror-text');
            const hackMessages = [
                'جاري الدخول للنظام...',
                'تم اختراق الحماية...',
                'SYSTEM COMPROMISED',
                'ERROR 666: UNAUTHORIZED ACCESS',
                'ماريا الغريري تعرف مكانك...',
                'أنت لست وحدك الآن...',
                'هي تراقبك من الظلام...',
                'لا يمكنك الهروب منها...',
                'مرحباً بك في عالم الأموات...',
                'الآن أنت جزء من قصتها...',
                'هل تشعر بها خلفك؟',
                'إغلاق الصفحة لن يوقفها...',
                'ماريا الغريري... ملكة الظلام الأبدية'
            ];
            
            let messageIndex = 0;
            const messageInterval = setInterval(() => {
                horrorText.textContent = hackMessages[messageIndex];
                messageIndex = (messageIndex + 1) % hackMessages.length;
                
                // تأثيرات عشوائية على النص
                if (Math.random() < 0.3) {
                    horrorText.style.fontSize = (Math.random() * 2 + 3) + 'rem';
                    horrorText.style.color = ['#ff0000', '#ff6666', '#8b0000', '#ffffff'][Math.floor(Math.random() * 4)];
                }
            }, 1000);

            // إنشاء صور مرعبة واقعية
            const horrorImagesContainer = document.getElementById('horror-images');
            const horrorElements = [
                // رموز مرعبة أكثر واقعية
                '💀', '🩸', '⚰️', '🕷️', '🕸️', '👁️', '🔪', '⚱️', 
                '🌙', '⚡', '🔥', '💉', '🦴', '👻', '🧛‍♀️', '🐺',
                // نصوص مرعبة
                'HELP', 'RUN', 'DEATH', 'FEAR', 'PAIN', 'DOOM', 'EVIL', 'DARK'
            ];

            const createHorrorImage = () => {
                const img = document.createElement('div');
                img.className = 'horror-image';
                img.style.top = Math.random() * 70 + '%';
                img.style.left = Math.random() * 70 + '%';
                img.style.animationDelay = Math.random() * 1 + 's';
                
                const element = horrorElements[Math.floor(Math.random() * horrorElements.length)];
                
                if (element.length === 1) {
                    // رمز إيموجي
                    img.innerHTML = element;
                    img.style.fontSize = '10rem';
                    img.style.background = 'radial-gradient(circle, #000, #8b0000, #ff0000)';
                } else {
                    // نص مرعب
                    img.innerHTML = element;
                    img.style.fontSize = '3rem';
                    img.style.fontFamily = 'Creepster, cursive';
                    img.style.color = '#ff0000';
                    img.style.background = 'radial-gradient(circle, #000, #1a0000)';
                    img.style.textShadow = '0 0 20px #ff0000';
                }
                
                // تأثيرات إضافية عشوائية
                if (Math.random() < 0.3) {
                    img.style.transform = 'rotate(' + (Math.random() * 360) + 'deg)';
                }
                
                horrorImagesContainer.appendChild(img);
                
                setTimeout(() => {
                    img.remove();
                }, 3000);
            };

            // إنشاء صور مرعبة بشكل أسرع
            const imageInterval = setInterval(createHorrorImage, 300);

            // تأثيرات صوتية محاكاة
            const playHorrorEffects = () => {
                // تأثير وميض الشاشة الأحمر
                const redFlash = () => {
                    document.body.style.background = '#ff0000';
                    setTimeout(() => {
                        document.body.style.background = '#000000';
                    }, 100);
                };
                
                // تأثير وميض الشاشة الأبيض
                const whiteFlash
