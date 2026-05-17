<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Wash panda</title>
    <link rel="stylesheet" href="style.css" />
    <style>
      *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
/* home */
.navbar{
    height: 80px;
    width: 100%;
    background-color: #fff;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    align-items: center;
    display: flex;
    justify-content: space-between;
    padding: 0 5%;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo{
    background-image: url("logo.jfif");
    background-size: cover;
    height: 60px;
    width: 60px;
    border-radius: 50%;
    flex-shrink: 0;
}
.logo{
    position: fixed;
}
.menu{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; 
    text-decoration: none;
    
}
.menu a:hover{
    color: rgb(47,47,207);
}
.menu a{
    text-decoration: none;
    padding-inline-start: 120px;
    font-weight: 600;
    color: #333;
}
.contactinfo{
    text-align: right;
    flex-shrink: 0;
}
.contactinfo p{
    font-size: 12px;
    color: #888;
    margin: 0;
}
.contactinfo h5{
    font-size: 15px;
    color: rgb(47,47,207);
    margin: 0;
}
.firstpage{
    margin: 30px;
    padding-top: 20px;
}
.welcome{
    justify-content: center;
    display: flex;
    align-items: center;
    flex-direction: column;

}
.welcome p{
    font-weight: bold;
}
.booking {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 30px;
    
}
.booking button{
    color: white;
    background-color: rgb(47, 47, 207);
    height: 40px;
    width: 100px;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    border: 1px solid  rgb(47, 47, 207);
}
.booking button, .plan1 button, .plan2 button, .plan3 button, .send_messsage button{
    border-radius: 6px;
    cursor: pointer;
    transition: all 0.3s ease;
}
.frontpic{
    padding-top: 10px;}
.pic{
    background-image: url("front.png");
    background-size: cover;
    height: 80vh;
}
.heading{
    align-items: center;
    justify-content: center;
    display: flex;
    padding-top: 20px;
    margin-top: 20px;
 }
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    
} 
.pic2{
    margin-left: 30px;
    padding-right: 30px;
}
.box-img img{
    height: 450px;
    width: 450px;
    padding: 10px;
    margin-left: 15px;
}
.wraped{
    display: flex;
    padding-top: 50px;
    padding-left: 50px;
    gap: 15px;
    justify-content: space-evenly;
}

.parah{
    padding-left: 50px;
    justify-content: center;
    display: flex;
    align-items: center;
    padding-right: 50px;
}
/* booking */
.offer{
    padding-top: 20px;
    margin-top: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}
/* .packages{
    height: 100px;
    width: 200px;
    border: 2px solid black;
    padding-top: 20px;
    margin-top: 20px;
} */
/* .boxes{
    display: flex;
} */
.box1{
    
    background-image: url(car.png);
    background-size: cover;
    height: 140px;
    width: 250px;
    border: 0.006rem solid white;
    border-radius: 20%;
}
.box2{
    
    background-image: url(car.png);
    background-size: cover;
    height: 140px;
    width: 250px;
    border: 0.006rem solid white;
    border-radius: 20%;
}
.box3{
    
    background-image: url(car.png);
    background-size: cover;
    height: 140px;
    width: 250px;
    border: 2px solid white;
    border-radius: 20%;
}
.box4{
    
    background-image: url(car.png);
    background-size: cover;
    height: 140px;
    width: 250px;
    border: 2px solid white;
    border-radius: 20%;
}
.box5{
    
    background-image: url(car.png);
    background-size: cover;
    height: 140px;
    width: 250px;
    border: 2px solid white;
    border-radius: 20%;
}
.packages{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
    
    gap: 20px;
    margin-left: 10px;
    margin-right: 10px;
}
.basic, .deluxe, .ultimate{
    height: auto;
    width: 300px;
    border: 0.5px solid #ddd;
    border-top: 5px solid rgb(47, 47, 207) ;
    border-radius: 12px;
    margin: 20px;
    background-color: whitesmoke;
    padding-bottom: 20px ;
    flex-direction: column;
}
.Wash{
    color: rgb(47, 47, 207) ;
    padding-top: 25px;
    padding-left: 20px;
}
.basic p{
    padding-left: 20px;
}
.qualities {
    text-decoration: none;
    padding-left: 20px;

}
.plan1 button, .plan2 button, .plan3 button{
    /* margin: 45px; */
    height: 38px;
    width: 80%;
    background-color:white;
    color: rgb(47, 47, 207) ;
    border: 3px solid rgb(47, 47, 207) ;
    border-radius: 6px;
    cursor: pointer;
    transition: all 0.3 ease;
    font-weight: 600;
}
.plan1 button:hover, .plan2 button:hover, .plan3 button:hover{
    background-color: rgb(47,47,207);
    color: white;
}
.boxes{
    display: flex;
    justify-content: center;
    align-items: stretch;
    flex-wrap: wrap;
}
.Wash2{
    color: rgb(47, 47, 207) ;
    padding-top: 35px;
    padding-left: 20px;
}
.plan1, .plan2, .plan3{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: auto;
    padding: 15px 0;
}

.deluxe p{
    padding-left: 20px;
}
.qualities2 {
    text-decoration: none;
    padding-left: 20px;

}
.Wash3{
    color: rgb(47, 47, 207) ;
    padding-top: 25px;
    padding-left: 20px;
}
.ultimate p{
    padding-left: 20px;
}
.qualities3 {
    text-decoration: none;
    padding-left: 20px;

}
/* About */
.page4{
    display: flex;
    background-color: rgb(47, 47, 207);
    color: white;
    height: auto;
    padding: 40px 0;
    
}
.full{
    display: flex;
    flex-wrap: wrap;
    height: auto;
}

.details{
    margin-top: 30px;
    margin-left: 70px;
    display: inline-block;
    
}
.find{
    margin-top: 30px;
    padding-top: 30px;
    font-weight: 400;
}
.point1  img{
    height: 40px;
    width: 50px;
    display: inline;
}
.point1{
    display: flex; 
    justify-content: center;
    align-items: center;
    gap: 10px;
    
}
.point2  img{
    height: 40px;
    width: 50px;
    display: inline;
}
.point2{
    display: flex; 
    justify-content: center;
    align-items: center;
    gap: 10px;
    
}
.point3  img{
    height: 40px;
    width: 50px;
    display: inline;
}
.point3{
    display: flex; 
    justify-content: center;
    align-items: center;
    gap: 10px;
    
}
.proof{
    /* background-image: url(GBG-Car-vallet_-83_111117.jpg); */
    background-size: cover;
    height: 80px;
    width: 100%;
    max-width: 500px;
    display: flex;
    right: 100px;
    justify-content: center;
    align-items: center;
    margin-top: 60px;
    margin-right: 30px;
}

/* Gallery */
.banner{
    background-image: url("banner.jpeg");
    background-size: cover;
    height: 200px;
}
.title{
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 20px;
}
.pic_collection{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: auto;
    flex-wrap: wrap;
    padding-left: 20px;
    padding-right:20px ;
}
.pic_collection img{
    background-size: cover;
    height: 200px;
    width: 100%;
    object-fit: cover;
}
.boxa, .boxb, .boxc, .boxd, .boxe, .boxf{
    flex: 1;
    min-width: 200px;
}
/* client review */
.first-person{
    height: 50px;
    width: 50px;
    border: 2px thin black;
    border-radius: 50%;
    background-color: blueviolet;
    display: flex;
    justify-content: center;
    align-items: center;
}
.second-person{
    height: 50px;
    width: 50px;
    border: 2px thin black;
    border-radius: 50%;
    background-color: blueviolet;
    display: flex;
    justify-content: center;
    align-items: center;
}
.third-person{
    height: 50px;
    width: 50px;
    border: 2px thin black;
    border-radius: 50%;
    background-color: blueviolet;
    display: flex;
    justify-content: center;
    align-items: center;
}
.client-profile{
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 50px;
    gap: 20px;
}
/* CONTACT US */
.form{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px;
    margin-left: 50px;

}
.info-pic{
    padding: 20px;
    padding-left: 50px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 50px

}
.info-pic img{
    height: 500px;
    width: 500px;
    
}
.name{
    font-weight: bold;
}
.name input{
    font-weight: bold;
    width: 400px;
    height: 35px;
    border: 1px thin rgb(44, 40, 40);
    border-radius: 5%;
}
.email{
    font-weight: bold;
}
.email input{
    font-weight: bold;
    width: 400px;
    height: 35px;
    border: 1px thin rgb(44, 40, 40);
    border-radius: 5%;
}
.number{
    font-weight: bold;
}
.number input{
    font-weight: bold;
    width: 400px;
    height: 35px;
    border: 1px thin rgb(44, 40, 40);
    border-radius: 5%;
}
.message{
    font-weight: bold;
}
.message input{
    font-weight: bold;
    width: 400px;
    height: 135px;
    border: 1px thin rgb(44, 40, 40);
    border-radius: 5%;
    justify-content:flex-start;
    display: flex;
    align-items: center;
    justify-content: center;
}
.send_messsage{
    position: static;
    margin-top: 10px;
}
.send_messsage button{
    max-width: 400px;
    width: 100%;
    height: 42px;
    border-radius: 5px ;
    background-color: rgb(47, 47, 207);
    color: white;
    font-weight: 600;
}
.send_messsage button:hover{
    border: 3px solid rgb(47, 47, 207);
    color:rgb(47, 47, 207) ;
    background-color: white;
}
.name input, .eamil input, .number input, .message input{
    border: 1px solid #ccc;
    border-radius: 6px;
    width: 100%;
    max-width: 400px;
}
.contact{
    padding-top: 60px;
    padding-bottom: 60px ;
}
/* foot rah gaya bs  */
.foot-bar{
    height: 100px;
    background-color: rgb(19, 17, 17);
    color: white;
    display: flex;
    justify-content: space-evenly;
    padding-left: 20px;
    align-items: center;
}
.foot-bar li{
    list-style: none;
}
.atlast{
    background-color:rgb(47, 47, 207) ;
    height: 200px;
    color:white ;
    display: flex;
    justify-content: center;
    
}
.logo-last img{
    height: 130px;
    padding-top: 60px;
    margin-left: 100px;
}
.footer-nav{
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    justify-content: center ;
}
.footer-nav a{
    color: white;
    text-decoration:none ;
    font-size: 14px;
}
.footer-nav a:hover{
    text-decoration: underline;
}
.hamburger { 
    display: none; 
}
/* Responsivness */
@media (max-width: 768px) {
  .navbar { flex-wrap: wrap; justify-content: space-between; padding: 10px 20px; }
  .logo { position: static; }
  .contactinfo { position: static; text-align: right; }
  .menu { display: none; flex-direction: column; width: 100%; text-align: center; }
  .menu.open { display: flex; }
  .menu a { padding: 10px 0; border-top: 1px solid #eee; }
  .hamburger { display: block; font-size: 24px; background: none; border: none; cursor: pointer; }

  .container { flex-direction: column; }
  .box-img img { width: 100%; height: auto; }
  .wraped { flex-direction: column; padding-left: 20px; }

  .boxes { flex-direction: column; align-items: center; }
  .packages { flex-wrap: wrap; }

  .full { flex-direction: column; }
  .proof { width: 90%; margin: 20px auto; }

  .info-pic { flex-direction: column; }
  .info-pic img { width: 100%; height: auto; }
  .name input, .email input, .number input, .message input { width: 100%; }

  .foot-bar { flex-direction: column; height: auto; padding: 20px; gap: 15px; }
  .logo-last { flex-direction: column; align-items: center; }
  .logo-last img { margin-left: 0; }
}
    </style>
  </head>
  <body>
    <header>
      <div class="navbar">
        <button class="hamburger" id="hamburger">&#9776;</button>
        <div class="logo"></div>
        <div class="menu">
          <a href="home.html">HOME</a>
          <a href="booking.html">BOOKING</a>
          <a href="about.html">ABOUT</a>
          <a href="gallery.html">GALLERY</a>
          <a href="contact.html">CONTACT</a>
        </div>
        <div class="contactinfo">
          <p>Have any question?</p>
          <h5>+92 300 00000</h5>
        </div>
      </div>
    </header>
    <main>
      <div class="firstpage">
        <div class="welcome">
          <p>WELCOME TO WASHPANDA</p>
          <h1>YOUR CAR IS ALWAYS IN GREAT HANDS WITH US</h1>
        </div>
        <div class="booking">
          <button>Book now</button>
        </div>
        <div class="frontpic">
          <div class="pic"></div>
        </div>
      </div>
      <div class="head">
      <div class="heading">
        <h2>WHO IS WASH PANDA</h2>
      </div>
      <div class="container">
        <div class="pic2">
          <div class="box-img">
            <img src="2nd.png" />
          </div>
        </div>
        <div class="about">
          <div class="parah">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aperiam
            eum beatae blanditiis a. Aut iusto voluptatum itaque qui quia magnam
            quod, nulla asperiores odio tenetur dignissimos veritatis hic
            dolores deleniti. Lorem ipsum dolor sit amet consectetur adipisicing
            elit. Illo, recusandae quaerat. Sit et quibusdam unde voluptate
            reprehenderit quia repellat nesciunt sed beatae fuga. Maiores
            voluptatem, quae omnis id explicabo earum. Totam, possimus. Magnam,
            accusantium porro neque consequuntur, culpa quidem nam reprehenderit
            laudantium labore.
          </div>
          <div class="wraped">
          <div class="carwash">
            <h4>The Best Car Wash</h4> <br>
            <p>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
            </p>
          </div>
          <div class="contact">
            <h4>Contacting Us</h4> <br>
            <p>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
              <li>Lorem ipsum dolor sit amet consectetur </li> <br>
              <li>Lorem ipsum dolor sit amet consectetur </li><br>
            </p>
          </div>
          </div>
        </div>
      </div>
      </div>
    </main>
    
    <section class="packages-section">
        <div class="offer">
            <h2> WASH PACKAGES</h2>
        </div>
        <div class="packages">
            <div class="box1 box"> </div>
            <div class="box2 box"> </div>
            <div class="box3 box"></div>
            <div class="box4 box"></div>
            <div class="box5 box"></div>
        </div>
        <div class="boxes">
            <div class="basic">
                <h4 class="Wash"> BASIC WASH</h4> <br>
                <p> Starting From</p>
                <p> <b> <b>999PKR</b></b> </p> <br> <br>
                <div class="qualities"><ul>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                </ul> </div>
                <div class="plan1">
                    <button> Select Plan</button>
                </div>
            </div>
            <div class="deluxe">
                <h4 class="Wash2"> DELUXE WASH</h4> <br>
                <p> Starting From</p>
                <p> <b> <b>1499PKR</b></b> </p> <br> <br>
                <div class="qualities2"><ul>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                </ul> </div>
                <div class="plan2">
                    <button> Select Plan</button>
                </div>
            </div>
            <div class="ultimate">
                <h4 class="Wash3">  ULTIMATE SHINE</h4> <br>
                <p> Starting From</p>
                <p> <b> <b>1999PKR</b></b> </p> <br> <br>
                <div class="qualities3"><ul>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                    <li>Lorem ipsum dolor sit amet conse</li> <br>
                </ul> </div>
                <div class="plan3">
                    <button> Select Plan</button>
                </div>
            </div>
                
        </div>

      </section>
    <section class="page4">
        <div class="full">
        <div class="details">
            <p class="find"> Find Who We Are</p> <br>
            <h2> WE ONLY PROVIDE QUALITY CARE SERVICES</h2> <br> <br>
            <div class="point1">
                <img src="natural.jpeg" alt="">
                <h4> Natural Cleaner</h4> <br> 
                
                <p> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique inventore, nostrum eligendi placeat quod quisquam dolorem aliquid cumque sunt dolorum.</p>
            </div> <br><br>
            <div class="point2">
                <img src="tire.jpeg" alt="">
                <h4> Tire Shines</h4>
                <p> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique inventore, nostrum eligendi placeat quod quisquam dolorem aliquid cumque sunt dolorum.</p>
            </div> <br> <br>
            <div class="point3">
                <img src="mat.jpeg" alt="">
                <h4> Mat Washing</h4>
                <p> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique inventore, nostrum eligendi placeat quod quisquam dolorem aliquid cumque sunt dolorum.</p>
            </div>
            
        </div>
        <div class="proof">
                
            </div>

        </div>
    </section>

    <section class="gallery">
        <div class="banner">

        </div>
        <div class="title">
            <h2> GALLERY</h2>
        </div>
        <div class="pic_collection">
            <div class="boxa">
                <img src="aaa.jpeg" alt="">
            </div>
            <div class="boxb">
                <img src="bbb.jpeg" alt="">
            </div>
            <div class="boxf">
                <img src="eee.jpeg" alt="">
            </div>
            <div class="boxb">
                <img src="bbb.jpeg" alt="">
            </div>
            <div class="boxc">
                <img src="aaa.jpeg" alt="">
            </div>
            <div class="boxd">
                <img src="ddd.jpeg" alt="">
            </div>
            <div class="boxe">
                <img src="eee.jpeg" alt="">
            </div>
        </div>
    </section> <br>
    
    <section class="contact">
      <div class="form">
        <h2>QUICK CONTACT</h2>
      </div>
      <div class="info-pic">
        <img src="comp panda.jpg" alt="" />
        <div class="information">
        <div class="name">
          <p>Full Name*</p>
          <input type="text" placeholder="Enter your name" />
        </div> <br> 
        <div class="email">
          <p>Email*</p>
          <input type="text" placeholder="Enter your email address" />
        </div> <br> 
        <div class="number">
          <p>Phone Number*</p>
          <input type="text" placeholder="Enter your phone number" />
        </div> <br> 
        <div class="message">
            <p>Message*</p>
            <input type="feedback" placeholder="Place your message here!">
        </div> <br> <br>
        <div class="send_messsage">
            <button>Send Message</button>
        </div>
    </div>
      </div>
    </section>
      <footer>
          <div class="foot-bar">
            <ul>
            <li> Phone Number</li>
            <li> +92 300 00000</li></ul>
            <ul>
              <li> Mail Info</li>
              <li>info@mail.com</li>
            </ul>
            <ul>
              <li> Address</li>
              <li> Johar Town</li>
            </ul>
          </div>
          <div class="atlast">
            <div class="logo-last">
               <div>
               <img src="logo.jfif" alt=""> </div>
              <div><nav> Home | Booking | About | Gallery | Privacy Policy | Terms & Conditions</nav></div>
            </div>
          </div>
      </footer>
    

      <script>
      document.getElementById('hamburger').addEventListener('click', function() {
      document.querySelector('.menu').classList.toggle('open');
  });
</script>
  </body>
</html>
