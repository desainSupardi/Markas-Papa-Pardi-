<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Papa Pardi Channel - Official</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .video-item {
            background: white;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .share-btn {
            background: #2c3e50;
            color: white;
            border: none;
            padding: 5px 10px;
            border-radius: 4px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Papa Pardi Channel</h1>
        <p>Hai, saya Papa Pardi, creator dari Malang</p>
    </header>

    <div class="container">
        <!-- Video 1 -->
        <div class="video-item">
            <h3>Detika Head of Command (drama) multi...</h3>
            <div class="video-container">
                <!-- Ganti LINK_YOUTUBE_ID dengan ID video Anda -->
                <iframe width="100%" height="315" src="https://www.youtube.com/embed/LINK_YOUTUBE_ID" frameborder="0" allowfullscreen></iframe>
            </div>
            <button class="share-btn">Share</button>
        </div>

        <!-- Video 2 -->
        <div class="video-item">
            <h3>Bocah lucu spiral (Kirulbaby sportubes)...</h3>
            <div class="video-container">
                <iframe width="100%" height="315" src="https://www.youtube.com/embed/LINK_YOUTUBE_ID" frameborder="0" allowfullscreen></iframe>
            </div>
            <button class="share-btn">Share</button>
        </div>

        <!-- Video 3 -->
        <div class="video-item">
            <h3>Barongan Macau Aviat (syouubeshorts)</h3>
            <div class="video-container">
                <iframe width="100%" height="315" src="https://www.youtube.com/embed/LINK_YOUTUBE_ID" frameborder="0" allowfullscreen></iframe>
            </div>
            <button class="share-btn">Share</button>
        </div>
    </div>

    <script>
        // Fungsi tombol share
        document.querySelectorAll('.share-btn').forEach(btn => {
            btn.addEventListener('click', function() {
                const videoTitle = this.parentElement.querySelector('h3').innerText;
                alert(`Berbagi "${videoTitle}" - Fitur akan ditambahkan soon!`);
            });
        });
    </script>
</body>
</html>
