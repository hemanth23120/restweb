# Ex.07 Restaurant Website
## Date:

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
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <!-- Banner Section -->
  <section class="banner" style="text-align: center; position: relative;">
    <img src="Background.png" alt="Restaurant Banner" style="width:100%; height:auto; display:block;">
    <div style="position: absolute; top: 40%; left: 50%; transform: translate(-50%, -50%); color: white; text-shadow: 2px 2px 5px black;">
      <h1>Welcome to Our Restaurant</h1>
      <p>Delicious food, made with love!</p>
    </div>
  </section>

  <!-- About Section -->
  <section style="padding: 40px; text-align: center;">
    <h2>About Us</h2>
    <p>
      We serve fresh, tasty, and hygienic food to satisfy your cravings.  
      From traditional Indian dishes to global flavors, we bring the best of both worlds.  
      Visit us and enjoy a wonderful dining experience with your friends and family.
    </p>
  </section>

  <!-- Highlights -->
  <section style="padding: 40px; background-color: #f9f9f9; text-align: center;">
    <h2>Why Choose Us?</h2>
    <div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap; margin-top: 20px;">
      <div style="max-width: 250px;">
        <h3>🍽️ Quality Food</h3>
        <p>We use only fresh ingredients to prepare mouth-watering dishes.</p>
      </div>
      <div style="max-width: 250px;">
        <h3>👨‍🍳 Expert Chefs</h3>
        <p>Our chefs bring authentic taste and creativity to every dish.</p>
      </div>
      <div style="max-width: 250px;">
        <h3>🏠 Cozy Ambience</h3>
        <p>Enjoy your meals in a comfortable and welcoming environment.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>Designed by Deepika Annamalai</p>
  </footer>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <h2 style="text-align:center; margin-top:20px;">Our Menu</h2>

  <section class="menu-grid">
    <div class="item">
      <img src="Pizza.png" alt="Pizza">
      <h3>Pizza</h3>
      <p>₹250</p>
    </div>
    <div class="item">
      <img src="Burger.png" alt="Burger">
      <h3>Burger</h3>
      <p>₹150</p>
    </div>
    <div class="item">
      <img src="Pasta.png" alt="Pasta">
      <h3>Pasta</h3>
      <p>₹180</p>
    </div>
    <div class="item">
      <img src="Sandwich.png" alt="Sandwich">
      <h3>Sandwich</h3>
      <p>₹120</p>
    </div>
    <div class="item">
      <img src="Salad.png" alt="Salad">
      <h3>Salad</h3>
      <p>₹100</p>
    </div>
    <div class="item">
      <img src="Soup.png" alt="Soup">
      <h3>Soup</h3>
      <p>₹90</p>
    </div>
    <div class="item">
      <img src="Biriyani.png" alt="Biriyani">
      <h3>Biryani</h3>
      <p>₹220</p>
    </div>
    <div class="item">
      <img src="Idli.png" alt="Idli">
      <h3>Idli</h3>
      <p>₹60</p>
    </div>
    <div class="item">
      <img src="Dosa.png" alt="Dosa">
      <h3>Dosa</h3>
      <p>₹80</p>
    </div>
    <div class="item">
      <img src="IceCream.png" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>₹70</p>
    </div>
    <div class="item">
      <img src="Juice.png" alt="Juice">
      <h3>Juice</h3>
      <p>₹50</p>
    </div>
    <div class="item">
      <img src="Cake.png" alt="Cake">
      <h3>Cake</h3>
      <p>₹150</p>
    </div>
  </section>

  <footer>
    <p>Designed by Deepika A</p>
  </footer>
</body>
</html>


admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Administration - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <h2>Administration Team</h2>
  <section class="admin-grid">
    <div class="person"><img src="Manager.png" alt="Person 1"><p>Manager</p></div>
    <div class="person"><img src="Chef.png" alt="Person 2"><p>Chef</p></div>
    <div class="person"><img src="Assistant Chef.png" alt="Person 3"><p>Assistant Chef</p></div>
    <div class="person"><img src="Cashier.png" alt="Person 4"><p>Cashier</p></div>
    <div class="person"><img src="Waiter.png" alt="Person 5"><p>Waiter</p></div>
    <div class="person"><img src="Cleaner.png" alt="Person 6"><p>Cleaner</p></div>
  </section>

  <footer>
    <p>Designed by Deepika A</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <h2>Contact Us</h2>
  <p>Address: 123, Food Street, Chennai, India</p>
  <p>Phone: +91-8438880438</p>
  <p>Email: contact@princessrestaurant.com</p>

  <footer>
    <p>Designed by Deepika A</p>
  </footer>
</body>
</html>

```

## OUTPUT:
<img width="1162" height="786" alt="REST1" src="https://github.com/user-attachments/assets/e1547c36-23ee-4788-a4af-cc01d628c365" />


<img width="1083" height="359" alt="REST2" src="https://github.com/user-attachments/assets/d543074f-0cee-40d9-8ed9-fb0bf03a5051" />


<img width="1033" height="809" alt="Screenshot 2025-12-26 094750" src="https://github.com/user-attachments/assets/00c73094-7ad5-44b6-9344-8d7af93473f8" />
<img width="1057" height="665" alt="REST6 094806" src="https://github.com/user-attachments/assets/d362acfe-da6a-4b65-acdb-314c67433fcb" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
