CSS CREATION 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Define the styles for the circle */
        .circle {
            width: 100px;
            height: 100px;
            background-color: #3498db;
            border-radius: 50%;
            position: relative;
            animation: moveCircle 4s infinite;
        }

        /* Define the keyframes for the animation */
        @keyframes moveCircle {
            0% {
                left: 0;
            }
            50% {
                left: 50%;
            }
            100% {
                left: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Create the animated circle element -->
    <div class="circle"></div>
</body>
</html>
