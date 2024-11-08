[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_rEaNyCz)
# NAVBAR
sticky
```html
    <header>
        <img src="flagpack--mx.png" alt="Mexican" class="logo">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Menu</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </header>
```

Media query 
```css
 .hamburger {
        display: block;

    }

    .hamburger.active .bar:nth-child(2) {
        opacity: 0;
    }

    .hamburger.active .bar:nth-child(1) {
        transform: translateY(8px) rotate(45deg);
    }

    .hamburger.active .bar:nth-child(3) {
        transform: translateY(-8px) rotate(-45deg);
    }

    .nav-menu {
        position: fixed;
        left: -1000%;
        top: 70px;
        gap: 0;
        flex-direction: column;
        background-color: black;
        width: 100%;
        text-align: center;
        transition: 0.3s;


    }

    .nav-item {
        margin: 16px 0;
    }

    .nav-menu .active {
        left: 0;
    }

```

# MENU CONTENT
this is the content
```html
<h1>Our Menu</h1>
        <div class="flex-container container">
            <div class="menu-container">
                <img src="burito_carne_asada.jpeg" alt="Burito Carne Asada">
                <h3>Burito Carne Asada</h3>
                <h5>Burito filled with Mexican authentuic grilled meat</h5>
            </div>
            <div class="menu-container">
                <img src="burito_pollo_chille.jpg" alt="Burito Pollo con Chille">
                <h3>Burito Pollo con Chille</h3>
                <h5>Burito filled with spicy chicken</h5>
            </div>
            <div class="menu-container">
                <img src="burger.jpg" alt="Burger">
                <h3>Burger</h3>
                <h5>Special burger by our restaurant that will crave your gut</h5>
            </div>
        </div>
```

Media quey for Content 
```css
 .grid-container {
        display: grid;
        grid-template-rows: 1fr 1fr 1fr;
        grid-template-columns: 1fr;
        width: 100%;
        margin-left: 0;
        margin-right: 0;
        padding-left: 0;
        padding-right: 0;

    }
```
# OUR GALLERY
```html
    <div class="gallery">
            <h1>Our Gallery</h1>
            <div class="grid-gallery">
                <picture class="grid-item1 child">
                    <source srcset="mexican_flag.png" media="(min-width: 600px)">
                    <img src="metropolitan-cathedral-zocalo-mexico-city.webp" alt="">
                </picture>
                <img class="grid-item2 child" src="maxresdefault.jpg" alt="">
                <img class="grid-item3 child" src="KH_011924_MDWL0076-525cbfe2b7364ec487682b55a3935816.jpg" alt="">
                <img class="grid-item4 child"
                    src="depositphotos_87542386-stock-photo-person-wearing-sombrero-hat-in.jpg" alt="">
                <div class="grid-item5">
                    <h2 class="text">Happy Taco</h2>
                    <h2 class="text">Happy Tummy</h2>
                </div>
            </div>
        </div>
```
# ABOUT US
```html
    <div class="aboutUs container">
            <h1 class="aboutUs-text">About Us</h1>
            <h3 class="aboutUs-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem, atque!
                Porro magnam odio
                similique officia, architecto nulla minima reprehenderit incidunt adipisci, labore cupiditate!
                Voluptate, ratione?
            </h3>
            <ul class="aboutUs-text">
                <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, id.</li>
                <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi, quasi.</li>
                <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, quasi!</li>
            </ul>
        </div>
```

# HOW TO REACH US
```html
    <div class="container">
            <h3>Contact Us</h3>
            <form action="">
                <div class="contactUs">
                    <input type="text" id="fname" name="fname" placeholder="Your Name">
                    <input type="text" id="email" name="email" placeholder="Your email">
                </div>
                <textarea name="" id="" cols="30" rows="10">Your Message</textarea>
                <input type="submit">

            </form>
        </div>
```
Pictures inside the content :

![Burito Carne Asada](burito_carne_asada.jpeg)
![Burito Pollo con Chille](burito_pollo_chille.jpg)
![Burger](burger.jpg )
<br>
<br>
<br>
<br>
<br>

# Deployment link :
https://revou-fsse-oct24.github.io/module-2-parsadi/





