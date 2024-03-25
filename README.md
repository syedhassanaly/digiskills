<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
</head>
<style>
* {box-sizing:border-box}


.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}


.mySlides {
  display: none;
}
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}


.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}


.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}


.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}


.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}


.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}


.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
.topnav {
  background-color:rgb(0, 0, 0);
  overflow: hidden;
}


.topnav a {
  float: left;
  color:aqua;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}


.topnav a:hover {
  background-color: #ddd;
  color: black;
}


.topnav a.active {
  background-color:green;
  color: white;
}
.column {
  float: left;
  width: 25%;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}
.main{
    padding: 0px;
    margin: 4px 4px;
}
#footer{
    background-color: black;
    color: aqua;
    padding: 10px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
#contact{
    padding: 30px 0px;
background-color: pink;
}
.contact-row{
    display: flex;
    justify-content: center;
    align-items: center;
}
.contact-left-col{
    flex-basis: 50%;
    padding-top: 50px;
}
.contact-right-col{
    flex-basis: 50%;
    max-width: 450%;
    margin: auto;
}
.contact-right-col i{
    font-size: 15px;
    padding: 10px;
    background-color: #000000;
    color: aqua;
    }
.contact-right-col p{
    margin-top: 10px;
    margin-bottom: 20px;
    background-color: aqua;
    
}
</style>
<body>
    <div class="topnav">
        <a class="active" href="#home">Home</a>
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
      </div>
      <br>
      
      <br>
      
      <div>
<div class="slideshow-container">

   
    <div class="mySlides fade">
      <div class="numbertext">1 / 3</div>
      <img src="https://www.slideteam.net/media/catalog/product/cache/1280x720/o/n/one_page_digital_marketing_plan_powerpoint_presentation_slides_slide01.jpg" style="width:100%">
      <div class="text">Caption Text</div>
    </div>
  
    <div class="mySlides fade">
      <div class="numbertext">2 / 3</div>
      <img src="https://www.slideteam.net/media/catalog/product/cache/1280x720/a/p/app_marketing_powerpoint_ppt_template_bundles_slide01.jpg" style="width:100%">
      <div class="text">Caption Two</div>
    </div>
  
    <div class="mySlides fade">
      <div class="numbertext">3 / 3</div>
      <img src="https://slidemodel.com/wp-content/uploads/4008-01-portfolio-business-template-red-3.jpg" style="width:100%">
      <div class="text">Caption Three</div>
    </div>
  
   
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>
  <br>
  
 
  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>

</div>
<script>let slideIndex = 1;
    showSlides(slideIndex);
    
    // Next/previous controls
    function plusSlides(n) {
      showSlides(slideIndex += n);
    }
    
    // Thumbnail image controls
    function currentSlide(n) {
      showSlides(slideIndex = n);
    }
    
    function showSlides(n) {
      let i;
      let slides = document.getElementsByClassName("mySlides");
      let dots = document.getElementsByClassName("dot");
      if (n > slides.length) {slideIndex = 1}
      if (n < 1) {slideIndex = slides.length}
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
      }
      slides[slideIndex-1].style.display = "block";
      dots[slideIndex-1].className += " active";
    }</script>
    <br>
    <div class="main">
        <img src="https://brandastic.com/wp-content/uploads/2021/12/The-Top-10-Must-Have-Digital-Marketing-Apps-in-2020.jpg" alt="" height="1000px"  >
      </div>
<br>
<div class="row">
    <div class="column"><img src="https://static.vecteezy.com/system/resources/previews/003/519/650/non_2x/promotion-isolated-cartoon-concept-user-sees-big-sale-advertising-on-mobile-app-marketing-people-scene-in-flat-design-illustration-for-blogging-website-mobile-app-promotional-materials-vector.jpg"height="400px"
        width="400px" alt=""></div>
    <div class="column"><img src="https://static.vecteezy.com/system/resources/previews/003/519/654/non_2x/advertising-isolated-cartoon-concept-digital-marketing-and-online-promotion-strategy-people-scene-in-flat-design-illustration-for-blogging-website-mobile-app-promotional-materials-vector.jpg"height="400px"
        width="400px" alt=""></div>
    <div class="column"><img src="https://static.vecteezy.com/system/resources/thumbnails/003/521/682/small_2x/digital-marketing-isolated-cartoon-concept-user-sees-ads-and-commercial-offer-in-mobile-app-people-scene-in-flat-design-illustration-for-blogging-website-mobile-app-promotional-materials-vector.jpg" height="400px"
        width="400px" alt="" ></div>
    <div class="column"><img src="https://img.freepik.com/premium-vector/digital-marketing-illustration_294101-219.jpg" height="400px"
        width="400px" alt=""></div>
  </div>
  <section id="contact">
    <div class="services-info">
        <h1>Get in<span id="blue">Touch</span></h1>
        <p>We are Available</p>
    </div>
    <div class="contact-row">
        <div class="contact-left-col">
            <div class="form">
                <input type="text" name="" placeholder="E-mail">
                <input type="text" name="" placeholder="Subject">
                <textarea rows="5" cols="40" placeholder="Message"></textarea>
                <br> <Button class="c-btn">Send</Button>
            </div>
    </div>
    <div class="contact-right-col">
        <h1><i class="fa fa-envelope" aria-hidden="true"></i>E-mail</h1><p>
            abc34@gmail.com</p><br>
            <h1><i class="fa fa-phone" aria-hidden="true"></i>Mobile</h1><p>03132507953 </p>
            <br>
            <h1><i class="fa fa-location-arrow" aria-hidden="true"></i>Location</h1>
            <p>Near nipa block-11 Gulshan-e-iqbal,Karachi
            </p>
    </div>
    </div>
</section>
      
</body>
<section id="footer">
    <h1>Hassan's<span id="blue"> Digi skills</span></h1>
    <p>&copy; Hassan Digi skills, Pakistan</p>
</section>
</html>
