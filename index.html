<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random YouTube Video Player</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        
        .container {
            background: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        
        h1 {
            color: #333;
            margin-bottom: 30px;
        }
        
        #randomButton {
            background: linear-gradient(45deg, #ff0000, #cc0000);
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            border-radius: 25px;
            cursor: pointer;
            margin-bottom: 30px;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        
        #randomButton:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(255, 0, 0, 0.3);
        }
        
        #randomButton:active {
            transform: translateY(0);
        }
        
        #videoContainer {
            margin-top: 20px;
        }
        
        #videoFrame {
            width: 100%;
            max-width: 800px;
            height: 450px;
            border: none;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
        .video-info {
            margin-top: 15px;
            color: #666;
            font-size: 14px;
        }
        
        .instructions {
            background: #e8f4fd;
            border-left: 4px solid #2196f3;
            padding: 15px;
            margin-bottom: 20px;
            text-align: left;
            border-radius: 4px;
        }
        
        .instructions h3 {
            margin-top: 0;
            color: #1976d2;
        }
        
        .instructions code {
            background: #f0f0f0;
            padding: 2px 4px;
            border-radius: 3px;
            font-family: monospace;
        }

        @media (max-width: 600px) {
            #videoFrame {
                height: 250px;
            }
            
            body {
                padding: 10px;
            }
            
            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎬 Random YouTube Video Player</h1>
        
        <div class="instructions">
            <h3>How to add your videos:</h3>
            <p>1. Right-click this page and select "View Page Source" or "Inspect"</p>
            <p>2. Find the <code>videoIds</code> array in the JavaScript section</p>
            <p>3. Replace the example video IDs with your own 600+ video IDs</p>
            <p><strong>Video ID example:</strong> For <code>https://youtube.com/watch?v=dQw4w9WgXcQ</code>, the ID is <code>dQw4w9WgXcQ</code></p>
        </div>
        
        <button id="randomButton">🎲 Get Random Video</button>
        
        <div id="videoContainer">
            <iframe id="videoFrame" src="" allowfullscreen></iframe>
            <div class="video-info">
                <p>Click the button above to load a random video!</p>
            </div>
        </div>
    </div>

    <script>
        // Replace this array with your 600+ YouTube video IDs
        const videoIds = [
            'dQw4w9WgXcQ',  // Rick Astley - Never Gonna Give You Up
            'L_jWHffIx5E',  // Smash Mouth - All Star
            'ZZ5LpwO-An4',  // HEYYEYAAEYAAAEYAEYAA
            '2Z4m4lnjxkY',  // Gangnam Style
            'kJQP7kiw5Fk',  // Luis Fonsi - Despacito
            '9bZkp7q19f0',  // PSY - Gangnam Style
            'CevxZvSJLk8',  // Katy Perry - Roar
            'hTWKbfoikeg',  // Nirvana - Smells Like Teen Spirit
            'fJ9rUzIMcZQ',  // Queen - Bohemian Rhapsody
            'djV11Xbc914'   // a-ha - Take On Me
        ];

        let currentVideoIndex = -1;
        
        function getRandomVideo() {
            // Make sure we don't get the same video twice in a row
            let randomIndex;
            do {
                randomIndex = Math.floor(Math.random() * videoIds.length);
            } while (randomIndex === currentVideoIndex && videoIds.length > 1);
            
            currentVideoIndex = randomIndex;
            const videoId = videoIds[randomIndex];
            
            // Update the iframe with the new video
            const iframe = document.getElementById('videoFrame');
            iframe.src = `https://www.youtube.com/embed/${videoId}?autoplay=1`;
            
            // Update the info
            const info = document.querySelector('.video-info p');
            info.textContent = `Now playing video ${randomIndex + 1} of ${videoIds.length}`;
        }
        
        // Add event listener to the button
        document.getElementById('randomButton').addEventListener('click', getRandomVideo);
        
        // Load a random video when page loads
        window.addEventListener('load', getRandomVideo);
    </script>
</body>
</html>
