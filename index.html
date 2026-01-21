<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For You ❤️</title>

<style>
    body {
        background: linear-gradient(135deg, #ffdde1, #ee9ca7);
        font-family: 'Segoe UI', sans-serif;
        margin: 0;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        overflow: hidden;
    }

    #card {
        background: rgba(255, 255, 255, 0.88);
        padding: 30px 25px;
        border-radius: 22px;
        box-shadow: 0 15px 35px rgba(0,0,0,0.25);
        max-width: 90%;
        animation: fadeIn 2s ease;
    }

    h1 {
        margin-bottom: 10px;
        color: #e91e63;
    }

    #hint {
        font-size: 14px;
        color: #555;
        margin-bottom: 20px;
        animation: blink 1.5s infinite;
    }

    .line {
        font-size: 20px;
        margin: 14px 0;
        min-height: 28px;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: scale(0.9); }
        to { opacity: 1; transform: scale(1); }
    }

    @keyframes blink {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.3; }
    }
</style>
</head>

<body>

<div id="card">
    <h1>For You ❤️</h1>
    <div id="hint">Tap anywhere to start the music 🎶</div>
    <div id="lyrics"></div>
</div>

<!-- 🎶 Google Drive Audio -->
<audio id="bgMusic" loop>
    <source src="https://drive.google.com/uc?export=download&id=YOUR_FILE_ID" type="audio/mpeg">
</audio>

<script>
const lyrics = [
    ["Devatha Thane Oka Devatha", " ❤️"],
    ["Mukamukhi Andhame Choodaga Ayuve Chaluna..?", " ✨"],
    ["Galilo Thane Kadha Parimalam", " 💕"],
    ["Cheli Sakhi Anumathe Adagaka Puvvule Pooyuna..?", " 🌹"],
    ["Sighalo Kurule Meghalale Adevela", " ☁️"],
    ["Gundellona Merupe Merise Choope Maimarache", " ⚡"],
    ["Cheli Chekkille Muddhulthone Thadimeyyala", " 😘"],
    ["Changu Changu Adugullona Muvvai Madhi Murise", " 🎶"]
];

const container = document.getElementById("lyrics");
const hint = document.getElementById("hint");
let index = 0;

function typeLine(text, emoji, callback) {
    const div = document.createElement("div");
    div.className = "line";
    container.appendChild(div);

    let i = 0;
    const interval = setInterval(() => {
        div.textContent += text[i];
        i++;
        if (i === text.length) {
            clearInterval(interval);
            div.textContent += emoji;
            setTimeout(callback, 1800);
        }
    }, 55);
}

function startLyrics() {
    if (index < lyrics.length) {
        typeLine(lyrics[index][0], lyrics[index][1], () => {
            index++;
            startLyrics();
        });
    }
}

// ▶️ Play music after first tap
document.body.addEventListener("click", () => {
    document.getElementById("bgMusic").play();
    hint.style.display = "none";
    startLyrics();
}, { once: true });
</script>

</body>
</html>
