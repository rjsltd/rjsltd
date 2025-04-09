- 👋 Hi, I’m @rjsltd
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
rjsltd/rjsltd is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
I’ll now generate a starter website for RJS.LTD (ticket booking agency) with:
I’ll now generate a starter website for RJS.LTD (ticket booking agency) with:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RJS.LTD - Your Travel Booking Partner</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header, footer {
      background-color: #0d6efd;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
    }
    section {
      padding: 2rem;
    }
    form input, form textarea, form select, form button {
      display: block;
      width: 100%;
      margin-bottom: 1rem;
      padding: 0.5rem;
      font-size: 1rem;
    }
    .promo {
      margin-top: 2rem;
      background-color: #e9ecef;
      padding: 1rem;
      border-radius: 8px;
    }
  </style>
</head>
<body>

<header>
  <h1>RJS.LTD</h1>
  <p>Your Gateway to Travel</p>
  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#appointment">Book</a>
    <a href="#promo">Promo</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>Welcome to RJS.LTD</h2>
  <p>We help you book tickets easily, affordably, and securely. Your journey begins with us!</p>
</section>

<section id="services">
  <h2>Our Services</h2>
  <ul>
    <li>Flight Ticket Booking</li>
    <li>Bus Ticket Booking</li>
    <li>Train Reservations</li>
    <li>Holiday Packages</li>
  </ul>
</section>

<section id="appointment">
  <h2>Book Your Tickets</h2>
  <form>
    <input type="text" placeholder="Full Name" required>
    <input type="email" placeholder="Email Address" required>
    <input type="tel" placeholder="Phone Number" required>
    <select required>
      <option value="">Select Service</option>
      <option value="flight">Flight</option>
      <option value="bus">Bus</option>
      <option value="train">Train</option>
    </select>
    <input type="date" required>
    <button type="submit">Submit</button>
  </form>
</section>

<section id="promo" class="promo">
  <h2>Apply Promo Code</h2>
  <form>
    <input type="text" placeholder="Enter Promo Code">
    <button type="submit">Apply</button>
  </form>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Your Message" rows="4" required></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 RJS.LTD. All rights reserved.</p>
</footer>

</body>
</html>
