[HTML]

<!doctype html>
<html>
<head>

	
 <meta charset="utf-8">

	<link rel="stylesheet" type="text/css" href="Arngren StyleSheet.css"
	
	</head>

<body>

<div class="custom-padding">
  <nav>
    <div class="logo">Arngren</div>

    <ul class="menu-area">
        
		<li><a class="selected" href="Arngren Home.html">Home</a></li>
		<li><a class="selected" href="Arngren Products.html">Products</a></li>
		<li><a class="selected" href="Arngren Contact.html">Contact</a></li>
		<li><a class="selected" href="Arngren Cart.html">Cart</a></li>
		
    </ul>
  </nav>
</div>
	
	<div id="container">
	<div id="header">
	</div>
			
			<div id="Main">
		    
	            <h3>Search</h3>  
				
				<h3>25% off all parts on July 4th</h3>
	        
		        <h3>Arngren the place for all your classic
                       electronic needs ...Read More</h3>
			
				<h3>25% OFF DEALS</h3>
				
				<h3>50% OFF DEALS</h3>
				
				<h3>Buy Now</h3>
				
		</div>
		
		<div id="left">
		
		<section>
					
				<div>RC</div>
				
				<div>Vehicle</div>
				
				<div>Toys</div>
				
				<div>Electric</div>
				
				<div>Collect</div>
				
			</section>
				
				
				
           
   
	</div>
	
	 <div class="footer">
      
        <p>Copyright 2020 &copy; Shadow</p>

	 </div>
	
	
</body>
</html>

[CSS]

@charset "utf-8";
/* CSS Document */

* {
  margin: 0;
  padding: 0;
  outline: 0;
  box-sizing: border-box;
}
body {
  background-color: #e7f5df;
  background-size:cover;
  background-position: center center;
  height: 100vh;
}
.menu-area li a {
  text-decoration: none;
}

.menu-area li {
  list-style-type: none;
}

.custom-padding{
  padding-top: 25px;
}

nav {
  position: relative;
  margin: 0 auto;
  padding: 10px 0;
  background: #004200;
  z-index: 1;
  text-align: right;
  padding-right: 2%;
}

.logo {
  width: 15%;
  float: left;
  text-transform: uppercase;
  color: #e7f5df;
  font-size: 25px;
  text-align: left;
  padding-left: 2%;
}

.menu-area li {
  display: inline-block;
}

.menu-area a {
  color: #fff;
  font-weight: 300;
  letter-spacing: 1px;
  text-transform: uppercase;
  display: block;
  padding: 0 25px;
  font-size: 14px;
  line-height: 30px;
  position: relative;
  z-index: 1;
}
.menu-area a:hover {
  background: #000;
  color: #e7f5df;
}

.menu-area a:hover:after {
  transform: translateY(-50%) rotate(-35deg);
}

section{
	background: #004200;
	color: #e7f5df;
	display: flex;
	flex-direction: column;
	float: left;
}

div left{
	background: #004200;
	display: inline;
	color: #e7f5df;
	margin: auto;
	font-size: 
}

nav:before {
  position: absolute;
  content: '';
  top: 100%;
  left: 0;
}

nav:after {
  position: absolute;
  content: '';
  top: 100%;
  right: 0;
}

.footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: #004200;
   color: #e7f5df;
   text-align: center;
}
