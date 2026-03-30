<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Celebration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Hero Section with Countdown -->
    <section class="hero">
        <div class="hero-content">
            <h1 class="main-title">A Beautiful Beginning</h1>
            <p class="subtitle">A Celebration of Love & Joy</p>
            
            <div class="countdown-timer">
                <div class="countdown-box">
                    <span id="days" class="countdown-number">0</span>
                    <p class="countdown-label">Days</p>
                </div>
                <div class="countdown-box">
                    <span id="hours" class="countdown-number">0</span>
                    <p class="countdown-label">Hours</p>
                </div>
                <div class="countdown-box">
                    <span id="minutes" class="countdown-number">0</span>
                    <p class="countdown-label">Minutes</p>
                </div>
                <div class="countdown-box">
                    <span id="seconds" class="countdown-number">0</span>
                    <p class="countdown-label">Seconds</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Wedding Details -->
    <section class="details">
        <div class="container">
            <h2>Wedding Details</h2>
            
            <div class="details-grid">
                <div class="detail-card">
                    <div class="detail-icon">📅</div>
                    <h3>Date & Time</h3>
                    <p id="eventDate">Coming Soon</p>
                    <input type="hidden" id="dateInput" value="2026-05-15T18:00:00">
                </div>
                
                <div class="detail-card">
                    <div class="detail-icon">📍</div>
                    <h3>Venue</h3>
                    <p>Grand Celebration Hall<br>Your City, Your State</p>
                </div>
                
                <div class="detail-card">
                    <div class="detail-icon">👰</div>
                    <h3>The Bride</h3>
                    <p>Your Sister's Name<br>A Beautiful Soul</p>
                </div>
                
                <div class="detail-card">
                    <div class="detail-icon">💍</div>
                    <h3>The Groom</h3>
                    <p>Groom's Name<br>A Perfect Match</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery">
        <div class="container">
            <h2>Beautiful Moments</h2>
            
            <div class="gallery-grid">
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1519741497674-611481863552?w=500&h=500&fit=crop" alt="Wedding moment 1">
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1552053831-71594a27c62d?w=500&h=500&fit=crop" alt="Wedding moment 2">
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1531746020798-e6953c6e8e04?w=500&h=500&fit=crop" alt="Wedding moment 3">
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1519741497674-611481863552?w=500&h=500&fit=crop" alt="Wedding moment 4">
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1515934751601-74f2b25a10c7?w=500&h=500&fit=crop" alt="Wedding moment 5">
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1537634066038-aca1d26f2c62?w=500&h=500&fit=crop" alt="Wedding moment 6">
                </div>
            </div>
        </div>
    </section>

    <!-- Message Section -->
    <section class="message">
        <div class="container">
            <h2>Special Message</h2>
            <div class="message-box">
                <p>
                    On this beautiful journey of marriage, we celebrate the love, commitment, and joy 
                    that brings two souls together. Here's to a lifetime of happiness, laughter, and 
                    cherished moments together.
                </p>
                <p style="margin-top: 20px; font-style: italic;">
                    With love and blessings from family! 💕
                </p>
            </div>
        </div>
    </section>

    <!-- Guest Book Section -->
    <section class="guest-book">
        <div class="container">
            <h2>Wishes & Blessings</h2>
            <form id="wishForm">
                <input type="text" id="guestName" placeholder="Your Name" required>
                <textarea id="guestMessage" placeholder="Share your wishes and blessings..." rows="5" required></textarea>
                <button type="submit" class="btn-submit">Send Wishes</button>
            </form>
            <div id="wishesList" class="wishes-list">
                <!-- Wishes will appear here -->
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 A Celebration of Love. Created with ❤️</p>
    </footer>
