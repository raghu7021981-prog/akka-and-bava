<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akka & Bava Wedding</title>
    <link rel="stylesheet" href="styles.css">

    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: #fff5f8;
        }

        .hero {
            background: linear-gradient(rgba(255,192,203,0.6), rgba(255,182,193,0.6)),
                        url('https://images.unsplash.com/photo-1522673607200-164d1b6ce486?w=1200');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .main-title {
            font-size: 3rem;
        }

        .subtitle {
            font-size: 1.5rem;
        }

        .details, .gallery, .message, .guest-book {
            padding: 50px 20px;
            text-align: center;
        }

        .detail-card {
            background: white;
            padding: 20px;
            margin: 10px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .message-box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            max-width: 700px;
            margin: auto;
            font-size: 18px;
            line-height: 1.6;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #ffb6c1;
            color: white;
        }
    </style>
</head>

<body>

<!-- Hero -->
<section class="hero">
    <h1 class="main-title">My Dearest Akka ❤️</h1>
    <p class="subtitle">A Beautiful Beginning with Bava 💍</p>

    <h2>Wedding Countdown</h2>
    <p id="countdown"></p>
</section>

<!-- Details -->
<section class="details">
    <h2>Wedding Details</h2>

    <div class="detail-card">
        <h3>📅 Date & Time</h3>
        <p>May 3, 2026 | 6:00 PM</p>
    </div>

    <div class="detail-card">
        <h3>📍 Venue</h3>
        <p>Grand Celebration Hall<br>Hyderabad</p>
    </div>

    <div class="detail-card">
        <h3>👰 Bride</h3>
        <p>My Loving Akka 💕</p>
    </div>

    <div class="detail-card">
        <h3>🤵 Groom</h3>
        <p>My Dear Bava ❤️</p>
    </div>
</section>

<!-- Message -->
<section class="message">
    <h2>My Wishes to You 💖</h2>

    <div class="message-box">
        <p>
            Dear Akka & Bava,
        </p>

        <p>
            From childhood till today, you have always been my biggest support, my guide, 
            and my best friend, Akka. Seeing you start this beautiful new journey fills my 
            heart with happiness.
        </p>

        <p>
            Bava, thank you for coming into our family and taking care of my Akka with love 
            and respect. I know you both are made for each other.
        </p>

        <p>
            I wish you both a life full of love, laughter, success, and endless happiness. 
            May your bond grow stronger every day and your life be filled with beautiful memories.
        </p>

        <p style="margin-top:20px;">
            ❤️ Love you both forever ❤️<br>
            — Your Loving Brother
        </p>
    </div>
</section>

<!-- Footer -->
<footer>
    <p>Made with ❤️ for Akka & Bava | 2026</p>
</footer>

<!-- Countdown Script -->
<script>
    const weddingDate = new Date("May 3, 2026 18:00:00").getTime();

    const timer = setInterval(function() {
        const now = new Date().getTime();
        const distance = weddingDate - now;

        const days = Math.floor(distance / (1000 * 60 * 60 * 24));
        const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((distance % (1000 * 60)) / 1000);

        document.getElementById("countdown").innerHTML =
            days + " Days " + hours + " Hours " + minutes + " Minutes " + seconds + " Seconds ";

        if (distance < 0) {
            clearInterval(timer);
            document.getElementById("countdown").innerHTML = "Wedding Day ❤️";
        }
    }, 1000);
</script>

</body>
</html>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 A Celebration of Love. Created with ❤️</p>
    </footer>
