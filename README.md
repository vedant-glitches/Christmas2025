<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Merry Christmas Piyu 🎄</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins', sans-serif;
}
body{
  background: linear-gradient(to bottom, #a8e6cf, #e6e6fa); /* Green shade main + lavender secondary */
  overflow-x:hidden;
}
.page{
  display:none;
  min-height:100vh;
  padding:30px;
  text-align:center;
}
.page.active{
  display:block;
}
h1{
  font-size:2rem;
  color:#b30000;
  margin-bottom:15px;
}
p{
  font-size:1rem;
  color:#333;
  line-height:1.5;
}
button{
  margin-top:25px;
  padding:12px 25px;
  border:none;
  border-radius:30px;
  background:#b30000;
  color:white;
  font-size:1rem;
  cursor:pointer;
  box-shadow:0 5px 15px rgba(0,0,0,0.2);
}
button:hover{
  background:#800000;
}
.card{
  background:white;
  padding:20px;
  border-radius:20px;
  box-shadow:0 10px 25px rgba(0,0,0,0.2);
  margin-top:30px;
  text-align:center;
}
.heart{
  font-size:2rem;
  animation:beat 1s infinite;
  margin-top:10px;
}
@keyframes beat{
  50%{ transform:scale(1.2); }
}

/* Snow effect */
.snow{
  position:fixed;
  top:-10px;
  color:white;
  animation: fall linear infinite;
}
@keyframes fall{
  to{ transform:translateY(110vh); }
}
</style>
</head>
<body>

<!-- PAGE 1 -->
<div class="page active" id="page1">
  <h1>Wish You A Merry Christmas Piyu 💗</h1>
  <div class="card">
    <p>This December brought Love and Joy to me,</p>
    <p>This Christmas is as special as YOU 💖</p>
  </div>
  <button onclick="nextPage(2)">Next ➜</button>
</div>

<!-- PAGE 2 -->
<div class="page" id="page2">
  <h1>For a Special Person</h1>
  <div class="card">
    <p>"Birds of a feather, we should be together ~ Billie Ellish"</p>
    <p>You are special to me, aur cutie pieeee toh you are from the beginning 💕</p>
    <p>I hope you remain the same always</p>
  </div>
  <button onclick="nextPage(3)">Next ➜</button>
</div>

<!-- PAGE 3 -->
<div class="page" id="page3">
  <h1>A Very Very Happy Christmas Piyu 🎄</h1>
  <div class="card">
    <p>Always stay the same, be unique as you are.</p>
    <p>I'm grateful to God, that he made this possible 🙏</p>
    <p>Stay Safe, Stay Blessed 💖</p>
  </div>
  <button onclick="alert('Merry Christmas Mammmm 💗🎄')">Finish 🎅</button>
</div>

<script>
function nextPage(n){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page'+n).classList.add('active');
}

/* Snow effect */
for(let i=0;i<40;i++){
  let snow=document.createElement('div');
  snow.className='snow';
  snow.innerHTML='❄';
  snow.style.left=Math.random()*100+'vw';
  snow.style.animationDuration=(Math.random()*3+2)+'s';
  snow.style.fontSize=(Math.random()*10+10)+'px';
  document.body.appendChild(snow);
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Merry Christmas Piyu 🎄</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins', sans-serif;
}
body{
  background: linear-gradient(to bottom, #a8e6cf, #e6e6fa); /* Green shade main + lavender secondary */
  overflow-x:hidden;
}
.page{
  display:none;
  min-height:100vh;
  padding:30px;
  text-align:center;
}
.page.active{
  display:block;
}
h1{
  font-size:2rem;
  color:#b30000;
  margin-bottom:15px;
}
p{
  font-size:1rem;
  color:#333;
  line-height:1.5;
}
button{
  margin-top:25px;
  padding:12px 25px;
  border:none;
  border-radius:30px;
  background:#b30000;
  color:white;
  font-size:1rem;
  cursor:pointer;
  box-shadow:0 5px 15px rgba(0,0,0,0.2);
}
button:hover{
  background:#800000;
}
.card{
  background:white;
  padding:20px;
  border-radius:20px;
  box-shadow:0 10px 25px rgba(0,0,0,0.2);
  margin-top:30px;
  text-align:center;
}
.heart{
  font-size:2rem;
  animation:beat 1s infinite;
  margin-top:10px;
}
@keyframes beat{
  50%{ transform:scale(1.2); }
}

/* Snow effect */
.snow{
  position:fixed;
  top:-10px;
  color:white;
  animation: fall linear infinite;
}
@keyframes fall{
  to{ transform:translateY(110vh); }
}
</style>
</head>
<body>

<!-- PAGE 1 -->
<div class="page active" id="page1">
  <h1>Wish You A Merry Christmas Piyu 💗</h1>
  <div class="card">
    <p>This December brought Love and Joy to me,</p>
    <p>This Christmas is as special as YOU 💖</p>
  </div>
  <button onclick="nextPage(2)">Next ➜</button>
</div>

<!-- PAGE 2 -->
<div class="page" id="page2">
  <h1>For a Special Person</h1>
  <div class="card">
    <p>"Birds of a feather, we should be together ~ Billie Ellish"</p>
    <p>You are special to me, aur cutie pieeee toh you are from the beginning 💕</p>
    <p>I hope you remain the same always</p>
  </div>
  <button onclick="nextPage(3)">Next ➜</button>
</div>

<!-- PAGE 3 -->
<div class="page" id="page3">
  <h1>A Very Very Happy Christmas Piyu 🎄</h1>
  <div class="card">
    <p>Always stay the same, be unique as you are.</p>
    <p>I'm grateful to God, that he made this possible 🙏</p>
    <p>Stay Safe, Stay Blessed 💖</p>
  </div>
  <button onclick="alert('Merry Christmas Mammmm 💗🎄')">Finish 🎅</button>
</div>

<script>
function nextPage(n){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page'+n).classList.add('active');
}

/* Snow effect */
for(let i=0;i<40;i++){
  let snow=document.createElement('div');
  snow.className='snow';
  snow.innerHTML='❄';
  snow.style.left=Math.random()*100+'vw';
  snow.style.animationDuration=(Math.random()*3+2)+'s';
  snow.style.fontSize=(Math.random()*10+10)+'px';
  document.body.appendChild(snow);
}
</script>

</body>
</html>
