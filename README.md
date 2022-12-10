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



Second Page Product -
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="products.css    ">
   <title>Products</title>

   

</head>
<body>
   <header class="header">

      <a href="#" class="logo"> <i class="fas fa-tape"></i> Book It </a>
  
      <nav class="navbar">
          <a href="index.html">home</a>
          <!-- <a href="#features">revolution</a> -->
          <a href="products.html" target="_blank">movies</a>
          <a href="#categories">offers</a>
          <a href="review.html">review</a>
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
<br><br><br><br>
<div class="container">

   <h3 class="title"> Now Showing </h3>

   <div class="products-container">

      <div class="product" data-name="p-1">
         <img src="Now Showing/1-1.jpg" alt="">
         <h3>bhediya</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-2">
         <img src="Now Showing/an-action-hero-movie-review-02.jpg" alt="">
         <h3>an action hero</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-3">
         <img src="Now Showing/images.jpg" alt="">
         <h3>smile</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-4">
         <img src="Now Showing/MHA_WHM_Concept_KeyArt_TrailerPoster.jpg" alt="">
         <h3>my hero academia</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-5">
         <img src="Now Showing/MV5BNTM4NjIxNmEtYWE5NS00NDczLTkyNWQtYThhNmQyZGQzMjM0XkEyXkFqcGdeQXVyODk4OTc3MTY@._V1_.jpg" alt="">
         <h3>wakanda forever</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-6">
         <img src="Now Showing/MV5BNzc1N2NkMDktNDBmNy00NDJmLWIzZGEtOTgyMjc2ZmFmNWEwXkEyXkFqcGdeQXVyOTI3MzI4MzA@._V1_.jpg" alt="">
         <h3>drishyam 2</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

   </div>

</div>
<div class="container">

   <h3 class="title"> Upcoming movies </h3>

   <div class="products-container">

      <div class="product" data-name="p-1">
         <img src="Big Upcoming Projects/99800372_max.jpg" alt="">
         <h3>puss in boots</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00 - Advance Booking Open</div>
      </div>

      <div class="product" data-name="p-2">
         <img src="Big Upcoming Projects/avatar-the-way-of-water-poster-960x1200.jpg" alt="">
         <h3>avatar</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00 - Advance Booking Open</div>
      </div>

      <div class="product" data-name="p-3">
         <img src="Big Upcoming Projects/Colourful-new-Cirkus-poster-is-a-glimpse-of-Ranveers-dual-role.jpg" alt="">
         <h3>cirkus</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-4">
         <img src="Big Upcoming Projects/Fi628fHVUAA4q3i.jpg" alt="">
         <h3>Babylon</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-5">
         <img src="Big Upcoming Projects/md5wZRRj8biHrGtyitgBZo7674t.jpg" alt="">
         <h3>Evangelion 3.0</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

      <div class="product" data-name="p-6">
         <img src="Big Upcoming Projects/u6A9Z2jfMG76HIk9TGpufknTejuCSbrZD1upBYoo.jpg" alt="">
         <h3>Salaam Venky</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">$2.00</div>
      </div>

   </div>

</div>
<div class="container">

   <h3 class="title"> 2023 - Get Hyped!</h3>

   <div class="products-container">

      <div class="product" data-name="p-1">
         <img src="2023/FaL4BXuVQAAVV1Y.jpg" alt="">
         <h3>Salaar</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">Coming Soon</div>
      </div>

      <div class="product" data-name="p-2">
         <img src="2023/th.jpg" alt="">
         <h3>Guardians Of The Galaxy Vol.3</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">Coming Soon</div>
      </div>

      <div class="product" data-name="p-3">
         <img src="2023/Maidaan_Poster.jpg" alt="">
         <h3>Maidaan</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">Coming Soon</div>
      </div>

      <div class="product" data-name="p-4">
         <img src="2023/MV5BMDMwODg0M2EtODVhNC00NmUxLThlNDYtNjUyNDE2OWFkNGU2XkEyXkFqcGdeQXVyMTUzNDYyMDk4._V1_.jpg" alt="">
         <h3>Jawan</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">Coming Soon</div>
      </div>

      <div class="product" data-name="p-5">
         <img src="2023/MV5BNDgyNGM4NTYtN2M3MS00YTY2LTk0OWUtZmIzYjg3MmQ0OGM4XkEyXkFqcGdeQXVyODk4OTc3MTY@._V1_FMjpg_UX1000_.jpg" alt="">
         <h3>Antamn and The Wasp Quantamania</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">Coming Soon</div>
      </div>

      <div class="product" data-name="p-6">
         <img src="2023/MV5BNDUyODIzZGUtYmU3OS00MGZlLTgwZGItOTQxOWMwZDliOWRmXkEyXkFqcGdeQXVyNTkzNDQ4ODc@._V1_.jpg" alt="">
         <h3>Pathaan</h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">Coming Soon</div>
      </div>

   </div>

</div>

<section class="footer">

   <div class="box-container">

       <div class="box">
           <h3> book It <i class="fas fa-shopping-basket"></i> </h3>
           <p>The Perfect Theatre Experience For The True Fans</p>
           <p>Find Us</p>
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
           <a href="#" class="links"> <i class="fas fa-phone"></i> +917601090520</a>
           <a href="#" class="links"> <i class="fas fa-envelope"></i> shanuarkham50@gmail.com </a>
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

   <div class="credit"> created by <span> Vivekananda Banerjee, Vivek Kumar Singh and Ayush Singh</span> | all rights reserved </div>

</section>


</body>
</html>
