<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>My Sweet Valentine 💖</title>

<style>
body {
    margin: 0;
    padding: 0;
    font-family: 'Comic Sans MS', cursive, sans-serif;
    background: linear-gradient(135deg, #ffc1e3, #ffe6f2, #ffd6eb);
    text-align: center;
    overflow-x: hidden;
}

/* Floating hearts background */
.heart-bg {
    position: fixed;
    color: #ff4da6;
    animation: floatUp 8s linear infinite;
    font-size: 20px;
}

@keyframes floatUp {
    0% { transform: translateY(100vh); opacity: 1; }
    100% { transform: translateY(-10vh); opacity: 0; }
}

h1 {
    margin-top: 60px;
    font-size: 3em;
    color: #ff1a75;
    text-shadow: 2px 2px 10px white;
}

.subtitle {
    font-size: 1.6em;
    color: #ff4da6;
}

.love-box {
    background: white;
    margin: 30px auto;
    padding: 25px;
    border-radius: 25px;
    width: 80%;
    max-width: 600px;
    box-shadow: 0 10px 25px rgba(255, 77, 166, 0.3);
}

.love-box p {
    font-size: 1.2em;
    color: #ff3385;
}

.btn {
    margin: 20px;
    padding: 15px 35px;
    font-size: 1.2em;
    border: none;
    border-radius: 30px;
    cursor: pointer;
    transition: 0.3s;
}

.yes-btn {
    background-color: #ff4da6;
    color: white;
}

.yes-btn:hover {
    background-color: #ff1a75;
    transform: scale(1.1);
}

.no-btn {
    background-color: white;
    color: #ff4da6;
    border: 2px solid #ff4da6;
    position: relative;
}

#secretMessage {
    display: none;
    margin-top: 30px;
    font-size: 1.6em;
    color: #ff1a75;
    animation: fadeIn 2s forwards;
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

.footer {
    margin-top: 50px;
    padding-bottom: 20px;
    color: #ff4da6;
}

/* Cute sparkle animation */
.sparkle {
    position: fixed;
    font-size: 20px;
    animation: sparkleAnim 1.5s linear forwards;
}

@keyframes sparkleAnim {
    0% { transform: scale(1); opacity: 1; }
    100% { transform: scale(2); opacity: 0; }
}
</style>
</head>

<body>

<h1>Happy Valentine's Day 💖</h1>
<p class="subtitle">To the most precious girl in my universe 🌸✨</p>

<div class="love-box">
    <p>💗 You are the sunshine that brightens my darkest days.</p>
    <p>🌷 Your smile is my favorite view in the whole world.</p>
    <p>🧸 Your laugh is my favorite sound ever.</p>
    <p>🌹 Every moment with you feels like a beautiful dream.</p>
    <p>💞 You are not just my girlfriend… you are my best friend, my safe place, and my forever.</p>
</div>

<h2 style="color:#ff1a75;">Will you be my Valentine? 💌💕</h2>

<button class="btn yes-btn" onclick="showLove()">Yes, of course! 💖</button>
<button class="btn no-btn" onmouseover="moveButton(this)">No 😜</button>

<div id="secretMessage">
    🥰 You make my heart skip a beat every single day.<br><br>
    💍 I promise to love you, support you, and annoy you forever.<br><br>
    💕 I love you more than chocolate… and that says A LOT! 🍫✨<br><br>
    You are my today, my tomorrow, and my always 💞
</div>

<div class="footer">
    Made with infinite love 💖 just for you
</div>

<script>
function showLove() {
    document.getElementById("secretMessage").style.display = "block";
    createSparkles();
}

function moveButton(button) {
    button.style.position = "absolute";
    button.style.top = Math.random() * window.innerHeight + "px";
    button.style.left = Math.random() * window.innerWidth + "px";
}

function createSparkles() {
    for (let i = 0; i < 30; i++) {
        let sparkle = document.createElement("div");
        sparkle.className = "sparkle";
        sparkle.innerHTML = "✨";
        sparkle.style.left = Math.random() * window.innerWidth + "px";
        sparkle.style.top = Math.random() * window.innerHeight + "px";
        document.body.appendChild(sparkle);
        setTimeout(() => sparkle.remove(), 1500);
    }
}

/* Create floating hearts */
setInterval(() => {
    let heart = document.createElement("div");
    heart.className = "heart-bg";
    heart.innerHTML = "💖";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (Math.random() * 20 + 15) + "px";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 8000);
}, 500);
</script>

</body>
</html>
