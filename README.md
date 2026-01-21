<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RCJ Ride | Hamilton, Niagara & GTA</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; background-color: #1a1a1a; color: white; text-align: center; }
        .container { padding: 20px; }
        .logo-box img { max-width: 100%; height: auto; width: 500px; margin-top: 20px; }
        h1 { color: #ffcc00; }
        .btn { background-color: #ffcc00; color: black; padding: 20px 40px; text-decoration: none; font-weight: bold; font-size: 1.5rem; border-radius: 10px; display: inline-block; margin: 20px 0; }
        
        /* Form Styling */
        .quote-section { padding: 40px 20px; background: #222; border-top: 2px solid #333; }
        form { max-width: 500px; margin: 0 auto; text-align: left; }
        label { display: block; margin-top: 10px; color: #ffcc00; font-weight: bold; }
        input { width: 100%; padding: 12px; margin-top: 5px; border-radius: 5px; border: none; box-sizing: border-box; }
        .submit-btn { background: #ffcc00; color: black; border: none; padding: 15px; font-weight: bold; cursor: pointer; width: 100%; margin-top: 20px; border-radius: 5px; font-size: 1.1rem; }

        footer { padding: 40px 20px; background-color: #000; color: #fff; font-size: 0.9rem; border-top: 2px solid #333; }
        .social-links a { color: #ffcc00; text-decoration: none; margin: 0 10px; font-weight: bold; }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-box">
            <img src="logo.png" alt="RCJ Ride Logo">
        </div>
        <h1>Professional Ride Service</h1>
        <p>Hamilton • Niagara • GTA</p>
        
        <a href="tel:1647-460-6550" class="btn">📞 CLICK TO CALL</a>
    </div>

    <section class="quote-section">
        <h2>Request a Quote</h2>
        <p>Send trip details for a quick estimate!</p>
        
        <form action="https://formspree.io/f/rcjride@yahoo.com" method="POST">
            <label>Your Name:</label>
            <input type="text" name="name" required>
            
            <label>Phone Number:</label>
            <input type="tel" name="phone" required>
            
            <label>Pickup Location:</label>
            <input type="text" name="pickup" placeholder="e.g. Hamilton Airport" required>
            
            <label>Destination:</label>
            <input type="text" name="destination" placeholder="e.g. Downtown Toronto" required>
            
            <label>Date & Time:</label>
            <input type="datetime-local" name="datetime" required>
            
            <button type="submit" class="submit-btn">SUBMIT REQUEST</button>
        </form>
    </section>

    <footer>
        <p><strong>RCJ RIDE</strong></p>
        <p>Hamilton • Niagara • GTA</p>
        <p>Available 24/7 | Licensed & Insured</p>
        
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">TikTok</a>
        </div>

        <p style="color: #666; font-size: 0.8rem; margin-top: 20px;">&copy; 2026 RCJ Ride. All rights reserved.</p>
    </footer>

</body>
</html>
