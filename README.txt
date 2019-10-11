<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
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
  .one, .two, .three {
    width:100%;
  }
}
</style>
</head>
<body>

<div class="topnav">

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
  <p style="color:#404040;font-size:2vw;padding-top:0px;">Aenan lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Fusce.<br><br>
 <a href="#2" class="button button1">LEARN MORE</a>
<a href="#1" class="button button2"><span>BUY NOW</span></a>
<br><br><br><br>....</p>
</div>
<br><br><br>
<div style="background-color:white;">
<div class="one" style="padding-left:5vw;"><i>fas fa-pie-chart</i>
<br><b><div style="font-size:2vw;">Business Plan Services</div></b><br>
<p style="font-size:1.5vw;">Aenean lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.</p>
<hr>
<p style="font-size:1.5vw;">01</p>
</div>
<div class="two" style="padding-left:5vw;"><i>fas fa-customer</i>
<br><b><div style="font-size:2vw;">Brand Identity</div></b><br>
<p style="font-size:1.5vw;">Aenean lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.</p>
<hr>
<p style="font-size:1.5vw;">02</p>
</div>
<div class="three" style="padding-left:5vw;"><i>fas fa-service</i>
<br><b><div style="font-size:2vw;">Social Media Planning</div></b><br>
<p style="font-size:1.5vw;">Aenean lacinia bibendum nulla sed consectetur. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.</p>
<hr>
<p style="font-size:1.5vw;">03</p>
</div>
</div>
<br>

</body>
</html>
