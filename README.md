<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prefcat RP | قوانين السيرفر</title>

<style>

body{
margin:0;
font-family:Tahoma;
background:black;
color:white;
overflow-x:hidden;
}

/* خلفية نجوم */
.stars{
position:fixed;
width:100%;
height:100%;
background:url("https://i.imgur.com/YKY28eT.png");
animation:stars 100s linear infinite;
z-index:-1;
opacity:0.3;
}

@keyframes stars{
from{background-position:0 0;}
to{background-position:0 1500px;}
}

/* الشريط الجانبي */
.dev{
position:fixed;
left:0;
top:0;
height:100%;
width:40px;
background:linear-gradient(180deg,#140028,#2a0050);
display:flex;
align-items:center;
justify-content:center;
box-shadow:0 0 15px #7a00ff;
}

.dev span{
transform:rotate(-90deg);
font-size:13px;
color:#ffd700;
font-weight:bold;
letter-spacing:1px;
}

/* العنوان */
.title{
text-align:center;
font-size:34px;
color:#ffd700;
margin-top:60px;
text-shadow:0 0 15px #ffd700;
}

.owner{
text-align:center;
font-size:18px;
margin-top:10px;
}

/* القوانين */
.rules{
width:92%;
margin:auto;
margin-top:40px;
}

.rule{
background:#2a0050;
margin:15px 0;
padding:18px;
border-radius:12px;
cursor:pointer;
font-size:18px;
border:1px solid #7a00ff;
transition:0.3s;
}

.rule:hover{
background:linear-gradient(45deg,#3c0075,#7a00ff);
box-shadow:0 0 15px #7a00ff;
}

.content{
max-height:0;
overflow:hidden;
background:#120025;
margin-top:10px;
padding:0 15px;
border-radius:10px;
line-height:1.8;
font-size:16px;
transition:max-height 0.4s ease, padding 0.3s ease;
}

/* موبايل */
@media(max-width:768px){
.title{
font-size:26px;
}
}

</style>
</head>

<body>

<div class="stars"></div>

<div class="dev">
<span>Developer Eyad</span>
</div>

<div class="title">
قوانين سيرفر Prefcat RP
</div>

<div class="owner">
👑 Owner Server: ضرغام
</div>

<div class="rules">

<div class="rule" onclick="toggle(this)">
القوانين العامة
<div class="content">
احترام جميع اللاعبين – يمنع السب – يمنع العنصرية – الالتزام بالرول بلاي – يمنع الغش – يمنع استغلال الثغرات – احترام الإدارة – يمنع القتل بدون سبب – يمنع تخريب السيناريو – مخالفة القوانين تعرضك للعقوبة.
</div>
</div>

<div class="rule" onclick="toggle(this)">
قوانين NLR
<div class="content">
عند موت شخصيتك تبدأ حياة جديدة ولا يمكنك تذكر الأحداث السابقة أو الانتقام.
</div>
</div>

<div class="rule" onclick="toggle(this)">
PowerGaming
<div class="content">
القيام بأفعال غير واقعية أو إجبار لاعب على شيء غير منطقي.
</div>
</div>

<div class="rule" onclick="toggle(this)">
Metagaming
<div class="content">
استخدام معلومات خارج اللعبة داخل الرول بلاي.
</div>
</div>

<div class="rule" onclick="toggle(this)">
RDM
<div class="content">
قتل لاعب بدون سبب أو بدون سيناريو واضح.
</div>
</div>

<div class="rule" onclick="toggle(this)">
NVL
<div class="content">
يجب تقدير حياتك والخوف على شخصيتك في المواقف الخطرة.
</div>
</div>

<div class="rule" onclick="toggle(this)">
قوانين العصابات
<div class="content">
يجب وجود سيناريو واضح قبل أي هجوم أو اشتباك.
</div>
</div>

<div class="rule" onclick="toggle(this)">
قوانين الشرطة
<div class="content">
الالتزام بالقوانين وعدم استخدام القوة بدون مبرر.
</div>
</div>

</div>

<script>

function toggle(element){

var allContents = document.querySelectorAll(".content");

allContents.forEach(function(c){
if(c !== element.querySelector(".content")){
c.style.maxHeight = null;
c.style.padding = "0 15px";
}
});

var content = element.querySelector(".content");

if(content.style.maxHeight){
content.style.maxHeight = null;
content.style.padding = "0 15px";
}else{
content.style.maxHeight = content.scrollHeight + "px";
content.style.padding = "15px";
}

}

</script>

</body>
</html>
