# Ex.07 Restaurant Website
## Date: 13.12.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
`home.html`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="lemon">
            <h1>Little Lemon</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="menu.html" target="_blank">Menu</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="contacts.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner">
          <h2>30% Off This Weekend</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
        </section>
        <section class="info-grid">
            <div class="info-card">
                <img src="https://img.freepik.com/free-psd/restaurant-food-menu-poster-design-template_47987-16881.jpg?t=st=1733836478~exp=1733840078~hmac=350f724024c67e9ff14dcb6dbe37fb2cd81fbff6a1c332528d1270c6376a73c4&w=740" alt="New Menu">
                <h3>Our New Menu</h3>
                <p>Our new menu is a delightful blend of classic favorites and exciting new creations, crafted to tantalize your taste buds. Featuring fresh, high-quality ingredients and innovative recipes, each dish is designed to deliver a unique dining experience. From mouthwatering appetizers to indulgent desserts, there’s something for everyone to enjoy. Savor our signature dishes or try something new, expertly prepared by our talented chefs. Whether you’re in the mood for a hearty meal or a light bite, our menu offers a variety of options to suit all palates. Come explore the flavors of our new menu and elevate your dining experience!</p>
                <a href="menu.html">
                  <button>See our new menu
                  </button>
                </a>
            </div>
            <div class="info-card">
              <img
                src="https://media.gettyimages.com/id/1226046055/photo/3d-rendering-of-a-luxury-restaurant-interior.jpg?s=612x612&w=0&k=20&c=vph6561o_UR0lGNLj7ClNeIR2xsyctlGcFNF95OaYss="
                alt="Book a Table">
              <h3>Book a Table</h3>
              <p>Book a table now so that we can prepare the best experience for you based on your taste.</p>
              <form class="booking-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone Number" required>
                <input type="date" name="date" required>
                <input type="time" name="time" required>
                <center><button type="submit">Book Now</button></center>
              </form>
            </div>
            <div class="info-card">
                <img src="https://img.freepik.com/free-photo/young-woman-holding-shop-sign_23-2148731708.jpg?t=st=1733837783~exp=1733841383~hmac=226697454d935446c091c6f5c5530cd365d1157597c35b0cba948150e48bb83a&w=360" alt="Opening Hours">
                <h3>Opening Hours</h3>
                <p>We are open throughout the week to serve you the finest culinary delights! Join us during weekdays from 2:00 PM to 10:00 PM for a relaxing dining experience. On Saturdays, we extend our hours to 2:00 PM to 11:00 PM, perfect for your weekend plans. On Sundays, we welcome you from 2:00 PM to 9:00 PM, offering a cozy atmosphere to wind down the weekend. Whether it’s lunch, dinner, or a special occasion, our team is here to make your visit memorable. Come dine with us and experience exceptional service and delicious food at your convenience!</p>
                <p><strong>Mon-Fri:</strong> 2pm - 10pm<br>
                   <strong>Sat:</strong> 2pm - 11pm<br>
                   <strong>Sun:</strong> 2pm - 9pm</p>
            </div>
        </section>
    </main>
    <footer>
        <div class="footer-logo">
            <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="Little Lemon Logo">
            <p>Little Lemon</p>
        </div>
        <p>Designed and Developed by S Rajath - 24900186</p>
    </footer>
</body>
</html>
```

`menu.html`
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header>
    <div class="logo">
      <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="lemon">
      <h1>Little Lemon</h1>
    </div>
    <nav>
      <ul>
        <li><a href="home.html" target="_blank">Home</a></li>
        <li><a href="#" target="_blank">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contacts.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section class="banner">
      <h2>30% Off This Weekend</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
    </section>
    <section class="menu">
      <div class="menu-item">
        <h3>Pizza</h3>
        <p>Rs 200/-</p>
      </div>
      <div class="menu-item">
        <h3>Pasta</h3>
        <p>Rs 150/-</p>
      </div>
      <div class="menu-item">
        <h3>Burger</h3>
        <p>Rs 100/-</p>
      </div>
      <div class="menu-item">
        <h3>Salad</h3>
        <p>Rs 50/-</p>
      </div>
      <div class="menu-item">
        <h3>Sushi</h3>
        <p>Rs 120/-</p>
      </div>
      <div class="menu-item">
        <h3>Soup</h3>
        <p>Rs 70/-</p>
      </div>
      <div class="menu-item">
        <h3>Fries</h3>
        <p>Rs 90/-</p>
      </div>
      <div class="menu-item">
        <h3>Steak</h3>
        <p>Rs 150/-</p>
      </div>
      <div class="menu-item">
        <h3>Tacos</h3>
        <p>Rs 500/-</p>
      </div>
      <div class="menu-item">
        <h3>Ice Cream</h3>
        <p>Rs 120/-</p>
      </div>
      <div class="menu-item">
        <h3>Coffee</h3>
        <p>Rs 130/-</p>
      </div>
      <div class="menu-item">
        <h3>Juice</h3>
        <p>Rs 60/-</p>
      </div>
    </section>
    <h2 class="cmb">Combo Offers</h2>
    <section class="combo-offers">
      <div class="combo-card">
        <h3>Pizza & Pasta Combo</h3>
        <p>Rs 300/-</p>
        <p>Enjoy a delicious pizza and pasta combo at a special price!</p>
      </div>
      <div class="combo-card">
        <h3>Burger & Fries Combo</h3>
        <p>Rs 150/-</p>
        <p>Get a juicy burger with crispy fries for a perfect meal.</p>
      </div>
      <div class="combo-card">
        <h3>Sushi & Soup Combo</h3>
        <p>Rs 180/-</p>
        <p>Experience the taste of sushi paired with a warm soup.</p>
      </div>
    </section>
  </main>
  <footer>
    <div class="footer-logo">
      <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="Little Lemon Logo">
      <p>Little Lemon</p>
    </div>
    <p>Designed and Developed by S Rajath - 24900186</p>
  </footer>
</body>
</html>
```
`admin.html`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="lemon">
            <h1>Little Lemon</h1>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html" target="_blank">Menu</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="contacts.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner">
          <h2>Meet our team</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa.</p>
        </section>
        <section class="team">
            <div class="member">
                <img src="https://imgs.search.brave.com/Y_-CrFYeVJR1kw2x0kxhnZi8aTIskFW1i-akv57EZgk/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly93YWxs/cGFwZXJjYXZlLmNv/bS93cC8zQXlxVHBL/LmpwZw" alt="Team Member">
                <h3>Tony Stark</h3>
                <p>Chief Cook</p>
            </div>
            <div class="member">
                <img src="https://imgs.search.brave.com/ejD5PHYKfg3Zw9ve744XY-sU-XcZj6TSuuN4ht8ADJ8/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tLm1l/ZGlhLWFtYXpvbi5j/b20vaW1hZ2VzL00v/TVY1QllUUTNORFUz/WWpFdE1EUXhOaTAw/TjJReExXSXhOakF0/TW1GbE9XTTVaRFkz/TUdWa1hrRXlYa0Zx/Y0djQC5qcGc" alt="Team Member">
                <h3>Veera Raghavan</h3>
                <p>CEO, Manager</p>
            </div>
            <div class="member">
                <img src="https://imgs.search.brave.com/CDi8ANg6A1zJfSEKaXa6p2No0f1ZIH6xxdYxXcRR2Fs/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvOTk4/ODM3MjcvcGhvdG8v/bG9uZG9uLWVuZ2xh/bmQtYWN0b3ItaHJp/dGhpay1yb3NoYW4t/YXR0ZW5kcy10aGUt/ZXVyb3BlYW4tcHJl/bWllcmUtb2Yta2l0/ZXMtYXQtb2Rlb24t/d2VzdC1lbmQtb24u/anBnP3M9NjEyeDYx/MiZ3PTAmaz0yMCZj/PW90R1ZHelZhMWpY/WDZqdUloY0sxRlRh/c0JBWHFBXzlqUzhv/UzM5WkN3NmM9" alt="Team Member">
                <h3>Rajveer</h3>
                <p>Asst. Cook</p>
            </div>
            <div class="member">
                <img src="https://imgs.search.brave.com/UAs2LzqlxFJmddTV2-YlFsEYK98qIzW9CTAa6CooNYs/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pLnBp/bmltZy5jb20vb3Jp/Z2luYWxzLzEyL2Jl/L2U0LzEyYmVlNDg0/ODliZmMyYzA2Zjcy/N2YxZWRiYjM0MmZl/LmpwZw" alt="Team Member">
                <h3>Dark Devil</h3>
                <p>Marketing Director</p>
            </div>
            <div class="member">
                <img src="https://imgs.search.brave.com/nkGImihmaoyWnpkuuz3XQ_n6Ju1EdMhhEfKuVTVfvEg/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly93YWxs/cGFwZXJzLmNvbS9p/bWFnZXMvaGQvcm9u/YWxkby0yMDQ4LXgt/MTUzNi1waWN0dXJl/LXVuOGRpaGx6Z3N0/bmc1N3guanBn" alt="Team Member">
                <h3>Chrono</h3>
                <p>Head of Finance</p>
            </div>
            <div class="member">
                <img src="https://imgs.search.brave.com/ohKlry6IGxdQyeyTpr0Ly928-f0HbwBEcOPCVomY9CE/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvODUy/MzEwNTYvcGhvdG8v/dW5zcGVjaWZpZWQt/cGhvdG8tb2YtZW1p/bmVtLmpwZz9zPTYx/Mng2MTImdz0wJms9/MjAmYz1QOU90bWJP/b0tRaWhoY3piLVlf/ZWJ2UGNzRThUcEpf/R1dvYm5RRkNQZzY4/PQ" alt="Team Member">
                <h3>Eminem</h3>
                <p>Quality Checker</p>
            </div>
        </section>
    </main>
    <footer>
        <div class="footer-logo">
            <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="Little Lemon Logo">
            <p>Little Lemon</p>
        </div>
        <p>Designed and Developed by S Rajath - 24900186</p>
    </footer>
</body>
</html>
```
`contacts.html`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="lemon">
            <h1>Little Lemon</h1>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html" target="_blank">Menu</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="contact-us">
            <h2>Contact Us</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get in Touch</h3>
                    <p>Feel free to reach out to us for any inquiries or reservations.</p>
                    <p><strong>Email:</strong> contact@littlelemon.com</p>
                    <p><strong>Phone:</strong> +91 12345 67890</p>
                    <p><strong>Address:</strong> 123 Lemon Street, Dholakpur</p>
                </div>
                <form class="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
            </div>
        </section>
    </main>
    <footer>
        <div class="footer-logo">
            <img src="https://www.freeiconspng.com/uploads/lemon-png-3.png" alt="Little Lemon Logo">
            <p>Little Lemon</p>
        </div>
        <p>Designed and Developed by S Rajath - 24900186</p>
    </footer>
</body>
</html>
```
`style.css`
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #f8f9fa;
}

header {
    background-color: #ffffff;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-bottom: 2px solid #ccc;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.banner {
    background: url('https://img.freepik.com/free-photo/fresh-gourmet-meal-grilled-beef-salad-generated-by-ai_188544-10126.jpg?t=st=1733838908~exp=1733842508~hmac=4a57584873ad10ac05390420d2870566a0bdd03f9f66733f3cb87fdc7645cffb&w=1380') no-repeat center center;
    background-size: cover;
    margin-right: 2%;
    margin-left: 2%;
    margin-top: 1%;
    border-radius: 37px;
    text-align: center;
    color: #fff;
    padding: 50px 20px;
}

.banner h2 {
    font-size: 36px;
    margin-bottom: 10px;
}

.banner p {
    font-size: 18px;
}

.info-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    padding: 40px 20px;
}

.info-card {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.info-card img {
    max-width: 100%;
    border-radius: 8px;
}

.info-card h3 {
    font-size: 24px;
    margin: 15px 0;
}

.info-card p {
    font-size: 16px;
    color: #666;
}

.info-card a button {
    background-color: #007bff;
    border: solid;
    padding: 15px;
    border-radius: 9px;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: background-color 0.3s;
}

.info-card a button:hover {
    color: #007bff;
    border: solid;
    padding: 15px;
    border-radius: 9px;
    background-color: #fff;
    text-decoration: none;
    font-weight: bold;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin-top: 20px;
}

.footer-logo {
    display: flex;
    align-items: center;
    justify-content: center;
}

footer .footer-logo img {
    height: 40px;
    margin-bottom: 10px;
}

footer p {
    margin: 0;
}

.menu {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
    background-color: #f9f9f9;
}

.menu-item {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.menu-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.menu-item h3 {
    margin: 0;
    font-size: 20px;
    color: #007bff;
}

.menu-item p {
    margin: 10px 0 0;
    font-size: 16px;
    color: #555;
}

.combo-offers {
    display: flex;
    padding: 40px 20px;
    background-color: #f9f9f9;
    text-align: center;
}

.cmb {
    text-align: center;
    font-size: 28px;
    margin-bottom: 20px;
    color: #007bff;
}


.combo-card {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin: 20px auto;
    max-width: 300px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.combo-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.combo-card h3 {
    margin: 0;
    font-size: 22px;
    color: #333;
}

.combo-card p {
    margin: 10px 0;
    color: #555;
}

.team {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 40px 20px;
    background-color: #ffffff;
}

.member {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.member img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    margin-bottom: 15px;
    object-fit: cover;
}

.member h3 {
    margin: 10px 0;
    font-size: 20px;
    color: #007bff;
}

.member p {
    color: #555;
    font-size: 16px;
}

.contact-us {
    padding: 40px 20px;
    background-color: #f1f1f1;
    text-align: center;
}

.contact-us h2 {
    font-size: 28px;
    margin-bottom: 20px;
    color: #007bff;
}

.contact-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
}

.contact-info {
    max-width: 400px;
    text-align: left;
}

.contact-info h3 {
    font-size: 22px;
    color: #333;
}

.contact-info p {
    color: #555;
    margin: 5px 0;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    max-width: 400px;
    width: 100%;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 16px;
}

.contact-form textarea {
    resize: vertical;
    height: 100px;
}

.contact-form button {
    background-color: #007bff;
    color: #fff;
    border: solid #007bff;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.contact-form button:hover {
    background-color: #fff;
    border: solid;
    border-color: #007bff;
    color: #007bff;
}


.booking-form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin-top: 10px;
    margin-right: 20px;
}

.booking-form input {
    width: 100%;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 16px;
}

.booking-form button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.booking-form button:hover {
    background-color: #0056b3;
}
```
## OUTPUT:

**home page**
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/home1.png)
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/home2.png)

**menu page**
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/menu1.png)
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/menu2.png)

**administration page**
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/admin1.png)
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/admin2.png)

**contacts page**
![alt text](file:///C:/Users/TonyStark/Documents/Education/WebApplication/HTML/contact.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
