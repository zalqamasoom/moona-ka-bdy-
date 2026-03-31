<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Moona! 🎂</title>
    <style>
        body {
            background-color: #ffeef2;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            color: #d81b60;
            padding: 20px;
        }
        h1 { font-size: 2.5em; margin-bottom: 10px; }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        .photo-card {
            background: white;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            width: 250px;
            transition: transform 0.3s;
        }
        .photo-card:hover { transform: scale(1.05); }
        .photo-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }
        .caption {
            margin-top: 10px;
            font-weight: bold;
            font-size: 0.9em;
        }
        .play-btn {
            background-color: #d81b60;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 25px;
            font-size: 1.1em;
            cursor: pointer;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(216, 27, 96, 0.3);
            margin: 20px 0;
        }
        .play-btn:hover { background-color: #ad1457; }
    </style>
</head>
<body>

    <h1>Happy Birthday Moona! 🎂✨</h1>

    <div id="music-area">
        <button class="play-btn" onclick="startMusic()">🎵 Play Birthday Music</button>
        <div id="video-container"></div>
    </div>

    <div class="gallery">
        <div class="photo-card"><img src="pic1.jpg.jpeg"><div class="caption">merii jan ho hmesha muskurati rho ❤️</div></div>
        <div class="photo-card"><img src="pic2.jpg.jpeg"><div class="caption">chuzaa barha hogya h ab 🌟</div></div>
        <div class="photo-card"><img src="pic3.jpg.jpeg"><div class="caption">Baloon mera wo b red wala 📸</div></div>
        <div class="photo-card"><img src="pic4.jpg.jpeg"><div class="caption">hayee jab smile krti hou dil karta hay kha jaoun ✨</div></div>
        <div class="photo-card"><img src="pic5.jpg.jpeg"><div class="caption">lub u mery bachy 🎈</div></div>
        <div class="photo-card"><img src="pic6.jpg.jpeg"><div class="caption">ap itni payri keshy ooo 🌸</div></div>
        <div class="photo-card"><img src="pic7.jpg.jpeg"><div class="caption">meri jan ko happy bdy 🍭</div></div>
        <div class="photo-card"><img src="pic8.jpg.jpeg"><div class="caption">uff ap ki ankhain 🎀</div></div>
        <div class="photo-card"><img src="pic9.jpg.jpeg"><div class="caption">Happy bdy once again 💎</div></div>
        <div class="photo-card"><img src="pic10.jpg.jpeg"><div class="caption">Bestie Forever 👑</div></div>
    </div>

    <script>
        function startMusic() {
            const container = document.getElementById('video-container');
            // Using the birthday song ID we picked earlier
            container.innerHTML = '<iframe width="0" height="0" src="https://www.youtube.com/embed/F9Esh7pY8o0?autoplay=1&loop=1&playlist=F9Esh7pY8o0" frameborder="0" allow="autoplay"></iframe>';
            alert("Music Started! Happy Birthday Moona! ❤️");
        }
    </script>

</body>
</html>
