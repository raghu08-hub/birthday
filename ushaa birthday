<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Dhyan!</title>
    <style>
        body {
            text-align: center;
            background: linear-gradient(45deg, #ff99cc, #ff66b2, #ff3366);
            background-size: 400% 400%;
            animation: gradient 15s ease infinite;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            color: white;
            padding: 50px;
            overflow-x: hidden;
        }

        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .card {
            width: 60%;
            margin: auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.3);
            position: relative;
            margin-top: 50px;
            transition: all 0.5s ease;
            transform-style: preserve-3d;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .card:hover {
            transform: scale(1.1) rotate(3deg);
        }

        .btn {
            background: linear-gradient(to right, #ff3366, #ff66b2);
            color: white;
            padding: 15px 30px;
            font-size: 20px;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            margin-top: 20px;
            transition: all 0.3s;
            box-shadow: 0 5px 20px rgba(255, 51, 102, 0.5);
        }

        .btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(255, 51, 102, 0.7);
        }

        .hidden-message {
            display: none;
            font-size: 28px;
            margin-top: 20px;
            color: #ff3366;
            font-weight: bold;
            animation: fadeIn 1s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .balloon {
            position: fixed;
            font-size: 50px;
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-30px); }
            100% { transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="card">
        <h1 style="font-size: 54px;">🎉 Happy Birthday ushaa pappaa! 🎂</h1>
        <p style="font-size: 26px;">Wishing you all the happiness and joy in the world. Have an amazing day!</p>
        <button class="btn" onclick="celebrate()">Click for a Birthday Surprise!</button>
        <p class="hidden-message" id="message"></p>
    </div>

    <script>
        const messages = [
            "To my bestie, my partner-in-crime, my forever friend! 💖🎊 You make life more fun, more beautiful, and absolutely unforgettable! Wishing you an extraordinary birthday filled with love, laughter"     
        ];

        function celebrate() {
            const message = document.getElementById("message");
            message.style.display = "block";
            message.textContent = messages[Math.floor(Math.random() * messages.length)];
            createBalloons();
            confettiEffect();
        }

        function createBalloons() {
            for(let i = 0; i < 15; i++) {
                const balloon = document.createElement("div");
                balloon.innerHTML = "🎈";
                balloon.className = "balloon";
                balloon.style.left = Math.random() * 100 + "vw";
                balloon.style.animationDelay = Math.random() * 2 + "s";
                document.body.appendChild(balloon);
            
            }
        }
    </script>
</body>
</html>
