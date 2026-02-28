<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>Prefcat RP | قوانين السيرفر</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

body{
margin:0;
font-family:Tahoma;
color:white;
background:black;
overflow-x:hidden;
}

/* النجوم */

.stars{
position:fixed;
width:100%;
height:100%;
background:url("https://i.imgur.com/YKY28eT.png");
animation:stars 80s linear infinite;
z-index:-1;
opacity:0.4;
}

@keyframes stars{
from{background-position:0 0;}
to{background-position:0 1200px;}
}

/* المطور الجانبي */

.dev{
position:fixed;
left:0;
top:0;
height:100%;
width:70px;
background:linear-gradient(180deg,#140028,#2a0050);
display:flex;
align-items:center;
justify-content:center;
box-shadow:0 0 20px #7a00ff;
}

.dev span{
transform:rotate(-90deg);
font-size:18px;
color:#ffd700;
font-weight:bold;
letter-spacing:2px;
}

/* العنوان */

.title{
text-align:center;
font-size:48px;
color:#ffd700;
margin-top:50px;
text-shadow:0 0 15px #ffd700;
}

.owner{
text-align:center;
font-size:22px;
color:#fff;
margin-top:10px;
}

/* القوانين */

.rules{
width:70%;
margin:auto;
margin-top:50px;
}

.rule{
background:#2a0050;
margin:20px;
padding:20px;
border-radius:12px;
cursor:pointer;
font-size:22px;
border:1px solid #7a00ff;
transition:0.3s;
position:relative;
}

.rule:hover{
background:linear-gradient(45deg,#3c0075,#7a00ff);
transform:scale(1.03);
box-shadow:0 0 20px #7a00ff;
}

/* المحتوى الداخلي */

.content{
max-height:0;
overflow:hidden;
background:#120025;
margin-top:15px;
padding:0 20px;
border-radius:10px;
line-height:2;
font-size:18px;
transition:max-height 0.4s ease, padding 0.3s ease;
}

/* اسكرول احترافي */

::-webkit-scrollbar{
width:8px;
}

::-webkit-scrollbar-track{
background:black;
}

::-webkit-scrollbar-thumb{
background:#7a00ff;
border-radius:10px;
}

</style>
</head>

<body>

<div class="stars"></div>

<div class="dev">
<span>Developer Eyad El Karf</span>
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
1 احترام جميع اللاعبين داخل السيرفر.<br>
2 يمنع السب أو الإهانة.<br>
3 يمنع العنصرية.<br>
4 الالتزام بالرول بلاي الواقعي.<br>
5 يمنع استخدام برامج الغش.<br>
6 يمنع استغلال الثغرات.<br>
7 احترام الإدارة.<br>
8 يمنع تقليد الإدارة.<br>
9 يمنع نشر روابط غير مسموحة.<br>
10 يمنع الإزعاج المتكرر.<br>
11 يمنع السبام داخل الشات.<br>
12 احترام اللاعبين الجدد.<br>
13 يمنع الاستفزاز المتعمد.<br>
14 يمنع القتل بدون سبب.<br>
15 يمنع تعطيل السيناريوهات.<br>
16 التعاون بين اللاعبين.<br>
17 منع استخدام معلومات خارج اللعبة.<br>
18 يمنع الكذب على الإدارة.<br>
19 يمنع التهديد داخل السيرفر.<br>
20 يمنع إزعاج اللاعبين بالمايك.<br>
21 يمنع تشغيل أصوات مزعجة.<br>
22 الحفاظ على بيئة لعب محترمة.<br>
23 يمنع استغلال اللاعبين الجدد.<br>
24 يمنع تعطيل الفعاليات.<br>
25 يمنع إثارة المشاكل.<br>
26 الالتزام بالتعليمات.<br>
27 يمنع إفساد الرول بلاي.<br>
28 احترام قوانين السيرفر.<br>
29 يمنع تخريب ممتلكات اللاعبين.<br>
30 يمنع الهروب من السيناريو.<br>
31 يمنع الشخصيات غير الواقعية.<br>
32 يمنع الأفعال غير المنطقية.<br>
33 احترام الجميع.<br>
34 يمنع السخرية من اللاعبين.<br>
35 يمنع نشر معلومات خاصة.<br>
36 يمنع تعطيل اللعب الجماعي.<br>
37 يجب التصرف بواقعية.<br>
38 يمنع تكرار المخالفات.<br>
39 الحفاظ على اللعب النظيف.<br>
40 مخالفة القوانين تؤدي للعقوبة.
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
القيام بأفعال غير واقعية أو إجبار لاعب آخر على فعل شيء غير منطقي.
</div>
</div>

<div class="rule" onclick="toggle(this)">
Metagaming
<div class="content">
استخدام معلومات خارج اللعبة داخل الرول بلاي مثل الديسكورد.
</div>
</div>

<div class="rule" onclick="toggle(this)">
RDM
<div class="content">
قتل اللاعبين بدون سبب واضح أو بدون سيناريو.
</div>
</div>

<div class="rule" onclick="toggle(this)">
NVL
<div class="content">
يجب على اللاعب تقدير حياة شخصيته والخوف على حياته في المواقف الخطرة.
</div>
</div>

<div class="rule" onclick="toggle(this)">
قوانين العصابات
<div class="content">
يجب على العصابات الالتزام بالرول بلاي وعدم الهجوم بدون سيناريو واضح.
</div>
</div>

<div class="rule" onclick="toggle(this)">
قوانين الشرطة
<div class="content">
يجب على الشرطة الالتزام بالقوانين وعدم استخدام القوة بدون سبب.
</div>
</div>

</div>

<script>

function toggle(element){

var allContents = document.querySelectorAll(".content");

allContents.forEach(function(c){
if(c !== element.querySelector(".content")){
c.style.maxHeight = null;
c.style.padding = "0 20px";
}
});

var content = element.querySelector(".content");

if(content.style.maxHeight){
content.style.maxHeight = null;
content.style.padding = "0 20px";
}else{
content.style.maxHeight = content.scrollHeight + "px";
content.style.padding = "20px";
}

}

</script>

</body>
</html>
