<!DOCTYPE html>  
<html lang="ar">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">  
<title>Valentine 💖</title>  
  
<style>  
  * {  
    box-sizing: border-box;  
    -webkit-tap-highlight-color: transparent; /* **يمنع** **الوميض** **الأزرق** **عند** **الضغط** **في** **الآيفون** */  
  }  
  
  body {  
    margin: 0;  
    height: 100vh;  
    height: -webkit-fill-available; /* **حل** **لمشكلة** **ارتفاع** **الشاشة** **في** **متصفح** **سفاري** */  
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
    background: linear-gradient(135deg, #ffd6e8, #ffeef6);  
    display: flex;  
    flex-direction: column;  
    align-items: center;  
    justify-content: space-around; /* **توزيع** **أفضل** **للعناصر** **على** **الشاشات** **الطويلة** */  
    overflow: hidden;  
    padding: 20px;  
  }  
  
  h1 {  
    font-size: 28px;  
    text-align: center;  
    color: #ff2f7d;  
    text-shadow: 1px 1px 2px rgba(0,0,0,0.1);  
    z-index: 10;  
  }  
  
  .buttons-container {  
    position: relative;  
    width: 100%;  
    height: 60vh; /* **تحديد** **منطقة** **واسعة** **لتحرك** **زر** "No" */  
    display: flex;  
    flex-direction: column;  
    align-items: center;  
    justify-content: center;  
  }  
  
  button {  
    padding: 16px 40px;  
    font-size: 20px;  
    font-weight: bold;  
    border-radius: 50px;  
    border: none;  
    cursor: pointer;  
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);  
    transition: transform 0.2s ease;  
    touch-action: manipulation; /* **تحسين** **الاستجابة** **للمس** */  
  }  
  
  #yes {  
    background: #ff4d88;  
    color: white;  
    z-index: 5;  
  }  
  
  #no {  
    background: #b3b3b3;  
    color: white;  
    position: absolute; /* **مهم** **لجعل** **الزر** **يهرب** **داخل** **الـ** container */  
    z-index: 4;  
  }  
  
  #result {  
    font-size: 36px;  
    color: #ff1a75;  
    display: none;  
    text-align: center;  
    animation: pop 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);  
  }  
  
  @keyframes pop {  
    0% { transform: scale(0); opacity: 0; }  
    100% { transform: scale(1); opacity: 1; }  
  }  
  
  .heart {  
    position: fixed;  
    bottom: -50px;  
    font-size: 24px;  
    animation: floatUp 5s linear infinite;  
    opacity: 0.8;  
    pointer-events: none;  
    z-index: 1;  
  }  
  
  @keyframes floatUp {  
    0% { transform: translateY(0) rotate(0deg); opacity: 1; }  
    100% { transform: translateY(-120vh) rotate(360deg); opacity: 0; }  
  }  
</style>  
</head>  
  
<body>  
  
<h1 id="question">Would u be my Valentine? 💖</h1>  
  
<div class="buttons-container" id="area">  
  <button id="yes">Yes</button>  
  <button id="no">No</button>  
</div>  
  
<div id="result">Finally! <br> I Love You ❤️</div>  
  
<audio id="song">  
  <source src="all-i-need.m4a" type="audio/mp4">  
</audio>  
  
<script>  
  const noBtn = document.getElementById("no");  
  const yesBtn = document.getElementById("yes");  
  const result = document.getElementById("result");  
  const question = document.getElementById("question");  
  const area = document.getElementById("area");  
  const song = document.getElementById("song");  
  
  // **دالة** **لجعل** **الزر** **يهرب** **بذكاء** **داخل** **حدود** **الشاشة**  
  function moveNoButton() {  
    // **حساب** **الحدود** **المتاحة** **داخل** **منطقة** **الأزرار** **فقط** **لضمان** **عدم** **خروجه** **عن** **الشاشة**  
    const padding = 20;  
    const maxX = area.clientWidth - noBtn.offsetWidth - padding;  
    const maxY = area.clientHeight - noBtn.offsetHeight - padding;  
  
    const randomX = Math.floor(Math.random() * maxX);  
    const randomY = Math.floor(Math.random() * maxY);  
  
    noBtn.style.left = randomX + "px";  
    noBtn.style.top = randomY + "px";  
  }  
  
  // **في** **الآيفون،** **يفضل** **استخدام** 'touchstart' **للهروب** **السريع** **أو** 'click'  
  noBtn.addEventListener("touchstart", (e) => {  
    e.preventDefault(); // **منع** **السلوك** **الافتراضي** **للمس**  
    moveNoButton();  
  });  
  
  noBtn.addEventListener("click", moveNoButton);  
  
  // **زر** **نعم**  
  yesBtn.addEventListener("click", () => {  
    question.style.display = "none";  
    area.style.display = "none";  
    result.style.display = "block";  
  
    // **تشغيل** **الموسيقى**  
    song.currentTime = 140;   
    song.play().catch(error => console.log("Audio play failed:", error));  
      
    // **زيادة** **كثافة** **القلوب** **عند** **الموافقة**  
    setInterval(createHeart, 200);  
  });  
  
  // **مولد** **القلوب**  
  function createHeart() {  
    const heart = document.createElement("div");  
    heart.classList.add("heart");  
    heart.innerHTML = "💖";  
    heart.style.left = Math.random() * 100 + "vw";  
    heart.style.fontSize = Math.random() * 20 + 15 + "px";  
    heart.style.animationDuration = Math.random() * 2 + 3 + "s";  
  
    document.body.appendChild(heart);  
  
    setTimeout(() => {  
      heart.remove();  
    }, 5000);  
  }  
  
  setInterval(createHeart, 600);  
</script>  
  
</body>  
</html>  
