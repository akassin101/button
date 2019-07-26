<!doctype html>
<html>
  <meta charset="utf-8">
  <body id= "mybody">
    <head>
    
    <style>
    button {color: black}
h1 {color: black}
h1 {background-color: silver}
h1 {border: 10px solid maroon}
h1 {border-radius: 500px}
h1 {text-align: center}
h1 {padding: 20px}
button {padding: 10px}
button {border-radius: 150px}
button {background-color: silver}
button {border-color: maroon}
button {padding-left: 500px}
button {padding-right: 500px}
button {margin-left: 130px}
body {background-color: black}
</style>

<script>
function project() {
var title = document.querySelector("#myheader");
title.style.color= "orange";
title.style.borderColor= "green";
title.style.backgroundColor= "white";
  var title = document.querySelector("#mybutton");
  title.style.color= "orange";
  title.style.borderColor= "green";
  title.style.backgroundColor= "white";
var title= document.querySelector("#mybody");
  title.style.backgroundColor= "silver"
  }
  </script>


<h1 id="myheader">
        Abraham
      </h1>
      <hr>
    </head>
    <p>
      <button id= "mybutton" onclick="project();">
       <b>
        click me
        </b>
      </button>
  </body>
</html>

