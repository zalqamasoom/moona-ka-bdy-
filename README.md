<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birthday Surprise</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            padding-top: 50px;
        }
        button {
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            background-color: #ff4b2b;
            color: white;
            border: none;
            border-radius: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }
        #video-container {
            display: none; /* Player ko hidden rakhne ke liye */
        }
    </style>
</head>
<body>

    <h1>Happy Birthday! 🎂</h1>
    <p>Surprise sunne ke liye niche button dabayein:</p>

    <button onclick="startMusic()">Start Music 🎵</button>

    <div id="video-container"></div>

    <script>
        function startMusic() {
            const container = document.getElementById('video-container');
            
            // YouTube iframe background mein music play karne ke liye (Alert remove kar diya gaya hai)
            container.innerHTML = '<iframe width="0" height="0" src="https://www.youtube.com/embed/F9Esh7pY8o0?autoplay=1&loop=1&playlist=F9Esh7pY8o0" frameborder="0" allow="autoplay"></iframe>';
            
            // Optional: Button click hone ke baad button ko hide karne ke liye
            document.querySelector('button').style.display = 'none';
        }
    </script>

</body>
</html>
