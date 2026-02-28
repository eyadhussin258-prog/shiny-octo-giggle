<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>قوانين Prefcat RP</title>

<style>

body{
margin:0;
font-family:Tahoma;
color:white;
direction:rtl;
background:black;
}

/* النجوم */

.stars{
position:fixed;
width:100%;
height:100%;
background:url("https://i.imgur.com/YKY28eT.png");
animation:moveStars 80s linear infinite;
z-index:-1;
}

@keyframes moveStars{
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

/* اسم المطور */

.dev{
position:fixed;
right:10px;
top:40%;
font-size:22px;
color:#ffd700;
font-weight:bold;
background:#140028;
padding:10px 20px;
border-radius:10px;
}

/* القوانين */

.rules{
width:75%;
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
}

.content{
display:none;
background:#120025;
margin-top:15px;
padding:20px;
border-radius:10px;
line-height:1.9;
font-size:17px;
}

</style>

</head>

<body>

<div class="stars"></div>

<div class="dev">
Developer: Eyad El Karf
</div>

<div class="title">
قوانين سيرفر Prefcat RP
</div>

<div class="rules">

<div class="rule" onclick="toggle(this)">
القوانين العامة
<div class="content">

1- يجب احترام جميع اللاعبين داخل السيرفر وعدم السب أو الإهانة بأي شكل.  
2- يمنع استخدام الألفاظ العنصرية أو الكلام المسيء.  
3- يجب الالتزام بالرول بلاي الواقعي في جميع الأوقات.  
4- يمنع استخدام أي برامج غش أو تهكير.  
5- يمنع استغلال الثغرات داخل اللعبة.  
6- يمنع التخريب أو إفساد تجربة اللعب.  
7- يجب احترام قرارات الإدارة.  
8- يمنع تقليد الإدارة أو الادعاء بأنك إداري.  
9- يمنع نشر روابط غير مسموح بها.  
10- يمنع الإزعاج المتكرر للاعبين.  
11- يمنع السبام داخل الشات.  
12- يجب احترام اللاعبين الجدد.  
13- يمنع الاستفزاز المتعمد.  
14- يمنع القتل بدون سبب واضح.  
15- يمنع تعطيل السيناريوهات الجارية.  
16- يجب التعاون بين اللاعبين.  
17- يمنع استخدام معلومات خارج اللعبة داخل الرول بلاي.  
18- يمنع الكذب على الإدارة.  
19- يمنع التهديد داخل السيرفر.  
20- يمنع إزعاج اللاعبين بالمايكروفون.  
21- يمنع تشغيل أصوات مزعجة.  
22- يجب الحفاظ على بيئة لعب محترمة.  
23- يمنع استغلال اللاعبين الجدد.  
24- يمنع تعطيل الفعاليات.  
25- يمنع إثارة المشاكل داخل السيرفر.  
26- يجب الالتزام بالتعليمات أثناء الأحداث.  
27- يمنع إفساد الرول بلاي.  
28- يجب احترام القوانين في جميع الأوقات.  
29- يمنع تخريب ممتلكات اللاعبين بدون سبب.  
30- يمنع الهروب من السيناريو بدون سبب.  
31- يمنع استخدام شخصيات غير واقعية.  
32- يمنع تمثيل أفعال غير ممكنة في الواقع.  
33- يجب احترام قوانين السيرفر دائمًا.  
34- يمنع السخرية من اللاعبين.  
35- يمنع نشر معلومات خاصة باللاعبين.  
36- يمنع تعطيل اللعب الجماعي.  
37- يجب التعامل بواقعية داخل السيناريو.  
38- يمنع تكرار المخالفات.  
39- يجب الحفاظ على روح اللعب النظيف.  
40- مخالفة القوانين قد تؤدي إلى تحذير أو حظر دائم من السيرفر.

</div>
</div>

<div class="rule" onclick="toggle(this)">
قانون NLR
<div class="content">
يعني عندما تموت شخصيتك داخل اللعبة تبدأ حياة جديدة ولا يمكنك تذكر الأحداث السابقة أو الانتقام من الشخص الذي تسبب في موتك.
</div>
</div>

<div class="rule" onclick="toggle(this)">
PowerGaming
<div class="content">
هو القيام بأفعال غير واقعية أو إجبار لاعب آخر على فعل شيء بدون إعطائه فرصة للتفاعل.
</div>
</div>

<div class="rule" onclick="toggle(this)">
Metagaming
<div class="content">
استخدام معلومات خارج اللعبة مثل الديسكورد أو البث داخل الرول بلاي.
</div>
</div>

<div class="rule" onclick="toggle(this)">
RDM
<div class="content">
قتل اللاعبين بدون سبب واضح أو بدون سيناريو رول بلاي.
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
