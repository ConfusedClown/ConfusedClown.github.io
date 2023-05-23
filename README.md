<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css"> 
    <meta name="viewport" content=""width=device-width, initial-scale="1">
    <link rel="stylesheet" href="htts://use.fontawesome.com/releases/v5.5.0/css/all.css">
    <link  href="https://unpkg.com/boxicons@2.1.4/css/boxicond.min.css" rel="stylesheet">
</head>
<body>
    <!--header section starts-->
<section class="header" id="home">
<a href="#" class="logo"><span>Keansburg</span>Park</a>
<div class="visit"> 

                                                                                     
    <script type="text/javascript">
                                                   var counterContainer = document.querySelector(".website-counter");
                                                   var resetButton = document.querySelector("#reset");
                                                   var visitCount = localStorage.getItem("page_view");
                                                   
                                                   // Check if page_view entry is present
                                                   if (visitCount) {
                                                     visitCount = Number(visitCount) + 1;
                                                     localStorage.setItem("page_view", visitCount);
                                                     document.write("VISIT COUNT: "+visitCount);
                                                   } else {
                                                     visitCount = 1;
                                                     localStorage.setItem("page_view", 1);
                                                   }
                                                   counterContainer.innerHTML = visitCount;
                                                   
                                                   // Adding onClick event listener
                                                   resetButton.addEventListener("click", () => {
                                                     visitCount = 1;
                                                     localStorage.setItem("page_view", 1);
                                                     counterContainer.innerHTML = visitCount;
                                                   });
                                                       </script>
                                          </div>
 <!--navbar stars-->
 <div id="toggle"></div>
    
 <div id="sidebar">
     <ul>
         <li><a href="#home">Home</a></li>
         <li><a href="#aboutus">About us</a></li>
         <li><a href="#restaurant">Restaurant</a></li>
         <li><a href="#gallery">Gallery</a></li>
         <li><a href="#entertainment">Entertainment</a></li>
         <li><a href="#ticket">Ticket</a></li>
         <li><a href="#contactus">Contact us</a></li>
         <li><a href="#reviews">Reviews</a></li>
         
         
     </ul>
 </div>

 <button class="btnlogin-popup">Login</button>
 <section>
    
 </section>
</div>
<script>
 const toggle = document.getElementById('toggle');
 const sidebar = document.getElementById('sidebar')


document.onclick = function(e){
 if(e.target.id !== 'sidebar' && e.target.id !== 'toggle'){
     toggle.classList.remove('active');  
     sidebar.classList.remove('active') 
 }
}

 toggle.onclick = function(){
     toggle.classList.toggle('active');  
     sidebar.classList.toggle('active') 
 }
</script>
 <!--navbar endrs-->

</section>


    <!--header section ends-->
   <!--login form-->



  <!--login form-->

<!---home section starts-->

<section class="home" id="home">
    
<h1 class="home-parallax" data-speed="-2">Keansburg park</h1>
<img class="home-parallax" data-speed="5" src="imges/background1" alt="">

<div class="wrappers">
      <span class="icon-close"><ion-icon name="close-outline"></ion-icon></span>
    <div class="form-box login">
        <h2>Login</h2>
        <form action="#">
            <div class="input-box">
                <span class="icon"><ion-icon name="mail-outline"></ion-icon></span>
                
                <input type="email" required>
                <label>Email</label>
            </div>
            <div class="input-box">
                <span class="icon"><ion-icon name="lock-closed-outline"></ion-icon></span>
                <input type="password" required>
                <label>password</label>
            </div>
            <div class="remember-forgot">
                <label><input type="checkbox">
                Remember me</label>
                <a href="#">foegot password?</a>
            </div>
            <button type="submit" class="btn">Login</button>
            <div class="login-register">
                <p>Dont have an account <a href="#" class="register-link">Register</a></p>
            </div>
        </form>
    </div>



    <div class="form-box register">
        <h2>Register</h2>
        <form action="#">
            <div class="input-box">
                <span class="icon"><ion-icon name="person-outline"></ion-icon></span>
                
                <input type="text" required>
                <label>User Name</label>
            </div>

            <div class="input-box">
                <span class="icon"><ion-icon name="mail-outline"></ion-icon></span>
                
                <input type="email" required>
                <label>Email</label>
            </div>

            <div class="input-box">
                <span class="icon"><ion-icon name="lock-closed-outline"></ion-icon></span>
                <input type="password" required>
                <label>password</label>
            </div>
            <div class="remember-forgot">
                <label><input type="checkbox">
                I agree to the terams & conditions</label>
                
            </div>
            <button type="submit" class="btn">Regidter</button>
            <div class="login-register">
                <p>Already have an account <a href="#" class="login-link">Login</a></p>
            </div>
        </form>
    </div>
</div>



</section>



<!---home section ends-->

<!--icons section starts-->


<section class="icons-container">

<div class="icons">
<i class="fas fa-home"></i>
<div class="content">
    <h3>80+</h3>
    <p>branches</p>
</div>
</div>

<div class="icons">
    <i class="fas fa-plane"></i>
    <div class="content">
        <h3>888+</h3>
        <p>tauris</p>
    </div>
    </div>

    <div class="icons">
        <i class="fas fa-users"></i>
        <div class="content">
            <h3>8880+</h3>
            <p>happy clients</p>
        </div>
        </div>

</section>

<!--icons section starts-->


<!--Gallery-->
<hr>

<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;">our <span>Gallery</span> </h1>
<hr>
<section class="gallery"id="gallery"></section>
<section class="gallery"id="gallery"style=>
    <div class="gallery-slider">
        <div>
            <div >
            <div class=" box">
                <img src="imges/boat.jpg">
                <div class="content">
                    <h3>BOAT RIDE</h3>
                    <div class="price"><span>Ticket Price:</span>$5.1</div>
                  
                    <a href="#" type="button" class="btn">Check out</a>
                </div>
            </div>

                <div class=" box">
                    <img src="imges/bomber.jpg">
                    <div class="content">
                        <h3>BUMPER CAR</h3>
                        <div class="price"><span>Ticket Price:</span>$4.5</div>
                     
                        <a href="#" type="button" class="btn">Check out</a>
                    </div>
                </div>
    
               <div class="box">
                <img src="imges/merrygo.jpg">
                <div class="content">
                    <h3>MERRY GO AROUND</h3>
                    <div class="price"><span>Ticket Price:</span>$6.</div>
                    
                    
                    <a href="#" type="button" class="btn">Check out</a>
                </div>
                </div>
    
                <div class=" box">
                    <img src="imges/ounce.jpg">
                    <div class="content">
                        <h3>BOUNCE HOUSE</h3>
                        <div class="price"><span>Ticket Price:</span>$5.</div>
                       
                        <a href="#" type="button" class="btn">Check out</a>
                    </div>
            </div>
        </div>
        <div class="box">
            <img src="imges/rollercoaster.jpg">
            <div class="content">
                <h3>ROLLACOATER</h3>
                <div class="price"><span>Ticket Price:</span>$7.</div>
              
                <a href="#" type="button" class="btn">Check out</a>
            </div>
            </div>
           </div>
           <div class="box">
            <img src="imges/wheel.jpg">
            <div class="content">
                <h3>FERIS WHEEL</h3>
                <div class="price"><span>Ticket Price:</span>$4.6</div>
                
                <a href="#" type="button" class="btn">Check out</a>
            </div>
           </div>
         </div>
        
        <br>
        <br>
        <br>
        
      
        <!-- If we need navigation buttons -->
        <div class="swiper-button-prev"></div>
        <div class="swiper-button-next"></div>
    <div>
    </div>
    </div>
    </div>
    
          
</section> 

<!--Gallery-->
<!--TICKETS-->
<hr>

<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;"><span>Ticket</span> </h1>
<hr>
<section class="ticket" id="ticket"></section>
<div id="ticket">
    <div class="container">
        <div class="row">
            <div class="ticket-col-1">
                <img src="imges/Ticket1.jpg" >
            </div>
            <div class="ticket-col-2">
                
                

                <div class="tab-titles">
                    <p class="tab-links active-link" onclick="opentab('Rides')">Rides</p>
                    <p class="tab-links" onclick="opentab('Go Karts')">Go Karts</p>
                    <p class="tab-links" onclick="opentab('Water Park')">Water Park</p>
                </div>
                <div class="tab-contents active-tab" id="Rides">
                    <ul>
                        <li><span>sheet of 50 Tickets</span><br> $45*($42.20 +NJ sales tax)</li>
                        <li><span>Book of 100 Tickets</span><br>$79*($74.09 + NJ sales tax)</li>
                        <li><span>Book of 200 Tickets</span><br>$149*($139.74+NJ sales tax)</li>
                    </ul>
                </div>
                <div class="tab-contents" id="Go Karts">
                    <ul>
                        <li><span>Adult Track</span><br>$7.95</li>
                        <li><span>Double Seater</span><br>$9.95</li>
                        <li><span>Kiddie Track</span><br>$4.95</li>
                        <li><span>Book  fo 4 Adult Rides</span><br>$29.95</li>
                        <li><span>Book of * Adult Rides</span><br>$49.95</li>
                    </ul>
                </div>
                <div class="tab-contents" id="Water Park">
                    <ul>
                        <li><span>3 Hour Ticket</span><br> Cash:$38 Credit:$39 </li>
                        <li><span>Splash Night Mon-Fri(4pm-close)</span><br>Cash:$17 Credit:$18</li>
                        <li><span>Splash Night Saturday, Sunday & Holidays(4pm-close*)</span>Cash:$24 Credit:$25<br></li>
                        <li><span>Ride Upgrade Wristband (Unlimitad Amusement Park Rides)*ONLY available Waterpark purchase*</span><br> cash:$31 Credit:$32</li>
                        <li><span>Toddler Rate(Up to 45"tall)</span><br> Cash:$19 Credit:$20 </li>
                        <li><span>Dry Spectators</span><br> Cash:$15 Credit:$16 </li>
                        <li><span>Lockers</span><br> $20($10 refund upon key return)  </li>
                    </ul>
                </div>
                <a href="#" class="btn home-parallax" data-speed="7">Book Now</a>
            </div>
        </div>
    </div>
</div>

</section>

<!--TICKET-->
<!--Resturant-->
<hr>


<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;">our <span>menu</span> </h1>
<hr>
<section class="restaurant"id="restaurant"> 
    <div class="box-container">

       <div class="box">
        <img src="imges/botito.jpg" alt="">
        <h3>barito</h3>
        <p>FOR $18 </p>
        <a href="#" class="btn">place your order</a>
       </div> 

       <div class="box">
        <img src="imges/chikenrice.jpg" alt="">
        <h3>chicken rice</h3>
        <p>FOR $3.78</p>
        <a href="#" class="btn">place your order</a>
       </div> 

       <div class="box">
        <img src="imges/harmburger.webp" alt="">
        <h3>harmburger</h3>
        <p>FOR $2.34 </p>
        <a href="#" class="btn">place your order</a>
       </div> 

       <div class="box">
        <img src="imges/loadedfrys.jpeg" alt="">
        <h3>loaded fries</h3>
        <p>FOR  $4</p>
        <a href="#" class="btn">place your order</a>
       </div>
       
       <div class="box">
        <img src="imges/meatpie.jpg" alt="">
        <h3>meat pie</h3>
        <p>FOR $4</p>
        <a href="#" class="btn">place your order</a>
       </div> 

       <div class="box">
        <img src="imges/samosa.jpg" alt="">
        <h3>samosa</h3>
        <p>FOR $7 </p>
        <a href="#" class="btn">place your order</a>
       </div> 

    </div>
</section>

<!--Resturant-->



<!--entertainment-->
<hr>

<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;"><span>entaertainments</span> </h1>
<hr>
<section class="entertainment" id="entertainment"></section>
    
<div class="entertainments">
    <div class="inner">
        
        <div class="border"></div>

        <div class="row">
          
            <div class="col">
                <div class="entertainment">
                    <img src="imges/bomber.jpg" alt="">
                    
                   

                

                </div>
            </div>

            <div class="col">
                <div class="entertainment">
                    <img src="imges/merrygo.jpg" alt="">
                   
                   

               

                </div>
            </div>
            <div class="col">
                <div class="entertainment">
                    <img src="imges/boat.jpg" alt="">
                  
                   

                 

                </div>
            </div>
            <div class="col">
                <div class="entertainment">
                    <img src="imges/ounce.jpg" alt="">
                   
                    

                
                </div>
            </div>
            <div class="col">
                <div class="entertainment">
                    <img src="imges/rollercoaster.jpg" alt="">
                  
                   

                

                </div>
            </div>

            <div class="col">
                <div class="entertainment">
                    <img src="imges/waterslide2.jpg" alt="">
                    
                  
                

                </div>
            </div>

        </div>
    </div>
</div>
        
    </section>
    
    <!--entertainment-->
    <!--review-->
    <hr>
<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;"><span>Reviews</span> </h1>
<hr>
    <div class="reviews">
        <div class="inner">
            <h1>clients Reviews</h1>
            <div class="border"></div>

            <div class="row">
              
                <div class="col">
                    <div class="review">
                        <img src="imges/sam.avif" alt="">
                        <div class="name">Frank</div>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>

                     <p>
                        This is the best park i have been too
                     </p>

                    </div>
                </div>

                <div class="col">
                    <div class="review">
                        <img src="imges/salim.avif" alt="">
                        <div class="name">Salim</div>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>

                     <p>
                     I loved the food 
                     </p>

                    </div>
                </div>
                <div class="col">
                    <div class="review">
                        <img src="imges/pere.avif" alt="">
                        <div class="name">Devid</div>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>

                     <p>
                 This is now my fevorait place on earth
                     </p>

                    </div>
                </div>
                <div class="col">
                    <div class="review">
                        <img src="imges/abdulrahamn.avif" alt="">
                        <div class="name">Abdulrahaman</div>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>

                     <p>
                        Me and my children had the best time fo there life
                     </p>

                    </div>
                </div>
                <div class="col">
                    <div class="review">
                        <img src="imges/beller.avif" alt="">
                        <div class="name">Beller</div>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>

                     <p>I had the best experance of my life i would like to come back again
                        
                     </p>

                    </div>
                </div>
            </div>
        </div>
    </div>
    <!--review-->

<!--comtact us-->

<hr>
<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;">contact <span>us</span> </h1>
<hr>
<section class="contactus" id="contactus">
    
    <div class="row">
        
        
        
        <div style="overflow:hidden;max-width:100%;width:500px;height:500px;">
          <div id="embed-ded-map-canvas" style="height:100%; width:100%;max-width:100%;">
             <iframe style="height:100%;width:100%;border:0;" class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3035.901403953527!2d-74.13721912474308!3d40.45531915329107!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.
    1!3m3!1m2!1s0x89c24ecd58443ccd%3A0x2137997ca2385d5!2sKeansburg%20Amusement%20Park!5e0!3m2!1sen!2sng!4v1683908209771!5m2!1sen!
    2sng"  allowfullscreen="" loading="lazy" ></iframe>
          </div>
          <a class="our-googlemap-code" href="https://www.bootstrapskins.com/themes" id="grab-map-info">premium bootstrap themes</a>
          <style>#embed-ded-map-canvas img{max-height:none;max-width:none!important;background:none!important;}</style>
      </div>
        <form action="">
            <h3>GET IN TOUCH WITH US</h3>
            <input type="text" placeholder="your name" class="box">
            <input type="email" placeholder="your email" class="box">
            <input type="tel" placeholder="subject" class="box">
            <textarea placeholder="your message" class="box" cols="30" rows="10"></textarea>
             <input  type="submit"  value="send message"  class="btn">
        </form>
        
  
    </div>
    <div class="row" style="display: flex; justify-content: center; align-items: center;">
    <div class="contact_us back_gray">
                                    
            
               <div  class="cticon"> <i class="fas fa-envelope"> </i> 
                
                    <a href="mailto:mailto:abdulqadiraisha04@gmail.com"><h1>MAIL</h1>
                        Keansburgs Park-NG@Keansburgs Park.com</a>
                
            </div>
</div>

<div class="row" id="prow" style="display: flex; justify-content: center; align-items: center;">
    <div class="contact_us back_gray">
                                    
        <div  class="cticon"> <i class="fas fa-phone"> </i>
                
            
                                            <a href="tel:+2349053287364"><h1>PHONE</h1> +2348132218926</a>
        
    </div>
</div>

    
<div class="row" style="float: right;">
    <div class="contact_us back_gray">
                                    
        <div  class="cticon"> <i class="fa fa-map-marker" aria-hidden="true"></i> 
                
            <a href="mailto:Hudson Furnishing-NG@Hudson Furnishing.com"><h1>ADDRESS</h1> plot 740 Aminu Kano cresent Abuja, FL 33131, NG</a>
        
    </div>
</div>
</div>

</div>
    </div>
    
  </section>

<!--contact us-->
<!---about us-->
<hr>
<h1 class="heading" style="padding-bottom: 0.9%; background-color: #fff; box-shadow: brown;">about <span>us</span> </h1>
<hr>
<section class="aboutus" id="aboutus">

    

    <div class="row">

        <img src="imges/abdulrahamn.avif" width="400">

        <div style="font-size:x-large">
            
            <a href="#"> <i class="fas fa-envelope"></i> Keansburgpark@Keansburgpark.com </a><br/>
            <a href="#"> <i class="fas fa-phone"></i> +2348132218926 </a> 
            <a href="#"> <i class="fas fa-phone"></i>+2348132218926 </a><br/>
            
            <a href="#"> <i class="fas fa-map-marker-alt"></i> Aptech Computer Education Centre Abuja </a>
        </div>










    </div>

</section>


<!---about us-->
<section class="footer" id="footer">

    <div class="box-container">

        
     <marquee style="font-size: large; color: red;"><script type="text/javascript"> 

var currentdate;
var currenttime;
var location;

var d = new Date();
var n = d.toLocaleTimeString();


let currentDate = new Date().toJSON().slice(0, 10);
console.log(currentDate); // "2022-06-17"

const date = new Date();
 // Fri Jun 17 2022 11:27:28 GMT+0100 (British Summer Time)


</script><script type="text/javascript">document.write("Current Date: "+currentDate+ "        "+ "Current Time: " +n);</script></marquee>

 


 <marquee id="demo" style="font-size: large; color: red;" >
     
     <script type="text/javascript">
         
     </script>
 </marquee>
<script>
var x = document.getElementById("demo");

function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition);
  } else { 
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}

function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude +"       Longitude: " + position.coords.longitude;
}
getLocation();

</script>  

        

    </div>

    <div class=""> &#169; Keansburg park | all rights reserved </div>

</section>




<script>
    const swiper = new Swiper('.swiper', {
        slidePerview:1,
        spaceBetween:2,
        loop: true,
  grabCusor:true,
        autoplay: {
            delay: 3000,
            displayOnInteraction: false,
        },
  // Optional parameters
  
  // If we need pagination
  pagination: {
    el: '.swiper-pagination',
    clickable: true,
  },

  // Navigation arrows
  navigation: {
    nextEl: '.swiper-button-next',
    prevEl: '.swiper-button-prev',
  },
});
</script>
<!--slider js end-->

 

 
  </script>




  <script>



var tablinks = document.getElementsByClassName("tab-links");
var tabcontents = document.getElementsByClassName("tab-contents");
function opentab(tabname){
    for(tablink of tablinks){
    tablink.classList.remove("active-link");
    }
    for(tabcontent of tabcontents){
    tabcontent.classList.remove("active-tab");
    }
    event.currentTarget.classList.add("active-link");
    document.getElementById(tabname).classList.add("active-tab");
}

  </script>
   <!--custom js link-->
   <script src="script.js"></script>
   <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</body>
</html>
