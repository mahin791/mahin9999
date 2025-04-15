<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Fire Top Up - Get Diamonds Instantly!</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <img src="images/freefire_logo.png" alt="Free Fire Top Up">
                <h1>Free Fire Top Up</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#topup-section">Top Up</a></li>
                    <li><a href="#faq-section">FAQ</a></li>
                    <li><a href="#contact-section">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="container">
                <div class="hero-content">
                    <h2>Instant Free Fire Diamond Top Up</h2>
                    <p>Get your diamonds quickly and securely. Enjoy exclusive in-game items and bonuses!</p>
                    <a href="#topup-section" class="button">Top Up Now</a>
                </div>
                <div class="hero-image">
                    <img src="images/freefire_hero.png" alt="Free Fire Diamonds">
                </div>
            </div>
        </section>

        <section id="topup-section" class="section">
            <div class="container">
                <h2>Select Your Top Up Amount</h2>
                <div class="topup-options">
                    <div class="option" data-diamonds="100" data-price="1.00">
                        <span>100 Diamonds</span>
                        <strong>$1.00</strong>
                        <button class="select-option">Select</button>
                    </div>
                    <div class="option" data-diamonds="300" data-price="3.00">
                        <span>300 Diamonds</span>
                        <strong>$3.00</strong>
                        <button class="select-option">Select</button>
                    </div>
                    <div class="option popular" data-diamonds="500" data-price="5.00">
                        <span>500 Diamonds + Bonus</span>
                        <strong>$5.00</strong>
                        <button class="select-option">Select</button>
                    </div>
                    </ul>
                </div>

                <div class="topup-form">
                    <h3>Enter Your Game ID</h3>
                    <form id="topup-form">
                        <div class="form-group">
                            <label for="game-id">Game ID:</label>
                            <input type="text" id="game-id" name="game-id" placeholder="Enter your Free Fire Game ID" required>
                        </div>
                        <div class="form-group">
                            <label for="selected-diamonds">Diamonds:</label>
                            <input type="text" id="selected-diamonds" name="selected-diamonds" value="" readonly>
                        </div>
                        <div class="form-group">
                            <label for="total-price">Total Price:</label>
                            <input type="text" id="total-price" name="total-price" value="" readonly>
                        </div>
                        <button type="submit" class="button primary">Proceed to Payment</button>
                        <p class="payment-note">Secure payment gateway integration will be here.</p>
                    </form>
                </div>
            </div>
        </section>

        <section id="faq-section" class="section">
            <div class="container">
                <h2>Frequently Asked Questions</h2>
                <div class="faq-item">
                    <h3>How do I find my Free Fire Game ID?</h3>
                    <p>Your Game ID is a unique number that identifies your Free Fire account. You can find it in your profile section within the game.</p>
                </div>
                <div class="faq-item">
                    <h3>How long does it take to receive the diamonds?</h3>
                    <p>Diamonds are usually credited to your account instantly after successful payment.</p>
                </div>
                </div>
            </div>
        </section>

        <section id="contact-section" class="section">
            <div class="container">
                <h2>Contact Us</h2>
                <p>If you have any questions or need assistance, feel free to contact us.</p>
                <form id="contact-form">
                    <div class="form-group">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="button">Send Message</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Free Fire Top Up. All rights reserved.</p>
            <p>This is a fan-made website and is not affiliated with or endorsed by Garena.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
