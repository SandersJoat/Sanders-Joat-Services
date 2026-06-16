<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sanders JOAT Services | Business Support & Project Execution</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

:root{
    --navy:#0f172a;
    --blue:#2563eb;
    --light:#f8fafc;
    --gray:#64748b;
    --white:#ffffff;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Inter',sans-serif;
    color:#1e293b;
    background:white;
}

nav{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(15,23,42,.95);
    backdrop-filter:blur(10px);
    z-index:1000;
}

.nav-container{
    max-width:1200px;
    margin:auto;
    padding:18px 20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:white;
    font-weight:800;
    font-size:1.1rem;
}

.nav-links{
    display:flex;
    gap:25px;
}

.nav-links a{
    color:white;
    text-decoration:none;
    font-weight:500;
}

.hero{
    min-height:100vh;
    background:
    linear-gradient(rgba(15,23,42,.78), rgba(15,23,42,.78)),
    url('https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:100px 20px;
}

.hero-content{
    max-width:900px;
    color:white;
}

.hero h1{
    font-size:4rem;
    font-weight:800;
    margin-bottom:20px;
}

.hero p{
    font-size:1.35rem;
    margin-bottom:30px;
    color:#e2e8f0;
}

.btn{
    display:inline-block;
    padding:15px 30px;
    border-radius:10px;
    text-decoration:none;
    font-weight:700;
    transition:.3s;
}

.btn-primary{
    background:var(--blue);
    color:white;
}

.btn-primary:hover{
    transform:translateY(-3px);
}

.section{
    max-width:1200px;
    margin:auto;
    padding:90px 20px;
}

.section-title{
    text-align:center;
    font-size:2.5rem;
    margin-bottom:20px;
    color:var(--navy);
}

.section-subtitle{
    text-align:center;
    max-width:700px;
    margin:auto;
    color:var(--gray);
    margin-bottom:60px;
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.stat{
    background:var(--light);
    padding:30px;
    border-radius:16px;
    text-align:center;
}

.stat h3{
    color:var(--blue);
    font-size:2rem;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:25px;
}

.card{
    background:white;
    border:1px solid #e2e8f0;
    border-radius:18px;
    padding:30px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-6px);
    box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.card h3{
    margin-bottom:15px;
    color:var(--navy);
}

.card p{
    color:var(--gray);
}

.about{
    background:var(--light);
}

.about-box{
    max-width:900px;
    margin:auto;
    text-align:center;
    font-size:1.1rem;
    line-height:1.8;
}

.why{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.why-item{
    background:white;
    border:1px solid #e2e8f0;
    padding:25px;
    border-radius:14px;
}

.contact{
    background:var(--navy);
    color:white;
    text-align:center;
}

.contact h2{
    margin-bottom:25px;
}

.contact p{
    margin-bottom:15px;
    font-size:1.1rem;
}

.contact a{
    color:#93c5fd;
    text-decoration:none;
}

footer{
    background:#020617;
    color:white;
    text-align:center;
    padding:25px;
}

@media(max-width:768px){

.hero h1{
    font-size:2.5rem;
}

.hero p{
    font-size:1.1rem;
}

.nav-links{
    display:none;
}

}

</style>
</head>

<body>

<nav>
    <div class="nav-container">
        <div class="logo">SANDERS JOAT SERVICES</div>

        <div class="nav-links">
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#why">Why Us</a>
            <a href="#contact">Contact</a>
        </div>
    </div>
</nav>

<section class="hero">

    <div class="hero-content">

        <h1>Flexible Business Support.<br>Reliable Execution.</h1>

        <p>
            Administrative, technical, operational, and project-based support
            for businesses throughout Western North Carolina.
        </p>

        <a href="#contact" class="btn btn-primary">
            Request a Quote
        </a>

    </div>

</section>

<section class="section">

    <div class="stats">

        <div class="stat">
            <h3>24hr</h3>
            <p>Typical Response Time</p>
        </div>

        <div class="stat">
            <h3>Flexible</h3>
            <p>Project-Based Support</p>
        </div>

        <div class="stat">
            <h3>Local</h3>
            <p>Western NC Service Area</p>
        </div>

        <div class="stat">
            <h3>UNC</h3>
            <p>Student-Owned Business</p>
        </div>

    </div>

</section>

<section id="services" class="section">

    <h2 class="section-title">Services</h2>

    <p class="section-subtitle">
        Reliable support across administrative, digital, operational,
        and project-based business needs.
    </p>

    <div class="services">

        <div class="card">
            <h3>Business Operations</h3>
            <p>
                Data entry, documentation, inventory management,
                spreadsheets, organization, and administrative support.
            </p>
        </div>

        <div class="card">
            <h3>Digital Services</h3>
            <p>
                Website development, website updates, online business
                setup, digital organization, and technical assistance.
            </p>
        </div>

        <div class="card">
            <h3>Logistics & Projects</h3>
            <p>
                Event support, moving assistance, project execution,
                operational tasks, and business logistics.
            </p>
        </div>

        <div class="card">
            <h3>Facilities Support</h3>
            <p>
                Landscaping, cleanup, grounds maintenance,
                exterior upkeep, and property support.
            </p>
        </div>

    </div>

</section>

<section id="about" class="section about">

    <h2 class="section-title">About</h2>

    <div class="about-box">

        Founded by UNC Chapel Hill student Will Sanders,
        Sanders JOAT Services helps businesses solve operational
        challenges without the cost of adding full-time staff.

        <br><br>

        From administrative projects and digital services to logistics,
        maintenance, and project execution, we provide dependable,
        adaptable support wherever it is needed most.

    </div>

</section>

<section id="why" class="section">

    <h2 class="section-title">Why Businesses Choose Us</h2>

    <div class="why">

        <div class="why-item">
            ✓ Flexible project-based support
        </div>

        <div class="why-item">
            ✓ Professional communication
        </div>

        <div class="why-item">
            ✓ Affordable alternative to additional staffing
        </div>

        <div class="why-item">
            ✓ Quick turnaround times
        </div>

        <div class="why-item">
            ✓ Dependable execution
        </div>

        <div class="why-item">
            ✓ Wide-ranging capabilities
        </div>

    </div>

</section>

<section id="contact" class="section contact">

    <h2>Request a Quote</h2>

    <p>
        Need an extra set of hands for your business?
    </p>

    <p>
        <strong>Phone:</strong> 828-423-8613
    </p>

    <p>
        <strong>Email:</strong>
        <a href="mailto:lliwsanders@icloud.com">
            lliwsanders@icloud.com
        </a>
    </p>

    <p>
        Typical response time: within 24 hours.
    </p>

</section>

<footer>
    © 2026 Sanders JOAT Services • Serving Western North Carolina
</footer>

</body>
</html>
