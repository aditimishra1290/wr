<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
*{
font-family:Palatino Linotype;
}
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background-color:white
 ;
}


.topnav {
  overflow: hidden;
  background-color: white;
  width:100%;
  height:30%;
  position:sticky;
}

.topnav a {
  float: right;
  color: grey;
  text-align: center;
margin-top:15px;
margin-bottom:15px;
  padding: 15px 16px;
  text-decoration: none;
  font-size: 15px;
  position:sticky;
}

.topnav a:hover {
  background-color: white;
  color: black;
  border-bottom-style:solid;
  border-color:black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: white;
}
.pic{
margin-top:0;
background-image:url('http://optontest2.com/wp/wp-content/uploads/2016/08/minimal-white-chair-700x500.jpg');
background-repeat:no-repeat;
background-size:cover;


max-width:100%;height:auto;

}
.button  {
border-radius:30px;
  background-color:none;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
.button1 
{
border-style:solid;
background-color:none;
color:#404040;
border-color:#404040;
}
.button2{
background-color:#404040;
padding: 17px 42px;
}
.button1:hover{
color:black;
}
.button2:hover{
color:black;
background-color:white;
}
.button2 span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button2 span:after {
  content: '\203a';
  position: relative;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.2s;
}

.button2:hover span {
  padding-right: 10px;
}

.button2:hover span:after {
  opacity: 1;
  right: 1;
}
/*@media only screen and (max-width: 600px) {
  .topnav a{
 float:none;
 width:100%;
 margin-top:15px;
margin-bottom:15px;
 text-align: center;
  padding: 35px 16px;
  text-decoration: none;
  font-size: 15px;
  }
  .pic{
  width:100%;
  }
}*/
.one{
float:left;
width:25%;
color:#404040;
}
.two{
float:left;
width:25%;
color:#404040;
}
.three{
float:left;
width:25%;
color:#404040;
}
@media only screen and (max-width:620px) {
  /* For mobile phones: */
  .one, .two, .three, .works,.details {
    width:100%;
  }
}
.pic2{

background-image:url('http://max-themes.net/demos/kleanity/upload/minimal-chair-black.jpg');
background-repeat:no-repeat;
background-size:cover;
margin-top:28vw;


max-width:100%;height:auto;

}
.total{
color:#404040;
}
.works{

font-size:3vw;
width:30%;
float:left;
text-align:center;

}
.details{
padding:2vw;
margin-left:0;
font-size:1.5vw;
width:60%;
float:right;
opacity:0.8;
}
.navb  {

  background-color:none;
  border: none;
  color: #404040;
  width:60%;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 1.5vw;
  padding-left:20%;
  cursor: pointer;
}
.navb a{
color: #404040;
padding:2 vw;
margin:0.5vw;
text-decoration:none;
font-size:2vw;
font-weight:400;
opacity:0.6;
}
.navb a:hover{
opacity:1;
}
.pictures{
margin:6vw;
padding:2vw;
display:inline-block;
}
.picture1 {

width:18.5vw;
height:22vw;
float:left;
opacity:0.8;
margin-right:2vw;
margin-top:2vw;
}
.picture1:hover{
width:19.5vw;
height:23vw;
opacity:1;
}
.picture2{
width:18.5vw;
height:22vw;
float:left;
opacity:0.8;
margin-right:2vw;
margin-top:2vw;

}
.picture2:hover{
width:19.5vw;
height:23vw;
opacity:1;
}
.picture3{
width:18.5vw;
height:22vw;
float:left;
opacity:0.8;
margin-right:2vw;
margin-top:2vw;

}
.picture3:hover{
width:19.5vw;
height:23vw;
opacity:1;
}
.picture4{
width:18.5vw;
height:22vw;
float:left;
opacity:0.8;
margin-top:2vw;



}
.picture4:hover{
width:19.5vw;
height:23vw;
opacity:1;
}

</style>
</head>
<body>

<div class="topnav">
  <a href="#search"><i class="fas fa-search"></i></a>
  <a href="#shop">SHOP</a>
  <a href="#features">FEATURES</a>
  <a href="#gallery">GALLERY</a>
  <a href="#about">BLOG</a>
  <a href="#contact">PORTFOLIO</a>
  <a href="#news">PAGES</a>
  <a href="#home">HOME</a>
  <a href="#home" style=" font-size:20px;float:left;position:sticky;color:black; font-family:times new roman; border:none;"><b>KLEANITY.</b></a>
  
  </div>

<div class="pic" style="padding-left:20%; ">
  <p style="padding-top:30%; margin-top:0px;font-size:5vw;color:#404040;">Keep Your Business<br><b style="font-size:7vw;">Clean & Simple</b></p>
  <p style="color:#404040;font-size:2vw;padding-top:0px;opacity:0.8;">Aenan lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Fusce.<br><br>
 <a href="#2" class="button button1">LEARN MORE</a>
<a href="#1" class="button button2"><span>BUY NOW</span></a>
<br><br><br><br>....</p>
</div>
<br><br><br>
<div style="background-color:white;">
<div class="one" style="padding-left:5vw;"> <i class="fa fa-pie-chart" style="font-size:4vw;"></i><br>
<br><b><div style="font-size:2vw;">Business Plan Services</div></b><br>
<p style="font-size:1.5vw;opacity:0.8;">Aenean lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.</p>
<hr>
<p style="font-size:1.5vw;">01</p>
</div>
<div class="two" style="padding-left:5vw;"> <i class="fa fa-user" style="font-size:4vw;"></i><br>
<br><b><div style="font-size:2vw;">Brand Identity</div></b><br>
<p style="font-size:1.5vw;opacity:0.8;">Aenean lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.</p>
<hr>
<p style="font-size:1.5vw;">02</p>
</div>
<div class="three" style="padding-left:5vw;"> <i class="fa fa-globe" style="font-size:4vw;"></i><br>
<br><b><div style="font-size:2vw;">Social Media Planning</div></b><br>
<p style="font-size:1.5vw;opacity:0.8;">Aenean lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.</p>
<hr>
<p style="font-size:1.5vw;">03</p>
</div>
</div>
<br>
<div class="pic2" style="padding-left:5%; padding-top:10%; ">
 <i class="fas fa-edit" style="font-size:4vw;"></i><br> <p style=" margin-top:50px;font-size:6vw;color:#404040;"><b>Story About Us</b><br>
  <i style="font-size:2.5vw;">What we have done from the past</i><br>
  <p style="color:#404040;font-size:2vw;padding-top:0px;opacity:0.8;">Donec id elit non mi porta gravida at eget metus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id dolor id nibh ultricies vehicula ut id elit. Maecenas sed diam eget risus varius blandit sit amet non magna. Praesent commodo cursus magna, vel scelerisque.<br><br>
  <a href="#2" class="button button1">LEARN MORE</a>

<br><br>

</div>
<div class="total">
<div class="works">
    <h2>Our Works.</h2>
    
  </div>

  <div class="details">
  
    <p>Donec id elit non mi porta gravida at eget metus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id dolor id nibh ultricies vehicula. Lorem ipsum dolor sit amet.</p>
  </div>
  </div>
<div class="navb">
  <a href="#all"><i>All /</i></a>
  <a href="#branding"><i>Branding /</i></a>
  <a href="#minimal"><i>Minimal /</i></a>
  <a href="#photography"><i>Photography /</i></a>
  <a href="#product"><i>Product</i></a>
  </div>
<br><br>
<div class="pictures">
<div class="picture1"><a href="#picture1"><img src="http://max-themes.net/demos/kleanity/upload/colored-sofa.jpg" alt="sofa" style="width:100% ;height:100%;" ></a></div>
<div class="picture2"><a href="#picture2"><img src="http://max-themes.net/demos/kleanity/upload/wooden-clock-400x377.jpg" alt="wooden clock" style="width:100%; height:100%;"></a></div>
<div class="picture3"><a href="#picture3"><img src="http://max-themes.net/demos/kleanity/upload/typo-frame-400x257.jpg" alt="topography frame" style="width:100%;height:100%;"></a></div>
<div class="picture4"><a href="#picture4"><img src="http://max-themes.net/demos/kleanity/upload/typewriter-keys-mechanically-letters-400x377.jpg" alt="typewriter" style="width:100%;height:100%;"></a></div>

<div class="picture1"><a href="#picture5"><img src="http://max-themes.net/demos/kleanity/upload/minimal-chair-black-400x257.jpg" alt="chair" style="width:100% ;height:100%;" ></a></div>
<div class="picture2"><a href="#picture6"><img src="https://www.ntabacoffeehaus.com/wp-content/uploads/2016/08/green-scene-700x450.jpg" alt="lamp" style="width:100% ;height:100%;" ></a></div>
<div class="picture3"><a href="#picture7"><img src="http://lifejacketunderyourseat.com/wp-content/uploads/2016/08/brown-notebook-700x660.jpg" alt="portfolio" style="width:100% ;height:100%;" ></a></div>
<div class="picture4"><a href="#picture8"><img src="http://max-themes.net/demos/kleanity/upload/minimal-bag-400x257.jpg" alt="bag" style="width:100% ;height:100%;" ></a>
</div>
<div class="picture1"><a href="#picture9"><img src="http://max-themes.net/demos/kleanity/upload/pexels-photo-30222.jpg" alt="headphones" style="width:100% ;height:100%;" ></a></div>
<div class="picture2"><a href="#picture10"><img src="https://www.emanueledibiase.com/wp-content/uploads/2016/08/sofa-pink-scene.jpg" alt="sofa" style="width:100% ;height:100%;" ></a></div>
<div class="picture3"><a href="#picture11"><img src="https://www.ntabacoffeehaus.com/wp-content/uploads/2016/08/minimal-clock-700x450.jpg" alt="clock" style="width:100% ;height:100%;" ></a></div>
<div class="picture4"><a href="#picture12"><img src="http://max-themes.net/demos/kleanity/upload/modern-clock-scene.jpg" alt="digital clock" style="width:100% ;height:100%;" ></a></div>
</div>


</body>
</html>