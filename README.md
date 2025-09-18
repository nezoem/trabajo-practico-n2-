<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cafe Menu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="menu">
    <header>
      <h1>CAMPER CAFE</h1>
      <p class="established">Est. 2020</p>
    </header>
    <hr>
    <section>
      <h2>Coffee</h2>
      <img src="https:                                                                         
      <article class="item">
        <p class="flavor">French Vanilla</p><p class="price">3.00</p>
      </article>
      <article class="item">
        <p class="flavor">Caramel Macchiato</p><p class="price">3.75</p>
      </article>
      <article class="item">
        <p class="flavor">Pumpkin Spice</p><p class="price">3.50</p>
      </article>
      <article class="item">
        <p class="flavor">Hazelnut</p><p class="price">4.00</p>
      </article>
      <article class="item">
        <p class="flavor">Mocha</p><p class="price">4.50</p>
      </article>
    </section>
    <section>
      <h2>Desserts</h2>
      <img src="https://cdn.freecodecamp.org/curriculum/css-cafe/pie.jpg" alt="pie icon">
      <article class="item">
        <p class="dessert">Donut</p><p class="price">1.50</p>
      </article>
      <article class="item">
        <p class="dessert">Cherry Pie</p><p class="price">2.75</p>
      </article>
      <article class="item">
        <p class="dessert">Cheesecake</p><p class="price">3.00</p>
      </article>
      <article class="item">
        <p class="dessert">Cinnamon Roll</p><p class="price">2.50</p>
      </article>
    </section>
    <hr class="bottom-line">
    <footer>
      <p><a href="https:                                             
      <p class="address">Ies Manuel Belgrano</p>
    </footer>
  </div>
</body>
</html>
body {
  background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
  font-family: sans-serif;
  padding: 20px;
}

.menu {
  width: 80%;
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
  padding: 20px;
  background-color: burlywood;
}

h1, h2 {
  font-family: Impact, serif;
}

h1 {
  font-size: 40px;
  margin-top: 0;
  margin-bottom: 15px;
}

h2 {
  font-size: 30px;
}

.established {
  font-style: italic;
}

.item p {
  display: inline-block;
  margin-top: 5px;
  margin-bottom: 5px;
  font-size: 18px;
}

.flavor, .dessert {
  text-align: left;
  width: 75%;
}

.price {
  text-align: right;
  width: 25%;
}

img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

hr {
  height: 2px;
  background-color: brown;
  border-color: brown;
}

.bottom-line {
  margin-top: 25px;
}

footer {
  font-size: 14px;
}

a {
  color: black;
}

a:visited {
  color: grey;
}

a:hover {
  color: brown;
}

a:active {
  color: white;
}

.address {
  margin-bottom: 5px;
}
