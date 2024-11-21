E-commerce website using HTML CSS JS:

Introduction:
This project is about an e-commerce website where a user can do shopping with a seamless experience. A user can choose a product as per his choice He can filter the products by size as well as by the color he wants.

Explanation :
Structure of Project:
The code begins with a tag that contains two child tags: one for the main content of the page, and another for the navigation.
This will be used to help users find what they’re looking for on the site.  Inside of that holds all of the content on the page, you’ll see a series of paragraphs.  The first paragraph contains information about how to purchase items from this store. It includes details like product categories and prices. The next paragraph lists all of the available products in each category.

 Each product has its own row, and there are images associated with each item so that users can better understand what they’re buying. You also include links to more detailed descriptions if needed. Finally, at the bottom of this paragraph is a link to view additional product information (such as dimensions and materials).

Next comes a section where users can search for products by keyword or phrase. The code creates a div with the class navItem, which will house all of the navigation for our ecommerce store. Within this div, we have two elements: a search input and an icon for our search bar.

The code within the search input will allow users to enter text into the form and it will be autofilled with the current page’s title. The icon will be used as a placeholder for our search bar and it will dynamically change depending on whether or not there is any content in our search input.

Finally, we have created a div with the class navItem which will house all of our navigation. Within this div, we have created a heading titled “Ecommerce Store” and beneath this heading

JavaScript Logic :

The code starts by creating an array of objects called products . Each object in the products array will contain information about a different product. The first object in the products array is called choosen Product . This object will hold the information about the product that was chosen by the user (in this case, it’s Air Jordan).

Next, we need to get hold of all of the information about choosen Product . We do this by using document.querySelectorAll() .

This method takes two arguments: The first is a selector (in this case, “.productTitle”) and the second is a list of strings (in this case, “.color”). We then use forEach() to loop through all of the menuItems in our document.

Each time around the loop, we’ll add an event listener to each item so that we can track when it’s clicked. In this case, when someone clicks on one of our menuItems , we want to run a function called analyze() .

This function will take three arguments: The first is choosenProduct , which we’ve already obtained from earlier; secondly, currentProductImg , which is our image pointer for displaying what’s currently being displayed on our screen; and finally, current

The code creates a slider with six different products. Each product has an id, title, price, and colors. The code also creates a menu item for each product. When the user clicks on any of the menu items, the code will call a function that will take care of the rest. The first thing that the function does is find the product that was clicked on. This is done by using the index variable which refers to the particular menu item that was clicked on.

Once it finds the product, it sets up some event handlers for it so that when it is clicked again or when something else happens in the slider, it will be triggered.

The event handlers are used to change some variables in regard to each of the products.

These are the explation of my project on E commerce Website.

CODE OF MY PROJECT:

indec.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Male Fashion</title>
    <link rel="stylesheet" href="./index.css">
</head>
<body>
    <section class=" top-txt ">
        <div class="head container ">
            <div class="head-txt ">
                <p>Free shipping, 30-day return or refund guarantee.</p>
            </div>
            <div class="sing_in_up ">
                <a href="# ">SIGN IN</a>
                <a href="# ">SIGN UP</a>
            </div>
        </div>
    </section>
    <nav class="navbar">
        <div class="navbar-container">
            <input type="checkbox" name="" id="checkbox">
            <div class="hamburger-lines">
                <span class="line line1"></span>
                <span class="line line2"></span>
                <span class="line line3"></span>
            </div>
            <ul class="menu-items">
                <li><a href="#home">Home</a></li>
                <li><a href="#sellers">Shop</a></li>
                <li><a href="#news">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="logo">
                <img src="https://i.postimg.cc/TP6JjSTt/logo.webp" alt="">
            </div>
        </div>
    </nav>
    <section id="home">
        <div class="home_page ">
            <div class="home_img ">
                <img src="https://i.postimg.cc/t403yfn9/home2.jpg" alt="img ">
            </div>
            <div class="home_txt ">
                <p class="collectio ">SUMMER COLLECTION</p>
                <h2>FALL - WINTER<br>Collection 2023</h2>
                <div class="home_label ">
                    <p>A specialist label creating luxury essentials. Ethically crafted<br>with an unwavering commitment to exceptional quality.</p>
                </div>
                <button><a href="#sellers">SHOP NOW</a><i class='bx bx-right-arrow-alt'></i></button>
                <div class="home_social_icons">
                    <a href="#"><i class='bx bxl-facebook'></i></a>
                    <a href="#"><i class='bx bxl-twitter'></i></a>
                    <a href="#"><i class='bx bxl-pinterest'></i></a>
                    <a href="#"><i class='bx bxl-instagram'></i></a>
                </div>
            </div>
        </div>
    </section>

    <section id="collection">
        <div class="collections container">
            <div class="content">
                <img src="https://i.postimg.cc/Xqmwr12c/clothing.webp" alt="img" />
                <div class="img-content">
                    <p>Clothing Collections</p>
                    <button><a href="#sellers">SHOP NOW</a></button>
                </div>
            </div>
            <div class="content2">
                <img src="https://i.postimg.cc/8CmBZH5N/shoes.webp" alt="img" />
                <div class="img-content2">
                    <p>Shoes Spring</p>
                    <button><a href="#sellers">SHOP NOW</a></button>
                </div>
            </div>
            <div class="content3">
                <img src="https://i.postimg.cc/MHv7KJYp/access.webp" alt="img" />
                <div class="img-content3">
                    <p>Accessories</p>
                    <button><a href="#sellers">SHOP NOW</a></button>
                </div>
            </div>
        </div>
    </section>
    <section id="sellers">
        <div class="seller container">
            <h2>Top Sales</h2>
            <div class="best-seller">
                <div class="best-p1">
                    <img src="https://i.postimg.cc/8CmBZH5N/shoes.webp" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Shoes</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                        </div>
                        <div class="price">
                            &dollar;37.24
                            <div class="colors">
                                <i class='bx bxs-circle red'></i>
                                <i class='bx bxs-circle blue'></i>
                                <i class='bx bxs-circle white'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                        <!-- <div class="add-cart">
                            <button>Add To Cart</button>
                        </div> -->
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/76X9ZV8m/Screenshot_from_2022-06-03_18-45-12.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Jacket</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                        </div>
                        <div class="price">
                            &dollar;17.24
                            <div class="colors">
                                <i class='bx bxs-circle green'></i>
                                <i class='bx bxs-circle grey'></i>
                                <i class='bx bxs-circle brown'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/j2FhzSjf/bs2.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Shirt</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bx-star'></i>
                        </div>
                        <div class="price">
                            &dollar;27.24
                            <div class="colors">
                                <i class='bx bxs-circle brown'></i>
                                <i class='bx bxs-circle green'></i>
                                <i class='bx bxs-circle blue'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/QtjSDzPF/bs3.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Shoes</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;43.67
                            <div class="colors">
                                <i class='bx bxs-circle red'></i>
                                <i class='bx bxs-circle grey'></i>
                                <i class='bx bxs-circle blue'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="seller container">
            <h2>New Arrivals</h2>
            <div class="best-seller">
                <div class="best-p1">
                    <img src="https://i.postimg.cc/fbnB2yfj/na1.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England T-Shirt</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;10.23
                            <div class="colors">
                                <i class='bx bxs-circle blank'></i>
                                <i class='bx bxs-circle blue'></i>
                                <i class='bx bxs-circle brown'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/zD02zJq8/na2.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Bag</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                        </div>
                        <div class="price">
                            &dollar;09.28
                            <div class="colors">
                                <i class='bx bxs-circle brown'></i>
                                <i class='bx bxs-circle red'></i>
                                <i class='bx bxs-circle green'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/Dfj5VBcz/sunglasses1.jpg" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Sunglass</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;06.24
                            <div class="colors">
                                <i class='bx bxs-circle grey'></i>
                                <i class='bx bxs-circle blank'></i>
                                <i class='bx bxs-circle blank'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/FszW12Kc/na4.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Shoes</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;43.67
                            <div class="colors">
                                <i class='bx bxs-circle grey'></i>
                                <i class='bx bxs-circle red'></i>
                                <i class='bx bxs-circle blue'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="seller container">
            <h2>Hot Sales</h2>
            <div class="best-seller">
                <div class="best-p1">
                    <img src="https://i.postimg.cc/jS7pSQLf/na4.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Shoes</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;37.24
                            <div class="colors">
                                <i class='bx bxs-circle grey'></i>
                                <i class='bx bxs-circle black'></i>
                                <i class='bx bxs-circle blue'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/fbnB2yfj/na1.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England T-Shirt</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;10.23
                            <div class="colors">
                                <i class='bx bxs-circle blank'></i>
                                <i class='bx bxs-circle blue'></i>
                                <i class='bx bxs-circle brown'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/RhVP7YQk/hs1.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England T-Shirt</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                            <i class='bx bxs-star'></i>
                        </div>
                        <div class="price">
                            &dollar;15.24
                            <div class="colors">
                                <i class='bx bxs-circle blank'></i>
                                <i class='bx bxs-circle red'></i>
                                <i class='bx bxs-circle blue'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
                <div class="best-p1">
                    <img src="https://i.postimg.cc/zD02zJq8/na2.png" alt="img">
                    <div class="best-p1-txt">
                        <div class="name-of-p">
                            <p>PS England Bag</p>
                        </div>
                        <div class="rating">
                            <i class='bx bxs-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                            <i class='bx bx-star'></i>
                        </div>
                        <div class="price">
                            &dollar;09.28
                            <div class="colors">
                                <i class='bx bxs-circle blank'></i>
                                <i class='bx bxs-circle grey'></i>
                                <i class='bx bxs-circle brown'></i>
                            </div>
                        </div>
                        <div class="buy-now">
                            <button><a href="https://codepen.io/sanketbodke/full/mdprZOq">Buy  Now</a></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="news">
        <div class="news-heading">
            <p>LATEST NEWS</p>
            <h2>Fashion New Trends</h2>
        </div>
        <div class="l-news container">
            <div class="l-news1">
                <div class="news1-img">
                    <img src="https://i.postimg.cc/2y6wbZCm/news1.jpg" alt="img">
                </div>
                <div class="news1-conte">
                    <div class="date-news1">
                        <p><i class='bx bxs-calendar'></i> 12 February 2024</p>
                        <h4>What Curling Irons Are The Best Ones</h4>
                        <a href="https://www.vogue.com/article/best-curling-irons" target="_blank">read more</a>
                    </div>
                </div>
            </div>
            <div class="l-news2">
                <div class="news2-img">
                    <img src="https://i.postimg.cc/9MXPK7RT/news2.jpg" alt="img">
                </div>
                <div class="news2-conte">
                    <div class="date-news2">
                        <p><i class='bx bxs-calendar'></i> 15 May 2024</p>
                        <h4>The Health Benefits Of Sunglasses</h4>
                        <a href="https://www.rivieraopticare.com/blog/314864-the-health-benefits-of-wearing-sunglasses_2/" target="_blank">read more</a>
                    </div>
                </div>
            </div>
            <div class="l-news3">
                <div class="news3-img">
                    <img src="https://i.postimg.cc/x1KKdRLM/news3.jpg" alt="img">
                </div>
                <div class="news3-conte">
                    <div class="date-news3">
                        <p><i class='bx bxs-calendar'></i> 30 June 2024</p>
                        <h4>Eternity Bands Do Last Forever</h4>
                        <a href="https://www.briangavindiamonds.com/news/eternity-bands-symbolize-love-that-lasts-forever/" target="_blank">read more</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="contact container">
        <div class="map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.121169986175!2d73.90618951442687!3d18.568575172551647!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bc2c131ed5b54a7%3A0xad718b8b2c93d36d!2sSky%20Vista!5e0!3m2!1sen!2sin!4v1654257749399!5m2!1sen!2sin"
                width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
        <form action="https://formspree.io/f/xzbowpjq" method="POST">
            <div class="form">
                <div class="form-txt">
                    <h4>INFORMATION</h4>
                    <h1>Contact Us</h1>
                    <span>As you might expect of a company that began as a high-end interiors contractor, we pay strict
                        attention.</span>
                    <h3>USA</h3>
                    <p>195 E Parker Square Dr, Parker, CO 801<br>+43 982-314-0958</p>
                    <h3>India</h3>
                    <p>HW95+C9C, Lorem ipsum dolor sit.<br>411014</p>
                </div>
                <div class="form-details">
                    <input type="text" name="name" id="name" placeholder="Name" required>
                    <input type="email" name="email" id="email" placeholder="Email" required>
                    <textarea name="message" id="message" cols="52" rows="7" placeholder="Message" required></textarea>
                    <button>SEND MESSAGE</button>
                </div>
            </div>
        </form>
    </div>
    </section>
    <footer>
        <div class="footer-container container">
            <div class="content_1">
                <img src="https://i.postimg.cc/htGyQ4JB/footer-logo.png" alt="logo">
                <p>The customer is at the heart of our<br>unique business model, which includes<br>design.</p>
                <img src="https://i.postimg.cc/Nj9dgJ98/cards.png" alt="cards">
            </div>
            <div class="content_2">
                <h4>SHOPPING</h4>
                <a href="#sellers">Clothing Store</a>
                <a href="#sellers">Trending Shoes</a>
                <a href="#sellers">Accessories</a>
                <a href="#sellers">Sale</a>
            </div>
            <div class="content_3">
                <h4>SHOPPING</h4>
                <a href="./contact.html">Contact Us</a>
                <a href="https://payment-method-sb.netlify.app/" target="_blank">Payment Method</a>
                <a href="https://delivery-status-sb.netlify.app/" target="_blank">Delivery</a>
                <a href="https://codepen.io/sandeshbodake/full/Jexxrv" target="_blank">Return and Exchange</a>
            </div>
            <div class="content_4">
                <h4>NEWLETTER</h4>
                <p>Be the first to know about new<br>arrivals, look books, sales & promos!</p>
                <div class="f-mail">
                    <input type="email" placeholder="Your Email">
                    <i class='bx bx-envelope'></i>
                </div>
                <hr>
            </div>
        </div>
        <div class="f-design">
            <div class="f-design-txt container">
                <p>Design and Code by code.sanket</p>
            </div>
        </div>
    </footer>
</body>
</html>


index.css:

@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Poppins", sans-serif;
}

.container {
    max-width: 1200px;
    width: 90%;
    margin: 0 auto;
}


/* //........top text ........// */

:root {
    /* //....... Color ........// */
    --primary-color: #ff3c78;
    --light-black: rgba(0, 0, 0, 0.89);
    --black: #000;
    --white: #fff;
    --grey: #aaa;
}


/* //........top text ........// */

.top-txt {
    background-color: var(--black);
}

.head {
    display: flex;
    justify-content: space-between;
    color: rgba(255, 255, 255, 0.945);
    padding: 10px 0;
    font-size: 14px;
}

.head a {
    text-decoration: none;
    color: rgba(255, 255, 255, 0.945);
    margin: 0 10px;
}


/* //........ Navbar ........// */

.navbar input[type="checkbox"],
.navbar .hamburger-lines {
    display: none;
}

.navbar {
    box-shadow: 0 5px 4px rgb(146 161 176 / 15%);
    position: sticky;
    top: 0;
    background: var(--white);
    color: var(--black);
    z-index: 100;
}

.navbar-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 64px;
}

.navbar img {
    margin-left: 3rem;
}

.menu-items {
    order: 2;
    display: flex;
    margin-right: 3rem;
}

.menu-items li {
    list-style: none;
    margin-left: 1.5rem;
    font-size: 1.2rem;
}

.navbar-container ul a {
    text-decoration: none;
    color: var(--black);
    font-size: 18px;
    position: relative;
}

.navbar-container ul a:after {
    content: "";
    position: absolute;
    background: var(--primary-color);
    height: 3px;
    width: 0;
    left: 0;
    bottom: -10px;
    transition: 0.3s;
}

.navbar-container ul a:hover:after {
    width: 100%;
}

@media (max-width: 768px) {
    .navbar {
        opacity: 0.95;
    }
    .navbar-container input[type="checkbox"],
    .navbar-container .hamburger-lines {
        display: block;
    }
    .navbar-container {
        display: block;
        position: relative;
        height: 64px;
    }
    .navbar-container input[type="checkbox"] {
        position: absolute;
        display: block;
        height: 32px;
        width: 30px;
        top: 20px;
        left: 20px;
        z-index: 5;
        opacity: 0;
        cursor: pointer;
    }
    .navbar-container .hamburger-lines {
        display: block;
        height: 28px;
        width: 35px;
        position: absolute;
        top: 20px;
        left: 20px;
        z-index: 2;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    .navbar-container .hamburger-lines .line {
        display: block;
        height: 4px;
        width: 100%;
        border-radius: 10px;
        background: #333;
    }
    .navbar-container .hamburger-lines .line1 {
        transform-origin: 0% 0%;
        transition: transform 0.3s ease-in-out;
    }
    .navbar-container .hamburger-lines .line2 {
        transition: transform 0.2s ease-in-out;
    }
    .navbar-container .hamburger-lines .line3 {
        transform-origin: 0% 100%;
        transition: transform 0.3s ease-in-out;
    }
    .navbar .menu-items {
        padding-top: 100px;
        background: #fff;
        height: 100vh;
        max-width: 100%;
        transform: translate(-150%);
        display: flex;
        flex-direction: column;
        /* margin-left: -40px;
        padding-left: 40px; */
        text-align: center;
        transition: transform 0.5s ease-in-out;
        /* box-shadow: 5px 0px 10px 0px #aaa; */
        overflow: scroll;
    }
    .navbar .menu-items li {
        margin-bottom: 2rem;
        font-size: 1.1rem;
        font-weight: 500;
    }
    .menu-items li,
    .navbar img {
        margin: 0;
    }
    .navbar .menu-items li:nth-child(1) {
        margin-top: 1.5rem;
    }
    .navbar-container .logo img {
        position: absolute;
        top: 10px;
        right: 15px;
        margin-top: 8px;
    }
    .navbar-container input[type="checkbox"]:checked~.menu-items {
        transform: translateX(0);
    }
    .navbar-container input[type="checkbox"]:checked~.hamburger-lines .line1 {
        transform: rotate(45deg);
    }
    .navbar-container input[type="checkbox"]:checked~.hamburger-lines .line2 {
        transform: scaleY(0);
    }
    .navbar-container input[type="checkbox"]:checked~.hamburger-lines .line3 {
        transform: rotate(-45deg);
    }
    .navbar-container input[type="checkbox"]:checked~.home_page img {
        display: none;
        background: #fff;
    }
}

@media (max-width: 500px) {
    .navbar-container input[type="checkbox"]:checked~.navbar-container img {
        display: none;
    }
}


/* //........ Home ........// */

.home_page img {
    height: auto;
    width: 100%;
    background-position: center;
    position: relative;
    background-size: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
}

.home_txt {
    position: absolute;
    top: 37%;
    left: 5%;
}

.home_txt p {
    color: var(--primary-color);
    font-weight: 600;
    padding-bottom: 20px;
    letter-spacing: 1.5px;
}

.home_txt h2 {
    font-size: 2.6rem;
    font-weight: 500;
    line-height: 53px;
    letter-spacing: 3px;
    font-weight: 600;
    color: var(--light-black);
}

.home_txt .home_label p {
    color: grey;
    font-size: 14px;
    padding-top: 10px;
}

.home_txt a {
    text-decoration: none;
    color: var(--white);
}

.home_txt button {
    background-color: var(--black);
    color: var(--white);
    border: none;
    padding: 15px 30px;
    font-size: 14px;
    letter-spacing: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 30px;
    cursor: pointer;
}

.home_txt .bx-right-arrow-alt {
    font-size: 25px;
    padding-left: 5px;
}

.home_txt .home_social_icons a {
    text-decoration: none;
    color: var(--light-black);
    margin-right: 15px;
    font-size: 18px;
}


/* //........ Collections ........// */

.collections {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 65px;
}

.content {
    width: 330px;
    margin: 20px;
    position: relative;
}

.content::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0%;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.871);
    z-index: 2;
    opacity: 0;
}

.content:hover::after {
    opacity: 1;
}

.content img {
    width: 100%;
    height: 300px;
    box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.22);
}

.img-content {
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translate(-50%, -50%);
    transition: all 0.3s ease-in-out;
    color: var(--white);
    text-align: center;
    font-size: 2.2rem;
    font-weight: bolder;
    z-index: 5;
    opacity: 0;
}

.img-content p {
    font-size: 1.6rem;
}

.img-content button {
    border: none;
    background-color: var(--primary-color);
    color: var(--white);
    border-radius: 10px;
    padding: 10px;
}

.img-content a {
    text-decoration: none;
    font-size: 1.1rem;
    color: #fff;
    transition: 0.3s;
}

.img-content button:hover {
    background: var(--white);
    color: var(--primary-color);
}

.img-content button:hover~.img-content a {
    color: var(--primary-color);
}

.img-content a:hover {
    color: var(--primary-color);
}

.content:hover .img-content {
    opacity: 1;
    top: 50%;
}


/* //........ Content 2 ........// */

.content2 {
    width: 330px;
    margin: 20px;
    position: relative;
}

.content2::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0%;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.871);
    z-index: 2;
    opacity: 0;
}

.content2:hover::after {
    opacity: 1;
}

.content2 img {
    width: 100%;
    height: 300px;
    box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.22);
}

.img-content2 {
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translate(-50%, -50%);
    transition: all 0.3s ease-in-out;
    color: var(--white);
    text-align: center;
    font-size: 2.2rem;
    font-weight: bolder;
    z-index: 5;
    opacity: 0;
}

.img-content2 p {
    font-size: 1.6rem;
}

.img-content2 a {
    text-decoration: none;
    font-size: 1.1rem;
    color: #fff;
    transition: 0.3s;
}

.img-content2 button {
    border: none;
    background-color: var(--primary-color);
    color: var(--white);
    border-radius: 10px;
    padding: 10px;
}

.img-content2 button:hover {
    background: var(--white);
    color: var(--primary-color);
}

.img-content2 button:hover~.img-content2 a {
    color: var(--primary-color);
}

.img-content2 a:hover {
    color: var(--primary-color);
}

.content2:hover .img-content2 {
    opacity: 1;
    top: 50%;
}


/* //........ Content 3 ........// */

.content3 {
    width: 330px;
    margin: 20px;
    position: relative;
}

.content3::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0%;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.871);
    z-index: 2;
    opacity: 0;
}

.content3:hover::after {
    opacity: 1;
}

.content3 img {
    width: 100%;
    height: 300px;
    box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.22);
}

.img-content3 {
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translate(-50%, -50%);
    transition: all 0.3s ease-in-out;
    color: var(--white);
    text-align: center;
    font-size: 2.2rem;
    font-weight: bolder;
    z-index: 5;
    opacity: 0;
}

.img-content3 p {
    font-size: 1.6rem;
}

.img-content3 a {
    text-decoration: none;
    font-size: 1.2rem;
    color: #fff;
    transition: 0.3s;
}

.img-content3 button {
    border: none;
    background-color: var(--primary-color);
    color: var(--white);
    border-radius: 10px;
    padding: 10px;
}

.img-content3 button:hover {
    background: var(--white);
    color: var(--primary-color);
}

.img-content3 button:hover~.img-content3 a {
    color: var(--primary-color);
}

.img-content3 a:hover {
    color: var(--primary-color);
}

.content3:hover .img-content3 {
    opacity: 1;
    top: 50%;
}

.content3:hover .img-content3 {
    opacity: 1;
    top: 50%;
}


/* //........ seller  ........// */

.best-seller {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.best-seller .red {
    color: var(--primary-color);
    cursor: pointer;
}

.best-seller .blue {
    color: #8989ce;
    cursor: pointer;
}

.best-seller .white {
    color: var(--light-black);
    cursor: pointer;
}

.best-seller .grey {
    color: grey;
    cursor: pointer;
}

.best-seller .brown {
    color: rgb(175, 53, 53);
    cursor: pointer;
}

.best-seller .yellow {
    color: #ffff00;
    cursor: pointer;
}

.best-seller .orange {
    color: #ffa500;
    cursor: pointer;
}

.best-seller .green {
    color: #008000;
    cursor: pointer;
}

.seller h2 {
    margin-top: 65px;
    margin-bottom: 20px;
}

.seller .best-p1 {
    width: 250px;
    height: 370px;
    /* border: 2px solid black; */
}

.seller .best-p1 img {
    height: 250px;
    width: 250px;
}

.seller .best-p1 .price {
    display: flex;
    justify-content: space-between;
}

.seller .best-p1 .price .colors input[type="radio"] {
    color: #000;
    background-color: #000;
}

.best-seller .buy-now a {
    text-decoration: none;
    color: var(--white);
}

.seller a:hover {
    color: #f05e8a;
}

.best-seller .buy-now button,
.best-seller .add-cart button {
    padding: 10px 15px;
    margin-top: 5px;
    font-size: 14px;
    cursor: pointer;
    text-transform: uppercase;
    background-color: #f05e8a;
    color: var(--white);
    border: none;
    border-radius: 15px;
    font-weight: 500;
    border: 1px solid #f05e8a;
    transition: 0.5s;
}

.best-seller .buy-now button:hover,
.best-seller .add-cart button:hover {
    background-color: var(--white);
    font-weight: 600;
}

.best-seller .buy-now button:hover a,
.best-seller .add-cart button:hover a {
    color: #f05e8a;
}


/* .best-seller .add-cart button {
    padding: 5px 5px;
    margin-top: 5px;
    font-size: 14px;
    cursor: pointer;
} */


/* //........ deal of week ........// */

.deal_of_week {
    display: flex;
    justify-content: center;
    align-items: center;
}

.deal_of_week .names_of_brand p,
.deal_of_week .names_of_brand h3 {
    font-size: 1.8rem;
    margin-bottom: 1rem;
}

.deal_of_week .names_of_brand p {
    color: var(--grey);
}

.deal_of_week .countdown span {
    color: var(--primary-color);
    font-weight: 600;
    letter-spacing: 2px;
    margin: 0.8rem 0 0 3rem;
}

.deal_of_week .countdown h3 {
    font-size: 2rem;
    font-weight: 600;
    color: var(--light-black);
    line-height: 40px;
    margin: 0.8rem 0 0 3rem;
}

.deal_of_week .countdown p {
    margin: 0.8rem 0 0 3rem;
}

.deal_of_week .countdown a {
    text-decoration: none;
    color: var(--white);
    font-weight: 800;
}

.deal_of_week .countdown button {
    margin: 0.8rem 3rem;
    border: 2px solid var(--primary-color);
    background-color: var(--primary-color);
    color: var(--white);
    border-radius: 10px;
    padding: 12px;
    transition: 0.4s;
}

.deal_of_week .countdown button:hover {
    background: var(--white);
    color: var(--primary-color);
}

.deal_of_week .countdown button:hover~.countdown a {
    background: var(--white);
    color: var(--primary-color);
}

.countdown a:hover {
    color: var(--primary-color);
}


/* //........ NEWS ........// */

#news {
    margin-bottom: 250px;
}

.news-heading p {
    text-align: center;
    font-size: 18px;
    color: var(--primary-color);
    letter-spacing: 2px;
    font-weight: 500;
    margin-bottom: 15px;
    margin-top: 70px;
}

.news-heading h2 {
    text-align: center;
    font-size: 32px;
    font-weight: 600;
    color: var(--light-black);
}

.l-news {
    padding-top: 45px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    position: relative;
}

.l-news img {
    height: 200px;
    width: 300px;
}

.l-news1 {
    position: relative;
    width: 280px;
    height: 230px;
}

.l-news1 .news1-conte {
    position: absolute;
    bottom: -60%;
    left: 7%;
    background: var(--white);
    padding: 25px;
}

.l-news2 {
    position: relative;
    width: 280px;
    height: 230px;
}

.l-news2 .news2-conte {
    position: absolute;
    bottom: -60%;
    left: 7%;
    background: var(--white);
    padding: 25px;
}

.l-news3 {
    position: relative;
    width: 280px;
    height: 230px;
}

.l-news3 .news3-conte {
    position: absolute;
    bottom: -60%;
    left: 7%;
    background: var(--white);
    padding: 25px;
}

.l-news1 .news1-conte .date-news1 p {
    color: var(--light-black);
    text-align: center;
    padding: 15px 0;
}

.l-news1 .news1-conte .date-news1 h4 {
    font-size: 18px;
    text-align: center;
    font-weight: 600;
    padding-bottom: 15px;
}

.l-news1 .news1-conte .date-news1 a {
    text-decoration: none;
    text-align: center;
    padding: 0 50px;
    color: var(--primary-color);
    position: relative;
    font-weight: 600;
}

.l-news1 .news1-conte .date-news1 a::after {
    content: "";
    position: absolute;
    background: #ff3c78;
    height: 3px;
    width: 100%;
    left: 0;
    bottom: -10px;
    transition: 0.3s;
}

.l-news1 .news1-conte .date-news1 a:hover:after {
    width: 0%;
}

.l-news1 .news1-conte .date-news1 a:hover {
    color: var(--black);
}

.l-news2 .news2-conte .date-news2 p {
    color: var(--light-black);
    text-align: center;
    padding: 15px 0;
}

.l-news2 .news2-conte .date-news2 h4 {
    font-size: 18px;
    text-align: center;
    font-weight: 600;
    padding-bottom: 15px;
}

.l-news2 .news2-conte .date-news2 a {
    text-decoration: none;
    text-align: center;
    padding: 0 60px;
    color: var(--primary-color);
    position: relative;
    font-weight: 600;
}

.l-news2 .news2-conte .date-news2 a::after {
    content: "";
    position: absolute;
    background: #ff3c78;
    height: 3px;
    width: 100%;
    left: 0;
    bottom: -10px;
    transition: 0.3s;
}

.l-news2 .news2-conte .date-news2 a:hover:after {
    width: 0%;
}

.l-news2 .news2-conte .date-news2 a:hover {
    color: var(--black);
}

.l-news3 .news3-conte .date-news3 p {
    color: var(--light-black);
    text-align: center;
    padding: 15px 0;
}

.l-news3 .news3-conte .date-news3 h4 {
    font-size: 18px;
    text-align: center;
    font-weight: 600;
    padding-bottom: 15px;
}

.l-news3 .news3-conte .date-news3 a {
    text-decoration: none;
    text-align: center;
    padding: 0 60px;
    color: var(--primary-color);
    position: relative;
    font-weight: 600;
}

.l-news3 .news3-conte .date-news3 a::after {
    content: "";
    position: absolute;
    background: #ff3c78;
    height: 3px;
    width: 100%;
    left: 0;
    bottom: -10px;
    transition: 0.3s;
}

.l-news3 .news3-conte .date-news3 a:hover:after {
    width: 0%;
}

.l-news3 .news3-conte .date-news3 a:hover {
    color: var(--black);
}


/* //........ Footer ...... // */

footer {
    width: 100%;
    background: var(--black);
}

.footer-container .content_1 img {
    height: 25px;
    width: 180px;
}

.footer-container {
    display: flex;
    justify-content: space-between;
    padding: 60px 0;
}

.footer-container h4 {
    color: var(--white);
    font-weight: 500;
    letter-spacing: 1px;
    margin-bottom: 25px;
    font-size: 18px;
}

.footer-container a {
    display: block;
    text-decoration: none;
    color: var(--grey);
    margin-bottom: 15px;
    font-size: 14px;
}

.footer-container .content_1 p,
.footer-container .content_4 p {
    color: var(--grey);
    margin: 25px 0;
    font-size: 14px;
}

.footer-container .content_4 input[type="email"] {
    background-color: var(--black);
    border: none;
    color: var(--white);
    outline: none;
    padding: 15px 0;
}

.footer-container .content_4 .f-mail {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer-container .content_4 .bx {
    color: var(--white);
}

.f-design {
    width: 100%;
    color: var(--white);
    text-align: center;
}

.f-design .f-design-txt {
    border-top: 1px solid var(--grey);
    padding: 25px 0;
    font-size: 14px;
    color: var(--grey);
}


/* //........ contact ...... // */

.contact {
    margin-top: 45px;
}

iframe {
    height: 72vh;
    width: 100%;
}

.form {
    display: flex;
    justify-content: space-between;
    margin: 80px 0;
}

.form .form-txt {
    flex-basis: 48%;
}

.form .form-txt h4 {
    font-weight: 600;
    color: var(--primary-color);
    letter-spacing: 1.5px;
    font-size: 15px;
    margin-bottom: 15px;
}

.form .form-txt h1 {
    font-weight: 600;
    color: var(--black);
    font-size: 40px;
    letter-spacing: 1.5px;
    margin-bottom: 10px;
    color: var(--light-black);
}

.form .form-txt span {
    color: var(--light-black);
    font-size: 14px;
}

.form .form-txt h3 {
    font-size: 22px;
    font-weight: 600;
    margin: 15px 0;
    color: var(--light-black);
}

.form .form-txt p {
    color: var(--light-black);
    font-size: 14px;
}

.form .form-details {
    flex-basis: 48%;
}

.form .form-details input[type="text"],
.form .form-details input[type="email"] {
    padding: 15px 20px;
    color: var(--grey);
    outline: none;
    border: 1px solid var(--grey);
    margin: 35px 15px;
    font-size: 14px;
}

.form .form-details textarea {
    padding: 15px 20px;
    margin: 0 15px;
    color: var(--grey);
    outline: none;
    border: 1px solid var(--grey);
    font-size: 14px;
    resize: none;
}

.form .form-details button {
    padding: 15px 25px;
    color: var(--white);
    font-weight: 500;
    background: var(--black);
    outline: none;
    border: none;
    margin: 15px;
    font-size: 14px;
    letter-spacing: 2px;
    cursor: pointer;
}


/* //....... Media Queries .......// */

@media (max-width: 500px) {
    .head {
        display: none;
    }
    .top-txt .head p,
    .top-txt .head a {
        font-size: 10px;
    }
    .home_txt h2,
    .home_txt .home_label p {
        display: none;
    }
    .home_txt {
        position: absolute;
        top: 20%;
        left: 5%;
        font-size: 12px;
    }
    .home_txt button {
        padding: 7px 7px;
        font-size: 10px;
    }
    .home_txt i {
        display: none;
    }
    .home_txt .home_social_icons {
        /* display: flex; */
        display: none;
    }
    .menu-items {
        margin-right: 0;
    }
    .best-seller {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .l-news {
        display: flex;
        flex-direction: column;
        margin-right: 30px;
    }
    .l-news .l-news1,
    .l-news .l-news2 {
        margin-bottom: 200px;
    }
    .footer-container {
        display: flex;
        flex-direction: column;
    }
    .footer-container .content_1 {
        margin-bottom: 30px;
    }
    .best-seller img {
        padding-top: 40px;
    }
}

@media(min-width: 501px) and (max-width: 768px) {
    .head {
        display: none;
    }
    .top-txt .head p,
    .top-txt .head a {
        font-size: 10px;
    }
    .home_txt h2,
    .home_txt .home_label p {
        display: none;
    }
    .home_txt {
        position: absolute;
        top: 20%;
        left: 5%;
        font-size: 12px;
    }
    .home_txt button {
        padding: 7px 7px;
        font-size: 10px;
    }
    .home_txt i {
        display: none;
    }
    .home_txt .home_social_icons {
        /* display: flex; */
        display: none;
    }
    .menu-items {
        margin-right: 0;
    }
    .best-seller {
        display: flex;
        flex-direction: column;
    }
    .l-news {
        display: flex;
        flex-direction: column;
        margin-right: 30px;
    }
    .l-news .l-news1,
    .l-news .l-news2 {
        margin-bottom: 200px;
    }
    .footer-container {
        display: flex;
        flex-direction: column;
    }
    .footer-container .content_1 {
        margin-bottom: 30px;
    }
    .best-seller img {
        padding-top: 40px;
    }
}

@media(orientation: landscape) and (max-height: 500px) {
    .header {
        height: 90vmax;
    }
}


/* //....... Media Queries For Contact .......// */

@media (max-width: 500px) {
    .form {
        display: flex;
        flex-direction: column;
    }
    .form .form-details button {
        margin-left: 0;
    }
    .form .form-details input[type="text"],
    .form .form-details input[type="email"],
    .form .form-details textarea {
        width: 100%;
        margin-left: 0;
    }
    .form .form-details input[type="text"] {
        margin-bottom: 0px;
    }
}

@media(min-width: 501px) and (max-width: 768px) {
    .form {
        display: flex;
        flex-direction: column;
    }
    .form .form-details button {
        margin-left: 0;
    }
    .form .form-details input[type="text"],
    .form .form-details input[type="email"],
    .form .form-details textarea {
        width: 100%;
        margin-left: 0;
    }
    .form .form-details input[type="text"] {
        margin-bottom: 0px;
    }
}

index.JS:

$(document).ready(function () {
    $("a").on("click", function (event) {
      if (this.hash !== "") {
        event.preventDefault();
  
        var hash = this.hash;
        $("html, body").animate(
          {
            scrollTop: $(hash).offset().top,
          },
          800,
          function () {
            window.location.hash = hash;
          }
        );
      }
    });
  });
  
  $(".menu-items a").click(function () {
    $("#checkbox").prop("checked", false);
  });

  
