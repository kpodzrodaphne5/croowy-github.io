<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>CROOWY | Live Guitar Booking</title>
<style>
body{margin:0;background:#f5f1e8;color:#303129;font-family:Arial,sans-serif}
header,section{padding:70px 8%;max-width:1000px;margin:auto}
header{min-height:70vh;display:flex;flex-direction:column;justify-content:center}
h1,h2,h3{font-family:Georgia,serif;font-weight:400}
h1{font-size:70px;line-height:.95}
h2{font-size:42px}.olive{color:#596647}
p{color:#77766e;font-size:18px}
.btn{display:inline-block;background:#687354;color:white;padding:14px 22px;margin:10px 5px 10px 0;text-decoration:none;border-radius:4px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:15px}
.card{background:#fffdf8;padding:25px;border:1px solid #ddd8ca;border-radius:5px}
.price{font-size:28px;font-weight:bold;color:#596647}
.tags{display:flex;flex-wrap:wrap;gap:10px}
.tag{background:#e5e8dc;padding:10px 15px;border-radius:20px;color:#4f5b42}
form{display:grid;gap:12px;max-width:700px}
input,select,textarea{padding:14px;border:1px solid #d5d1c5;background:#fffdf8;border-radius:4px;font-size:16px}
textarea{height:120px}
footer{text-align:center;padding:35px;background:#e5e8dc}
</style>
</head>
<body>

<header>
<small class="olive">CROOWY · LIVE GUITARIST</small>
<h1>Music for exceptional moments.</h1>
<p>Neo Soul · Jazz · R&B · Afro</p>
<p>Guitare live élégante pour mariages, yachts, domaines, hôtels, rooftops et événements privés.</p>
<a class="btn" href="#booking">RÉSERVER CROOWY</a>
</header>

<section>
<h2>Formules</h2>
<div class="cards">
<div class="card"><h3>Essential</h3><p>1h</p><div class="price">300 €</div></div>
<div class="card"><h3>Signature</h3><p>1h30</p><div class="price">500 €+</div></div>
<div class="card"><h3>Premium</h3><p>2h</p><div class="price">800 €+</div></div>
<div class="card"><h3>Prestige</h3><p>2h30–3h</p><div class="price">1 500 €+</div></div>
<div class="card"><h3>Luxury</h3><p>Événement haut de gamme</p><div class="price">2 500 €+</div></div>
</div>
</section>

<section>
<h2>Événements</h2>
<div class="tags">
<span class="tag">🛥️ Yachts</span>
<span class="tag">🍷 Domaines</span>
<span class="tag">🍇 Vignobles</span>
<span class="tag">💍 Mariages</span>
<span class="tag">🏨 Hôtels</span>
<span class="tag">🌃 Rooftops</span>
<span class="tag">🥂 Dîners privés</span>
<span class="tag">💎 Galas</span>
</div>
</section>

<section>
<h2>Options</h2>
<p>🎶 Chanson personnalisée : <b>+100 € / titre</b></p>
<p>🚗 Déplacement : supplément selon destination</p>
<p>✈️ Transport / hébergement : supplément si nécessaire</p>
</section>

<section id="booking">
<h2>Réserver CROOWY</h2>
<p>Décrivez votre événement pour recevoir un devis.</p>

<form action="mailto:TON_EMAIL" method="post" enctype="text/plain">
<input name="Nom" placeholder="Nom / Société" required>
<input name="Email" type="email" placeholder="Email" required>
<input name="Date" placeholder="Date">
<input name="Lieu" placeholder="Lieu / Pays">

<select name="Formule">
<option>Choisir une formule</option>
<option>Essential — 300 €</option>
<option>Signature — 500 €+</option>
<option>Premium — 800 €+</option>
<option>Prestige — 1 500 €+</option>
<option>Luxury — 2 500 €+</option>
</select>

<textarea name="Message" placeholder="Parlez-nous de votre événement..."></textarea>
<button class="btn" type="submit">DEMANDER UN DEVIS</button>
</form>
</section>

<footer>
<strong>CROOWY</strong><br>
Live Guitar Booking · France · Europe · International<br><br>
Instagram : @croowy
</footer>

</body>
</html>
