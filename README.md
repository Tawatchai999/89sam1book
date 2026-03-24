<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>89sam1book</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>89sam1book</h1>
<p>เข้าใจตัวเองในแบบที่คุณไม่เคยรู้มาก่อน</p>
<button onclick="toggleMode()">🌙 Dark Mode</button>
<a class="btn" onclick="showPage('chapters')">📖 เริ่มอ่าน</a>
</header>

<!-- HOME -->
<div id="home" class="section">
<h2>🧠 Psychebook คืออะไร</h2>
<p>หนังสือจิตวิทยาที่ช่วยให้คุณเข้าใจความคิด อารมณ์ และตัวตนของตัวเอง</p>

<h3>🔥 Highlights</h3>
<ul>
<li>เข้าใจตัวเองลึกขึ้น</li>
<li>จัดการอารมณ์ได้</li>
<li>อ่านง่าย ใช้ได้จริง</li>
</ul>
</div>

<!-- CHAPTERS -->
<div id="chapters" class="section" style="display:none">
<h2>📖 Chapters</h2>

<div class="card" onclick="showPage('c1')">
<h3>Chapter 1</h3>
<p>ทำไมเราคิดมาก</p>
</div>

<div class="card" onclick="showPage('c2')">
<h3>Chapter 2</h3>
<p>วงจรของอารมณ์</p>
</div>

<h3>🎬 วิดีโอแนะนำ</h3>
<iframe width="100%" height="200" src="https://www.youtube.com/embed/4WXs3sKu41I" frameborder="0" allowfullscreen></iframe>
</div>

<!-- CHAPTER 1 -->
<div id="c1" class="section" style="display:none">
<h2>ทำไมเราคิดมาก</h2>
<p>คุณไม่ได้คิดมากเกินไป แต่คุณ “หยุดคิดไม่ได้”</p>

<h3>🧠 คำถาม</h3>
<p>คุณคิดเรื่องอะไรซ้ำ ๆ ?</p>
<textarea placeholder="พิมพ์ reflection ของคุณ..."></textarea>

<button onclick="showPage('chapters')">← กลับ</button>
</div>

<!-- CHAPTER 2 -->
<div id="c2" class="section" style="display:none">
<h2>วงจรของอารมณ์</h2>
<p>อารมณ์มาแล้วก็ไป แต่การตอบสนองคือสิ่งสำคัญ</p>

<h3>🧠 คำถาม</h3>
<p>คุณตอบสนองอารมณ์ยังไง?</p>
<textarea placeholder="พิมพ์ reflection ของคุณ..."></textarea>

<button onclick="showPage('chapters')">← กลับ</button>
</div>

<!-- ABOUT -->
<div class="section">
<h2>👤 About</h2>
<p>ผมสร้าง Psychebook เพื่อช่วยให้คนเข้าใจตัวเองและใช้ชีวิตได้ดีขึ้น</p>
</div>

<!-- CTA + Email -->
<div class="section">
<h2>🚀 สมัคร / ดาวน์โหลด / ติดตาม</h2>
<form action="https://formspree.io/f/your-id" method="POST">
<input type="email" name="email" placeholder="ใส่อีเมล">
<button type="submit">สมัคร</button>
</form>
</div>

<!-- SOCIAL -->
<div class="section">
<h2>🌍 ติดตามเรา</h2>
<div class="social">
<a href="https://www.linkedin.com/in/sam-phongphaew-ab2111347" target="_blank">LinkedIn</a>
<a href="https://www.youtube.com/@Ebook1book" target="_blank">YouTube</a>
<a href="https://www.facebook.com/" target="_blank">Facebook</a>
<a href="https://www.instagram.com/" target="_blank">Instagram</a>
<a href="https://www.tiktok.com/" target="_blank">TikTok</a>
<a href="https://wa.me/" target="_blank">WhatsApp</a>
<a href="https://www.twitter.com/" target="_blank">Twitter</a>
</div>

<h3 style="margin-top:30px;">📖 เว็บไซต์หลัก</h3>
<p style="text-align:center;">
<a href="https://tawatchai999.github.io/89sam1book" target="_blank">👉 เข้าอ่าน Psychebook</a>
</p>
</div>

<script src="script.js"></script>
</body>
</html>