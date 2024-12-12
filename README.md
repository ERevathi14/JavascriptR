12/12/2024
Introduction:
============
JavaScript is the world's most popular programming language. 

JavaScript is the programming language of the Web. 

JavaScript is easy to learn. 

Why Study JavaScript?
======================
JavaScript is one of the 3 languages all web developers must learn: 

   1. HTML to define the content of web pages 

   2. CSS to specify the layout of web pages 

   3. JavaScript to program the behavior of web pages. 

JavaScript Can Change HTML Content 
=====================================
One of many JavaScript HTML methods is getElementById(). 

The example below "finds" an HTML element (with id="demo"), and changes the element content (innerHTML) to "Hello JavaScript": 

<!DOCTYPE html>                                                                                              

<html> 

<body> 

<h2>What Can JavaScript Do?</h2> 

<p id="demo">JavaScript can change HTML content.</p> 

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button> 

</body> 

</html> 


*JavaScript and Java are completely different languages, both in concept and design. 

*JavaScript was invented by Brendan Eich in 1995, and became an ECMA standard in 1997. 

*ECMA-262 is the official name of the standard. ECMAScript is the official name of the language. 

The <script> Tag 
=================
In HTML, JavaScript code is inserted between <script> and </script> tags. 

<script> 
document.getElementById("demo").innerHTML = "My First JavaScript"; 
</script> 

External JavaScript 
===================
myScript.js 

function myFunction() { 
  document.getElementById("demo").innerHTML = "Paragraph changed."; 
} 

<script src="myScript.js"></script> 


Path: 
======
<script src="https://www.w3schools.com/js/myScript.js"></script> 

<script src="/js/myScript.js"></script> 

<script src="myScript.js"></script> 

==========================================================================================================================================================
JavaScript Output :
-----------------
JavaScript Display Possibilities 

JavaScript can "display" data in different ways: 
==============================================
Writing into an HTML element, using innerHTML. 

Writing into the HTML output using document.write(). 

Writing into an alert box, using window.alert(). 

Writing into the browser console, using console.log(). 

 
