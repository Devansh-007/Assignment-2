<html>
<head>
<meta charset="utf-8">
<title></title>
<meta charset="utf-8">
<meta name="viewport"
contetnt="width=device-width,initial-scale=1">
<link rel="stylesheet" type="text/css" href="CSS2.CSS">
 <style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

.mobile-container {
  max-width: 480px;
  margin: auto;
  background-color: #555;
  height: 500px;
  color: white;
  border-radius: 10px;
}

.topnav {
  overflow: hidden;
  background-color: #333;
  position: relative;
}

.topnav #myLinks {
  display: none;
}

.topnav a {
  color: white;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  display: block;
}

.topnav a.icon {
  background: black;
  display: block;
  position: absolute;
  right: 0;
  top: 0;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.active {
  background-color: #4CAF50;
  color: white;
}
</style>
</head>
 </head>
<BODY>
 

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
  </div> <!-- Simulate a smartphone / tablet -->
<div class="mobile-container">

<!-- Top Navigation Menu -->
<div class="topnav">
  <a href="#home" class="active">Logo</a>
  <div id="myLinks">
    <a href="#news">News</a>
    <a href="#contact">Contact</a>
    <a href="#about">About</a>
  </div>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<div style="padding-left:16px">
  <h3>Vertical Mobile Navbar</h3>
  <p>This example demonstrates how a navigation menu on a mobile/smart phone could look like.</p>
  <p>Click on the hamburger menu (three bars) in the top right corner, to toggle the menu.</p>
</div>

<!-- End smartphone / tablet look -->
</div>

<script>
function myFunction() {
  var x = document.getElementById("myLinks");
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>


</BODY>
</html>
