Hello everyone for anyone intrested in makeing travel website here is the Html, Css to help with that.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flight Teller</title>
    <link rel="stylesheet" 
    href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
    />
    
      




    <link rel="stylesheet" 
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">

 <link rel="stylesheet" href="style.css">
</head>
<body>
 <header class="header">
      <a href="#" class="logo"> <img class="logo-img" src="Logo.png" alt=""></a>
      <form action="" class="search-form">
         <input type="search"  name="" placeholder="Search here..." id="searchBox">
         <label for="searchBox" class=" fas fa-search"></label>
      </form>
      <div class="icons">
         <div class="fas fa-search" id="search-btn"></div>
         <div class="fas fa-moon" id="theme-btn"></div>
         <div class="fas fa-user" id="login-btn"></div>
         <div class="fas fa-user-plus" id="sign-btn"></div>
         <div class="fas fa-bars" id="menu-btn"></div>
      </div>
     
    <nav class="navbar">
      <a href="#home" class="home">Home</a>
       <a href="#packages">Packages</a>
        <a href="#services">Services</a>
          <a href="#review">Review</a>
           <a href="#contact">Contact</a>
    </nav>

    <form action="" class="login-form">

      <div class="inputbox" >
         <span> Username</span>
         <input type="text" placeholder="Enter your name">
      </div>


       <div class="inputbox" >
         <span> Password</span>
         <input type="password" placeholder="Enter your password">
      </div>
     <Div class="sign"> <li><a href="#"></a> <div class="signup">  <a href="sign up .html"> Don't have an account? Sign Up here</a></li></div></Div>

       <div class="remember">
         <input type="checkbox"  name="" id="remember-me">
         <label for="remember-me"> Remember Me</label>
         <br>
         <input type="submit" class="btn" value="Login">
      </div>
    </form>

    
<form action="" class="sign-form">

      <div class="inputbox" >
         <span> Username</span>
         <input type="text" placeholder="Enter your name">
      </div>


       <div class="inputbox" >
         <span> Password</span>
         <input type="password" placeholder="Enter your password">
      </div>


       <div class="remember">
         <input type="checkbox"  name="" id="remember-me">
         <label for="remember-me"> Remember Me</label>
         <br>
         <input type="submit" class="btn" value="Sign Up">
      </div>
    </form>

   </header>
 
   








<section class="home" id="home">
   <div class="image">

      <img src="home image 2.webp" alt="">
   </div>
   
   <div class="content">
      <h3>Adventure is worth it with Flight Teller</h3>
      <p>Your one-stop solution for all your flight needs.
         From booking to boarding, we've got you covered.
         Whether you're planning a business trip or a vacation,
         Flight Teller is here to make your travel experience seamless and enjoyable.
         With our user-friendly platform, you can easily search for flights, compare prices,
         and book your tickets in just a few clicks.
      </p>
      <a href="#" class="btn">Adventure Awaits you now</a>
</div>
</section>

<div class="contents">
   <h1>Welcome to Flight Teller</h1>
   <p>Where your journey begins with ease and comfort.</p>
</div>

<section class="form-container">
   <form action="">

      <div class="inputbox">
         <div class="inputbox">
         <span> Where from</span>
         <input type="text"  placeholder=  "Enter your location">
      </div>

        

         <span> Where to</span>
         <input type="text" placeholder="Enter your destination">
      </div>

      <div class="inputbox">
         <span> Arrival Date</span>
         <input type="date" >
      </div>



       <div class="inputbox">
         <span> Leaving Date</span>
         <input type="date" >


         <input type="submit" value="book now" class="btn"> 
      </div>
   </form>

</section>




<section class="packages" id="packages">
   
   <h1 class="heading">Our <span>packages</span></h1>
      
   <div class="box-container">
      <div class="box">
         <div class="image">
            <img src="Paris.avif" alt="">
            <h3><i class="fas fa-map-marker-alt">Paris</i> </h3>
         </div>
         <div class="content">
            <div class="price"> $290.99 <span>$360.99</span></div>
            <p>Discover the modern marvels and rich heritage of Paris.
               From the iconic Eiffel Tower to the charming streets of Montmartre,
               there's a perfect blend of art, culture, and history waiting for you.
            </p>
            <a href="#" class="btn">Book Now</a>
         </div>
      </div>
   
      <div class="box">
         <div class="image">
            <img src="hong kong.jpg" alt="">
            <h3><i class="fas fa-map-marker-alt">Hong Kong</i> </h3>
         </div>
         <div class="content">
            <div class="price"> $290.99 <span>$360.99</span></div>
            <p>Experience the vibrant culture and stunning skyline of Hong Kong.
               From the bustling streets of Mong Kok to the serene beauty of Victoria Harbour,
               there's something for every traveler to enjoy.
            </p>
            <a href="#" class="btn">Book Now</a>
         </div>
      </div>

      <div class="box">
         <div class="image">
            <img src="pic 1 Mumbai.avif" alt="">
            <h3><i class="fas fa-map-marker-alt">Mumbai</i> </h3>
         </div>
         <div class="content">
            <div class="price"> $290.99 <span>$360.99</span></div>
            <p>Discover the modern marvels and rich heritage of Mumbai.
               From the iconic Gateway of India to the bustling markets of Colaba,
               there's a perfect blend of tradition and innovation waiting for you.
            </p>
            <a href="#" class="btn">Book Now</a>
         </div>
      </div>

      <div class="box">
         <div class="image">
            <img src="Pic two Tokyo.webp" alt="">
            <h3><i class="fas fa-map-marker-alt">Tokyo</i> </h3>
         </div>
          <div class="content">
            <div class="price"> $290.99 <span>$360.99</span></div>
            <p>Explore the vibrant culture and rich history of Tokyo.
               From the bustling streets of Shibuya to the serene gardens of the Imperial Palace,
               especially for anime lovers, Tokyo is a paradise with its countless anime shops, themed cafes, and events.
               Just waiting to be explored!
            </p>
            <a href="#" class="btn">Book Now</a>
         </div>
      </div>

      <div class="box">
        <div class="image">
         <img src="pic four Dubai.jpg" alt="">
            <h3><i class="fas fa-map-marker-alt">Dubai</i> </h3>
        </div>
        <div class="content">
            <div class="price"> $290.99 <span>$360.99</span></div>
            <p>Discover the modern marvels and rich heritage of Dubai.
               From the iconic Burj Khalifa to the historic Al Fahidi neighborhood,
               there's a perfect blend of tradition and innovation waiting for you.
            </p>
            <a href="#" class="btn">Book Now</a>
        </div>
      </div>
     
      <div class="box">
         <div class="image">
            <img src="OIP (1).webp" alt="">
            <h3><i class="fas fa-map-marker-alt">Nigeria</i> </h3>
         </div>
         <div class="content">
            <div class="price"> $290.99 <span>$360.99</span></div>
            <p>
               Explore the vibrant culture and rich history of Nigeria.
               From the bustling markets of Lagos to the serene landscapes of Abuja,
               there's something for every traveler to enjoy.
               Whether you're interested in the diverse wildlife, the rich traditions, or the modern cities,
               Nigeria offers a unique and unforgettable experience.
            </p>
            <a href="#" class="btn">Book Now</a>
         </div>
      </div>
   </div>
</section>





<section class="services" id="services">
   <h1 class="heading">Our <span>Services</span></h1>

   <div class="box-container">
         <div class="box">
            <span>01</span>
            <i class="fas fa-hotel"></i>
            <h3>Affordable hotels</h3>
            <p>               Enjoy a comfortable stay at our affordable hotels.
               We offer a range of accommodations to suit every budget,
               ensuring you have a pleasant and relaxing experience during your travels.
               From cozy rooms to luxurious suites, we have it all.
            </p> 
         </div>
         

            <div class="box">
            <span>02</span>
            <i class="fas fa-plane"></i>
            <h3>Affordable flights/fastest flights</h3>
            <p>
               Find the best deals on flights to your favorite destinations.
               Our platform offers a wide range of options, from budget airlines to premium carriers,
               ensuring you get the best value for your money.
            </p> 
            </div>

             <div class="box">
            <span>03</span>
            <i class="fas fa-utensils"></i>
            <h3>Affordable restaurants with good food and drinks</h3>
            <p>
               Discover a selection of affordable restaurants offering delicious food and drinks.
               From local delicacies to international cuisine, we have options to satisfy every palate.
               Enjoy a memorable dining experience without breaking the bank. 
            </p> 
         </div>

          <div class="box">
            <span>04</span>
            <i class="fas fa-globe"></i>
            <h3>Travel packages/around the world</h3>
            <p>
               Explore our diverse range of travel packages designed to take you around the world.
               Whether you're looking for a relaxing beach getaway or an adventurous mountain trek,
               we have the perfect package for you.   
            </p> 
         </div>

          <div class="box">
            <span>05</span>
            <i class="fas fa-hiking"></i>
            <h3>Adventure trips</h3>
            <p>
               Experience the thrill of adventure with our curated trips.
               From hiking in the mountains to exploring hidden gems,
               we offer a range of exciting adventures tailored to your interests.
               Join us for an unforgettable journey into the wild.
            </p> 
         </div>

          <div class="box">
            <span>06</span>
            <i class="fas fa-bullhorn"></i>
            <h3>Safety guides</h3>
            <p>
               Our safety guides ensure you have a secure and enjoyable travel experience.
               For every destination, we provide essential tips and advice to keep you safe.
               Our top priority being your safety and well-being.

            </p> 
         </div>

      </div>
   </div>   



</section>


<section class="review" id="review">
   <h1 class="heading">Customer <span>Reviews</span></h1>

<div class="swiper review-slider">

   <div class="swiper-wrapper">

      <div class="swiper-slide slide">
         <img src="review 1.jpg" alt="">
         <h2>Tie Chan</h2>
         <h3> The best travel experience I've ever had!
            website is user-friendly and the customer service is top-notch.
            Flight Teller made my trip unforgettable. Highly recommend!
         </h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>   
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
         </div>
      </div>
      <div class="swiper-slide slide">
         <img src="review 2.jpg" alt="">
         <h2>lia Chan</h2>
         <h3>
            Flight Teller exceeded my expectations! 
            The booking process was smooth, and the prices were unbeatable.
            I loved the personalized recommendations for my trip.
            Will definitely use it again!
        </h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>   
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
         </div>
      </div>
      <div class="swiper-slide slide">
         <img src="review 3.avif" alt="">
         <h2>Anime nerd</h2>
         <h3>
            Flight Teller is a game-changer for travelers! 
            The variety of options and the ease of booking are impressive. 
            I can't wait to plan my next adventure with them!
         </h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>   
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
         </div>
      </div>
      <div class="swiper-slide slide">
         <img src="review 4.jpg" alt="">
         <h2>John Doe</h2>
         <h3>
            Flight Teller made my trip unforgettable. Highly recommend!
            The website is user-friendly and the customer service is top-notch.
            The best travel experience I've ever had!
            
         </h3>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>   
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
         </div>
      </div>
   </div>



 <div class="swiper-pagination"></div>

</div>

</section>







<section class="contact" id="contact">
   <h1 class="heading"><span>Contact</span>us</h1>
   <form action="">
      <input type="text" placeholder="Enter your name">
      
      <input type="email" placeholder="Enter your email">
      
      <input type="password" placeholder="Enter your password">
      
      <input type="password" placeholder="Enter your password">

      
      <input type="text" placeholder="Enter your phone number">
      <textarea placeholder="Enter your message"></textarea>
      
      <input type="submit" value="Send Message">
   </form>
</section>

Here Is the Css part.
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600;700&display=swap');

:root{
     --blue: #56ceec;
    --text-color-1: #444;
    --text-color-2: #666;
    --bg-color-1: #fff;
    --bg-color-2: #eee;
    --box-shadow: 0 .5rem 1.5rem rgb(14, 13, 0);
}

*{
    font-family:'Poppins', sans-serif;
    margin: 0; padding: 0;
    box-sizing: border-box;
    outline: none; border: none;
    text-decoration: none;
    text-transform: capitalize;
    transition: all .2s linear;
} 

html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-padding-top: 7rem;
    scroll-behavior: smooth;
}

html ::-webkit-scrollbar{
    width:.8rem;

}    

html::-webkit-scrollbar-track{
background:transparent;

}



html::-webkit-scrollbar-thumb{
background:var(--blue);
    border-radius: 1rem;
}

body{
    background: var(--bg-color-2);
}


body.active{
 
    --text-color-1: #fff;
    --text-color-2: #eee;
    --bg-color-1: #333;
    --bg-color-2: #222;
    --box-shadow: 0 .5rem 1.5rem rgba(0,0,0,4); 
}

section{
    padding: 2rem 7%;
}

.header{
    position: fixed;
    top:0; left:0; right: 0;
    background:var(--bg-color-1);
    box-shadow:var(--box-shadow);
    padding: 1rem 2rem;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
}



.header .logo{
    font-size: 2.5rem;
    color: var(--blue);
    font-weight: 700;
    color: var(--text-color-1);
}


.header .logo > i{
    color: var(--blue);
}


.header .search-form{
    background: var(--bg-color-2);
    border-radius: 1rem;
    display: flex;
    align-items: center;
    height: 4.5rem;
    width: 50rem;
}


.header .search-form input{
    height: 100%;
    width: 100%;
    background: none;
    text-transform: none;
    font-size: 1.5rem;
    color: var(--text-color-1);
    padding: 1rem;
}


.header .search-form .label{
    font-size: 2rem;
    margin-right: 1.5rem;
    color: var(--text-color-1);
    cursor: pointer;
}


.header .search-form label:hover{
    color: var(--blue);
}


.header .search-form input:focus{
    border: 1px solid var(--blue);
    box-shadow: 0 0 0.5rem rgba(35, 31, 247, 0.5);
}


.header .icons>div{
    height: 3.5rem;
    width: 3.5rem;
    line-height: 3.5rem;
    border-radius: 1rem;
    margin-left: 5rem;
    background: var(--bg-color-2);
    color: var(--text-color-1);
    cursor: pointer;
    text-align: center;
}
.header .icons>div:hover{
     color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
}




#search-btn{
    display: none;
}


.header .navbar{
    position: absolute;
    top: 115%;right: 7%;
    background: var(--bg-color-1);
    border-radius: 1rem;
    box-shadow: var(--box-shadow);
    width: 25rem;
    transform: scale(0);
    transform-origin: top right;
}

.header .navbar.active{
    transform: scale(1);
   
}

.header .navbar a{
    display: block;
    margin: 1rem ;
    padding: 1rem;
    font-size: 1.5rem;
    color:black;
    border-radius:1rem ;
}



.header .navbar a:hover{
     color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
    padding-left: 2rem;
}


.header .login-form{
    position: absolute;
    top: 115%;right: 7%;
    background: var(--bg-color-1);
    border-radius: 1rem;
    box-shadow: var(--box-shadow);
    width: 45rem;
    padding: 2rem;
    height: 35rem;
     transform: scale(0);
    transform-origin: top right;
}

.header .login-form.active{
    transform: scale(1);
}



.header .login-form .inputbox span{
    font-size: 1.7rem;
    color: var(--text-color-2);
    width: 25rem;
}


.header .login-form .inputbox input{
   
    font-size: 1.5rem;
    color: var(--text-color-2);
    border-radius:  1rem;
    padding: 1rem;
    background: var(--bg-color-2);
    width: 100%;
    text-transform: none;
    margin: 10px 0;
    width: 25rem;
    display: block;

}


.header .login-form .inputbox input:hover{
      color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
    padding-left: 2rem;
    
}

.header .login-form .inputbox input:focus{
     color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
    padding-left: 2rem;
    
}


.header .login-form .remember{
    /* display: flex; */
    align-items: center;
   gap: 5rem 0;
   padding:1rem 0;
   
}

.header .login-form .remember label{
 color: var(--text-color-2);
 font-size: 1.5rem;
 cursor: pointer;
 
}

.header .sign-form{
    position: absolute;
    top: 115%;right: 7%;
    background: var(--bg-color-1);
    border-radius: 1rem;
    box-shadow: var(--box-shadow);
    width: 45rem;
    padding: 2rem;
    height: 35rem;
     transform: scale(0);
    transform-origin: top right;
}

.header .sign-form.active{
    transform: scale(1);
}



.header .sign-form .inputbox span{
    font-size: 1.7rem;
    color: var(--text-color-2);
    width: 25rem;
}


.header .sign-form .inputbox input{
   
    font-size: 1.5rem;
    color: var(--text-color-2);
    border-radius:  1rem;
    padding: 1rem;
    background: var(--bg-color-2);
    width: 100%;
    text-transform: none;
    margin: 10px 0;
    width: 25rem;
    display: block;

}


.header .sign-form .inputbox input:hover{
      color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
    padding-left: 2rem;
    
}

.header .sign-form .inputbox input:focus{
     color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
    padding-left: 2rem;
    
}


.header .sign-form .remember{
    /* display: flex; */
    align-items: center;
   gap: 5rem 0;
   padding:1rem 0;
   
}

.header .sign-form .remember label{
 color: var(--text-color-2);
 font-size: 1.5rem;
 cursor: pointer;
 
}







 input.btn{
    display: block;
}


.heading{
    text-align: center;
    padding: 2rem ;
    color: var(--text-color-1);
    font-size: 3rem;
}

.heading Span{
    position: relative;
    z-index: 0;
}

 .packages{
    width: 100%;
    /* display: grid;
    display: block; */
}




.heading Span::before{
    content: '';
    position: absolute;
    bottom: 1rem;left: 0;
   z-index: inherit;
   background: var(--blue);
   height: 100%;
    width: 100%;
    clip-path: polygon(0 90%, 100% 83%, 100% 100%, 0% 100%);
}

.btn{
    margin-top:1rem;
    display: inline-block;
    padding: 1rem 1rem;
    font-size: 1.7rem;
    color: var(--text-color-1);
    background: rgb(0, 183, 255);
    border-radius: 1rem;
    cursor: pointer;
    width: 100%;
    text-align: center;

}

.btn:hover{
    color: rgb(129, 1, 1);
    padding-left: 2rem;
}


.home{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 1.5rem;
    padding-top: 7rem ;
}

.home .image{
    flex: 1 1 45rem;
    }

    .home .image img{
    width: 100%;
    }


.home .content{
    flex: 1 1 45rem;
    }

    
.home .content h3{
    color: var(--text-color-1);
    font-size: 4rem;

 }


 .home .content p{
    color: var(--text-color-2);
    font-size: 1.7rem;
    line-height: 1.7;
    padding: 1rem 0;
    
 }



 .form-container form {
    display: flex;
    flex-wrap: wrap;
    gap: 2.5rem;
    justify-content: space-between;
    padding: 2rem;
    background: var(--bg-color-1);
    box-shadow: var(--box-shadow);
    border-radius: 1rem;
   font-weight: bold;
   background-color: var(--blue);


}

.btn:hover{
    background: rgb(250, 225, 0);
    color: rgba(156, 4, 183, 0.644);
    padding-left: 2rem;
}




.form-container .inputbox{
    max-width: 1200px;
      margin: auto;
      display: flex;
      flex-direction: row;
      padding: 2rem;
      background-color:var(--blue);
      color: #333;
      flex: 1;
      min-width: 200px;
      font-weight: bold;
    margin-right: 10px;

}

.form-container  form .inputbox span{
    font-size: 1.7rem;
    color: var(--text-color-2);
    width: 100%;
    text-transform: none;
     font-weight: bold;
    display: flex;
      flex-direction: column;
    gap: 12px;

}

.sign{
    color: var(--blue);
    font-size: 1.5rem;
   
}

.signup{
    color: var(--blue);
    
}

.form-container  form .inputbox input{
    color: black;
    display: block;
    margin: 1rem 0;
    display: flex;
      flex-wrap: wrap;
      gap: 1px;
      background-color: white;
      border-radius: 16px;
      overflow: hidden;
      align-items: center;
      font-weight: bold;
      

    
}


.form-container .inputbox input:hover{
     color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
    padding-left: 2rem;
    
}

.form-container form .btn{
     max-width: 1200px;
      margin: auto;
        background: var(--blue);
      color: white;
      padding: 0.6rem 1rem;
      border: 1px solid #174f72;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
}
.form-container form .btn{
    background-color: #0070f3;
      color: white;
      border: none;
      padding: 1.1rem 2rem;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      border-radius: 0 16px 16px 0;
      transition: background 0.3s ease;
     
}

.form-container form .btn:hover{
    background: rgb(250, 225, 0);
    color: rgba(156, 4, 183, 0.644);
    padding-left: 2rem;
}

 




.packages .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(25rem, 2fr));
    gap: 5rem;
}

.packages .box-container .box{
    background: var(--bg-color-1);
    box-shadow: var(--box-shadow);
}



.packages .box-container .box .image {
height: 25rem;
width: 100%;
padding: 1.5rem;
position: relative;
}

.packages .box-container .box .image img {
    height: 100%;
    width: 100%;
    object-fit: cover;
    border-radius: 1rem;
}


.packages .box-container .box .image h3{
    position: absolute;
    top: 2.5rem; left: 2.5rem;
    font-size: 2rem;
    color: #fff;
    background: rgba(0,0,0,.5);
    border-radius: 1rem;
    font-weight: lighter;
    padding: 1rem 1.5rem;
}


.packages .box-container .box .image h3 i{
    color   : rgba(200, 167, 4, 0.815);
}


.packages .box-container .box .content{
    padding: 1.5rem;
    padding-top: 0;

}

.packages .box-container .box .content .price{
    font-weight: 600;
    color: var(--text-color-1);
    font-size: 2.5rem;

}


.packages .box-container .box .content .price Span{
        font-weight: lighter;
    color: var(--text-color-2);
    font-size: 1.5rem;
    text-decoration:line-through ;
}


.packages .box-container .box .content p{
    font-size: 1.5rem;
    color: var(--text-color-2);
    line-height: 1.7;
    padding: 1rem 0;
}



.services .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(25rem, 2fr));
    gap: 1.5rem;
}


.services .box-container .box{
    background: var(--bg-color-1);
    border-radius: 1rem;
    box-shadow: var(--box-shadow);
    position: relative;
    padding: 1rem;
   
}


.services .box-container .box span{
    position: absolute;
    top: 5.5rem; right: 2rem; left: 20rem;
    color: var(--text-color-2);
    font-weight: bolder;
    font-size: 4rem;
    
}

.services .box-container .box i{
    height: 6rem;
    width: 6rem;
    line-height: 6rem;
    text-align: center;
    font-size: 2.5rem;
    color: #fff;
    background: var(--blue);
    border-radius: 50%;
    margin-bottom: 3rem;
}

.services .box-container .box i:hover{
     color: rgba(158, 140, 1, 0.957);
    background-color: rgba(156, 2, 2, 0.635);
}

.services .box-container .box h3{
    color: var(--text-color-1);
    font-size: 2rem;
    padding: 1rem 0;
}

.services .box-container .box p{
    color: var(--text-color-1);
    font-size: 1.5rem;
    line-height: 1.7;
}







.services{
    width: 100%;
    padding: 2rem 0;
}


.review .review-slider{
    box-shadow: var(--box-shadow);
}


.review .review-slider .slide {
    background: var(--bg-color-1);
    border-radius: 1rem;
    text-align: center;
    padding: 3rem;
    color: var(--text-color-1);
}

.slide img{
    height: 15rem;
    width: 15rem;
    border-radius: 50%;
    margin-bottom: 2rem;
}


.review .review-slider .slide .stars {   
    padding: 1rem 0;
    padding-bottom: 1.5rem;
    
}


.review .review-slider .slide .stars i{
    color: #f0c040;
    font-size: 2rem;
}



.swiper-pagination-bullet-active{
    background: var(--blue);
}


.form-container form .btn:hover{
    flex: 1 1 23rem;
    background: rgb(250, 225, 0);
    color: rgba(156, 4, 183, 0.644);
    padding-left: 2rem;
}



.contact form{
    max-width: 80rem; 
    margin: 0 auto;
    /* text-align: center; */
    background: var(--blue);
    padding: 2rem;
    box-shadow: var(--box-shadow);
    border-radius: 1rem;
    color: var(--text-color-1);
    width: 100%;
    flex-wrap: wrap;
    display: flex;
    gap: 1rem;
    justify-content: space-between;
}


.contact form textarea,
.contact form input{
    width: 49%;
    padding: 1rem;
    font-size: 1.5rem;
    color: var(--text-color-1);
    margin: 3rem 0;
    background: var(--bg-color-1);
    box-shadow: var(--box-shadow);
    text-transform: none;
    border: none;
    border-radius: 1rem;
   
}

.contact form textarea{
    width: 100%;
    padding: 1rem;
    font-size: 1.5rem;
    color: var(--text-color-1);
    margin: 1rem 0;
    background: var(--bg-color-1);
    box-shadow: var(--box-shadow);
    text-transform: none;
    border-radius: 1rem;
    height: 20rem;
    resize: none;
}






.contents{
    width: 100%;
    padding: 2rem;
    text-align: center;
    background: var(--bg-color-1);
    box-shadow: var(--box-shadow);
    border-radius: 1rem;
    margin-top: 2rem;
    color: var(--text-color-1);
    font-size: 1.5rem;
    line-height: 1.7;
}


.logo-img{
    height: 5rem;
    width: 15rem;
    border-radius: 25%;
    object-fit: cover;
    margin-left: 2rem;
    text-align: center;
    display: inline-block;
}











 @media(max-width:991px) {
 html{
    font-size: 55%;
}


.header{
    padding: 1.5rem 2rem;
}

section{
    padding:2rem;
}

.header .navbar{
    right: 2rem;
}



.header .login-form{
    right: 2rem;
}




.header .search-form{
    right: 2rem;
}
}



@media(max-width:768px) {
    .header{
    padding: 1.5rem 2rem;
}


.header .navbar{
    right: 2rem;
}



.header .login-form{
    right: 2rem;
}




.header .search-form{
    position: absolute;
     top: 115%;right: 2rem;
     background: var(--bg-color-1);
    border-radius: 1rem;
    box-shadow: var(--box-shadow);
    width: 90%;
    
}

.search-box {
        flex-direction: column;
        border-radius: 16px;
      }

      .search-button {
        border-radius: 0 0 16px 16px;
        width: 100%;
      }


 
} /* <-- Close the @media(max-width:768px) block here */

@media(max-width:450px) {
 html{
    font-size: 55%;
}


.header{
    padding: 1.5rem 2rem;
}


 }



















<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<script src="script.js"></script>

</body>
</html>
