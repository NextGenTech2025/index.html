<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NextGen Tech Ultimate Indicator</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
    body { background: #0e0e0e; color: #fff; line-height: 1.6; }
    header { background: #1e1e1e; padding: 2rem; text-align: center; }
    header h1 { font-size: 2.5rem; color: #00e0ff; }
    header p { margin-top: 0.5rem; color: #ccc; font-size: 1.2rem; }
    .features { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; padding: 2rem; max-width: 1000px; margin: auto; }
    .feature { background: #1a1a1a; padding: 1.5rem; border-radius: 12px; border-left: 4px solid #00e0ff; }
    .feature h3 { color: #00e0ff; margin-bottom: 0.5rem; }
    .cta { text-align: center; padding: 2rem; background: #121212; }
    .cta h2 { font-size: 2rem; color: #00e0ff; margin-bottom: 1rem; }
    .cta p { color: #ccc; margin-bottom: 1.5rem; }
    .cta a.button { background: #00e0ff; color: #000; padding: 1rem 2rem; text-decoration: none; font-weight: bold; border-radius: 8px; transition: background 0.3s ease; display: inline-block; margin: 0.5rem; }
    .cta a.button:hover { background: #00c0d6; }
    .qr-code { margin-top: 1.5rem; }
    .success-message { display: none; background: #1e1e1e; padding: 1rem; margin-top: 1rem; color: #4caf50; border-radius: 8px; font-weight: bold; }
    .testimonial { background: #1a1a1a; padding: 1.5rem; border-radius: 12px; margin: 2rem auto; max-width: 800px; border-left: 4px solid #4caf50; }
    .testimonial h3 { color: #4caf50; margin-bottom: 1rem; }
    .testimonial p { color: #ccc; font-style: italic; }
    footer { background: #1e1e1e; padding: 1rem; text-align: center; font-size: 0.9rem; color: #888; }
  </style>
  <script>
    function showSuccessMessage() {
      document.getElementById('success-message').style.display = 'block';
      window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
    }
  </script>
</head>
<body>

<header>
  <h1>NextGen Tech - Ultimate Indicator</h1>
  <p>Smarter Trading Starts Here – For Crypto, Gold & Nifty/BankNifty Traders</p>
</header>

<section class="features">
  <div class="feature">
    <h3>✔ Real-Time Buy/Sell Signals</h3>
    <p>Get instant visual signals powered by advanced ATR logic and EMAs.</p>
  </div>
  <div class="feature">
    <h3>✔ ATR-Based Trailing Stop</h3>
    <p>Stay in trends longer with smart auto-adjusted stop levels.</p>
  </div>
  <div class="feature">
    <h3>✔ Heikin Ashi Support</h3>
    <p>Switch to smoother candle data to filter out noise and false entries.</p>
  </div>
  <div class="feature">
    <h3>✔ Works on 5M, 15M, 4H Timeframes</h3>
    <p>Scalp or swing trade with precision on your preferred timeframes.</p>
  </div>
</section>

<section class="testimonial">
  <h3>📈 Real Success Stories</h3>
  <p>"Sir, I paid ₹6,999 and earned ₹10,000 profit the very next day using your signal. Best investment ever!" – <strong>Rahul S., Delhi</strong></p>
</section>

<section class="cta">
  <h2>🎯 Try Before You Buy!</h2>
  <p>Experience the power of our indicator – get a FREE DEMO and trade confidently.</p>
  <a href="https://wa.me/917400754619?text=I%20want%20a%20DEMO%20of%20NextGen%20Tech%20Ultimate" class="button">📲 DM "DEMO" on WhatsApp</a>
  <a href="https://rzp.io/l/nextgentech6999" class="button" onclick="showSuccessMessage()">💳 Pay ₹6,999 via Razorpay</a>
  <div class="qr-code">
    <img src="https://api.qrserver.com/v1/create-qr-code/?data=https://rzp.io/l/nextgentech6999&size=150x150" alt="QR Code to Pay ₹6999" />
    <p style="color: #ccc; font-size: 0.9rem;">Scan to Pay Instantly</p>
  </div>
  <div id="success-message" class="success-message">
    ✅ Payment Link Opened! Complete your payment and message us on WhatsApp for instant access.
  </div>
</section>

<footer>
  &copy; 2025 NextGen Tech. All rights reserved.
</footer>

</body>
</html>
