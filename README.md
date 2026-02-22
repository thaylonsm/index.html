# index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Velora Protocol</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
  font-family:'Inter',sans-serif;
  background:linear-gradient(to bottom,#000,#0a0a0a);
  color:#fff;
}
header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:20px 40px;
  border-bottom:1px solid #222;
}
header h1{font-size:24px;font-weight:800}
nav a{
  margin-left:20px;
  text-decoration:none;
  color:#aaa;
}
nav a:hover{color:#fff}
.hero{
  text-align:center;
  padding:120px 20px;
}
.hero h2{
  font-size:48px;
  font-weight:800;
  margin-bottom:20px;
}
.hero p{
  color:#aaa;
  max-width:700px;
  margin:0 auto 40px;
}
.btn{
  padding:14px 28px;
  border-radius:12px;
  text-decoration:none;
  font-weight:600;
  margin:10px;
  display:inline-block;
}
.primary{
  background:#fff;
  color:#000;
}
.outline{
  border:1px solid #fff;
  color:#fff;
}
.section{
  padding:100px 20px;
  text-align:center;
}
.features{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:30px;
  padding:80px 40px;
  max-width:1100px;
  margin:auto;
}
.card{
  background:#111;
  padding:30px;
  border-radius:16px;
}
.card h3{margin-bottom:10px}
.card p{color:#aaa;font-size:14px}
footer{
  text-align:center;
  padding:40px;
  border-top:1px solid #222;
  color:#666;
}
</style>
</head>
<body>

<header>
  <h1>Velora</h1>
  <nav>
    <a href="#technology">Technology</a>
    <a href="#developers">Developers</a>
    <a href="#governance">Governance</a>
  </nav>
</header>

<section class="hero">
  <h2>Sustainable BFT Infrastructure</h2>
  <p>No mining. No inflation. Deterministic finality powered by three-phase Byzantine consensus.</p>
  <a href="#technology" class="btn primary">Explore Technology</a>
  <a href="#developers" class="btn outline">Run a Node</a>
</section>

<section class="features">
  <div class="card">
    <h3>BFT Security</h3>
    <p>2/3 validator deterministic finality.</p>
  </div>
  <div class="card">
    <h3>Energy Efficient</h3>
    <p>Validator-based architecture.</p>
  </div>
  <div class="card">
    <h3>Deflationary</h3>
    <p>Fee burn mechanism.</p>
  </div>
  <div class="card">
    <h3>Sustainable</h3>
    <p>Rewards from real demand only.</p>
  </div>
</section>

<section id="technology" class="section">
  <h2>Technology</h2>
  <p style="color:#aaa;max-width:700px;margin:20px auto;">
    Velora uses a three-phase BFT consensus model: Propose, Prevote and Precommit.
    Deterministic finality with identity-based validators.
  </p>
</section>

<section id="developers" class="section">
  <h2>Developers</h2>
  <p style="color:#aaa;margin:20px;">Run a validator node:</p>
  <div style="background:black;padding:15px;border-radius:10px;display:inline-block;">
    python velora_node.py 5001 node1
  </div>
</section>

<section id="governance" class="section">
  <h2>Governance</h2>
  <p style="color:#aaa;max-width:700px;margin:20px auto;">
    Future on-chain governance including validator rotation,
    protocol parameter voting and upgrade proposals.
  </p>
</section>

<footer>
  © 2026 Velora Protocol. All rights reserved.
</footer>

</body>
</html>