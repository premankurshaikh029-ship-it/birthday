<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Moon</title>
    <style>
        /* --- CSS STYLES --- */
        body {
            margin: 0;
            padding: 0;
            background: radial-gradient(ellipse at bottom, #1b2735 0%, #090a0f 100%);
            height: 100vh;
            color: white;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            text-align: center;
        }

        /* The Stars Background */
        .stars {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            z-index: -1;
            pointer-events: none;
        }
        .star {
            position: absolute;
            width: 2px; height: 2px;
            background: white;
            border-radius: 50%;
            opacity: 0.8;
            animation: twinkle 2s infinite;
        }

        /* Page Transitions */
        .page {
            display: none; /* Hidden by default */
            flex-direction: column;
            align-items: center;
            justify-content: center;
            width: 90%;
            max-width: 600px;
            animation: fadeIn 1.5s ease-in-out;
        }

        .active {
            display: flex;
        }

        /* Typography */
        h1 { font-size: 2.5rem; color: #ffca28; text-shadow: 0 0 10px #ffca28; margin-bottom: 20px; }
        p { font-size: 1.2rem; line-height: 1.6; margin-bottom: 30px; }
        
        /* Buttons */
        button {
            padding: 15px 30px;
            font-size: 1.2rem;
            background: #e91e63;
            color: white;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 0 15px #e91e63;
            transition: transform 0.2s;
        }
        button:hover { transform: scale(1.1); }

        /* Moon Graphic */
        .moon-graphic {
            width: 150px;
            height: 150px;
            background: #ffca28;
            border-radius: 50%;
            box-shadow: 0 0 40px #ffca28;
            margin-bottom: 30px;
            position: relative;
        }
        .crater {
            position: absolute;
            background: rgba(0,0,0,0.1);
            border-radius: 50%;
        }

        /* Heart Animation */
        .heart {
            color: #e91e63;
            font-size: 50px;
            animation: beat 1s infinite;
        }

        /* Cake */
        .cake { font-size: 80px; margin-bottom: 20px; }

        /* Animations */
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes twinkle { 0% { opacity: 0.3; } 50% { opacity: 1; } 100% { opacity: 0.3; } }
        @keyframes beat { 0% { transform: scale(1); } 50% { transform: scale(1.2); } 100% { transform: scale(1); } }
    </style>
</head>
<body>

    <audio id="bgMusic" loop>
        <source src="https://www.bensound.com/bensound-music/bensound-sunny.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <div class="stars" id="starContainer"></div>

    <div id="page1" class="page active">
        <div class="heart">❤</div>
        <h1>Hey Beautiful...</h1>
        <p>I have a little surprise for you.</p>
        <p>Turn up your volume.</p>
        <button onclick="nextPage(1)">Open My Heart</button>
    </div>

    <div id="page2" class="page">
        <div class="moon-graphic">
            <div class="crater" style="top: 20px; left: 30px; width: 30px; height: 30px;"></div>
            <div class="crater" style="top: 70px; left: 80px; width: 20px; height: 20px;"></div>
            <div class="crater" style="top: 100px; left: 40px; width: 10px; height: 10px;"></div>
        </div>
        <h1>To My Moon</h1>
        <p>Just like the moon lights up the dark night sky,<br>you light up my whole world.</p>
        <button onclick="nextPage(2)">Continue</button>
    </div>

    <div id="page3" class="page">
        <h1>Why You?</h1>
        <p style="text-align: left; background: rgba(255,255,255,0.1); padding: 20px; border-radius: 10px;">
            ✨ Your smile is my favorite thing.<br>
            ✨ You understand me without words.<br>
            ✨ Every moment with you is magic.<br>
            ✨ I love you more than words can say.
        </p>
        <button onclick="nextPage(3)">One Last Thing...</button>
    </div>

    <div id="page4" class="page">
        <div class="cake">🎂</div>
        <h1>Happy Birthday, Moon!</h1>
        <p>May this year bring you as much joy as you bring into my life.</p>
        <p>I love you forever.</p>
        <div class="heart">❤❤❤</div>
        <br>
        <button onclick="location.reload()">Replay</button>
    </div>

    <script>
        // --- JAVASCRIPT LOGIC ---

        // 1. Create Stars Background
        const starContainer = document.getElementById('starContainer');
        for(let i=0; i<100; i++) {
            const star = document.createElement('div');
            star.classList.add('star');
            star.style.left = Math.random() * 100 + '%';
            star.style.top = Math.random() * 100 + '%';
            star.style.animationDelay = Math.random() * 2 + 's';
            starContainer.appendChild(star);
        }

        // 2. Navigation Function
        function nextPage(pageNumber) {
            // Hide current page
            document.getElementById('page' + pageNumber).classList.remove('active');
            
            // Show next page
            const nextPageNum = pageNumber + 1;
            const nextPageElement = document.getElementById('page' + nextPageNum);
            
            if(nextPageElement) {
                nextPageElement.classList.add('active');
            }

            // Play music on first click (Browser policy requires user interaction)
            if (pageNumber === 1) {
                const audio = document.getElementById("bgMusic");
                audio.volume = 0.4; // Set volume to 40%
                audio.play().catch(error => {
                    console.log("Audio play failed: " + error);
                });
            }
        }
    </script>
</body>
</html>
