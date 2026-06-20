# SS-DYNAMIC-FIX
SS DYNAMIC FIX PHONE &amp; LAPTOP REPAIR REPAIRING SPECIALIST CENTER SS DYNAMIC TELECOMMUNICATION (MA0200450)
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SS DYNAMIC FIX | Phone & Laptop Repair</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#000;
color:#fff;
}

header{
background:linear-gradient(rgba(0,0,0,.8),rgba(0,0,0,.8)),
url('https://images.unsplash.com/photo-1518770660439-4636190af475');
background-size:cover;
background-position:center;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero h1{
font-size:55px;
color:#ff0000;
}

.hero h2{
font-size:30px;
margin-top:10px;
}

.hero p{
margin-top:15px;
font-size:18px;
}

.btn{
display:inline-block;
padding:15px 30px;
background:#ff0000;
color:#fff;
text-decoration:none;
margin-top:20px;
border-radius:8px;
font-weight:bold;
}

section{
padding:60px 20px;
}

.container{
max-width:1200px;
margin:auto;
}

.title{
text-align:center;
font-size:40px;
color:#ff0000;
margin-bottom:40px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#111;
padding:25px;
border:1px solid #ff0000;
border-radius:10px;
}

.card h3{
color:#ff0000;
margin-bottom:10px;
}

form{
background:#111;
padding:30px;
border-radius:10px;
border:1px solid #ff0000;
}

input,textarea{
width:100%;
padding:12px;
margin-top:10px;
margin-bottom:15px;
border:none;
border-radius:5px;
}

button{
background:#ff0000;
color:#fff;
padding:15px;
border:none;
cursor:pointer;
width:100%;
font-size:18px;
border-radius:5px;
}

footer{
background:#111;
text-align:center;
padding:30px;
border-top:2px solid #ff0000;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:#fff;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

@media(max-width:768px){
.hero h1{
font-size:35px;
}
.hero h2{
font-size:22px;
}
}
</style>
</head>

<body>

<header>
<div class="hero">
<h1>SS DYNAMIC FIX</h1>
<h2>PHONE & LAPTOP REPAIR</h2>
<h2>REPAIRING SPECIALIST CENTER</h2>
<p>SS DYNAMIC TELECOMMUNICATION MA0200450</p>
<p>#SSDynamicFiX</p>

<a href="#repairform" class="btn">
BOOK REPAIR NOW
</a>

</div>
</header>

<section>
<div class="container">
<h2 class="title">OUR SERVICES</h2>

<div class="services">

<div class="card">
<h3>LCD Screen Repair</h3>
<p>Screen Pecah, Retak, Blank, No Display</p>
</div>

<div class="card">
<h3>Battery Replacement</h3>
<p>Battery Kembung, Battery Drop, Fast Drain</p>
</div>

<div class="card">
<h3>Motherboard Repair</h3>
<p>No Power, Short Circuit, Water Damage</p>
</div>

<div class="card">
<h3>Laptop Repair</h3>
<p>Screen, Keyboard, Battery, Motherboard</p>
</div>

<div class="card">
<h3>Charging Problem</h3>
<p>Not Charging, Slow Charging</p>
</div>

<div class="card">
<h3>Data Recovery</h3>
<p>Backup Data & Recovery Service</p>
</div>

</div>
</div>
</section>

<section id="repairform">
<div class="container">

<h2 class="title">SS DYNAMIC REPAIR FORM</h2>

<form onsubmit="sendRepair(); return false;">

<input type="text" id="brand" placeholder="BRAND" required>

<input type="text" id="model" placeholder="MODEL" required>

<input type="text" id="codemodel" placeholder="CODE MODEL">

<textarea id="damaged" placeholder="DAMAGED"></textarea>

<textarea id="chronology" placeholder="DEVICE CHRONOLOGY BEFORE DAMAGED"></textarea>

<input type="text" id="screenlock" placeholder="SCREEN LOCK CODE / PASSWORD / PIN / PATTERN">

<button type="submit">
SEND REPAIR FORM
</button>

</form>

</div>
</section>

<section>
<div class="container">

<h2 class="title">CUSTOMER FORM</h2>

<form onsubmit="sendCustomer(); return false;">

<input type="text" id="name" placeholder="NAME" required>

<input type="text" id="phone" placeholder="WHATSAPP NUMBER" required>

<input type="email" id="email" placeholder="EMAIL">

<textarea id="address" placeholder="ADDRESS"></textarea>

<input type="text" id="customerlock" placeholder="SCREEN LOCK CODE / PASSWORD / PIN">

<button type="submit">
SEND CUSTOMER FORM
</button>

</form>

</div>
</section>

<footer>

<h3>SS DYNAMIC FIX</h3>
<p>PHONE & LAPTOP REPAIR</p>
<p>REPAIRING SPECIALIST CENTER</p>
<p>WhatsApp: +601151453147</p>
<p>#SSDynamicFiX</p>

</footer>

<a href="https://wa.me/601151453147" class="whatsapp">
WhatsApp
</a>

<script>

function sendRepair(){

var text =
"🔧 SS DYNAMIC REPAIR FORM%0A%0A"+
"Brand: "+document.getElementById('brand').value+"%0A"+
"Model: "+document.getElementById('model').value+"%0A"+
"Code Model: "+document.getElementById('codemodel').value+"%0A"+
"Damaged: "+document.getElementById('damaged').value+"%0A"+
"Chronology: "+document.getElementById('chronology').value+"%0A"+
"Screen Lock: "+document.getElementById('screenlock').value;

window.open("https://wa.me/601151453147?text="+text);
}

function sendCustomer(){

var text =
"👤 CUSTOMER FORM%0A%0A"+
"Name: "+document.getElementById('name').value+"%0A"+
"WhatsApp: "+document.getElementById('phone').value+"%0A"+
"Email: "+document.getElementById('email').value+"%0A"+
"Address: "+document.getElementById('address').value+"%0A"+
"Screen Lock: "+document.getElementById('customerlock').value;

window.open("https://wa.me/601151453147?text="+text);
}

</script>

</body>
