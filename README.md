# Saeee
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Proposal Day Saee ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #ffe6eb, #fff);
  overflow-x: hidden;
  color: #5a1a2f;
}

/* Center Card */
.container {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
  position: relative;
}

.card {
  background: rgba(255,255,255,0.95);
  padding: 30px;
  border-radius: 22px;
  text-align: center;
  max-width: 380px;
  box-shadow: 0 15px 35px rgba(0,0,0,0.15);
  z-index: 2;
  animation: pop 1s ease;
}

h1 {
  font-family: 'Playfair Display', serif;
  color: #b1123f;
}

.ring {
  font-size: 60px;
  animation: float 2.5s infinite ease-in-out;
}

p {
  font-size: 15px;
  line-height: 1.6;
}

/* Buttons */
.buttons {
  margin-top: 20px;
}

button {
  padding: 12px 22px;
  border-radius: 30px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  margin: 8px;
}

.yes {
  background: linear-gradient(135deg, #ff4d6d, #e6005c);
  color: white;
}

.no {
  background: #ddd;
}

#surprise {
  display: none;
  margin-top: 15px;
  color: #e6005c;
  font-weight: 600;
}

/* Photo Section */
.photos {
  margin-top: 25px;
}

.photos img {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 12px;
}

/* Floating hearts & petals */
.heart, .petal {
  position: absolute;
  animation: floatUp linear infinite;
  opacity: 0.8;
}

.heart {
  font-size: 18px;
}

.petal {
  font-size: 16px;
}

@keyframes float {
  0%,100% { transform: translateY(0); }
  50% { transform: translateY(-12px); }
}

@keyframes pop {
  from { transform: scale(0.85); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}

@keyframes floatUp {
  from { transform: translateY(110vh); }
  to { transform: translateY(-10vh); }
}
</style>
</head>

<body>

<!-- 🎶 Background Music -->
<audio autoplay loop>
  <source src="ishq-wala-love.mp3" type="audio/mpeg">
</audio>

<div class="container">

  <div class="card">
    <div class="ring">💍</div>

    <h1>Happy Proposal Day Saee ❤️</h1>

    <p>
      Saee, from the moment you walked into my life,<br>
      everything changed for the better 💕
    </p>

    <p>
      You are my calm, my happiness,<br>
      and my favorite person forever 🥰
    </p>

    <p>
      So today, with all my heart…
    </p>

    <div class="buttons">
      <button class="yes" onclick="yesClick()">YES 💖</button>
      <button class="no" onclick="noClick()">NO 🙈</button>
    </div>

    <div id="surprise">
      You just made me the happiest person 😭❤️<br>
      I promise to love you, protect you,<br>
      and choose you every single day 💍
  

<script>
function yesClick() {
  document.getElementById("surprise").style.display = "block";
}

function noClick() {
  alert("Oops 😜 Try again, Saee ❤️");
}

/* Hearts */
for(let i=0;i<20;i++){
  let h = document.createElement("div");
  h.className="heart";
  h.innerHTML="❤️";
  h.style.left=Math.random()*100+"vw";
  h.style.animationDuration=(4+Math.random()*3)+"s";
  document.body.appendChild(h);
}

/* Rose Petals */
for(let i=0;i<25;i++){
  let p = document.createElement("div");
  p.className="petal";
  p.innerHTML="🌸";
  p.style.left=Math.random()*100+"vw";
  p.style.animationDuration=(5+Math.random()*4)+"s";
  document.body.appendChild(p);
}
</script>

</body>
</html>
