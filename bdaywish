<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Simmy! 🎉</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Comic Sans MS', cursive;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4, #ffeaa7);
            background-size: 400% 400%;
            animation: gradientShift 6s ease infinite;
            min-height: 100vh;
            overflow-x: hidden;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
        }

        .decorations {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .balloon {
            position: absolute;
            width: 60px;
            height: 80px;
            border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
            animation: float 3s ease-in-out infinite;
        }

        .balloon:nth-child(1) {
            background: #ff6b6b;
            top: 10%;
            left: 5%;
            animation-delay: 0s;
        }

        .balloon:nth-child(2) {
            background: #4ecdc4;
            top: 20%;
            right: 10%;
            animation-delay: 1s;
        }

        .balloon:nth-child(3) {
            background: #ffeaa7;
            top: 5%;
            left: 20%;
            animation-delay: 2s;
        }

        .balloon:nth-child(4) {
            background: #fd79a8;
            top: 15%;
            right: 20%;
            animation-delay: 0.5s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }

        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background: #ff6b6b;
            animation: fall 3s linear infinite;
        }

        .confetti:nth-child(5) {
            left: 10%;
            animation-delay: 0s;
            background: #4ecdc4;
        }

        .confetti:nth-child(6) {
            left: 20%;
            animation-delay: 1s;
            background: #ffeaa7;
        }

        .confetti:nth-child(7) {
            left: 30%;
            animation-delay: 2s;
            background: #fd79a8;
        }

        .confetti:nth-child(8) {
            left: 40%;
            animation-delay: 0.5s;
            background: #a29bfe;
        }

        .confetti:nth-child(9) {
            left: 50%;
            animation-delay: 1.5s;
            background: #ff7675;
        }

        .confetti:nth-child(10) {
            left: 60%;
            animation-delay: 2.5s;
            background: #6c5ce7;
        }

        .confetti:nth-child(11) {
            left: 70%;
            animation-delay: 0.8s;
            background: #00b894;
        }

        .confetti:nth-child(12) {
            left: 80%;
            animation-delay: 1.8s;
            background: #e17055;
        }

        .confetti:nth-child(13) {
            left: 90%;
            animation-delay: 2.2s;
            background: #0984e3;
        }

        @keyframes fall {
            0% { transform: translateY(-100vh) rotate(0deg); }
            100% { transform: translateY(100vh) rotate(360deg); }
        }

        .main-content {
            position: relative;
            z-index: 2;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 20px;
            padding: 40px;
            margin: 20px 0;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .title {
            font-size: 4rem;
            color: #ff6b6b;
            margin-bottom: 30px;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.3);
            animation: bounce 2s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }

        .animals {
            display: flex;
            justify-content: space-around;
            margin: 40px 0;
            flex-wrap: wrap;
        }

        .animal {
            font-size: 4rem;
            margin: 20px;
            animation: wiggle 2s ease-in-out infinite;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .animal:hover {
            transform: scale(1.2);
        }

        .animal:nth-child(1) { animation-delay: 0s; }
        .animal:nth-child(2) { animation-delay: 0.5s; }
        .animal:nth-child(3) { animation-delay: 1s; }

        @keyframes wiggle {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(5deg); }
            75% { transform: rotate(-5deg); }
        }

        .wish-button {
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
            color: white;
            border: none;
            padding: 20px 40px;
            font-size: 1.5rem;
            border-radius: 50px;
            cursor: pointer;
            margin: 30px 0;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            font-family: 'Comic Sans MS', cursive;
        }

        .wish-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
        }

        .wish-button:active {
            transform: translateY(0);
        }

        .birthday-wish {
            display: none;
            background: rgba(255, 255, 255, 0.95);
            padding: 30px;
            border-radius: 15px;
            margin: 30px 0;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
            font-size: 1.2rem;
            line-height: 1.6;
            color: #333;
            text-align: left;
            border: 3px solid #ff6b6b;
        }

        .birthday-wish.show {
            display: block;
            animation: slideIn 0.5s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .final-title {
            font-size: 5rem;
            color: #4ecdc4;
            margin: 40px 0;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.3);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .stars {
            position: absolute;
            width: 20px;
            height: 20px;
            color: #ffeaa7;
            font-size: 2rem;
            animation: twinkle 1.5s ease-in-out infinite;
        }

        .stars:nth-child(14) {
            top: 25%;
            left: 15%;
            animation-delay: 0s;
        }

        .stars:nth-child(15) {
            top: 35%;
            right: 15%;
            animation-delay: 0.5s;
        }

        .stars:nth-child(16) {
            top: 45%;
            left: 25%;
            animation-delay: 1s;
        }

        .stars:nth-child(17) {
            top: 55%;
            right: 25%;
            animation-delay: 1.5s;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.2); }
        }

        @media (max-width: 768px) {
            .title { font-size: 2.5rem; }
            .final-title { font-size: 3rem; }
            .animal { font-size: 3rem; margin: 10px; }
            .wish-button { padding: 15px 30px; font-size: 1.2rem; }
        }
    </style>
</head>
<body>
    <div class="decorations">
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="balloon"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="stars">⭐</div>
        <div class="stars">⭐</div>
        <div class="stars">⭐</div>
        <div class="stars">⭐</div>
    </div>

    <div class="container">
        <div class="main-content">
            <h1 class="title">🎉 Happy Birthday! 🎉</h1>
            
            <div class="animals">
                <div class="animal">🐻</div>
                <div class="animal">🐱</div>
                <div class="animal">🦁</div>
            </div>

            <button class="wish-button" onclick="showWish()">
                🎁 Click for Birthday Wishes! 🎁
            </button>

            <div class="birthday-wish" id="birthdayWish">
                <p>Wishing you a day filled with happiness, laughter, and everything that makes your heart smile. At 23 you're becoming a better person day by day and stronger, wiser, and smarter (u still dummy imo lol) 😄</p>
                
                <p>May this year bring you lasting happiness and peace of mind, new opportunities, and memories that stay with you forever. Keep shining, keep dreaming, and never forget how kind and incredible you are.</p>
                
                <p>And I really enjoyed every second and you always made my day when I talk to you, and to be honest you are the kindest person I know, and I like how mature and understanding you are in the end THANK YOU SO MUCH FOR EVERYTHING SIMRAN 🤍</p>
            </div>

            <h2 class="final-title">🎂 HAPPY BIRTHDAY SIMMY 🎂</h2>
        </div>
    </div>

    <script>
        function showWish() {
            const wish = document.getElementById('birthdayWish');
            wish.classList.add('show');
            
            // Add some extra celebratory effects
            document.body.style.animation = 'none';
            setTimeout(() => {
                document.body.style.animation = '';
            }, 100);
        }

        // Add click sound effect (visual feedback)
        document.querySelector('.wish-button').addEventListener('click', function() {
            this.style.transform = 'scale(0.95)';
            setTimeout(() => {
                this.style.transform = '';
            }, 150);
        });

        // Make animals interactive
        document.querySelectorAll('.animal').forEach(animal => {
            animal.addEventListener('click', function() {
                this.style.animation = 'none';
                this.style.transform = 'scale(1.5) rotate(360deg)';
                setTimeout(() => {
                    this.style.animation = '';
                    this.style.transform = '';
                }, 500);
            });
        });
    </script>
</body>
</html>
