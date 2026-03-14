<!DOCTYPE html>
<html lang="ku" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>سۆشیاڵ میدیاکانم</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Arabic:wght@400;700;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
/* ڕێکخستنی گشتی و فۆنت */
* {
box-sizing: border-box;
margin: 0;
padding: 0;
font-family: 'Noto Sans Arabic', sans-serif;
}
/* باکگراوەندی ئەنیمەیشنی جووڵاو */
body {
display: flex;
justify-content: center;
align-items: center;
min-height: 100vh;
background: linear-gradient(-45deg, #1a0b2e, #4b134f, #0f2027, #203a43);
background-size: 400% 400%;
animation: gradientBG 15s ease infinite;
color: #fff;
overflow: hidden;
}
@keyframes gradientBG {
0% { background-position: 0% 50%; }
50% { background-position: 100% 50%; }
100% { background-position: 0% 50%; }
}
/* بۆکسی سەرەکی (شووشەیی و مۆدێرن) */
.container {
background: rgba(255, 255, 255, 0.05);
backdrop-filter: blur(20px);
-webkit-backdrop-filter: blur(20px);
border: 1px solid rgba(255, 255, 255, 0.1);
padding: 40px 30px;
border-radius: 25px;
text-align: center;
width: 90%;
max-width: 400px;
box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
animation: fadeIn 1.5s ease;
}
@keyframes fadeIn {
from { opacity: 0; transform: translateY(20px); }
to { opacity: 1; transform: translateY(0); }
}
/* ناونیشانەکان */
h1 {
font-weight: 900;
font-size: 1.8rem;
margin-bottom: 5px;
background: linear-gradient(to right, #ff8a00, #e52e71);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
letter-spacing: 2px;
}
p {
font-size: 1.1rem;
color: #c8c8c8;
margin-bottom: 30px;
font-weight: 700;
}
/* بەستەرەکان */
.links-wrapper {
display: flex;
flex-direction: column;
gap: 15px;
}
.link-card {
display: flex;
align-items: center;
justify-content: space-between;
background: rgba(255, 255, 255, 0.08);
color: #fff;
padding: 15px 25px;
border-radius: 15px;
text-decoration: none;
font-weight: 700;
font-size: 1.1rem;
cursor: pointer;
transition: all 0.4s ease;
border: 1px solid rgba(255, 255, 255, 0.05);
position: relative;
overflow: hidden;
}
/* کاریگەری کاتی چوونە سەر لینکەکان */
.link-card:hover {
transform: translateY(-5px) scale(1.02);
background: rgba(255, 255, 255, 0.15);
box-shadow: 0 10px 20px rgba(0,0,0,0.3);
border-color: rgba(255, 255, 255, 0.4);
}
/* ڕەنگکردنی لۆگۆکان کاتی چوونەسەریان */
.link-card:hover .fa-tiktok { color: #25F4EE; text-shadow: 0 0 10px #25F4EE; }
.link-card:hover .fa-telegram { color: #0088cc; text-shadow: 0 0 10px #0088cc; }
.link-card:hover .fa-snapchat { color: #FFFC00; text-shadow: 0 0 10px #FFFC00; }
.link-card:hover .fa-facebook { color: #1877F2; text-shadow: 0 0 10px #1877F2; }
.link-card i:first-child {
font-size: 1.6rem;
width: 35px;
transition: all 0.3s ease;
}
.link-card span {
flex-grow: 1;
text-align: right;
padding-right: 15px;
}
.link-card .arrow {
font-size: 0.9rem;
opacity: 0.5;
transition: opacity 0.3s;
}
.link-card:hover .arrow { opacity: 1; color: #ff8a00; }
/* نامەی ئاگادارکردنەوەی زۆر جوان (Toast) */
.toast-notification {
position: fixed;
top: -300px;
left: 50%;
transform: translateX(-50%);
background: linear-gradient(135deg, #ff416c, #ff4b2b);
color: white;
padding: 15px 30px;
border-radius: 50px;
font-weight: 700;
box-shadow: 0 10px 30px rgba(255, 75, 43, 0.4);
transition: top 0.5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
z-index: 1000;
display: flex;
align-items: center;
gap: 10px;
}
.toast-notification.show { top: 30px; }
</style>
</head>
<body>
<div id="toast" class="toast-notification">
<i class="fas fa-exclamation-circle"></i>
<span>ببورە، ئەم لینکە جارێ بەردەست نییە!</span>
</div>
<div class="container">
<h1>بــــــەخـــــێـــــر بــــێــــیــــــت</h1>
<p>سۆشیاڵ میدیاکانم</p>
<div class="links-wrapper">
<a href="https://www.tiktok.com/@binar.tech01?_r=1&_t=ZS-94gq4fXX2fp" target="_blank" class="link-card">
<i class="fab fa-tiktok"></i>
<span>تیکتۆک</span>
<i class="fas fa-chevron-left arrow"></i>
</a>
<a href="https://t.me/+tiX7AblCtPZlZGFi" target="_blank" class="link-card">
<i class="fab fa-telegram"></i>
<span>تێلیگرام</span>
<i class="fas fa-chevron-left arrow"></i>
</a>
<a href="https://www.snapchat.com/add/binar.tech?share_id=6WXOJHsIe7s&locale=en-GB" target="_blank" class="link-card">
<i class="fab fa-snapchat"></i>
<span>سناپ چات</span>
<i class="fas fa-chevron-left arrow"></i>
</a>
<div onclick="showToast()" class="link-card">
<i class="fab fa-facebook"></i>
<span>فەیسبووک</span>
<i class="fas fa-lock arrow" style="font-size: 0.7rem;"></i>
</div>
</div>
</div>
<script>
let toastTimer;
function showToast() {
const toast = document.getElementById("toast");
clearTimeout(toastTimer);
toast.classList.add("show");
toastTimer = setTimeout(() => {
toast.classList.remove("show");
}, 3000);
}
</script>
</body>
</html>
