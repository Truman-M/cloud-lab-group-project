<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | Aroma Bistro</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <a href="index.html" class="logo">Aroma <span>Bistro</span></a>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html" class="active">Contact</a></li>
            </ul>
        </div>
    </nav>

    <div class="contact-container">
        <!-- Contact Information -->
        <div class="contact-info">
            <h2>Visit Us</h2>
            
            <div class="info-item">
                <h4>Address</h4>
                <p>123 Flavor Street<br>
                Foodie City, FC 12345</p>
            </div>
            
            <div class="info-item">
                <h4>Phone</h4>
                <p>(555) 123-4567</p>
            </div>
            
            <div class="info-item">
                <h4>Email</h4>
                <p><a href="mailto:info@bryt.com">info@bryt.com</a></p>
            </div>

            <div class="hours">
                <h4>Opening Hours</h4>
                <ul>
                    <li><strong>Monday – Thursday:</strong> 11:00 AM – 10:00 PM</li>
                    <li><strong>Friday – Saturday:</strong> 11:00 AM – 11:00 PM</li>
                    <li><strong>Sunday:</strong> 10:00 AM – 9:00 PM</li>
                </ul>
            </div>
        </div>

        <!-- Contact Form -->
        <div class="contact-form">
            <h2>Send Us a Message</h2>
            <form id="contactForm" onsubmit="handleSubmit(event)">
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name" placeholder="Your name" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" placeholder="your@email.com" required>
                </div>
                
                <div class="form-group">
                    <label for="phone">Phone Number (Optional)</label>
                    <input type="tel" id="phone" name="phone" placeholder="(555) 123-4567">
                </div>
                
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea id="message" name="message" placeholder="How can we help you?" required></textarea>
                </div>
                
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </div>

    <!-- Map placeholder -->
    <div style="max-width: 1100px; margin: -1rem auto 3rem; padding: 0 2rem;">
        <div style="background: #e8d5b7; height: 280px; border-radius: 16px; display: flex; align-items: center; justify-content: center; color: #8b5e3c; font-size: 1.1rem; text-align: center; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);">
            <div>
                <strong>📍 123 Flavor Street, Foodie City</strong><br>
                <span style="font-size: 0.95rem; opacity: 0.8;">(Interactive map would go here in a real website)</span>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2026 Aroma Bistro. All rights reserved. | 123 Flavor Street, Foodie City, FC 12345</p>
    </footer>

</script>
    <script>
        function handleSubmit(event) {
            event.preventDefault();

            const form = event.target;
            const name = form.name.value;

            // Show a nice confirmation
            alert(`Thank you, ${name}! Your message has been received. We'll get back to you within 24 hours.`);

            // Reset the form
            form.reset();
        }
    </script>
</body>
</html>
</html>
