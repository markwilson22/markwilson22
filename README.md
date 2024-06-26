- 👋 Hi, I’m @markwilson22
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
markwilson22/markwilson22 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ExploreAura - Personal Travel Agent</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .about, .services, .contact, .booking {
            margin: 20px 0;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .booking-form {
            margin-top: 20px;
        }
        .booking-form label {
            display: block;
            margin: 10px 0 5px;
        }
        .booking-form input, .booking-form select {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .booking-form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
        }
        .booking-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>ExploreAura</h1>
        <p>Your Personal Travel Agent</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#booking">Booking</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Hello! I'm Mark Wilson, the founder of ExploreAura. With years of experience in the travel industry, I am dedicated to providing personalized travel planning services to make your trips unforgettable. Whether you're looking for adventure, relaxation, or a bit of both, I've got you covered.</p>
        </section>
        <section id="services" class="services">
            <h2>Services</h2>
            <ul>
                <li>Custom Travel Planning</li>
                <li>Guided Tours</li>
                <li>Flight and Hotel Bookings</li>
                <li>Travel Insurance</li>
                <li>Destination Advice</li>
            </ul>
        </section>
        <section id="booking" class="booking">
            <h2>Booking</h2>
            <div class="booking-form">
                <h3>Book a Flight</h3>
                <form action="#" method="post">
                    <label for="flight-from">From:</label>
                    <input type="text" id="flight-from" name="flight-from" required>
                    <label for="flight-to">To:</label>
                    <input type="text" id="flight-to" name="flight-to" required>
                    <label for="flight-departure">Departure Date:</label>
                    <input type="date" id="flight-departure" name="flight-departure" required>
                    <label for="flight-return">Return Date:</label>
                    <input type="date" id="flight-return" name="flight-return">
                    <label for="flight-class">Class:</label>
                    <select id="flight-class" name="flight-class" required>
                        <option value="economy">Economy</option>
                        <option value="business">Business</option>
                        <option value="first">First Class</option>
                    </select>
                    <button type="submit">Book Flight</button>
                </form>
            </div>
            <div class="booking-form">
                <h3>Book a Hotel</h3>
                <form action="#" method="post">
                    <label for="hotel-destination">Destination:</label>
                    <input type="text" id="hotel-destination" name="hotel-destination" required>
                    <label for="hotel-checkin">Check-in Date:</label>
                    <input type="date" id="hotel-checkin" name="hotel-checkin" required>
                    <label for="hotel-checkout">Check-out Date:</label>
                    <input type="date" id="hotel-checkout" name="hotel-checkout" required>
                    <label for="hotel-rooms">Rooms:</label>
                    <input type="number" id="hotel-rooms" name="hotel-rooms" min="1" required>
                    <label for="hotel-guests">Guests:</label>
                    <input type="number" id="hotel-guests" name="hotel-guests" min="1" required>
                    <button type="submit">Book Hotel</button>
                </form>
            </div>
            <div class="booking-form">
                <h3>Book a Vacation Package</h3>
                <form action="#" method="post">
                    <label for="package-destination">Destination:</label>
                    <input type="text" id="package-destination" name="package-destination" required>
                    <label for="package-departure">Departure Date:</label>
                    <input type="date" id="package-departure" name="package-departure" required>
                    <label for="package-return">Return Date:</label>
                    <input type="date" id="package-return" name="package-return" required>
                    <label for="package-people">Number of People:</label>
                    <input type="number" id="package-people" name="package-people" min="1" required>
                    <button type="submit">Book Package</button>
                </form>
            </div>
        </section>
        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <p>If you're ready to plan your next adventure or have any questions, feel free to reach out!</p>
            <p>Email: <a href="mailto:mark@exploreaura.com">mark@exploreaura.com</a></p>
            <p>Phone: +123-456-7890</p>
            <p>Follow me on social media:</p>
            <p>
                <a href="https://facebook.com/exploreaura" target="_blank">Facebook</a> |
                <a href="https://instagram.com/exploreaura" target="_blank">Instagram</a> |
                <a href="https://twitter.com/exploreaura" target="_blank">Twitter</a>
            </p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 ExploreAura. All rights reserved.</p>
    </footer>
</body>
</html>

