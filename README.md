# Movie-Booking-Webiste
An HTML Project of a Movie Ticket Booking Website
Index Page Code -
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Booking Webiste - Book IT</title>
    <link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header class="header">

        <a href="#" class="logo"> <i class="fas fa-tape"></i> book It </a>
    
        <nav class="navbar">
            <a href="#home">home</a>
            
            <a href="products.html" target="_blank">Movies</a>
            <a href="#categories">offers</a>
            <a href="review.html" target="_blank">review</a>
            <a href=#contact>contact us</a>
            
        </nav>
    
        <div class="icons">
            <div class="fas fa-bars" id="menu-btn"></div>
            <div class="fas fa-search" id="search-btn"></div>
           
            <a href="login.html" target="_blank"><div class="fas fa-user" id="login-btn"></div></a>
        </div>  
    
        <form action="" class="search-form">
            <input type="search" id="search-box" placeholder="search here...">
            <label for="search-box" class="fas fa-search"></label>
        </form>
    
    
    </header>
    <section class="home" id="home">

        <div class="content">
            <br><br><br><br><br><br><br>
            <a href="products.html" class="btn">Book ticket</a>
        </div>
    
    </section>
    <h1 class="heading"> get a <span>combo</span> </h1>
    <section class="challen" id="home">
        
        <div class="content">
            <h3><span>Combo combo combo!!!!!!!!!!1</span></h3>
            <p>Get various kinds of drinks, beverages, tacos, sanwiches, burgers and much more, all of which will be provided to you inside the movie theatre</p>
            
        </div>
    
    </section>


    <marquee behavior="scroll" direction="left" onmousedown="this.stop();" onmouseup="this.start();">
        Today's Offer : 10% off on advance bookings 2 days before the show
        </marquee>

    <section class="footer">

        <div class="box-container">
    
            <div class="box">
                <h3> Book It <i class="fas fa-tape"></i> </h3>
                <p>The Perfect Theatre experience for the true fans</p>
                <p>Find us!</p>
                <div class="share">
                    <a href="#" target="_blank" class="fab fa-facebook-f" ></a>
                    <a href="#" target="_blank" class="fab fa-twitter"></a>
                    <a href="#" target="_blank" class="fab fa-instagram"></a>
                    <a href="#" target="_blank" class="fab fa-linkedin"></a>
                </div>
            </div>
    
            <div class="box">
                <h3>contact info</h3>
                <a href="#" class="links"> <i class="fas fa-phone"></i> +917223816456 </a>
                <a href="#" class="links"> <i class="fas fa-phone"></i> +917601090520 </a>
                <a href="#" class="links"> <i class="fas fa-envelope"></i>shanuarkham50@gmail.com </a>
                <a href="https://goo.gl/maps/vk2Vp9m6sQMgDNJ99" target="_blank" class="links"> <i class="fas fa-map-marker-alt"></i> Jalhandhar, india - 144001 </a>
            </div>

    
            <div class="box">
                <h3>newsletter</h3>
                <p>subscribe for latest updates</p>
                <input type="email" placeholder="your email" class="email">
                <input type="submit" value="subscribe" class="btn">
                <img src="image/payment.png" class="payment-img" alt="">
            </div>
    
        </div>
    
        <div class="credit"> created by <span> Vivekananda Banerjee, Vivek Kumar Singh and Ayush Singh </span> | all rights reserved </div>
    
    </section>


    
    <script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>
    <script src="javascript/index.js"></script>

</body>
</html>
