<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Room test</title>
    <style>
        body { margin: 0; background: #222; }

        /* --- paste your room CSS here --- */
        .room { position: relative; width: 100%; max-width: 960px; margin: 0 auto; container-type: inline-size; display: grid;}
        
        .room img {
            display: block;
            width: 100%;
            image-rendering: pixelated;
        }

        .room > * {
            grid-area: 1 / 1;
        }
        
        /* ...rest of the CSS... */
 
    </style>

</head>
<body>

    <!-- --- paste your room HTML here --- -->
     <div class="room">
        <div><img src="assets/background.png"></div>
        <div><img src="assets/recliner.png"></div>
        <div><img src="assets/me_sitting.png"></div>
        <div><img src="assets/recliner_foreground.png"></div>
        <img src="room-base.png" alt="Pixel art room">
        <a href="about.html"><img src="bookshelf.png" alt="About"></a>
    </div>

</body>
</html>
