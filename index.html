<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HAPPY YAOSANG 2026 - SPIN AND WIN</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            color: #333;
        }

        h1 { color: #d63384; text-shadow: 2px 2px #fff; margin-bottom: 5px; }
        h2 { color: #555; margin-top: 0; }

        .main-container {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 400px;
            width: 90%;
        }

        /* The Wheel Styling */
        .wheel-container {
            position: relative;
            width: 300px;
            height: 300px;
            margin: 20px auto;
        }

        #wheel {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            border: 8px solid #333;
            transition: transform 4s cubic-bezier(0.17, 0.67, 0.12, 0.99);
            background: conic-gradient(
                #ff6384 0deg 72deg, 
                #36a2eb 72deg 144deg, 
                #cc65fe 144deg 216deg, 
                #ffce56 216deg 288deg, 
                #4bc0c0 288deg 360deg
            );
        }

        .needle {
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
            width: 0; 
            height: 0; 
            border-left: 15px solid transparent;
            border-right: 15px solid transparent;
            border-top: 30px solid #333;
            z-index: 10;
        }

        /* Buttons */
        .btn {
            display: block;
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn-whatsapp { background-color: #25D366; color: white; }
        .btn-whatsapp:hover { background-color: #128C7E; }

        .btn-spin { background-color: #d63384; color: white; opacity: 0.5; cursor: not-allowed; }
        .btn-spin.enabled { opacity: 1; cursor: pointer; }

        #status { font-weight: bold; color: #d63384; margin-top: 15px; }
    </style>
</head>
<body>

    <div class="main-container">
        <h1>HAPPY YAOSANG 2026</h1>
        <h2>SPIN AND WIN</h2>

        <div class="wheel-container">
            <div class="needle"></div>
            <div id="wheel"></div>
        </div>

        <p id="instruction">Step 1: Share with 5 friends on WhatsApp to unlock the spin!</p>
        
        <button class="btn btn-whatsapp" onclick="shareOnWhatsApp()">Share on WhatsApp (<span id="count">0</span>/5)</button>
        <button id="spinBtn" class="btn btn-spin" onclick="spinWheel()" disabled>SPIN NOW</button>

        <div id="status"></div>
    </div>

    <script>
        let shareCount = 0;
        const prizes = [
            "iPhone 17", 
            "Better luck next time", 
            "₹500", 
            "₹5,000", 
            "₹50,000"
        ];

        function shareOnWhatsApp() {
            const text = encodeURIComponent("Hey! Play HAPPY YAOSANG 2026 Spin and Win to get an iPhone 17! Try here: " + window.location.href);
            const url = "whatsapp://send?text=" + text;
            
            // Open WhatsApp
            window.open(url, '_blank');

            // Simulate counting shares
            shareCount++;
            document.getElementById('count').innerText = shareCount > 5 ? 5 : shareCount;

            if (shareCount >= 5) {
                const spinBtn = document.getElementById('spinBtn');
                spinBtn.disabled = false;
                spinBtn.classList.add('enabled');
                document.getElementById('instruction').innerText = "Step 2: You've unlocked it! Click SPIN!";
            }
        }

        function spinWheel() {
            const wheel = document.getElementById('wheel');
            const status = document.getElementById('status');
            const spinBtn = document.getElementById('spinBtn');

            spinBtn.disabled = true; // Prevent double clicking
            spinBtn.classList.remove('enabled');

            // Random rotation between 2000 and 5000 degrees
            const randomDeg = Math.floor(Math.random() * 3000) + 2000;
            wheel.style.transform = `rotate(${randomDeg}deg)`;

            setTimeout(() => {
                // Calculate which slice it landed on
                const actualDeg = randomDeg % 360;
                // Since 360/5 = 72 degrees per slice
                const prizeIndex = Math.floor(((360 - actualDeg) % 360) / 72);
                
                status.innerHTML = `CONGRATULATIONS!<br>You won: ${prizes[prizeIndex]}`;
                alert("Congratulations! You won: " + prizes[prizeIndex]);
            }, 4000); // Matches the 4s CSS transition
        }
    </script>
</body>
</html>
