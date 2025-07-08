andex.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hicham Cook Restaurant Menu</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
</head>

<body>

  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#appetizers">Appetizers</a></li>
      <li><a href="#mains">Main Dishes</a></li>
      <li><a href="#desserts">Desserts</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <header>
    <h1>🍽️ Hicham Cook Restaurant Menu</h1>
    <p>Discover the finest Algerian and international dishes with a creative twist!</p>
  </header>

  <section id="appetizers" class="menu-section">
    <h2>🥗 Appetizers & Salads</h2>
    <div class="card-grid">
      <div class="card">
        <img src="https://i.imgur.com/6W6LZWy.jpg" alt="Caesar Salad">
        <h3>Hicham Caesar Salad</h3>
        <p>Fresh lettuce, crispy chicken, and creamy Caesar dressing.</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/OxhvPq6.jpg" alt="Mashed Potatoes">
        <h3>Spiced Mashed Potatoes</h3>
        <p>Soft potatoes blended with Algerian-style spices and butter.</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/LWjVZCB.jpg" alt="Grilled Starters">
        <h3>Grilled Mix Starters</h3>
        <p>Grilled seasonal veggies and meat bites.</p>
      </div>
    </div>
  </section>

  <section id="mains" class="menu-section">
    <h2>🍔 Main Dishes</h2>
    <div class="card-grid">
      <div class="card">
        <img src="https://i.imgur.com/TcVRlsT.jpg" alt="Burger">
        <h3>Hicham Signature Burger</h3>
        <p>Grilled beef patty, special bun, and our secret sauce.</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/D0jVlnV.jpg" alt="Shawarma">
        <h3>Grilled Shawarma</h3>
        <p>Spiced meat served with flatbread, veggies, and white sauce.</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/qxokZ1V.jpg" alt="Mixed Grill">
        <h3>Mixed Grill Platter</h3>
        <p>Ribs, kofta, sausage with grilled zucchini and fresh bread.</p>
      </div>
    </div>
  </section>

  <section id="desserts" class="menu-section">
    <h2>🍰 Desserts & Drinks</h2>
    <div class="card-grid">
      <div class="card">
        <img src="https://i.imgur.com/qHvkhOV.jpg" alt="Zlabia">
        <h3>Zlabia</h3>
        <p>Traditional Algerian sweet, deep-fried and dipped in honey.</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/RM7ybnJ.jpg" alt="Baklava">
        <h3>Baklava</h3>
        <p>Nut-filled layered pastry soaked in syrup.</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/AsN9qlf.jpg" alt="Drinks">
        <h3>Refreshing Drinks</h3>
        <p>Fresh juices, soda, and herbal teas.</p>
      </div>
    </div>
  </section>

  <footer>
    <p><a href="contact.html">📞 Contact us for orders or reservations</a></p>
  </footer>

</body>
</html>

styles.css
body {
  font-family: 'Roboto', sans-serif;

  margin: 0;
  background-color: #fefefe;
  color: #333;
}

nav {
  background: #222;
  padding: 15px 0;
  text-align: center;
}
nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
nav ul li {
  display: inline-block;
  margin: 0 15px;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}
nav ul li a:hover {
  color: #ffcc00;
}

header {
  text-align: center;
  padding: 30px 20px;
}
header h1 {
  margin-bottom: 10px;
  color: #d32f2f;
}
header p {
  font-size: 18px;
  color: #555;
}

.menu-section {
  padding: 40px 20px;
  max-width: 1200px;
  margin: auto;
}
.menu-section h2 {
  text-align: center;
  margin-bottom: 30px;
  color: #c2185b;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

.card {
  background: #fff;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.15);
}
.card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}
.card h3 {
  margin: 15px;
  font-size: 20px;
  color: #d32f2f;
}
.card p {
  margin: 0 15px 20px;
  color: #555;
}

footer {
  text-align: center;
  background: #f5f5f5;
  padding: 30px;
  margin-top: 40px;
}
footer a {
  text-decoration: none;
  font-weight: bold;
  color: #1976d2;
}
footer a:hover {
  color: #0d47a1;
}

@media (max-width: 600px) {
  nav ul li {
    display: block;
    margin: 10px 0;
  }
}
