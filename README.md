# SS-DYNAMIC-FIX
SS DYNAMIC FIX PHONE &amp; LAPTOP REPAIR REPAIRING SPECIALIST CENTER
SS DYNAMIC TELECOMMUNICATION (MA0200450)
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SS DYNAMIC FIX | Phone & Laptop Repair</title>

    <style>
        /* --- GLOBAL BASICS --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #000;
            color: #fff;
        }

        /* --- HEADER & HERO BLOCKS --- */
        header {
            background: #111;
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid red;
        }

        header h1 {
            font-size: 50px;
            color: red;
        }

        header h2 {
            font-size: 28px;
            color: #fff;
        }

        .hero {
            padding: 100px 20px;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,.8),rgba(0,0,0,.8)),
            url('https://images.unsplash.com/photo-1518770660439-4636190af475');
            background-size: cover;
            background-position: center;
        }

        .hero h1 {
            font-size: 60px;
            color: red;
        }

        .hero p {
            font-size: 22px;
            margin-top: 15px;
        }

        /* --- BUTTONS & ACTIONS --- */
        .btn {
            display: inline-block;
            padding: 15px 30px;
            background: red;
            color: white;
            text-decoration: none;
            margin-top: 20px;
            border-radius: 10px;
            font-weight: bold;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #cc0000;
        }

        .waze-btn {
            display: inline-block;
            padding: 12px 24px;
            background: #29b6f6; /* Waze inspired blue color */
            color: #000;         /* Dark text for strong contrast */
            text-decoration: none;
            margin-top: 15px;
            border-radius: 8px;
            font-weight: bold;
            font-size: 16px;
            transition: background 0.3s ease, transform 0.2s ease;
        }

        .waze-btn:hover {
            background: #0086c3;
            color: #fff;
            transform: translateY(-2px);
        }

        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            color: white;
            padding: 15px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            z-index: 999;
            box-shadow: 0px 4px 12px rgba(0,0,0,0.5);
            transition: transform 0.3s ease;
        }

        .whatsapp-float:hover {
            transform: scale(1.05);
        }

        /* --- LAYOUT GRID & SECTIONS --- */
        .section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: auto;
        }

        .section-title {
            text-align: center;
            font-size: 40px;
            color: red;
            margin-bottom: 30px;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: #111;
            padding: 20px;
            border: 1px solid red;
            border-radius: 10px;
        }

        .card h3 {
            color: red;
            margin-bottom: 10px;
        }

        /* --- FORMS & INPUT CONTROLS --- */
        form {
            background: #111;
            padding: 30px;
            border-radius: 10px;
            border: 1px solid #222;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #333;
            border-radius: 5px;
            background: #fff;
            color: #222;
            font-size: 16px;
        }

        textarea {
            resize: vertical;
            height: 100px;
        }

        button {
            background: red;
            color: white;
            padding: 15px;
            border: none;
            width: 100%;
            font-size: 18px;
            cursor: pointer;
            font-weight: bold;
            border-radius: 5px;
            margin-top: 10px;
            transition: background 0.3s ease;
        }

        button:hover {
            background: #cc0000;
        }

        /* --- IFRAME & FOOTER --- */
        iframe {
            width: 100%;
            height: 450px;
            border: 0;
            border-radius: 10px;
            background: #222;
        }

        footer {
            background: #111;
            padding: 20px;
            text-align: center;
            border-top: 4px solid red;
        }
    </style>

    <script>
        // Universal parser safely catching undefined structures 
        function getInputValue(id) {
            var element = document.getElementById(id);
            var value = element ? element.value.trim() : "";
            return value ? value : "Not Provided";
        }

        function sendRepairForm(event) {
            if (event) event.preventDefault(); // Prevents instant page reload

            var brand = getInputValue("brand");
            var model = getInputValue("model");
            var code = getInputValue("code");
            var damage = getInputValue("damage");
            var chrono = getInputValue("chrono");
            var lock = getInputValue("lock");

            // Validates against fallback string
            if (brand === "Not Provided" || model === "Not Provided" || damage === "Not Provided") {
                alert("Please fill in at least the Brand, Model, and Damaged fields.");
                return;
            }

            var text = "*SS DYNAMIC FIX REPAIR FORM*\n\n" +
                       "📱 Brand: " + brand + "\n" +
                       "📋 Model: " + model + "\n" +
                       "🔢 Code Model: " + code + "\n" +
                       "❌ Damaged: " + damage + "\n" +
                       "⏳ Device Chronology: " + chrono + "\n" +
                       "🔒 Lock Code: " + lock;

            window.open("https://wa.me/601151453147?text=" + encodeURIComponent(text), "_blank");
        }

        function sendCustomerForm(event) {
            if (event) event.preventDefault(); // Prevents instant page reload

            var name = getInputValue("name");
            var phone = getInputValue("phone");
            var email = getInputValue("email");
            var address = getInputValue("address");
            var screen = getInputValue("screen");
            var gmail = getInputValue("gmail");
            var apple = getInputValue("apple");

            // Validates against fallback string
            if (name === "Not Provided" || phone === "Not Provided") {
                alert("Please fill in your Name and WhatsApp Number.");
                return;
            }

            var text = "*CUSTOMER INFORMATION*\n\n" +
                       "👤 Name: " + name + "\n" +
                       "💬 WhatsApp: " + phone + "\n" +
                       "✉️ Email: " + email + "\n" +
                       "📍 Address: " + address + "\n" +
                       "🔓 Screen Lock: " + screen + "\n" +
                       "📧 Gmail Access: " + gmail + "\n" +
                       "🍏 Apple ID Access: " + apple;

            window.open("https://wa.me/601151453147?text=" + encodeURIComponent(text), "_blank");
        }
    </script>
</head>

<body>

    <header>
        <h1>SS DYNAMIC FIX</h1>
        <h2>PHONE & LAPTOP REPAIR</h2>
        <p>Repairing Specialist Center</p>
        <p>SS Dynamic Telecommunication (MA0200450)</p>
        <p>#SSDynamicFiX</p>
    </header>

    <section class="hero">
        <h1>EXPERT PHONE & LAPTOP REPAIR</h1>
        <p>Fast Repair • Trusted Service • Professional Technician</p>
        <a href="https://wa.me/601151453147" class="btn" target="_blank" rel="noopener noreferrer">WhatsApp Now</a>
    </section>

    <main>
        <section class="section">
            <h2 class="section-title">Our Services</h2>
            <div class="services">
                <div class="card">
                    <h3>Screen Replacement</h3>
                    <p>LCD & OLED Repair</p>
                </div>
                <div class="card">
                    <h3>Battery Replacement</h3>
                    <p>Fast & Genuine Parts</p>
                </div>
                <div class="card">
                    <h3>Charging Port Repair</h3>
                    <p>All Brands Supported</p>
                </div>
                <div class="card">
                    <h3>Water Damage Repair</h3>
                    <p>Motherboard Specialist</p>
                </div>
                <div class="card">
                    <h3>Board Repair</h3>
                    <p>Advanced Microsoldering</p>
                </div>
                <div class="card">
                    <h3>Software Repair</h3>
                    <p>Update & Unlock Service</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Repair Service Form</h2>
            <form onsubmit="sendRepairForm(event)">
                <input id="brand" type="text" placeholder="Brand (e.g., iPhone, Samsung)" required>
                <input id="model" type="text" placeholder="Model (e.g., 13 Pro, S22)" required>
                <input id="code" type="text" placeholder="Code Model (e.g., A2638)">
                <input id="damage" type="text" placeholder="Damaged Status (e.g., Cracked Screen, Dead Battery)" required>
                <textarea id="chrono" placeholder="Device Chronology Before Damage (How did it happen?)"></textarea>
                <input id="lock" type="text" placeholder="Screen Lock / Password / PIN">
                <button type="submit">Submit To WhatsApp</button>
            </form>
        </section>

        <section class="section">
            <h2 class="section-title">Customer Information Form</h2>
            <form onsubmit="sendCustomerForm(event)">
                <input id="name" type="text" placeholder="Full Name" required>
                <input id="phone" type="tel" placeholder="WhatsApp Number" required>
                <input id="email" type="email" placeholder="Email Address">
                <textarea id="address" placeholder="Mailing / Home Address"></textarea>
                <input id="screen" type="text" placeholder="Confirm Screen Lock / Password">
                <input id="gmail" type="text" placeholder="Gmail & Password (If required for bypassing/testing)">
                <input id="apple" type="text" placeholder="Apple ID / iCloud ID & Password (If required for restoration)">
                <button type="submit">Submit To WhatsApp</button>
            </form>
        </section>

        <section class="section">
            <h2 class="section-title">Our Location</h2>
            
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3986.4715569424784!2d102.1961605!3d2.382283!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31d1dd68037edaff%3A0x6b139d67fb8b71d4!2sAG%20Sentral!5e0!3m2!1sen!2smy!4v1710000000000!5m2!1sen!2smy" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
            <iframe
src="https://maps.google.com/maps?q=2.382035,102.211564&t=&z=15&ie=UTF8&iwloc=&output=embed">
</iframe>

<br><br>

<h3>SS DYNAMIC FIX</h3>

<p>
NO 2, BANGUNAN TERMINAL BAS,<br>
KOMPLEKS AG SENTRAL,<br>
78000 ALOR GAJAH,<br>
MELAKA
</p>

<p>
Plus Code: 96J6+RJ8
</p>

<footer>
        <h2>SS DYNAMIC FIX</h2>
        <p>Phone & Laptop Repair Specialist Center</p>
        <p>WhatsApp: 01151453147</p>
        <p>© SINCE:2011 SSDynamicFiX #SSDynamicFiX</p>
    </footer>

    <a class="whatsapp-float" href="https://wa.me/601151453147" target="_blank" rel="noopener noreferrer">WhatsApp</a>
</body>
