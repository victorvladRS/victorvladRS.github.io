<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="site_style.css">
	<script type="text/javascript" src="script.js"></script>
	<script type="text/javascript" src="jquery-3.2.1.js"></script>
<script type="text/javascript">
      alert("Welcome to my Website");
</script>



</head>
<body> 	

<style>
        a {
	background-color: transparent;
	}

</style>


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
  width: 100%; }
  </style>

<style> h1, p, ul, h3 {
    background-color: black;
    padding: 10px 10px;
    border-radius: 25px;
} 

a {
    color: white;
}
</style>

<h1 align="center">Sample Website</h1>


<div class="youtube_link">
<p>Here is an awesome <a text-align:center href="https://www.youtube.com/channel/UCIRIbjrEHserQZ6O1Jd9wrg">Climbing channel </a> on Youtube.<br/></p>
</div>

<style>

p {
   font-size: small;
}

</style>



<style>
    .youtube_link {
       background-color: black;
       border-radius: 25px;
    }
</style>


<div class='a'>

<button>Click Me!</button>

</div>
	
<script>
		
var button = document.createElement("button");
button.innerHTML = "Click me.";

var body = document.getElementsByTagName("body")[0];
body.appendChild(button);

button.addEventListener ("click", function() {
  alert("You just took directions from a button..");
});
	

</script>
		
<style>

button {
  margin-top: 20px;
  line-height: 60px;
  font-weight: bold;
  font-size: 200%;
  padding: 0 40px;
  background: linear-gradient(-90deg, red, yellow);
  border-radius: 10px;
  border: 2px;
}
button:hover {
  font-size: 250%;
  border-bottom: 8px;
  background: linear-gradient(-90deg, yellow, red);
}

</style>

<script>



$(".first-nav li a").hover(
    function(event) {
        // The mouse has entered the element, can reference the element via 'this'
    },
    function (event) {
        // The mouse has left the element, can reference the element via 'this'
    }
 );



$(document).ready(function(){
    animateDiv();
    
});

function makeNewPosition(){
    
    // Get viewport dimensions (remove the dimension of the div)
    var h = $(window).height() - 50;
    var w = $(window).width() - 50;
    
    var nh = Math.floor(Math.random() * h);
    var nw = Math.floor(Math.random() * w);
    
    return [nh,nw];    
    
}

function animateDiv(){
    var newq = makeNewPosition();
    $('.a').animate({ top: newq[0], left: newq[1] }, function(){
      animateDiv();        
    });
    
};

</script>

<style>

div.a {
   position: relative;
}

</style>


		
	<ul>
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
	ul {
	   visibility: visible;
	}
	</style>
<img src = "https://d36tnp772eyphs.cloudfront.net/blogs/1/2014/08/Smith-Rock-940x595.jpg">

<p> Sample text to show what it looks like... It is better to be hated for what you are than to be loved for what you are not.-André Gide etc..</p>
</body>
<footer> 
<h5>Victor Vladimirov 2017</h5>
</footer>
</html>
