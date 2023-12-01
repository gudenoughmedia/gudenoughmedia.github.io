---
layout: post
title:  "Crocheting"
date:   2023-11-27 13:20:23 -0700
categories: portfolio hobby


<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 33%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>

<div style="text-align:center">
  <h2>Crochet Projects</h2>
</div>

<div style="text-align:left">
  <p>My crochet journey started in June of 2023 with a shark kit from woobles. They had video guides that were very helpful and
  after finishing my first project I was hooked.
  <p>Enjoy my projects below, and reach out to me for any questions on comissions. <br>
  <small>click on the images below to expand them</small>

<!-- The four columns -->
<div class="row">
  <div class="column">
    <img src="../../../c_collection.jpeg" alt="Most of the collection" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="../../../c_mimics.jpg" alt="Functional mimic chests" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="../../../c_shark.png" alt="First crochet project" style="width:100%" onclick="myFunction(this);">
  </div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>