<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Prefcat RP | قوانين السيرفر</title>

<style>

body{
margin:0;
font-family:Tahoma;
direction:rtl;
color:white;
background:black;
}

/* النجوم */

.stars{
position:fixed;
width:100%;
height:100%;
background:url("https://i.imgur.com/YKY28eT.png");
animation:stars 80s linear infinite;
z-index:-1;
}

@keyframes stars{
from{background-position:0 0;}
to{background-position:0 1200px;}
}

/* العنوان */

.title{
text-align:center;
font-size:50px;
color:#ffd700;
margin-top:40px;
}

/* الاونر */

.owner{
text-align:center;
font-size:22px;
color:#ffd700;
margin-top:10px;
}

/* المطور */

.dev{
position:fixed;
left:0;
top:0;
height:100%;
width:60px;
background:#140028;
display:flex;
align-items:center;
justify-content:center;
}

.dev span{
transform:rotate(-90deg);
font-size:22px;
color:#ffd700;
font-weight:bold;
}

/* القوانين */

.rules{
width:70%;
margin:auto;
margin-top:40px;
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
}

.rule:hover{
background:#3c0075;
transform:scale(1.02);
}

.content{
display:none;
background:#120025;
margin-top:15px;
padding:20px;
border-radius:10px;
line-height:2;
font-size:18px;
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

1 احترام جميع اللاعبين داخل السيرفر.  
2 يمنع السب أو الإهانة.  
3 يمنع العنصرية.  
4 الالتزام بالرول بلاي الواقعي.  
5 يمنع استخدام برامج الغش.  
6 يمنع استغلال الثغرات.  
7 احترام الإدارة.  
8 يمنع تقليد الإدارة.  
9 يمنع نشر روابط غير مسموحة.  
10 يمنع الإزعاج المتكرر.  
11 يمنع السبام داخل الشات.  
12 احترام اللاعبين الجدد.  
13 يمنع الاستفزاز المتعمد.  
14 يمنع القتل بدون سبب.  
15 يمنع تعطيل السيناريوهات.  
16 التعاون بين اللاعبين.  
17 منع استخدام معلومات خارج اللعبة.  
18 يمنع الكذب على الإدارة.  
19 يمنع التهديد داخل السيرفر.  
20 يمنع إزعاج اللاعبين بالمايك.  
21 يمنع تشغيل أصوات مزعجة.  
22 الحفاظ على بيئة لعب محترمة.  
23 يمنع استغلال اللاعبين الجدد.  
24 يمنع تعطيل الفعاليات.  
25 يمنع إثارة المشاكل.  
26 الالتزام بالتعليمات.  
27 يمنع إفساد الرول بلاي.  
28 احترام قوانين السيرفر.  
29 يمنع تخريب ممتلكات اللاعبين.  
30 يمنع الهروب من السيناريو.  
31 يمنع الشخصيات غير الواقعية.  
32 يمنع الأفعال غير المنطقية.  
33 احترام الجميع.  
34 يمنع السخرية من اللاعبين.  
35 يمنع نشر معلومات خاصة.  
36 يمنع تعطيل اللعب الجماعي.  
37 يجب التصرف بواقعية.  
38 يمنع تكرار المخالفات.  
39 الحفاظ على اللعب النظيف.  
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

var content = element.querySelector(".content");

if(content.style.display === "block"){
content.style.display = "none";
}else{
content.style.display = "block";
}

}

</script>

</body>
</html>
