<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For You ❤️</title>

<style>
*{
  box-sizing:border-box;
}
body{
  margin:0;
  font-family:'Segoe UI',sans-serif;
  background:linear-gradient(135deg,#ffd6e8,#fff0f6);
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
  overflow:hidden;
}

/* CARD */
.card{
  background:white;
  padding:30px;
  border-radius:25px;
  max-width:360px;
  text-align:center;
  animation:pop 1.2s ease;
  box-shadow:0 20px 40px rgba(0,0,0,.15);
}
@keyframes pop{
  from{transform:scale(.7);opacity:0}
  to{transform:scale(1);opacity:1}
}

h1{
  color:#ff4d88;
  margin-bottom:10px;
}
p{
  color:#444;
  font-size:16px;
  line-height:1.6;
}

/* CAT */
.cat{
  font-size:80px;
  animation:jump 1.5s infinite alternate, blink 3s infinite;
}
@keyframes jump{
  from{transform:translateY(0)}
  to{transform:translateY(-20px)}
}
@keyframes blink{
  0%,90%,100%{transform:scale(1)}
  95%{transform:scale(1.08)}
}

/* FLOATING HEARTS */
.heart{
  position:fixed;
  color:#ff4d88;
  font-size:18px;
  animation:float linear infinite;
  pointer-events:none;
}
@keyframes float{
  from{transform:translateY(100vh)}
  to{transform:translateY(-10vh)}
}

/* TAP NOTE */
.tap{
  font-size:12px;
  color:#999;
  margin-top:10px;
}
</style>
</head>

<body>

<div class="card">
  <div class="cat">🐱</div>

  <h1>Hey Aqsa 💗</h1>

  <p>
    Pyari pyari si chiz  
    pyari pyari si Aqsa ke liye 💕  
    <br><br>
    Ye page bas ek chhoti si koshish hai  
    tumhe batane ke liye ki  
    tum bahut special ho ✨
  </p>

  <p>– Faiz 🤍</p>
  <div class="tap">(Tap anywhere for music 🎶)</div>
</div>

<!-- BACKGROUND MUSIC (Mobile Safe) -->
<audio id="bgm" autoplay loop muted>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3">
</audio>

<script>
/* Floating hearts */
for(let i=0;i<25;i++){
  let h=document.createElement("div");
  h.className="heart";
  h.innerHTML="❤️";
  h.style.left=Math.random()*100+"vw";
  h.style.fontSize=12+Math.random()*18+"px";
  h.style.animationDuration=4+Math.random()*4+"s";
  document.body.appendChild(h);
}

/* Enable music on tap */
document.body.addEventListener("click",()=>{
  const music=document.getElementById("bgm");
  music.muted=false;
  music.play();
});
</script>

</body>
</html>
