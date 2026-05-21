<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Invitation</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(135deg,#ffe6f0,#e6f7ff);
color:#222;
}

header{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.card{
background:white;
padding:40px;
border-radius:25px;
box-shadow:0 10px 30px rgba(0,0,0,0.1);
max-width:700px;
width:100%;
}

h1{
font-size:40px;
margin-bottom:10px;
color:#d63384;
}

h2{
font-size:24px;
margin-bottom:20px;
font-weight:500;
}

.info{
font-size:18px;
margin-bottom:10px;
}

.highlight{
font-weight:700;
color:#0d6efd;
}

.map{
margin-top:25px;
border-radius:20px;
overflow:hidden;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 25px;
background:#25D366;
color:white;
text-decoration:none;
border-radius:50px;
font-weight:600;
}

.btn:hover{
transform:scale(1.05);
}
</style>

</head>

<body>

<header>

<div class="card">

<h1>🎉 You're Invited 🎉</h1>

<h2>Mane’s 30th Birthday & Amelie’s First Tooth Party</h2>

<p class="info">📅 Date: <span class="highlight">20.06.2026</span></p>

<p class="info">⏰ Time: <span class="highlight">19:00</span></p>

<p class="info">📍 Location: <span class="highlight">Florence Restaurant</span></p>

<p class="info">We would love to celebrate this special day with you!</p>

<a class="btn" href="https://wa.me/" target="_blank">
Confirm on WhatsApp
</a>

<div class="map">

<iframe
width="100%"
height="300"
frameborder="0"
style="border:0"
referrerpolicy="no-referrer-when-downgrade"
src="https://www.google.com/maps?q=Florence%20Restaurant&output=embed"
allowfullscreen>
</iframe>

</div>

</div>

</header>

</body>
</html>
