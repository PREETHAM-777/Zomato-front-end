# Zomato-front-end
#html code
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400;1,700;1,900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title></title>
  </head>
  <body>
    <header>
      <nav class="navbar">
        <div class="navbar__brand">
           <img src="assets/logo.png" alt="logo" class="navbar__logo">
        </div>
        <div class="navbar__nav__items">
          <button class="nav__item button__primary">Order Food</button>
        </div>
      </nav>
    </header>
    <main class="container">
      <!-- Hero section -->
      <section class="hero__container">
        <div class="hero__image__container">
          <img src="assets/hero.jpg" alt="hero image" class="hero__image">
        </div>
        <div class="hero__description">
          <h1 class="hero__text">
            Order food from favourite restaurants near you.
          </h1>
          <button class="button__primary">Order Now</button>
        </div>
      </section>
<br>
<br>
<br>
<br>

      <!--Explore Menu-->
      <section class="explore__menu__container">
        <h1 class="explore__menu__text">Explore Our Menu</h1>
        <div class="explore__menu__gradient__bg">

        </div>
        <div class="explore__menu__lists">
          <!--Burger-->
          <div class="food__card">
            <div class="food__card__image__container">
              <img src="assets/burger.jpg" alt="burger" class="food__image">
            </div>
            <div class="food__card__description">
          <h3 class="food__title">Burger</h3>
          <p>Burger King, Mcdonalds, Burger Place <span style="color: #D83A56;">+3</span></p>
            </div>
          </div>

          <!--pizza-->
          <div class="food__card" id="pizza__card">
            <div class="food__card__image__container">
              <img src="assets/pizza.jpg" alt="burger" class="food__image">
            </div>
            <div class="food__card__description">
          <h3 class="food__title">Burger</h3>
          <p>Burger King, Mcdonalds, Burger Place <span style="color: #D83A56;">+3</span></p>
            </div>
          </div>
          <!--Ice creams-->
          <div class="food__card">
            <div class="food__card__image__container">
              <img src="assets/iceCream.jpg" alt="burger" class="food__image">
            </div>
            <div class="food__card__description">
          <h3 class="food__title">Burger</h3>
          <p>Burger King, Mcdonalds, Burger Place <span style="color: #D83A56;">+3</span></p>
            </div>
          </div>


        </div>
      </section>
    </main>
  </body>
</html>
