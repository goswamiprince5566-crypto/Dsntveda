# Dsntveda
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dant-Veda Official Store</title>
    <style>
        /* SMOOTH SCROLLING */
        html { scroll-behavior: smooth; }

        /* DESIGN STYLES */
        body { margin: 0; padding: 0; font-family: 'Segoe UI', sans-serif; background-color: #f4f9f4; color: #333; }
        
        /* --- INTRO LOADER (UPDATED - SAFE MODE) --- */
        #loader {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background-color: #0b4d2e; z-index: 9999;
            display: flex; flex-direction: column; align-items: center; justify-content: center;
            color: white; transition: opacity 0.5s ease-out;
        }
        .loader-logo { font-size: 40px; font-weight: bold; animation: pulse 1s infinite; }
        .loader-text { margin-top: 10px; font-size: 14px; opacity: 0.8; }
        
        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.1); opacity: 0.8; }
            100% { transform: scale(1); opacity: 1; }
        }

        /* HEADER & NAVIGATION */
        .header { background-color: #0b4d2e; color: white; padding: 15px; text-align: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 4px 6px rgba(0,0,0,0.1); }
        .nav { background: #333; overflow: hidden; display: flex; justify-content: center; }
        .nav a { color: white; padding: 14px 15px; text-decoration: none; display: block; font-size: 14px; }
        .nav a:hover { background-color: orange; color: black; }
        
        /* SECTIONS GENERAL */
        .section { padding: 40px 20px; border-bottom: 1px solid #ddd; text-align: center; }
        
        /* FEATURES SECTION (WHY CHOOSE US) */
        .features { display: flex; justify-content: center; gap: 20px; margin-top: 20px; flex-wrap: wrap; }
        .feat-box { width: 100px; text-align: center; font-size: 12px; }
        .feat-icon { font-size: 30px; background: #e8f5e9; padding: 15px; border-radius: 50%; display: block; margin: 0 auto 10px; }

        /* HERO SECTION */
        #home { background-color: #e8f5e9; }
        .hero-box { 
            width: 90%; height: 200px; background-color: #cccccc; 
            margin: 20px auto; border: 2px dashed #000; 
            display: flex; align-items: center; justify-content: center; 
            color: #555; font-weight: bold; font-size: 14px;
        }

        /* PRODUCT SHOP */
        #shop { background: white; }
        .product-list { display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; margin-top: 20px; }
        .card { background: #f9f9f9; border: 1px solid #ddd; width: 45%; padding: 10px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        
        .prod-img-box {
            width: 100%; height: 80px; background: #ddd; 
            margin-bottom: 10px; border: 1px dashed #666;
            display: flex; align-items: center; justify-content: center; font-size: 10px;
        }
        
        /* Order Button Style */
        .order-btn { background: #25D366; color: white; padding: 10px; text-decoration: none; border-radius: 4px; display: block; margin-top: 5px; cursor: pointer; border: none; width: 100%; font-weight: bold; }
        .order-btn:hover { background: #1ebc57; }

        .btn { background: #0b4d2e; color: white; padding: 8px; text-decoration: none; border-radius: 4px; display: block; margin-top: 5px; cursor: pointer; border: none; width: 100%; font-size: 14px; }

        /* SOCIAL WORK */
        #mission { background: #dff0d8; }
        .social-box {
            width: 90%; height: 180px; background-color: #a3d9a5; 
            margin: 20px auto; border: 2px dashed #0b4d2e; 
            display: flex; align-items: center; justify-content: center; 
            color: #0b4d2e; font-weight: bold;
        }

        /* DONATE SECTION */
        #donate { background: #fff3e0; }
        .donate-container {
            background: white; border: 2px dashed #0b4d2e; padding: 20px; border-radius: 15px; width: 90%; max-width: 300px; margin: 0 auto;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .pay-btn {
            background: orange; color: white; padding: 12px; text-decoration: none; border-radius: 5px; font-weight: bold; display: block; margin-top: 15px;
        }

        /* CONTACT FORM */
        #contact { background: #333; color: white; }
        input, textarea { width: 90%; padding: 10px; margin: 5px 0; border-radius: 5px; border: none; }
        .submit-btn { background: orange; color: white; padding: 10px; border: none; border-radius: 5px; cursor: pointer; width: 100%; font-weight: bold; }

        /* FOOTER */
        .footer { background: black; color: white; text-align: center; padding: 10px; font-size: 12px; }
    </style>
</head>
<body>

    <div id="loader">
        <div class="loader-logo">🌿 DANT-VEDA</div>
        <div class="loader-text">Loading Nature's Goodness...</div>
    </div>

    <div class="header">
        <h1>🌿 DANT-VEDA</h1>
        <div class="nav">
            <a href="#home">Home</a>
            <a href="#shop">Shop</a>
            <a href="#mission">Mission</a>
            <a href="#donate">Donate</a>
        </div>
    </div>

    <div id="home" class="section">
        <h2>Nature's Care, Best Repair</h2>
        <p>Experience the power of Neem & Clove.</p>
        <div class="hero-box">
            <img src="imagee3.png" style="width: 300px; height: 200px; object-fit: cover;" alt="Hero Image"> 
        </div>
        
        <div class="features">
            <div class="feat-box">
                <span class="feat-icon">🌿</span>
                <b>100% Herbal</b>
            </div>
            <div class="feat-box">
                <span class="feat-icon">🚫</span>
                <b>No Chemicals</b>
            </div>
            <div class="feat-box">
                <span class="feat-icon">🇮🇳</span>
                <b>Made in India</b>
            </div>
        </div>

        <br>
        <button class="btn" style="background:orange; width: 60%; margin: 0 auto;" onclick="window.location.href='#shop'">EXPLORE PRODUCTS 👇</button>
    </div>

    <div id="shop" class="section">
        <h2 style="color:#0b4d2e;">🔥 BEST SELLERS</h2>
        <p style="font-size:12px; color:gray;">Click 'Order' to buy on WhatsApp</p>
        
        <div class="product-list">
            <div class="card">
                <div class="prod-img-box"><img src="imagee1.png" style="width: 100%; height: 100%; object-fit: contain;"></div>
                <h4>Mini Pack</h4>
                <p><b>Rs. 30</b></p>
                <button class="order-btn" onclick="orderOnWhatsapp('Mini Pack', 30)">ORDER NOW 💬</button>
            </div>
            
            <div class="card" style="border: 2px solid orange;">
                <div class="prod-img-box"><img src="imagee2.png" style="width: 100%; height: 100%; object-fit: contain;"></div>
                <h4>Std. Pack</h4>
                <p><b>Rs. 55</b></p>
                <button class="order-btn" onclick="orderOnWhatsapp('Standard Pack', 55)">ORDER NOW 💬</button>
            </div>
            
            <div class="card">
                <div class="prod-img-box"><img src="imagee4.png" style="width: 100%; height: 100%; object-fit: contain;"></div>
                <h4>Family Pack</h4>
                <p><b>Rs. 100</b></p>
                <button class="order-btn" onclick="orderOnWhatsapp('Family Pack', 100)">ORDER NOW 💬</button>
            </div>
        </div>
    </div>

    <div id="mission" class="section">
        <h2>🙏 MISSION MUSKURATA BHARAT</h2>
        <p>Free Dental Camps in Rural India</p>
        <div class="social-box">
             <img src="imagee.png" style="width: 359px; height: 200px; object-fit: cover;" alt="Camp Photo">
        </div>
        <p>We donate Re. 1 from every pack.</p>
        
        <button class="btn" style="width: 220px; margin: 0 auto; background: orange;" onclick="window.location.href='#donate'">
            VOLUNTEER & DONATE 👇
        </button>
    </div>

    <div id="donate" class="section">
        <h2 style="color: #0b4d2e;">🤝 SUPPORT US</h2>
        <p>Scan to contribute directly to Prince Giri.</p>

        <div class="donate-container">
            <h3 style="color: #0b4d2e; margin-top: 0;">SCAN & PAY</h3>
            
            <div style="border: 1px solid #ddd; padding: 5px; display: inline-block; border-radius: 10px; background: white;">
                <img src="imagee5.png" alt="Payment QR Code" style="width: 200px; height: auto; border-radius: 5px; display: block;">
            </div>

            <br>
            <div style="background: #f4f4f4; padding: 10px; border-radius: 5px; font-weight: bold; color: #333; border: 1px solid #ccc; margin-top: 10px;">
                UPI: 9717489130@upi
            </div>
            <p style="font-size: 12px; color: #666; margin-top: 5px;">
                Name: <b>Prince Giri</b>
            </p>

            <a href="upi://pay?pa=9717489130@upi&pn=Prince%20Giri&cu=INR" class="pay-btn">
                PAY NOW ⚡
            </a>
        </div>
    </div>

    <div id="contact" class="section">
        <h2>📞 CONSUMER SUPPORT</h2>
        <form onsubmit="alert('Message Sent Successfully!'); return false;">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="4" placeholder="Your Message / Complaint"></textarea>
            <button type="submit" class="submit-btn">SEND MESSAGE</button>
        </form>
        <br>
        <p>Helpline: 1800-111-222</p>
    </div>

    <div class="footer">
        <p>© 2025 Dant-Veda Pvt Ltd | New Delhi</p>
    </div>

    <script>
        // 1. SAFE INTRO LOADER
        // Ye loader page khulte hi chalega aur 2.5 second baad gayab ho jayega
        document.addEventListener("DOMContentLoaded", function() {
            setTimeout(function() {
                var loader = document.getElementById('loader');
                if(loader) {
                    loader.style.opacity = '0'; // Dheere se gayab
                    setTimeout(function() {
                        loader.style.display = 'none'; // Poora hata do
                    }, 500); // 0.5 second transition ke liye
                }
            }, 2500); // 2.5 Second baad hatna shuru hoga
        });

        // 2. WHATSAPP ORDER LOGIC
        function orderOnWhatsapp(productName, price) {
            var phoneNumber = "919717489130"; 
            var text = "Hello Prince, I want to order " + productName + " (Rs. " + price + "). Please confirm delivery details.";
            var encodedText = encodeURIComponent(text);
            window.open("https://wa.me/" + phoneNumber + "?text=" + encodedText, "_blank");
        }
    </script>

</body>
</html>
