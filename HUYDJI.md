/* ACHIEVEMENT */

.stats{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:30px;
margin-top:70px;
}

.stat-box{
background:rgba(255,255,255,.03);
padding:50px;
border-radius:28px;
text-align:center;
border:1px solid rgba(255,255,255,.08);
}

.stat-box h3{
font-size:50px;
color:var(--gold);
margin-bottom:10px;
}

.stat-box p{
color:#aaa;
}

/* CONTACT */

.contact{
position:relative;
text-align:center;
padding:140px 8%;
}

.contact::before{
content:'';
position:absolute;
inset:0;
background:
linear-gradient(rgba(0,0,0,.82),rgba(0,0,0,.92)),
url('images/media-bg.jpg') center/cover fixed;
z-index:-1;
}

.contact-buttons{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:40px;
}

.contact-btn{
padding:18px 35px;
border-radius:60px;
background:rgba(255,255,255,.06);
border:1px solid rgba(255,255,255,.1);
color:#fff;
text-decoration:none;
font-weight:700;
transition:.4s;
}

.contact-btn:hover{
background:var(--gold);
color:#000;
transform:translateY(-8px);
}

/* FOOTER */

footer{
padding:35px;
text-align:center;
background:#050505;
color:#777;
border-top:1px solid rgba(255,255,255,.08);
}

/* MOBILE */

@media(max-width:991px){

.hero{
flex-direction:column;
padding-top:150px;
text-align:center;
}

.hero h1{
font-size:50px;
}

.hero-image{
width:100%;
height:500px;
}

.about{
grid-template-columns:1fr;
}

.portfolio-grid{
grid-template-columns:1fr;
}

.stats{
grid-template-columns:1fr;
}

nav{
display:none;
}

.section-title h2{
font-size:38px;
}
}

</style>
</head>

<body>

<header>
<div class="logo">HUYDJI MEDIA</div>

<nav>
<a href="#">Trang Chủ</a>
<a href="#about">Giới Thiệu</a>
<a href="#services">Dịch Vụ</a>
<a href="#portfolio">Dự Án</a>
<a href="#contact">Liên Hệ</a>
</nav>
</header>

<section class="hero">

<div class="hero-content">
<div class="hero-sub">
MEDIA PRODUCTION
</div>

<h1>
HUYDJI<br>MEDIA
</h1>

<p>
Wedding • Event • Flycam • Cinematic Production
Đơn vị media chuyên nghiệp tại Bắc Ninh, tạo nên hình ảnh cinematic cao cấp cho thương hiệu, sự kiện và đám cưới.
</p>

<div class="hero-buttons">
<a href="#portfolio" class="btn btn-primary">
Xem Dự Án
</a>

<a href="#contact" class="btn btn-outline">
Liên Hệ Ngay
</a>
</div>
</div>

<div class="hero-image">
<img src="images/hero.jpg">
</div>

</section>

<section id="about">

<div class="section-title">
<h2>Về <span>HUYDJI MEDIA</span></h2>
<p>Media chuyên nghiệp • Hình ảnh cinematic cao cấp</p>
</div>

<div class="about">

<div class="about-image">
<img src="images/stage.jpg">
</div>

<div class="about-text">
<h3>Top Media Wedding & Event Bắc Ninh</h3>

<p>
HUYDJI MEDIA chuyên sản xuất hình ảnh cinematic chuyên nghiệp trong lĩnh vực Wedding, Event, Flycam DJI và video truyền thông.
</p>

<p>
Tập trung vào sự chỉn chu, sáng tạo và cảm xúc chân thật để mang tới những thước phim đẳng cấp premium.
</p>
</div>

</div>

</section>

<section id="services">

<div class="section-title">
<h2>Dịch Vụ <span>Nổi Bật</span></h2>
</div>

<div class="services-grid">

<div class="card">
<h3>Wedding Media</h3>
<p>Quay cưới cinematic sang trọng, cảm xúc và hiện đại.</p>
</div>

<div class="card">
<h3>Event Production</h3>
<p>Sản xuất media sự kiện chuyên nghiệp.</p>
</div>

<div class="card">
<h3>Flycam DJI</h3>
<p>Footage cinematic trên không chất lượng cao.</p>
</div>

<div class="card">
<h3>Edit Video Viral</h3>
<p>Video TikTok, Reels, Shorts chuẩn xu hướng.</p>
</div>

</div>

</section>

<section id="portfolio">

<div class="section-title">
<h2>Dự Án <span>Nổi Bật</span></h2>
</div>

<div class="portfolio-grid">

<div class="portfolio-item">
<img src="images/hero.jpg">
<div class="overlay">
<h4>Luxury Portrait</h4>
<p>Fashion Media</p>
</div>
</div>

<div class="portfolio-item">
<img src="images/stage.jpg">
<div class="overlay">
<h4>Stage Production</h4>
<p>Media Event</p>
</div>
</div>

<div class="portfolio-item">
<img src="images/wedding.jpg">
<div class="overlay">
<h4>Wedding Media</h4>
<p>Premium Wedding</p>
</div>
</div>

<div class="portfolio-item">
<img src="images/avatar.png">
<div class="overlay">
<h4>Director</h4>
<p>HUYDJI MEDIA</p>
</div>
</div>

</div>

<div class="stats">

<div class="stat-box">
<h3>100+</h3>
<p>Dự Án</p>
</div>

<div class="stat-box">
<h3>1000+</h3>
<p>Khách Hàng</p>
</div>

<div class="stat-box">
<h3>24/7</h3>
<p>Hỗ Trợ</p>
</div>

</div>

</section>

<section class="contact" id="contact">

<div class="section-title">
<h2>Liên Hệ <span>Ngay</span></h2>
<p>Kết nối HUYDJI MEDIA</p>
</div>

<div class="contact-buttons">

<a href="https://www.tiktok.com/@huydjimini2" class="contact-btn">
TikTok
</a>

<a href="https://zalo.me/0337846894" class="contact-btn">
Zalo
</a>

<a href="tel:0337846894" class="contact-btn">
Hotline
</a>

</div>

</section>

<footer>
© 2026 HUYDJI MEDIA — Cinematic Production
</footer>

</body>
</html>
/* ACHIEVEMENT */

.stats{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:30px;
margin-top:70px;
}

.stat-box{
background:rgba(255,255,255,.03);
padding:50px;
border-radius:28px;
text-align:center;
border:1px solid rgba(255,255,255,.08);
}

.stat-box h3{
font-size:50px;
color:var(--gold);
margin-bottom:10px;
}

.stat-box p{
color:#aaa;
}

/* CONTACT */

.contact{
position:relative;
text-align:center;
padding:140px 8%;
}

.contact::before{
content:'';
position:absolute;
inset:0;
background:
linear-gradient(rgba(0,0,0,.82),rgba(0,0,0,.92)),
url('images/media-bg.jpg') center/cover fixed;
z-index:-1;
}

.contact-buttons{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:40px;
}

.contact-btn{
padding:18px 35px;
border-radius:60px;
background:rgba(255,255,255,.06);
border:1px solid rgba(255,255,255,.1);
color:#fff;
text-decoration:none;
font-weight:700;
transition:.4s;
}

.contact-btn:hover{
background:var(--gold);
color:#000;
transform:translateY(-8px);
}

/* FOOTER */

footer{
padding:35px;
text-align:center;
background:#050505;
color:#777;
border-top:1px solid rgba(255,255,255,.08);
}

/* MOBILE */

@media(max-width:991px){

.hero{
flex-direction:column;
padding-top:150px;
text-align:center;
}

.hero h1{
font-size:50px;
}

.hero-image{
width:100%;
height:500px;
}

.about{
grid-template-columns:1fr;
}

.portfolio-grid{
grid-template-columns:1fr;
}

.stats{
grid-template-columns:1fr;
}

nav{
display:none;
}

.section-title h2{
font-size:38px;
}
}

</style>
</head>

<body>

<header>
<div class="logo">HUYDJI MEDIA</div>

<nav>
<a href="#">Trang Chủ</a>
<a href="#about">Giới Thiệu</a>
<a href="#services">Dịch Vụ</a>
<a href="#portfolio">Dự Án</a>
<a href="#contact">Liên Hệ</a>
</nav>
</header>

<section class="hero">

<div class="hero-content">
<div class="hero-sub">
MEDIA PRODUCTION
</div>

<h1>
HUYDJI<br>MEDIA
</h1>

<p>
Wedding • Event • Flycam • Cinematic Production
Đơn vị media chuyên nghiệp tại Bắc Ninh, tạo nên hình ảnh cinematic cao cấp cho thương hiệu, sự kiện và đám cưới.
</p>

<div class="hero-buttons">
<a href="#portfolio" class="btn btn-primary">
Xem Dự Án
</a>

<a href="#contact" class="btn btn-outline">
Liên Hệ Ngay
</a>
</div>
</div>

<div class="hero-image">
<img src="images/hero.jpg">
</div>

</section>

<section id="about">

<div class="section-title">
<h2>Về <span>HUYDJI MEDIA</span></h2>
<p>Media chuyên nghiệp • Hình ảnh cinematic cao cấp</p>
</div>

<div class="about">

<div class="about-image">
<img src="images/stage.jpg">
</div>

<div class="about-text">
<h3>Top Media Wedding & Event Bắc Ninh</h3>

<p>
HUYDJI MEDIA chuyên sản xuất hình ảnh cinematic chuyên nghiệp trong lĩnh vực Wedding, Event, Flycam DJI và video truyền thông.
</p>

<p>
Tập trung vào sự chỉn chu, sáng tạo và cảm xúc chân thật để mang tới những thước phim đẳng cấp premium.
</p>
</div>

</div>

</section>

<section id="services">

<div class="section-title">
<h2>Dịch Vụ <span>Nổi Bật</span></h2>
</div>

<div class="services-grid">

<div class="card">
<h3>Wedding Media</h3>
<p>Quay cưới cinematic sang trọng, cảm xúc và hiện đại.</p>
</div>

<div class="card">
<h3>Event Production</h3>
<p>Sản xuất media sự kiện chuyên nghiệp.</p>
</div>

<div class="card">
<h3>Flycam DJI</h3>
<p>Footage cinematic trên không chất lượng cao.</p>
</div>

<div class="card">
<h3>Edit Video Viral</h3>
<p>Video TikTok, Reels, Shorts chuẩn xu hướng.</p>
</div>

</div>

</section>

<section id="portfolio">

<div class="section-title">
<h2>Dự Án <span>Nổi Bật</span></h2>
</div>

<div class="portfolio-grid">

<div class="portfolio-item">
<img src="images/hero.jpg">
<div class="overlay">
<h4>Luxury Portrait</h4>
<p>Fashion Media</p>
</div>
</div>

<div class="portfolio-item">
<img src="images/stage.jpg">
<div class="overlay">
<h4>Stage Production</h4>
<p>Media Event</p>
</div>
</div>

<div class="portfolio-item">
<img src="images/wedding.jpg">
<div class="overlay">
<h4>Wedding Media</h4>
<p>Premium Wedding</p>
</div>
</div>

<div class="portfolio-item">
<img src="images/avatar.png">
<div class="overlay">
<h4>Director</h4>
<p>HUYDJI MEDIA</p>
</div>
</div>

</div>

<div class="stats">

<div class="stat-box">
<h3>100+</h3>
<p>Dự Án</p>
</div>

<div class="stat-box">
<h3>1000+</h3>
<p>Khách Hàng</p>
</div>

<div class="stat-box">
<h3>24/7</h3>
<p>Hỗ Trợ</p>
</div>

</div>

</section>

<section class="contact" id="contact">

<div class="section-title">
<h2>Liên Hệ <span>Ngay</span></h2>
<p>Kết nối HUYDJI MEDIA</p>
</div>

<div class="contact-buttons">

<a href="https://www.tiktok.com/@huydjimini2" class="contact-btn">
TikTok
</a>

<a href="https://zalo.me/0337846894" class="contact-btn">
Zalo
</a>

<a href="tel:0337846894" class="contact-btn">
Hotline
</a>

</div>

</section>

<footer>
© 2026 HUYDJI MEDIA — Cinematic Production
</footer>

</body>
</html>
