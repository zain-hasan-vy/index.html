
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noor Getaways - Halal Travel in Bengaluru</title>
    <style>
        body { font-family: 'Poppins', sans-serif; margin: 0; padding: 0; background: #f8f9fa; }
        header { background: #004D40; color: white; padding: 20px; text-align: center; font-size: 1.5em; }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: url('https://source.unsplash.com/1600x900/?travel,city') no-repeat center center/cover;
            color: white;
        }
        .hero h1 { font-size: 3em; margin: 0; }
        .hero p { font-size: 1.2em; }
        .btn { background: #FF9800; color: white; padding: 12px 25px; text-decoration: none; border-radius: 5px; font-weight: bold; }
        .btn:hover { background: #E65100; }
        .section { padding: 50px 20px; text-align: center; }
        .package {
            display: inline-block;
            margin: 20px;
            padding: 20px;
            border-radius: 15px;
            width: 30%;
            background: white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .package h3 { color: #00796B; }
        .contact {
            background: #004D40;
            color: white;
            padding: 40px;
            text-align: center;
        }
        .testimonial, .blog {
            background: #fff3e0;
            padding: 40px;
            text-align: center;
        }
        .form-container {
            text-align: center;
            padding: 50px 20px;
            background: #ffffff;
        }
        form {
            display: inline-block;
            background: #f4f4f4;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: left;
        }
        form input, form select, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background: #00796B;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background: #004D40;
        }
    </style>
</head>
<body>
    <header>
        Noor Getaways - Halal Travel in Bengaluru
    </header>
    
    <div class="hero">
        <h1>Explore Bengaluru with Peace of Mind</h1>
        <p>Discover halal-friendly travel experiences, family trips, and Islamic heritage tours.</p>
        <a href="#packages" class="btn">Book Your Trip Now</a>
    </div>
    
    <div class="section" id="why">
        <h2>Why Choose Us?</h2>
        <p>✔ Halal-Certified Hotels & Food | ✔ Mosque Visits & Prayer Breaks | ✔ Family & Budget-Friendly Packages</p>
    </div>
    
    <div class="section" id="packages">
        <h2>Popular Packages</h2>
        <div class="package">
            <h3>Bengaluru City Tour</h3>
            <p>1 Day | ₹4,999</p>
            <a href="#contact" class="btn">Book Now</a>
        </div>
        <div class="package">
            <h3>Islamic Heritage Tour</h3>
            <p>2 Days | ₹6,999</p>
            <a href="#contact" class="btn">Book Now</a>
        </div>
        <div class="package">
            <h3>Luxury Halal Getaway</h3>
            <p>3 Days | ₹12,999</p>
            <a href="#contact" class="btn">Book Now</a>
        </div>
    </div>
    
    <div class="testimonial">
        <h2>What Our Customers Say</h2>
        <p>⭐⭐⭐⭐⭐ "Amazing service! Everything was halal and well-planned."</p>
        <p>⭐⭐⭐⭐⭐ "Loved the post-Ramzan getaway with my family!"</p>
    </div>
    
    <div class="blog">
        <h2>Travel Tips & Halal Guides</h2>
        <p>📖 <a href="#">Top 5 Halal Restaurants in Bengaluru</a></p>
        <p>📖 <a href="#">Best Places to Visit After Ramzan</a></p>
    </div>
    
    <div class="form-container">
        <h2>Book Your Trip</h2>
        <form action="https://formspree.io/f/your-form-id" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="package">Select Package:</label>
            <select id="package" name="package" required>
                <option value="Bengaluru City Tour">Bengaluru City Tour</option>
                <option value="Islamic Heritage Tour">Islamic Heritage Tour</option>
                <option value="Luxury Halal Getaway">Luxury Halal Getaway</option>
            </select>
            
            <label for="message">Additional Requests:</label>
            <textarea id="message" name="message" rows="4"></textarea>
            
            <button type="submit">Submit Booking</button>
        </form>
    </div>
    
    <div class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>📞 WhatsApp: +91 XXXXX XXXXX | 📩 Email: info@noorgetaways.com</p>
    </div>
</body>
</html>
