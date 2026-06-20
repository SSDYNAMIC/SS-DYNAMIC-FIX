# SS-DYNAMIC-FIX
SS DYNAMIC FIX PHONE &amp; LAPTOP REPAIR REPAIRING SPECIALIST CENTER SS DYNAMIC TELECOMMUNICATION (MA0200450)<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>SS DYNAMIC FIX</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0b0b0b;
color:white;
}

header{
background:linear-gradient(135deg,#8b0000,#ff0000,#111);
padding:80px 20px;
text-align:center;
}

header h1{
font-size:60px;
color:white;
}

header h2{
color:#ff4444;
margin-top:10px;
}

.hero{
background:url('repair-lab.jpg');
background-size:cover;
background-position:center;
padding:100px 20px;
text-align:center;
}

.container{
max-width:1200px;
margin:auto;
padding:40px 20px;
}

.form-box{
background:#151515;
padding:30px;
border-radius:15px;
border:1px solid #333;
}

input,textarea,select{
width:100%;
padding:15px;
margin-bottom:15px;
border:none;
border-radius:8px;
background:#222;
color:white;
}

button{
width:100%;
padding:15px;
background:#ff0000;
color:white;
border:none;
border-radius:8px;
font-size:18px;
font-weight:bold;
cursor:pointer;
}

button:hover{
background:#cc0000;
}

.section-title{
text-align:center;
font-size:35px;
margin-bottom:30px;
color:#ff4444;
}

footer{
background:#111;
padding:30px;
text-align:center;
}
</style>

</head>
<body>

<header>
<h1>SS DYNAMIC FIX</h1>
<h2>PHONE & LAPTOP REPAIRING SPECIALIST CENTER</h2>
<p>SS DYNAMIC TELECOMMUNICATION MA0200450</p>
<p>#SSDynamicFiX</p>
</header>

<section class="hero">
<h1>EXPERT MOBILE REPAIR LAB</h1>
<p>Professional Smartphone & Laptop Repair Solutions</p>
</section>

<div class="container">

<h2 class="section-title">
SS DYNAMIC REPAIR & SERVICE FORM
</h2>

<div class="form-box">

<form onsubmit="sendWhatsApp();return false;">

<h3>DEVICE INFORMATION</h3>

<input type="text" id="brand" placeholder="Brand">

<input type="text" id="model" placeholder="Model">

<input type="text" id="codemodel" placeholder="Code Model">

<textarea id="damage" placeholder="Damaged / Problem"></textarea>

<textarea id="chronology"
placeholder="Device Chronology Before Damaged"></textarea>

<select id="lockstatus">
<option>Screen Lock Status</option>
<option>Locked</option>
<option>Unlocked</option>
</select>

<select id="google">
<option>Google Account Removed?</option>
<option>Yes</option>
<option>No</option>
</select>

<select id="icloud">
<option>Apple ID Removed?</option>
<option>Yes</option>
<option>No</option>
</select>

<hr><br>

<h3>CUSTOMER INFORMATION</h3>

<input type="text" id="name" placeholder="Customer Name">

<input type="text" id="phone" placeholder="WhatsApp Number">

<input type="email" id="email" placeholder="Email">

<textarea id="address"
placeholder="Address"></textarea>

<label>
<input type="checkbox" required>
I confirm the device belongs to me and
I authorize SS DYNAMIC FIX to inspect and repair it.
</label>

<br><br>

<button type="submit">
SUBMIT TO WHATSAPP
</button>

</form>

</div>

</div>

<footer>
<h3>SS DYNAMIC FIX</h3>
<p>Professional Phone & Laptop Repair Specialist Center</p>
<p>WhatsApp: 01151453147</p>
</footer>

<script>
function sendWhatsApp(){

let message =
"*SS DYNAMIC FIX REPAIR FORM*%0A%0A"+

"Brand: "+document.getElementById('brand').value+"%0A"+
"Model: "+document.getElementById('model').value+"%0A"+
"Code Model: "+document.getElementById('codemodel').value+"%0A"+
"Damaged: "+document.getElementById('damage').value+"%0A"+
"Chronology: "+document.getElementById('chronology').value+"%0A"+
"Screen Lock Status: "+document.getElementById('lockstatus').value+"%0A"+
"Google Account Removed: "+document.getElementById('google').value+"%0A"+
"Apple ID Removed: "+document.getElementById('icloud').value+"%0A%0A"+

"Customer Name: "+document.getElementById('name').value+"%0A"+
"WhatsApp: "+document.getElementById('phone').value+"%0A"+
"Email: "+document.getElementById('email').value+"%0A"+
"Address: "+document.getElementById('address').value;

window.open(
"https://wa.me/601151453147?text="+message,
"_blank"
);

}
</script>

</body>
