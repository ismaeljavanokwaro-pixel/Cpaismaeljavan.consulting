<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CPA Ismael Javan Consulting</title>

<style>
body { font-family: 'Segoe UI', sans-serif; margin:0; background:#f4f6f9; }

header {
    background: linear-gradient(to right, #0b2545, #13315c);
    color: white;
    padding: 70px 20px;
    text-align: center;
}

header h1 {
    margin:0;
    font-size:36px;
}

header p {
    font-size:18px;
    margin-top:10px;
}

nav {
    background:#0b2545;
    padding:15px;
    text-align:center;
}

nav a {
    color:white;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
}

.section {
    padding:60px 20px;
    max-width:1100px;
    margin:auto;
}

.card {
    background:white;
    padding:25px;
    margin:15px 0;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.05);
}

.grid {
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap:20px;
}

button {
    background:#0b2545;
    color:white;
    padding:12px 20px;
    border:none;
    border-radius:6px;
    cursor:pointer;
}

input, textarea {
    width:100%;
    padding:10px;
    margin:8px 0;
    border-radius:6px;
    border:1px solid #ccc;
}

footer {
    background:#0b2545;
    color:white;
    text-align:center;
    padding:20px;
}

/* WhatsApp Button */
.whatsapp {
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    font-size:20px;
}
</style>
</head>

<body>

<header>
    <h1>CPA Ismael Javan Consulting</h1>
    <p>Providing CFO-Level Financial Management, Donor Fund Accountability, and Strategic Advisory Services</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#reports">Reports</a>
    <a href="#contact">Contact</a>
</nav>

<section class="section">

<div class="card" id="about">
<h2>About the Firm</h2>
<p>CPA Ismael Javan Consulting is a professional accounting and advisory firm providing financial management, donor fund accountability, and strategic support to NGOs, institutions, and businesses. We help organizations achieve financial clarity, compliance, and measurable impact.</p>
</div>

<h2 id="services">Our Services</h2>

<div class="grid">

<div class="card">
<h3>Accounting & Compliance</h3>
<p>Financial reporting, bookkeeping, payroll, and statutory compliance.</p>
</div>

<div class="card">
<h3>Budgeting & Forecasting</h3>
<p>Multi-year budgets, financial planning, and cost analysis.</p>
</div>

<div class="card">
<h3>Donor Fund Management</h3>
<p>Grant tracking, donor reporting, and compliance management.</p>
</div>

<div class="card">
<h3>Financial Advisory</h3>
<p>Strategic planning, risk management, and systems strengthening.</p>
</div>

<div class="card">
<h3>Dashboards & Analytics</h3>
<p>Excel & Power BI dashboards for data-driven decisions.</p>
</div>

<div class="card">
<h3>Audit & Internal Controls</h3>
<p>Internal audit support and financial control systems.</p>
</div>

</div>

<div class="card">
<h2>Work With Us</h2>
<p>We support organizations to strengthen financial systems, ensure donor compliance, and improve decision-making through data-driven insights.</p>
<button onclick="window.location='#contact'">Request a Consultation</button>
</div>

<div class="card" id="reports">
<h2>Reports & Insights</h2>
<p>Download financial reports, dashboards, and tools for better decision-making.</p>
<button onclick="downloadProfile()">Download Company Profile</button>
</div>

<div class="card" id="contact">
<h2>Contact Us</h2>

<p><strong>Email:</strong> cpa.ismaeljavan.consulting@gmail.com</p>
<p><strong>Phone:</strong> 0743 513 080</p>

<h3>Request a Quote</h3>

<form onsubmit="submitForm(event)">
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<input type="text" placeholder="Service Needed">
<textarea placeholder="Project Details"></textarea>
<button type="submit">Submit Request</button>
</form>

</div>

</section>

<footer>
<p>© 2026 CPA Ismael Javan Consulting</p>
</footer>

<!-- WhatsApp Button -->
<a href="https://wa.me/254743513080" class="whatsapp" target="_blank">💬</a>

<script>
function submitForm(e){
    e.preventDefault();
    alert("Thank you! Your request has been received. We will contact you shortly.");
}

function downloadProfile(){
    alert("Download your company profile from the link I provided earlier.");
}
</script>

</body>
</html>
