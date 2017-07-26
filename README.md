<html>
<div class="container">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
	<script type="text/javascript" src="script.js"></script>
	<script type="text/javascript" src="jquery-3.2.1.js"></script>


<style>

*{
position: relative;
border: 0;
padding: 0;
margin: 0;
}

</style>

<script>

function getViewportSize(w) {

   w = w || window;

  if (w.innerWidth != null) return { w: w.innerWidth, h: w.innerHeight };
    
  var d = w.document;
  if (document.compatMode == "CSS1Compat")
        return { w: d.documentElement.clientWidth,
           h: d.documentElement.clientHeight };

}

</script>


<script>
      alert("Viewport dimensions are(w,h): " + d.body.clientWidth + d.body.clientHeight );
</script>


<button onclick="getViewportSize(w)"> Click me to see viewport dimensions! </button>

<style>

button {
  font-weight: bold;
  font-size: 50%;
  background: linear-gradient(-90deg, red, yellow);
  border-radius: 10px;
  border: 2px;
  margin-top: 20px;
  line-height: 40px;
  padding: 0px 20px;
}
button:hover {
  background: linear-gradient(-90deg, yellow, red);
}

</style>

 

<ul class="navbar">
  <li><a href="default.asp">Home</a></li>
  <li><a href="news.asp">News</a></li>
  <li><a href="contact.asp">Contact</a></li>
  <li><a href="about.asp">About</a></li>
</ul>

<style>

body {margin: 0;}

ul.navbar {
    left: 0;
    text-align: center;
    width: 100vw;
    position: fixed;
    top: 0;
    display: inline;
    margin: auto;
    padding: 0px 20px;
    overflow: hidden;
    background-color: #060566;
    z-index: 9998;
}

li.navbar{
    list-style-type: none;
    display: inline-block;
    padding: 0px 20px;
}

</style>


<link rel="icon" type="image/png" href="http://theedgehalfmoon.com/sites/all/themes/theedge/images/boulderer.png">

</head>
<body> 	


<style> 
        img {
	   border-radius: 25px;
	}	
</style>

<style> body { background: url("https://i2.wp.com/techbeasts.com/wp-content/uploads/2016/12/4435365-mountain-wallpapers.jpg") no-repeat bottom center;
  background-size: cover;
  background-attachment: fixed;
  height: 900px;
  position: relative;
  top: -55px;
  width: 1440px; }
  </style>

<style> h1, p, ul, h3, footer {
    background-color: black;
    padding: 10px 10px;
    border-radius: 25px;
    text-align: center;
} 

a {
    color: white;
    background-color: transparent;
}
</style>

<h1 align="center">Climbing Website</h1>



<style>
 
   #button {
        width:200px;
        height:100px;
        position:absolute;
        top:0px;
        left:0px;
        background: linear-gradient(-90deg, blue, green);
        color: red;
        border: solid 2px black;
	z-index: 9999;
	font-size: 120%;
	line-height: 20px;
    }
 
 
    #button:hover {
        background: linear-gradient(-90deg, green, blue);
    }
    
    </style>


 
   <button id="button" onclick="myFunction()">Click me if you can!</button>
 
 
<script>

function myFunction() {
    alert("Wow you just wasted your time trying to click a completely useless button, you pathetic excuse for a person..Want a cookie?");
}

</script>



<script>
    var button = document.getElementById("button");
    var buttonWidth = button.offsetWidth;
    var buttonHeight = button.offsetHeight;
    var browserWidth = window.innerWidth || document.documentElement.clientWidth;
    var browserHeight = window.innerHeight || document.documentElement.clientHeight;

 
    function move() {
        button.style.left = Math.floor(Math.random()*(browserWidth-buttonWidth)) + "px";
        button.style.top = Math.floor(Math.random()*(browserHeight-buttonHeight)) + "px";
    }
 
    if(typeof addEventListener !== "undefined") {
        button.addEventListener("mouseover", move, false);
    } else if (typeof attachEvent !== "undefined") {
        button.attachEvent("onmouseover", move);
    } else {
        button.onmousover = move;
    }
 
</script>






<div class="youtube_link">
<p>Here is a cool <a text-align:center href="https://www.youtube.com/channel/UCIRIbjrEHserQZ6O1Jd9wrg">climbing channel </a> on Youtube.<br/></p>
</div>

<style>

p {
   font-size: medium;
}

.youtube_link {
       background-color: black;
       border-radius: 25px;
    }
</style>


<div class='b'>

<button>Click here to show 10 climbers that revolutionized the world of climbing</button>

</div>
	
<style> 
.b {
   font-size: 100%;
   align: center;  
   } 
</style>	
	
<script type="text/javascript">

$('.b').on('click', function() {
    $(this).toggleClass('active')
    .next().slideToggle(1000);
  });
  
</script>


<script>

var button1 = document.createElement("button");
button1.innerHTML = "Click me!";

var body = document.getElementsByTagName("body")[0];
body.appendChild(button1);

button1.addEventListener ("click", function() {
  alert("You just took directions from a button..");
});
	

</script>
		
		
		
		
		
		
		
		
<ul class="climbers">
		<li><a href = "https://en.wikipedia.org/wiki/Chris_Sharma">Chris Sharma</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Ashima_Shiraishi">Ashima Shiraishi</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Adam_Ondra">Adam Ondra</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Steph_Davis">Steph Davis</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Catherine_Destivelle">Catherine Destivelle</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Dean_Potter">Dean Potter</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Alex_Honnold">Alex Honnold</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Lynn_Hill">Lynn Hill</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Tommy_Caldwell">Tommy Caldwell</a></li>
		<li><a href = "https://en.wikipedia.org/wiki/Beth_Rodden">Beth Rodden</a></li>
</ul>
	        
		
		
<style> 
	ul.climbers {
	   list-style-type: none;
	   visibility: visible;
	}
</style>

<img src = "https://d36tnp772eyphs.cloudfront.net/blogs/1/2014/08/Smith-Rock-940x595.jpg">

<p> I realized that a climber’s ability can usually be judged by the point at which he gives up. Beginners fall off when they don’t know what to do, advanced climbers when they get pumped, but world-class climbers like Jerry Moffatt climb far beyond the phisical limitations of their muscles. -Christian Griffith
</p>

<p> Most sports require only one ball. </p>

<p> Rocks make no compromise for sex... rock climbing is not like some sports, where it is made easier for women; or sports like, say, softball, which is only baseball for soft people. On a rock, everything is equal. -Beverly Johnson </p>

<p> We do not deceive ourselves that we are engaging in an activity that is anything but debilitating, dangerous, euphoric, kinesthetic, expensive, frivolously essential, economically useless and totally without redeeming social significance. One should not probe for deeper meanings. -Allen Steck </p>

<p>The difference between climbers and normal workers is that climbers are glad of the Mondays, so they can rest. -Guillaume Dargaud </p>

<style>
div.container {
   max-width: 1400px;
   max-height: 900px;
}
</style>



</body>
<footer> 
<h5>Victor Vladimirov 2017</h5>
</footer>
</div>
</html>
