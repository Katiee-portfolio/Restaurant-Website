# Restaurant-Website
Welcome to restaurant website! Enjoy delicious food with a simple, user-friendly website. View our menu, order online, or book a table in seconds. Designed for all devices with accessibility in mind. Great taste, easy experience—just a click away!

Homepage:
<div class="container"> <!-- Container for the whole form -->
 <h2>LOGIN</h2><br> <!-- Heading for the form -->
 <form action="LandingPage.HTML" method="GET"> <!-- Form submits
data to LandingPage.HTML -->
 <strong> <!-- Makes form text bold -->
 <label for="fname">Full Name:</label> <!-- Label for name -->
 <input type="text" id="fname" name="fname" required> <!-- Name
input field -->
 <label for="email">Email:</label> <!-- Label for email -->
 <input type="email" id="email" name="email" required> <!--
Email input field -->
 <label for="password">Password:</label> <!-- Label for
password -->
 <input type="password" id="password" name="password" required>
<!-- Password input field -->
 <label for="confirm-password">Confirm Password:</label> <!--
Label for confirm password -->
 <input type="password" id="confirm-password"
name="confirm-password" required> <!-- Confirm password input -->
<form>
 <button type="submit" onclick="alert('Login
successfully!')">Submit</button> <!-- Submit button with alert -->
 </form>
 </strong>
 </form>

 Forgot password:
 <!-- Main container for the email verification form -->
 <div class="container">
 <!-- Start of the form that will send the email for verification
-->
 <form action="HomePage.HTML" method="GET">
 <!-- Label for the email input field, indicating what the user
should enter -->
 <label for="email"><strong>Enter your email for
verification:</strong></label>
 <!-- Input field for the user to enter their email address,
marked as required -->
 <input type="email" id="email" name="email" required>
 <!-- Submit button to send the data -->
 <button type="submit" onclick="alert('The verification has
been sent to your email successfully!')">Submit</button>
 </form>
 </div>

 Landing Page and Home Screenshot:
 <div class="w3-top w3-hide-small">
 <!-- A top navigation bar that is hidden on small screens -->
 <div class="w3-bar w3-xlarge w3-black w3-opacity
w3-hover-opacity-off" id="myNavbar">
 <!-- A navigation bar with large text, black background, and
opacity effects -->
 <a href="Home.HTML" class="w3-bar-item w3-button">HOME</a>
 <!-- A link to the Home page styled as a bar item button -->
 <a href="Menu.HTML" class="w3-bar-item w3-button">MENU</a>
 <!-- A link to the Menu page styled as a bar item button -->
 <a href="About_us.HTML" class="w3-bar-item
w3-button">ABOUT</a>
 <!!-- A link to the About Us page styled as a bar item button
-->
<a href="Contacts.HTML" class="w3-bar-item
w3-button">CONTACT</a>
 <!-- A link to the Contact page styled as a bar item button
-->
 <a href="Order.HTML" class="w3-bar-item w3-button">ORDER</a>
 <!-- A link to the Order page styled as a bar item button -->
 </div>
 <div class="w3-container w3-padding-64 w3-center w3-table-all"
style="margin-top:80px">
 <!-- A container for the main content, with padding and centered
text -->
 <h2 class="w3-xxlarge">Restaurant Menu</h2>
 <!-- A heading for the menu section, styled with extra-large
text -->
 <div class="w3-margin-top w3-bar w3-black w3-opacity
w3-hover-opacity-off">
 <!-- A bar for sub-menu items with margin on top -->
 <a href="Desserts.HTML" class="w3-bar-item
w3-button">DESSERT</a>
 <!-- A link to the Desserts page styled as a bar item
button -->
 <a href="Main Course.HTML" class="w3-bar-item
w3-button">MAIN COURSE</a>
 <!-- A link to the Main Course page styled as a bar item
button -->
 <a href="Appetizer.HTML" class="w3-bar-item
w3-button">APPETIZER</a>
 <!-- A link to the Appetizer page styled as a bar item
button -->
 </div>
 </div>
 </div>

 Menu - Dessert:
</head>
<body>
 <!-- Container for the navigation bar with padding -->
 <div class="w3-padding">
 <!-- Navigation bar with large text and black background -->
 <div class="w3-padding w3-bar w3-xlarge w3-black w3-opacity
w3-hover-opacity-off" id="myNavbar">
 <!-- Navigation links to different pages -->
 <a href="Home.HTML" class="w3-bar-item w3-button">HOME</a>
 <a href="Menu.HTML" class="w3-bar-item w3-button">MENU</a>
 <a href="About_us.HTML" class="w3-bar-item w3-button">ABOUT</a>
 <a href="Contacts.HTML" class="w3-bar-item w3-button">CONTACT</a>
 <a href="Order.HTML" class="w3-bar-item w3-button">ORDER</a>
 </div>

 <!-- Container for the menu title and category links -->
 <div class="w3-container w3-padding-64 w3-center w3-table-all"
style="margin-top:80px">
 <h2 class="w3-xxlarge">Restaurant Menu</h2>
 <div class="w3-margin-top w3-bar w3-black w3-opacity
w3-hover-opacity-off">
 <!-- Links to different menu categories -->
 <a href="Desserts.HTML" class="w3-bar-item w3-button">DESSERT</a>
 <a href="Main Course.HTML" class="w3-bar-item w3-button">MAIN
COURSE</a>
 <a href="Appetizer.HTML" class="w3-bar-item
w3-button">APPETIZER</a>
 </div>
 </div>
 <!-- Appetizer Cards -->
 <div class="w3-row-padding w3-margin-top">
 <!-- Cheesecake -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/Cheese cake.jpg" alt="Cheesecake"
style="width:100%; height: 200px; object-fit: cover;">
 <div class="w3-container w3-center">
 <h4>Cheesecake</h4>
 <p>Creamy Cheesecake with berry topping</p>
 <p><b>₱90</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 <!-- Chocolate Lava Cake -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/chocolate lava cake.jpg" alt="Chocolate
lava cake" style="width:100%; height:200px; object-fit:cover;">
 <div class="w3-container w3-center">
 <h4>Chocolate lava cake</h4>
 <p>Warm Chocolate cake with Molten Center</p>
 <p><b>₱75</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 <!-- Ice Cream Sundae -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/ice cream sundae.jpg" alt="Ice cream
sundae" style="width:100%; height:200px; object-fit:cover;">
 <div class="w3-container w3-center">
 <h4>Ice cream sundae</h4>
 <p>Vanilla Ice Cream with Chocolate Sauce and Nuts</p>
 <p><b>₱50</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 </div>

 Menu - Main Course:
<body>
 <!-- Container for the navigation bar with padding -->
 <div class="w3-padding">
 <!-- Navigation bar with large text and black background -->
 <div class="w3-padding w3-bar w3-xlarge w3-black w3-opacity
w3-hover-opacity-off" id="myNavbar">
 <!-- Navigation links to different pages -->
 <a href="Home.HTML" class="w3-bar-item w3-button">HOME</a>
 <a href="Menu.HTML" class="w3-bar-item w3-button">MENU</a>
 <a href="About_us.HTML" class="w3-bar-item w3-button">ABOUT</a>
 <a href="Contacts.HTML" class="w3-bar-item w3-button">CONTACT</a>
 <a href="Order.HTML" class="w3-bar-item w3-button">ORDER</a>
 </div>

 <!-- Container for the menu title and category links -->
 <div class="w3-container w3-padding-64 w3-center w3-table-all"
style="margin-top:80px">
 <h2 class="w3-xxlarge">Restaurant Menu</h2>
 <div class="w3-margin-top w3-bar w3-black w3-opacity
w3-hover-opacity-off">
 <!-- Links to different menu categories -->
 <a href="Desserts.HTML" class="w3-bar-item w3-button">DESSERT</a>
 <a href="Main Course.HTML" class="w3-bar-item w3-button">MAIN
COURSE</a>
 <a href="Appetizer.HTML" class="w3-bar-item
w3-button">APPETIZER</a>
 </div>
 </div>
 <!-- Appetizer Cards -->
 <div class="w3-row-padding w3-margin-top">
 <!-- Grilled Salmon -->
 <div class="w3-third w3-container">
<div class="w3-card-4 w3-white">
 <img src="../IMAGES/Grilled salmon.jpg" alt="Grilled salmon"
style="width:100%; height: 200px; object-fit: cover;">
 <div class="w3-container w3-center">
 <h4>Grilled salmon</h4>
 <p>Fresh salmon served with vegetables</p>
 <p><b>₱200</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 <!-- Spaghetti Bolognese -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/spaghetti bolognese.jpg" alt="Spaghetti
Bolognese" style="width:100%; height:200px; object-fit:cover;">
 <div class="w3-container w3-center">
 <h4>Spaghetti Bolognese</h4>
 <p>Classic Italian pasta with meat sauce</p>
 <p><b>₱150</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
</div>
 </div>
 </div>
 <!-- Chicken Alfredo -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/chicken alfredo.jpg" alt="Chicken
Alfredo" style="width:100%; height:200px; object-fit:cover;">
 <div class="w3-container w3-center">
 <h4>Chicken Alfredo</h4>
 <p>Fettuccine with creamy Alfredo sauce and Grilled
Chicken</p>
 <p><b>₱100</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 </div>

Menu - Appetizer:
 <body>
 <!-- Container for the navigation bar with padding -->
 <div class="w3-padding">
 <!-- Navigation bar with large text and black background -->
 <div class="w3-padding w3-bar w3-xlarge w3-black w3-opacity
w3-hover-opacity-off" id="myNavbar">
 <!-- Navigation links to different pages -->
 <a href="Home.HTML" class="w3-bar-item w3-button">HOME</a>
 <a href="Menu.HTML" class="w3-bar-item w3-button">MENU</a>
 <a href="About_us.HTML" class="w3-bar-item w3-button">ABOUT</a>
 <a href="Contacts.HTML" class="w3-bar-item w3-button">CONTACT</a>
 <a href="Order.HTML" class="w3-bar-item w3-button">ORDER</a>
 </div>

 <!-- Container for the menu title and category links -->
 <div class="w3-container w3-padding-64 w3-center w3-table-all"
style="margin-top:80px">
 <h2 class="w3-xxlarge">Restaurant Menu</h2>
 <div class="w3-margin-top w3-bar w3-black w3-opacity
w3-hover-opacity-off">
 <!-- Links to different menu categories -->
 <a href="Desserts.HTML" class="w3-bar-item w3-button">DESSERT</a>
 <a href="Main Course.HTML" class="w3-bar-item w3-button">MAIN
COURSE</a>
 <a href="Appetizer.HTML" class="w3-bar-item
w3-button">APPETIZER</a>
 </div>
 </div>
 <!-- Appetizer Cards -->
 <div class="w3-row-padding w3-margin-top">
 <!-- Spring Rolls -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/Chinese spring rolls.jpg" alt="Spring
Rolls" style="width:100%; height: 200px; object-fit: cover;">
 <div class="w3-container w3-center">
<h4>Spring Rolls</h4>
 <p>Crispy rolls with veggie filling</p>
 <p><b>₱60</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
</div>
 </div>
 </div>
 <!-- Mozzarella Sticks -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/Mozzarella.webp.crdownload"
alt="Mozzarella Sticks" style="width:100%; height:200px;
object-fit:cover;">
 <div class="w3-container w3-center">
 <h4>Mozzarella Sticks</h4>
 <p>Cheesy sticks served with marinara</p>
 <p><b>₱70</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 <!-- Nachos -->
 <div class="w3-third w3-container">
 <div class="w3-card-4 w3-white">
 <img src="../IMAGES/nachos.jpeg" alt="Nachos"
style="width:100%; height:200px; object-fit:cover;">
 <div class="w3-container w3-center">
 <h4>Nachos</h4>
 <p>Tortilla chips with cheese and salsa</p>
 <p><b>₱80</b></p>
 <button class="w3-button w3-black w3-round-large
w3-margin-bottom" onclick="alert('Add to order successfully')">Add to
Order</button>
 </div>
 </div>
 </div>
 </div>

About Us:
<!-- Container for the navigation bar with padding -->
 <div class="w3-padding">
 <!-- Navigation bar with large text and black background -->
 <div class="w3-padding w3-xlarge w3-black w3-opacity
w3-hover-opacity-off">
 <!-- Navigation links to different pages -->
 <a href="Home.HTML" class="w3-bar-item w3-button">HOME</a>
 <a href="Menu.HTML" class="w3-bar-item w3-button">MENU</a>
 <a href="About_us.HTML" class="w3-bar-item
w3-button">ABOUT</a>
 <a href="Contacts.HTML" class="w3-bar-item
w3-button">CONTACT</a>
 <a href="Order.HTML" class="w3-bar-item w3-button">ORDER</a>
 </div>
 </div>
 <!-- Container for the About Us section with padding -->
 <div class="w3-padding">
 <!-- Main heading for the About Us section -->
 <h2 class="w3-center"><strong>About Us</strong></h2>
 <!-- Description of the restaurant -->
 <p class="w3-center">Welcome to <strong>ResTo</strong>, where we
serve delicious meals made from the freshest ingredients.
Our restaurant is dedicated to providing a warm and inviting
atmosphere for all our guests.</p>
 <!-- Subheading for the mission statement -->
 <h3 class="w3-margin-top"><strong>Our Mission</strong></h3>
 <!-- Mission statement -->
 <p>To create memorable dining experiences through quality food and
exceptional service.</p>
 <!-- Subheading for the invitation -->
 <h3 class="w3-margin-top"><strong>Join Us</strong></h3>
 <!-- Invitation to visit the restaurant -->
 <p>We invite you to visit us and enjoy a meal that celebrates
flavor and community!</p>
 </div>
 <!-- Container for the footer with padding -->
 <div class="w3-padding">
 <!-- Footer section with black background and centered text -->
 <footer class="w3-container w3-black w3-center ">
 <!-- Copyright notice -->
 <p>&copy; 2025 ResTo. All rights reserved.</p>
 </footer>
 </div>

Contact us:
<!-- Container for the contact form with padding -->
 <div class="w3-padding">
 <!-- Card for the contact form with a white background -->
 <div class="w3-card-4 w3-white" style="max-width: 600px; margin:
auto;">
 <header class="w3-container w3-orange">
 <!-- Main heading for the contact section -->
 <h2 class="w3-center"><strong>Contact Us</strong></h2>
 </header>
 <div class="w3-container">
 <!-- Instruction for the user -->
 <p>If you have any questions or would like to make a
reservation, please fill out the form below, and we will get back to you
as soon as possible!</p>
 <!-- Contact form -->
 <form>
 <!-- Input for first name -->
 <label for="fname">First name:</label>
 <input class="w3-input w3-border" type="text"
id="fname" name="fname" required>
<!-- Input for last name -->
 <label for="lname">Last name:</label>
 <input class="w3-input w3-border" type="text"
id="lname" name="lname" required>
 <!-- Input for email -->
 <label for="email">Email:</label>
 <input class="w3-input w3-border" type="email"
id="email" name="email" required>
 <!-- Textarea for message -->
 <label for="message">Message:</label>
 <textarea class="w3-input w3-border" id="message"
name="message" required></textarea>

 <!-- Submit button for the form -->
 <button class="w3-button w3-orange w3-margin-top"
type="submit" onclick="alert('The message has been successfully
sent!')">Send Message</button>
 </form>
 </div>
 </div>
 </div>

 Order:
 <!-- Container for the order section with padding and centered text -->
<div class="w3-container w3-padding-64 w3-center w3-table-all"
style="margin-top:80px">
 <!-- Main heading for the order section -->
 <h2 class="w3-center"><strong>Place Your Order</strong></h2>
 <!-- Instruction for the user -->
 <p class="w3-center">Select your favorite dish and click "Order
Now"!</p>
</div>
<!-- Row for dessert items -->
<div class="w3-row-padding w3-margin-top">
 <h2 class="w3-center"><strong>Dessert</strong></h2>
 <!-- Individual dessert item: Cheesecake -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/Cheese cake.jpg" class="w3-image"> <!-- Image of
the dessert -->
<div class="w3-container">
 <h4>Cheesecake</h4> <!-- Name of the dessert -->
 <p>₱90</p> <!-- Price of the dessert -->
 <label>Quantity:</label> <!-- Label for quantity input -->
 <input class="w3-input w3-border" type="number" min="1" value="1">
<!-- Input for quantity -->
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Cheesecake ordered!')">Order Now</button> <!-- Order
button with alert -->
 </div>
 </div>
 </div>
 <!-- Individual dessert item: Chocolate Lava Cake -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/chocolate lava cake.jpg" class="w3-image">
 <div class="w3-container">
 <h4>Chocolate Lava Cake</h4>
 <p>₱75</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Lava Cake ordered!')">Order Now</button>
 </div>
 </div>
 </div>
 <!-- Individual dessert item: Ice Cream Sundae -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/ice cream sundae.jpg" class="w3-image">
 <div class="w3-container">
 <h4>Ice Cream Sundae</h4>
 <p>₱50</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Ice Cream ordered!')">Order Now</button>
 </div>
 </div>
 </div>
</div>
<!-- Row for main course items -->
<div class="w3-row-padding w3-margin-top">
 <h2 class="w3-center"><strong>Main Course</strong></h2>
 <!-- Individual main course item: Grilled Salmon --> </div>
 <!-- Individual main course item: Spaghetti Bolognese -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/spaghetti bolognese.jpg" class="w3-image">
 <div class="w3-container">
 <h4>Spaghetti Bolognese</h4>
 <p>₱150</p>
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/Grilled salmon.jpg" class="w3-image">
 <div class="w3-container">
 <h4>Grilled Salmon</h4>
 <p>₱200</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Grilled Salmon ordered!')">Order Now</button>
 </div>
 </div>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Spaghetti ordered!')">Order Now</button>
 </div>
 </div>
 </div>
 <!-- Individual main course item: Chicken Alfredo -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/chicken alfredo.jpg" class="w3-image">
 <div class="w3-container">
 <h4>Chicken Alfredo</h4>
 <p>₱100</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Chicken Alfredo ordered!')">Order Now</button>
 </div>
 </div>
 </div>
</div>
<!-- Row for appetizer items -->
<div class="w3-row-padding w3-margin-top">
 <h2 class="w3-center"><strong>Appetizer</strong></h2>
 <!-- Individual appetizer item: Spring Rolls -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/Chinese spring rolls.jpg" class="w3-image">
 <div class="w3-container">
 <h4>Spring Rolls</h4>
 <p>₱60</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Spring Rolls ordered!')">Order Now</button>
 </div>
 </div>
 </div>
 <!-- Individual appetizer item: Mozzarella Sticks -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/Mozzarella.webp" class="w3-image">
 <div class="w3-container">
 <h4>Mozzarella Sticks</h4>
 <p>₱70</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Mozzarella Sticks ordered!')">Order Now</button>
 </div>
 </div>
 </div>
 <!-- Individual appetizer item: Nachos -->
 <div class="w3-third w3-margin-bottom">
 <div class="w3-card-4">
 <img src="../IMAGES/nachos.jpeg" class="w3-image">
 <div class="w3-container">
 <h4>Nachos</h4>
 <p>₱80</p>
 <label>Quantity:</label>
 <input class="w3-input w3-border" type="number" min="1" value="1">
 <button class="w3-button w3-green w3-margin-top w3-block"
onclick="alert('Nachos ordered!')">Order Now</button>
 </div>
 </div>
 </div>
</div>


