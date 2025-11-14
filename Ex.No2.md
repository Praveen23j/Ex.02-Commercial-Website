# Ex02 Commercial Website
## Date:3/9/25

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
commercial.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Purrfect Cat Store</title>
  <link rel="stylesheet" href="text.css">
</head>
<body>
  <header>
    <h1> Purrfect Cat Store </h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#account">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Welcome to the Purrfect Cat Store!</h2>
    <p>Find everything your feline friend needs — toys, food, and cozy accessories.</p>
    <img src="download (3).jpeg" alt="Cute Cat">
  </section>

  <section id="products" class="flex-section">
    <h2>Our Products</h2>
    <div class="flex-container">
      <div class="card">
        <img src="download.jpeg" alt="Cat Toy">
        <h3>Cat Toys</h3>
        <p>Interactive and fun toys for endless playtime.</p>
      </div>
      <div class="card">
        <img src="download (1).jpeg" alt="Cat Food">
        <h3>Cat Food</h3>
        <p>Healthy and nutritious food for happy cats.</p>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>At Purrfect Cat Store, we love cats as much as you do. Our mission is to provide top-quality cat products that keep your furry friends healthy and happy.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@purrfectcats.com</p>
    <p>Phone: +91 123456789</p>
  </section>

  <section id="account">
    <h2>User Account</h2>
    <form>
      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">
      <button type="submit">Login</button>
    </form>
  </section>

  <footer>
    <p>Follow us on:
      <a href="#">Facebook</a> |
      <a href="#">Instagram</a> |
      <a href="#">Twitter</a>
    </p>
    <p>&copy; 2025 Purrfect Cat Store | Aadi pranav S, Reg. No: 21224230001</p>
  </footer>
</body>
</html>
```
text.css
```
.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #fff8f0;
  color: #333;
}

header {
  background: #ff9a8b;
  color: white;
  padding: 15px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav ul li a:hover {
  text-decoration: underline;
}

.hero {
  text-align: center;
  padding: 40px;
  background: #ffd6c0;
}

.hero img {
  margin-top: 20px;
  border-radius: 10px;
  box-shadow: 2px 2px 10px #aaa;
}

.flex-section {
  padding: 40px;
  text-align: center;
}

.flex-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.card {
  background: white;
  border-radius: 10px;
  padding: 20px;
  width: 250px;
  box-shadow: 2px 2px 10px #aaa;
  transition: transform 0.3s;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

.card:hover {
  transform: scale(1.05);
}

#about, #contact, #account {
  padding: 40px;
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  max-width: 300px;
  margin: auto;
}

form input, form button {
  padding: 10px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

form button {
  background: #ff9a8b;
  color: white;
  border: none;
  cursor: pointer;
}

form button:hover {
  background: #ff6f61;
}

footer {
  background: #ff9a8b;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
```

## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2025-09-03 154020" src="https://github.com/user-attachments/assets/374aaed2-3913-499b-8ea4-98b338dad6e5" />
<img width="1920" height="1200" alt="Screenshot 2025-09-03 154028" src="https://github.com/user-attachments/assets/83d51f18-9927-463e-b573-c5cc2eb47878" />

<img width="1920" height="1200" alt="Screenshot 2025-09-03 154035" src="https://github.com/user-attachments/assets/530e689a-dc17-4384-abd2-7d9496461bc7" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
