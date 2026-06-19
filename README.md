<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Biyaherong Chess Coach Academy</title>

<style>

:root{
--bg:#0f172a;
--card:#1e293b;
--green:#22c55e;
--text:#ffffff;
--muted:#cbd5e1;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,sans-serif;
}

body{
background:var(--bg);
color:var(--text);
}

header{
text-align:center;
padding:70px 20px;
background:linear-gradient(135deg,#1e293b,#0f172a);
}

header h1{
font-size:3rem;
}

header p{
margin-top:10px;
color:var(--muted);
}

.btn{
display:inline-block;
margin-top:20px;
padding:12px 24px;
background:var(--green);
border-radius:12px;
color:white;
text-decoration:none;
font-weight:bold;
}

nav{
position:sticky;
top:0;
background:#111827;
display:flex;
justify-content:center;
gap:20px;
padding:15px;
z-index:1000;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

nav a:hover{
color:var(--green);
}

.section{
padding:50px 20px;
}

.section h2{
text-align:center;
margin-bottom:25px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

.card{
background:var(--card);
padding:20px;
border-radius:15px;
transition:.3s;
}

.card:hover{
transform:translateY(-5px);
}

.video-container{
position:relative;
width:100%;
padding-bottom:56.25%;
overflow:hidden;
border-radius:10px;
}

.video-container iframe{
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
border:none;
}

.roadmap{
max-width:800px;
margin:auto;
}

.step{
background:var(--card);
padding:15px;
margin:10px 0;
border-radius:10px;
}

footer{
text-align:center;
padding:40px;
color:#94a3b8;
}

</style>
</head>
<body>

<header>

<h1>🚍 Biyaherong Chess Coach Academy</h1>

<p>
Learn Chess From Beginner to Advanced
</p>

<a href="#videos" class="btn">
Start Learning ♟️
</a>

</header>

<nav>

<a href="#roadmap">Roadmap</a>
<a href="#videos">Videos</a>
<a href="#tagalog">Tagalog</a>
<a href="#puzzles">Puzzles</a>
<a href="#ai">Play AI</a>

</nav>

<section id="roadmap" class="section">

<h2>🛤️ Learning Roadmap</h2>

<div class="roadmap">

<div class="step">1️⃣ Chess Basics</div>
<div class="step">2️⃣ Piece Movement</div>
<div class="step">3️⃣ Special Moves</div>
<div class="step">4️⃣ Checkmate Patterns</div>
<div class="step">5️⃣ Basic Tactics</div>
<div class="step">6️⃣ Opening Principles</div>
<div class="step">7️⃣ Middlegame Strategy</div>
<div class="step">8️⃣ Endgame Mastery</div>
<div class="step">9️⃣ Positional Play</div>
<div class="step">🔟 Advanced Tournament Play</div>

</div>

</section>

<section id="videos" class="section">

<h2>🎥 Featured Chess Tutorials</h2>

<div class="grid">

<div class="card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/NAIQyoPcjNM"
allowfullscreen>
</iframe>

</div>

<h3>Chess Basics</h3>

</div>

<div class="card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/OCSbzArwB10"
allowfullscreen>
</iframe>

</div>

<h3>Beginner Guide</h3>

</div>

<div class="card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/mtsabsZ4wG4"
allowfullscreen>
</iframe>

</div>

<h3>Opening Principles</h3>

</div>

</div>

</section>

<section id="tagalog" class="section">

<h2>🇵🇭 Tagalog Tutorials</h2>

<div class="grid">

<div class="card">

<h3>🚍 Biyaherong Chess Coach</h3>

<p>
Add your embedded Tagalog videos here.
</p>

</div>

<div class="card">

<h3>♟️ Filipino Chess Lessons</h3>

<p>
Beginner friendly lessons in Tagalog.
</p>

</div>

</div>

</section>

<section id="puzzles" class="section">

<h2>🧩 Daily Puzzle</h2>

<div class="card">

<h3>Mate in 1</h3>

<p>
White to move and checkmate.
</p>

<button class="btn">
Solve Puzzle
</button>

</div>

</section>

<section id="ai" class="section">

<h2>🤖 Play vs AI</h2>

<div class="card">

<h3>Practice Mode</h3>

<p>
Play against beginner, intermediate,
or advanced AI opponents.
</p>

<button class="btn">
Play Now
</button>

</div>

</section>

<section class="section">

<h2>🏆 Achievements</h2>

<div class="grid">

<div class="card">🥉 First Win</div>
<div class="card">🥈 Puzzle Solver</div>
<div class="card">🥇 Checkmate Master</div>
<div class="card">👑 Grandmaster Path</div>

</div>

</section>

<footer>

♟️ Biyaherong Chess Coach Academy

<br>

Learn • Practice • Improve

</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🚍 Biyaherong Chess Coach Academy</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:white;
}

header{
    background:linear-gradient(135deg,#1e293b,#0f172a);
    text-align:center;
    padding:70px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:10px;
}

header p{
    color:#cbd5e1;
}

nav{
    position:sticky;
    top:0;
    background:#111827;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:15px;
    padding:15px;
    z-index:1000;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

nav a:hover{
    color:#22c55e;
}

.section{
    padding:50px 20px;
}

.section h2{
    text-align:center;
    margin-bottom:25px;
}

.roadmap{
    max-width:800px;
    margin:auto;
}

.step{
    background:#1e293b;
    margin:10px 0;
    padding:15px;
    border-radius:12px;
    border-left:5px solid #22c55e;
}

.video-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:20px;
}

.video-card{
    background:#1e293b;
    border-radius:15px;
    overflow:hidden;
    transition:.3s;
}

.video-card:hover{
    transform:translateY(-4px);
}

.video-card h3{
    padding:15px;
}

.video-card p{
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
    top:0;
    left:0;
    width:100%;
    height:100%;
    border:none;
}

.tagalog-card{
    background:#1e293b;
    padding:20px;
    border-radius:15px;
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
}

@media(max-width:768px){

header h1{
    font-size:2rem;
}

.video-grid{
    grid-template-columns:1fr;
}

}
</style>
</head>

<body>

<header>

<h1>🚍 Biyaherong Chess Coach Academy</h1>

<p>
Learn Chess from Beginner to Advanced
</p>

</header>

<nav>

<a href="#roadmap">♟️ Roadmap</a>
<a href="#coach">🚍 Coach</a>
<a href="#tagalog">🇵🇭 Tagalog</a>
<a href="#videos">🎥 Videos</a>

</nav>

<!-- ROADMAP -->

<section id="roadmap" class="section">

<h2>♟️ Beginner → Advanced Roadmap</h2>

<div class="roadmap">

<div class="step">1️⃣ Chess Basics</div>

<div class="step">2️⃣ Board Setup & Rules</div>

<div class="step">3️⃣ Piece Movement</div>

<div class="step">4️⃣ Special Moves (Castling, Promotion, En Passant)</div>

<div class="step">5️⃣ Check & Checkmate</div>

<div class="step">6️⃣ Basic Tactics (Forks, Pins, Skewers)</div>

<div class="step">7️⃣ Opening Principles</div>

<div class="step">8️⃣ Middlegame Planning</div>

<div class="step">9️⃣ Endgame Fundamentals</div>

<div class="step">🔟 Advanced Positional Strategy</div>

<div class="step">🏆 Tournament Preparation</div>

</div>

</section>

<!-- BIYAHERONG CHESS COACH -->

<section id="coach" class="section">

<h2>🚍 Biyaherong Chess Coach</h2>

<div class="video-grid">

<div class="video-card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/NAIQyoPcjNM"
title="Chess Tutorial"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
allowfullscreen>
</iframe>

</div>

<h3>Chess Basics</h3>

<p>Perfect for absolute beginners.</p>

</div>

<div class="video-card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/OCSbzArwB10"
title="Beginner Chess"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
allowfullscreen>
</iframe>

</div>

<h3>Beginner Lesson</h3>

<p>Learn the fundamentals.</p>

</div>

</div>

</section>

<!-- TAGALOG -->

<section id="tagalog" class="section">

<h2>🇵🇭 Free Tagalog Chess Tutorials</h2>

<div class="video-grid">

<div class="tagalog-card">

<h3>🎓 Chess Basics in Tagalog</h3>

<p>
Add your Biyaherong Chess Coach Tagalog video embed here.
</p>

</div>

<div class="tagalog-card">

<h3>♟️ Tactics in Tagalog</h3>

<p>
Forks, Pins, Skewers explained in Filipino.
</p>

</div>

<div class="tagalog-card">

<h3>🏆 Advanced Strategy in Tagalog</h3>

<p>
Improve your tournament skills.
</p>

</div>

</div>

</section>

<!-- VIDEO GALLERY -->

<section id="videos" class="section">

<h2>🎥 Chess Video Gallery</h2>

<div class="video-grid">

<div class="video-card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/mtsabsZ4wG4"
title="Opening Principles"
allowfullscreen>
</iframe>

</div>

<h3>Opening Principles</h3>

</div>

<div class="video-card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/Ao9iOeK_jvU"
title="Chess Tactics"
allowfullscreen>
</iframe>

</div>

<h3>Basic Tactics</h3>

</div>

<div class="video-card">

<div class="video-container">

<iframe
src="https://www.youtube.com/embed/Esi5jgWEPw4"
title="Advanced Chess"
allowfullscreen>
</iframe>

</div>

<h3>Advanced Strategy</h3>

</div>

</div>

</section>

<footer>

♟️ Biyaherong Chess Coach Academy

<br>

Learn • Practice • Improve

</footer>

</body>
</html>
