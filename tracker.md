<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 20px;
}


#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: lightgrey;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
</style>
</head>
<body>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>

<script>
//Get the button
var mybutton = document.getElementById("myBtn");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

</body>
</html>


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.collapsible:after {
  content: '\002B';
  color: white;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
}
</style>
</head>
<body>

<h1>Table of Contents</h1>

<button class="collapsible">Live Action Shows</button>
<div class="content">
  <br>
  <h2>Test</h2>
  <br>
</div>
<button class="collapsible">Open Section 3</button>
<div class="content">
  <p><br>
  Text
  </p>
    <p></p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>
</body>
</html>
<title>GreenJ.net<title>


##### Path: [root](https://greenj.net):/[tracker](https://greenj.net/tracker)/

## Table of Contents
1. ### [Live Action Shows](#shows)
    - ### [Watching](#shows-watch)
    - ### [On Hold](#shows-hold)
    - ### [Planning](#shows-plan)
        - #### [Plan to rewatch](#shows-rewatch)
        - #### [High Priority](#shows-high)
        - #### [Normal Priority](#shows-norm)
        - #### [Low Priority](#shows-low)
    - ### [Dropped](shows-drop)
2. ### [Live Action Films](#film)
    - ### [Watching](#film-watch)
    - ### [On Hold](#film-hold)
    - ### [Planning](#film-plan)
        - #### [Plan to rewatch](#film-rewatch)
        - #### [High Priority](#film-high)
        - #### [Normal Priority](#film-norm)
        - #### [Low Priority](#film-low)
    - ### [Dropped](film-drop)
3. ### [Cartoons](#cartoon)
    - ### [Watching](#cartoon-watch)
    - ### [On Hold](#cartoon-hold)
    - ### [Planning](#cartoon-plan)
        - #### [Plan to rewatch](#cartoon-rewatch)
        - #### [High Priority](#cartoon-high)
        - #### [Normal Priority](#cartoon-norm)
        - #### [Low Priority](#cartoon-low)
    - ### [Dropped](cartoon-drop)
4. ### [Anime](anime)
    - ### [Watching](#anime-watch)
    - ### [On Hold](#anime-hold)
    - ### [Planning](#anime-plan)
        - #### [Plan to rewatch](#anime-rewatch)
        - #### [High Priority](#anime-high)
        - #### [Normal Priority](#anime-norm)
        - #### [Low Priority](#anime-low)
    - ### [Dropped](anime-drop)
5. ### [Manga/Manwha/Manhua](man)
    - ### [Watching](#man-watch)
    - ### [On Hold](#man-hold)
    - ### [Planning](#man-plan)
        - #### [Plan to rewatch](#man-rewatch)
        - #### [High Priority](#man-high)
        - #### [Normal Priority](#man-norm)
        - #### [Low Priority](#man-low)
    - ### [Dropped](man-drop)
6. ### [Webcomics](#web)
    - ### [Watching](#web-watch)
    - ### [On Hold](#web-hold)
    - ### [Planning](#web-plan)
        - #### [Plan to rewatch](#web-rewatch)
        - #### [High Priority](#web-high)
        - #### [Normal Priority](#web-norm)
        - #### [Low Priority](#web-low)
    - ### [Dropped](web-drop)