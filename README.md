<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Message for Zarith Ayrisya</title>
  <style>
    body{         margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #000;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: 'Quicksand', sans-serif;
        }

        .background {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            background: linear-gradient(135deg, #000428, #004e92);
            overflow: hidden;
        }

        .stars {
            position: absolute;
            width: 2px;
            height: 2px;
            background: white;
            box-shadow: 0 0 10px white, 0 0 20px white;
            animation: star-fall 10s linear infinite;
        }

        @keyframes star-fall {
            from {
                transform: translateY(-100vh);
            }
            to {
                transform: translateY(100vh);
            }
        }

        .heart {
            position: absolute;
            width: 200px;
            height: 200px;
            background-color: #ff6f61;
            transform: rotate(45deg);
            animation: beat 1.5s infinite ease-in-out;
        }

        .heart:before, .heart:after {
            content: "";
            position: absolute;
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background-color: #ff6f61;
        }

        .heart:before {
            top: -100px;
            left: 0;
        }

        .heart:after {
            left: 100px;
            top: 0;
        }

        @keyframes beat {
            0%, 100% {
                transform: scale(1) rotate(45deg);
            }
            50% {
                transform: scale(1.1) rotate(45deg);
            }
        }

        .moving-hearts {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
        }

        .moving-heart {
            position: absolute;
            width: 30px;
            height: 30px;
            background-color: #ff6f61;
            transform: rotate(45deg);
            animation: move-heart 10s linear infinite, spin 4s linear infinite;
        }

        @keyframes move-heart {
            0% {
                transform: translateX(0) translateY(100vh) rotate(45deg);
            }
            100% {
                transform: translateX(100vw) translateY(-100vh) rotate(45deg);
            }
        }

        @keyframes spin {
            0%, 100% {
                transform: rotate(45deg);
            }
            50% {
                transform: rotate(225deg);
            }
        }

        .wrapper {
            position: relative;
            font-size: 2.5rem;
            color: white;
            text-shadow: 0 0 10px white, 0 0 20px white, 0 0 30px white;
            z-index: 2;
            animation: text-glow 3s ease-in-out infinite alternate;
        }

        @keyframes text-glow {
            from {
                text-shadow: 0 0 10px #ff6f61, 0 0 20px #ff6f61, 0 0 30px #ff6f61;
            }
            to {
                text-shadow: 0 0 20px #ff6f61, 0 0 30px #ff6f61, 0 0 40px #ff6f61;
            }
        }

        .wrapper .text {
            white-space: nowrap;
            overflow: hidden;
            border-right: .15em solid white;
            animation: typing 6s steps(30, end), blink .75s step-end infinite;
        }

        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }

        @keyframes blink {
            from, to { border-color: transparent }
            50% { border-color: white }
        }

        .wrapper .shadow {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            text-shadow: 0 0 20px #ff6f61, 0 0 30px #ff6f61, 0 0 40px #ff6f61;
            opacity: 0;
            animation: shadow-glow 3s infinite;
        }

        @keyframes shadow-glow {
            0%, 100% {
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
        }

        /* Generating multiple stars */
        .stars:nth-child(10n+1) { top: 10%; left: 20%; animation-duration: 8s; }
        .stars:nth-child(10n+2) { top: 40%; left: 30%; animation-duration: 12s; }
        .stars:nth-child(10n+3) { top: 60%; left: 50%; animation-duration: 10s; }
        .stars:nth-child(10n+4) { top: 30%; left: 70%; animation-duration: 14s; }
        .stars:nth-child(10n+5) { top: 50%; left: 90%; animation-duration: 9s; }
        .stars:nth-child(10n+6) { top: 80%; left: 10%; animation-duration: 11s; }
        .stars:nth-child(10n+7) { top: 20%; left: 40%; animation-duration: 15s; }
        .stars:nth-child(10n+8) { top: 70%; left: 80%; animation-duration: 7s; }
        .stars:nth-child(10n+9) { top: 90%; left: 60%; animation-duration: 13s; }
        .stars:nth-child(10n+10) { top: 10%; left: 90%; animation-duration: 8s; }

        /* Moving hearts */
        .moving-heart:nth-child(3n+1) {
            width: 40px;
            height: 40px;
            top: 20%;
            left: 15%;
            animation-duration: 12s;
        }

        .moving-heart:nth-child(3n+2) {
            width: 50px;
            height: 50px;
            top: 50%;
            left: 60%;
            animation-duration: 14s;
        }

        .moving-heart:nth-child(3n+3) {
            width: 35px;
            height: 35px;
            top: 70%;
            left: 25%;
            animation-duration: 10s;
        }

        .moving-heart:nth-child(3n+4) {
            width: 45px;
            height: 45px;
            top: 80%;
            left: 80%;
            animation-duration: 11s;
        }

        .moving-heart:nth-child(3n+5) {
            width: 55px;
            height: 55px;
            top: 30%;
            left: 40%;
            animation-duration: 13s;
        }

        .moving-heart:nth-child(3n+6) {
            width: 60px;
            height: 60px;
            top: 60%;
            left: 70%;
            animation-duration: 9s;
        }

        .moving-heart:nth-child(3n+7) {
            width: 30px;
            height: 30px;
            top: 40%;
            left: 90%;
            animation-duration: 8s;
        }

        .moving-heart:nth-child(3n+8) {
            width: 50px;
            height: 50px;
            top: 90%;
            left: 50%;
            animation-duration: 7s;
        }

        .moving-heart:nth-child(3n+9) {
            width: 45px;
            height: 45px;
            top: 10%;
            left: 20%;
            animation-duration: 15s;
        }

        .moving-heart:nth-child(3n+10) {
            width: 55px;
            height: 55px;
            top: 25%;
            left: 75%;
            animation-duration: 14s;
        }

        /* Additional stars */
        .stars:nth-child(10n+11) { top: 5%; left: 15%; animation-duration: 9s; }
        .stars:nth-child(10n+12) { top: 25%; left: 35%; animation-duration: 13s; }
        .stars:nth-child(10n+13) { top: 45%; left: 55%; animation-duration: 11s; }
        .stars:nth-child(10n+14) { top: 15%; left: 75%; animation-duration: 15s; }
        .stars:nth-child(10n+15) { top: 65%; left: 85%; animation-duration: 10s; }
        .stars:nth-child(10n+16) { top: 35%; left: 5%; animation-duration: 14s; }
        .stars:nth-child(10n+17) { top: 55%; left: 25%; animation-duration: 8s; }
        .stars:nth-child(10n+18) { top: 75%; left: 45%; animation-duration: 12s; }
        .stars:nth-child(10n+19) { top: 95%; left: 65%; animation-duration: 7s; }
        .stars:nth-child(10n+20) { top: 85%; left: 95%; animation-duration: 11s; }

        /* Additional moving hearts */
        .moving-heart:nth-child(3n+11) {
            width: 35px;
            height: 35px;
            top: 35%;
            left: 15%;
            animation-duration: 10s;
        }

        .moving-heart:nth-child(3n+12) {
            width: 45px;
            height: 45px;
            top: 45%;
            left: 65%;
            animation-duration: 12s;
        }

        .moving-heart:nth-child(3n+13) {
            width: 40px;
            height: 40px;
            top: 55%;
            left: 35%;
            animation-duration: 13s;
        }

        .moving-heart:nth-child(3n+14) {
            width: 50px;
            height: 50px;
            top: 25%;
            left: 85%;
            animation-duration: 14s;
        }

        .moving-heart:nth-child(3n+15) {
            width: 60px;
            height: 60px;
            top: 65%;
            left: 45%;
            animation-duration: 15s;
        }

        .moving-heart:nth-child(3n+16) {
            width: 70px;
            height: 70px;
            top: 75%;
            left: 15%;
            animation-duration: 9s;
        }

        .moving-heart:nth-child(3n+17) {
            width: 30px;
            height: 30px;
            top: 85%;
            left: 35%;
            animation-duration: 8s;
        }

        .moving-heart:nth-child(3n+18) {
            width: 40px;
            height: 40px;
            top: 95%;
            left: 55%;
            animation-duration: 10s;
        }

        .moving-heart:nth-child(3n+19) {
            width: 50px;
            height: 50px;
            top: 5%;
            left: 75%;
            animation-duration: 11s;
        }

        .moving-heart:nth-child(3n+20) {
            width: 60px;
            height: 60px;
            top: 15%;
            left: 95%;
            animation-duration: 13s;
        }

        /* Additional styling for dynamic effects */
        .background::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, rgba(255,255,255,0.2) 10%, transparent 70%);
            opacity: 0.3;
            animation: pulse 5s infinite alternate;
        }

        @keyframes pulse {
            from {
                transform: scale(1);
            }
            to {
                transform: scale(1.1);
            }
        }

        .wrapper .text, .wrapper .shadow {
            font-size: 4rem;
            animation: float 5s ease-in-out infinite;
        }

        @keyframes float {
            from {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
            to {
                transform: translateY(0);
            }
        }

  </style>
</head>
<body>
    <div class="background">
        <!-- Generating multiple stars in the background -->
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
        <div class="stars"></div>
    </div>

    <div class="heart"></div>

    <div class="moving-hearts">
        <!-- Generating multiple moving hearts -->
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
        <div class="moving-heart"></div>
    </div>

    <div class="wrapper">
        <div class="text">I love you Zarith Ayrisya</div>
        <div class="shadow">I love you Zarith Ayrisya</div>
    </div>
</body>
</html>
