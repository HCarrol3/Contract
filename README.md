<!DOCTYPE html>
<html lang="en" data-color-mode="auto" data-light-theme="light" data-dark-theme="dark">
<head>
  <title>Hannah Carroll:WEB-115-N801: EVA Course Contract Activity</title>
    <meta charset="UTF-8">
    <meta name="keywords" content="HTML, CSS">
    <meta name="author" content="Hannah Carroll">
    <meta name="viewport" content="width=device-width, initial-scale=1">
	  <link rel="stylesheet" type="text/css" href="default.css">
</head>
<style>
	* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
  body {background-color: lavender;}
  h1   {color: white;}
  h2   {color: green;}
  p    {color: red;}
</style>
<body>
<header>

  <h1>Hannah Carroll : WEB-115-N801</h1>
  <h2>CPCC EVA COURSE CONTRACT - FIRST ACTIVITY</h2>

</header>
<main>
  
  <p>I, <a href = "introduction.html">Hannah L. Carroll</a>, agree to abide by the terms in my Fall 2021 WEB115-N801 Web Markup and Scripting with my instructor, D.I. von Briesen.<br> 

I understand that all work that I do on my school and personal websites will be publicly available to the world. I will not put information there that is inappropriate for schoolwork, or that I wish to keep private.<br>

I also understand that it is my work that counts for attendance, not logins or showing up for class. As such, failure to turn in assignments may show as an absences.<br>

Signed: Hannah L. Carroll, 22nd August 2021</p>
</main>

<footer>
<p><a href="http://students.cpcc.edu">My School WebPage</a> // <a href="https://github.com">Github Home</a> // <a href="https://view-source:https://github.com/HCarrol3/Contract/new/main?readme=1/">My Github Page</a> 
		<p>
			<a href="http://validator.w3.org/check?uri=referer" style = 'text-decoration: none'><img src='images/html_valid_button.png' alt='HTML Validation Button' height='31' width='88' /></a> 
			<a href="http://jigsaw.w3.org/css-validator/check/referer" style = 'text-decoration: none'><img src='images/css_valid_button.png' alt='CSS Validation Button' height='31' width='88' /></a>
		</p>
  Page Built By: HLC Industries&copy;
</footer>

</body>
</html> 
