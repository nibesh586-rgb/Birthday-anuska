# Birthday-anuska<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Anuska ❤️</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
height:100vh;
overflow:hidden;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(-45deg,#ff4d6d,#ff758f,#ff9a9e,#fad0c4);
background-size:400% 400%;
animation:bg 10s infinite alternate;
font-family:Arial,sans-serif;
text-align:center;
color:#fff;
}

@keyframes bg{
0%{background-position:0% 50%;}
100%{background-position:100% 50%;}
}

.card{
background:rgba(255,255,255,.15);
padding:30px;
border-radius:20px;
backdrop-filter:blur(10px);
box-shadow:0 0 25px rgba(255,255,255,.4);
z-index:2;
max-width:700px;
}

h1{
font-size:48px;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{text-shadow:0 0 10px white;}
to{text-shadow:0 0 30px yellow;}
}

p{
font-size:22px;
line-height:1.7;
margin-top:20px;
}

.heart{
position:absolute;
color:red;
font-size:25px;
animation:float 8s linear infinite;
}

@keyframes float{
0%{transform:translateY(100vh) scale(.5);opacity:0;}
100%{transform:translateY(-100px) scale(1.5);opacity:1;}
}
</style>
</head>

<body>

<div class="card">
<h1>🎂 Happy Birthday My Queen Anuska ❤️</h1>

<p>
My Dearest <b>Anuska</b>, ❤️<br><br>

Today is the most beautiful day because it is the day you were born. 🌹<br><br>

May every smile on your face stay forever.<br>
May every dream in your heart come true.<br>
May God always bless you with happiness, success and endless love. ✨<br><br>

Thank you for coming into my life and making every moment special. ❤️<br><br>

<b>I promise to stand by your side through every smile, every tear, and every dream.</b><br><br>

💖 Happy Birthday, My Love! 💖<br><br>

Forever Yours,<br>
❤️ <b>Nibesh</b> ❤️
</p>

<h2>🎉 🎂 💖 🎈 🎆</h2>

</div>

<script>
function heart(){
let h=document.createElement("div");
h.className="heart";
h.innerHTML="❤";
h.style.left=Math.random()*100+"vw";
h.style.fontSize=(15+Math.random()*35)+"px";
h.style.animationDuration=(4+Math.random()*5)+"s";
document.body.appendChild(h);

setTimeout(()=>{h.remove();},9000);
}
setInterval(heart,200);
</script>

<!-- Background Music -->
<!-- Apni birthday song ka naam "birthday.mp3" rakhkar isi folder me rakho -->
<audio autoplay loop>
<source src="birthday.mp3" type="audio/mpeg">
</audio>

</body>
</html>
