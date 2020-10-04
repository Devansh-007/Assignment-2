<html>
<head>
<meta charset="utf-8">
<title></title>
<meta charset="utf-8">
<meta name="viewport"
contetnt="width=device-width,initial-scale=1">
<link rel="stylesheet" type="text/css" href="CSS2.CSS">
  </head>
<BODY>
  <header>
    <!-- Load an icon library to show a hamburger menu (bars) on small screens -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!-- Top Navigation Menu -->
<div class="topnav">
  <a href="#home" class="active">Logo</a>
  <!-- Navigation links (hidden by default) -->
  <div id="myLinks">
    <a href="#news">News</a>
    <a href="#contact">Contact</a>
    <a href="#about">About</a>
  </div>
  <!-- "Hamburger menu" / "Bar icon" to toggle the navigation links -->
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
  </header>

  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="box">
      <p class="content-name name1">
        Dummy text1
      </p>
      <p class="content">
        This is a dummy text, no need to read this please do skip it , its no point in reading this.
      </p>
  </div>
  </div>
  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="box">
      <p class="content-name name2">
        Dummy text2
      </p>
      <p class="content">
        This is a dummy text too, no need to read this please do skip it , its no point in reading this.
      </p>
    </div>
  </div>
  <div  class="col-lg-4 col-md-6 col-sm-12">
    <div class="box">
      <p class="content-name name3">
        Dummy text3
      </p>
      <p class="content">
       This is a dummy text again, no need to read this please do skip it , its no point in reading this. 
      </p>
    </div>
  </div>
   /* Toggle between showing and hiding the navigation menu links when the user clicks on the hamburger menu / bar icon */
function myFunction() {
  var x = document.getElementById("myLinks");
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</BODY>
</html>
