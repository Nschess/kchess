<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Biyaherong Chess Coach</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Segoe UI,sans-serif;
}

body{
    background:#0f172a;
    color:white;
}

header{
    text-align:center;
    padding:60px 20px;
    background:linear-gradient(135deg,#1e293b,#0f172a);
}

header h1{
    font-size:3rem;
}

header p{
    margin-top:10px;
    color:#cbd5e1;
}

.start-btn{
    margin-top:20px;
    display:inline-block;
    background:#22c55e;
    color:white;
    padding:12px 24px;
    border-radius:12px;
    text-decoration:none;
    font-weight:bold;
}

.stats{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
    padding:20px;
}

.card{
    background:#1e293b;
    padding:20px;
    border-radius:15px;
    min-width:180px;
    text-align:center;
}

.section-title{
    text-align:center;
    margin:50px 0 20px;
}

.lesson-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
    padding:20px;
}

.lesson{
    background:#1e293b;
    border-radius:15px;
    overflow:hidden;
    transition:.3s;
}

.lesson:hover{
    transform:translateY(-5px);
}

.lesson h3{
    padding:15px;
}

.lesson p{
    padding:0 15px 15px;
    color:#cbd5e1;
}

.video-container{
    position:relative;
    width:100%;
    padding-bottom:56.25%;
}

.video-container iframe{
    position:absolute;
    width:100%;
    height:100%;
    left:0;
    top:0;
    border:none;
}

.path{
    max-width:900px;
    margin:auto;
    padding:20px;
}

.path-item{
    background:#1e293b;
    margin:10px 0;
    padding:15px;
    border-radius:10px;
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
}

</style>
</head>
<body>

<header>

<h1>🚍 Biyaherong Chess Coach</h1>

<p>Learn Chess From Beginner to Advanced</p>

<a href="#videos" class="start-btn">
Start Learning ♟️
</a>

</header>

<div class="stats">

<div class="card">
<h2>10</h2>
<p>Video Lessons</p>
</div>

<div class="card">
<h2>100+</h2>
<p>Puzzles</p>
</div>

<div class="card">
<h2>5</h2>
<p>Learning Paths</p>
</div>

</div>

<h2 class="section-title">
🛤️ Learning Path
</h2>

<div class="path">

<div class="path-item">1️⃣ Chess Basics</div>
<div class="path-item">2️⃣ Piece Movement</div>
<div class="path-item">3️⃣ Special Moves</div>
<div class="path-item">4️⃣ Tactics</div>
<div class="path-item">5️⃣ Checkmates</div>
<div class="path-item">6️⃣ Openings</div>
<div class="path-item">7️⃣ Middlegame</div>
<div class="path-item">8️⃣ Endgame</div>
<div class="path-item">9️⃣ Strategy</div>
<div class="path-item">🔟 Advanced Play</div>

</div>

<h2 id="videos" class="section-title">
🎥 Biyaherong Chess Coach Tutorials
</h2>

<div class="lesson-grid">

<!-- Replace VIDEO_ID values -->

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_1"
allowfullscreen
loading="lazy"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
</iframe>
</div>
<h3>Lesson 1 - Chess Basics</h3>
<p>Introduction to chess.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_2"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 2 - Piece Movement</h3>
<p>Learn how pieces move.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_3"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 3 - Special Moves</h3>
<p>Castling, promotion, en passant.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_4"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 4 - Tactics</h3>
<p>Forks, pins, skewers.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_5"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 5 - Checkmate Patterns</h3>
<p>Winning combinations.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_6"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 6 - Opening Principles</h3>
<p>Strong opening habits.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_7"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 7 - Middlegame</h3>
<p>Attack and defense.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_8"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 8 - Endgame</h3>
<p>Convert winning positions.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_9"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 9 - Strategy</h3>
<p>Think several moves ahead.</p>
</div>

<div class="lesson">
<div class="video-container">
<iframe src="https://www.youtube.com/embed/VIDEO_ID_10"
allowfullscreen
loading="lazy">
</iframe>
</div>
<h3>Lesson 10 - Advanced Play</h3>
<p>Tournament-level concepts.</p>
</div>

</div>

<footer>
♟️ Biyaherong Chess Coach • Learn Anywhere • Play Anywhere
</footer>

</body>
</html>
