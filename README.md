# Birthday_
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Happy Birthday Pushkar</title>
    <style>
        /* Force the page to be exactly the size of the screen */
        html, body {
            margin: 0;
            padding: 0;
            width: 100vw;
            height: 100vh;
            background-color: #000;
            overflow: hidden; /* Fixes the scrolling issue */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-family: 'sans-serif';
        }

        /* Fixed border that stays at the very edges */
        .border-layer {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 100;
            border: 20px solid transparent;
            border-image: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Ctext y='50' font-size='40'%3E🌸%3C/text%3E%3Ctext x='50' y='90' font-size='40'%3E🌺%3C/text%3E%3C/svg%3E") 30 round;
        }

        .text-container {
            text-align: center;
            z-index: 10;
        }

        /* Modern Appear Animation */
        .line {
            opacity: 0;
            transform: translateY(30px);
            animation: modernAppear 1s ease-out forwards;
        }

        .happiest {
            color: #ffffff;
            font-size: 1.8rem;
            font-weight: 300;
            margin-bottom: 10px;
        }

        .name {
            color: #ff4081;
            font-size: 4.5rem;
            font-weight: 900;
            text-transform: uppercase;
            letter-spacing: 5px;
            animation-delay: 0.5s;
            text-shadow: 0 0 20px rgba(255, 64, 129, 0.6);
        }

        @keyframes modernAppear {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <div class="border-layer"></div>

    <div class="text-container">
        <div class="line happiest">Happiest Birthday</div>
        <div class="line name">Pushkar</div>
    </div>

</body>
</html>
