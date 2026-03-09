<!DOCTYPE html>
<html>
<head>
<title>Birthday Surprise ❤️</title>

<style>

body{
background:#0f172a;
color:#00ff9c;
font-family:monospace;
text-align:center;
padding-top:80px;
overflow-x:hidden;
}

#code{
font-size:20px;
white-space:pre-line;
}

#message{
display:none;
font-size:38px;
color:#ff4d6d;
margin-top:40px;
}

.gallery{
margin-top:40px;
}

.gallery img{
width:220px;
height:300px;
object-fit:cover;
border-radius:12px;
margin:12px;
box-shadow:0 0 15px rgba(255,0,90,0.6);
transition:0.4s;
}

.gallery img:hover{
transform:scale(1.1);
}

</style>

</head>

<body>

<h2>💻 Coding Birthday Surprise...</h2>

<div id="code"></div>

<div id="message">

🎂 Happy Birthday My Special One ❤️

<p>
You are the most beautiful part of my life.<br>
May your day be filled with happiness and love.
</p>

<div class="gallery">

<img src="photo1.jpg">
<img src="photo2.jpg">
<img src="photo3.jpg">
<img src="photo4.jpg">

</div>

</div>

<script>

let text = `
Initializing birthday.exe
Connecting to heart ❤️
Loading beautiful memories...
Searching happiness...
Result found: YOU ❤️

Generating surprise...
Preparing birthday wish...
`;

let i = 0;
let speed = 45;

function typeWriter(){

if(i < text.length){

document.getElementById("code").innerHTML += text.charAt(i);
i++;

setTimeout(typeWriter,speed);

}
else{

document.getElementById("message").style.display="block";

}

}

typeWriter();

</script>

</body>
</html>
