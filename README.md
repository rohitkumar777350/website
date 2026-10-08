```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="TLM Automations Pvt. Ltd. - Industrial Automation, Machine Development, Mechanical Engineering and Industrial Support Solutions.">
<title>TLM Automations Pvt. Ltd.</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    color: #172033;
    background: #ffffff;
    line-height: 1.6;
}

a {
    text-decoration: none;
    color: inherit;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

/* HEADER */

header {
    position: sticky;
    top: 0;
    z-index: 1000;
    background: #ffffff;
    box-shadow: 0 2px 12px rgba(0,0,0,0.08);
}

.navbar {
    min-height: 76px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 28px;
    font-weight: 900;
    color: #0b4ea2;
    letter-spacing: 1px;
}

.logo span {
    color: #ef7d00;
}

.nav-links {
    display: flex;
    gap: 28px;
    list-style: none;
}

.nav-links a {
    font-weight: 600;
    color: #172033;
}

.nav-links a:hover {
    color: #0b4ea2;
}

.menu-btn {
    display: none;
    font-size: 28px;
    cursor: pointer;
}

/* HERO */

.hero {
    min-height: 650px;
    display: flex;
    align-items: center;
    background:
        linear-gradient(90deg, rgba(5,20,45,0.94), rgba(5,20,45,0.72)),
        url("https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=1800&q=85")
        center/cover no-repeat;
    color: white;
}

.hero-content {
    max-width: 780px;
}

.hero h1 {
    font-size: 58px;
    line-height: 1.1;
    margin-bottom: 22px;
}

.hero h1 span {
    color: #ff9200;
}

.hero p {
    font-size: 20px;
    color: #e5edf8;
    margin-bottom: 32px;
    max-width: 700px;
}

.btn {
    display: inline-block;
    padding: 14px 25px;
    border-radius: 6px;
    font-weight: 700;
    margin-right: 10px;
    margin-bottom: 10px;
    transition: 0.3s;
}

.btn-primary {
    background: #ef7d00;
    color: white;
}

.btn-primary:hover {
    background: #d96800;
    transform: translateY(-2px);
}

.btn-outline {
    border: 2px solid white;
    color: white;
}

.btn-outline:hover {
    background: white;
    color: #0b4ea2;
}

/* SECTION */

section {
    padding: 85px 0;
}

.section-title {
    text-align: center;
    margin-bottom: 50px;
}

.section-title h2 {
    font-size: 38px;
    color: #0b4ea2;
    margin-bottom: 12px;
}

.section-title p {
    color: #667085;
    max-width: 700px;
    margin: auto;
}

/* ABOUT */

.about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    align-items: center;
}

.about-image {
    min-height: 400px;
    border-radius: 12px;
    background:
        linear-gradient(rgba(0,0,0,.15), rgba(0,0,0,.15)),
        url("https://images.unsplash.com/photo-1565439370925-3c5c0d8b0f72?auto=format&fit=crop&w=1000&q=80")
        center/cover;
}

.about-text h3 {
    font-size: 30px;
    margin-bottom: 18px;
    color: #172033;
}

.about-text p {
    margin-bottom: 15px;
    color: #5d6878;
}

/* SERVICES */

.services {
    background: #f5f8fc;
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
}

.service-card {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 5px 22px rgba(0,0,0,.06);
    border-top: 4px solid #0b4ea2;
    transition: .3s;
}

.service-card:hover {
    transform: translateY(-7px);
    box-shadow: 0 12px 30px rgba(0,0,0,.10);
}

.service-icon {
    font-size: 38px;
    margin-bottom: 15px;
}

.service-card h3 {
    color: #0b4ea2;
    margin-bottom: 10px;
}

.service-card p {
    color: #687386;
}

/* EXPERTISE */

.expertise-grid {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 18px;
}

.expertise {
    padding: 25px 18px;
    text-align: center;
    border: 1px solid #e4e8ef;
    border-radius: 8px;
    background: white;
}

.expertise strong {
    display: block;
    font-size: 17px;
    margin-top: 10px;
}

/* PROJECTS */

.projects {
    background: #f5f8fc;
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 24px;
}

.project {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 20px rgba(0,0,0,.06);
}

.project-img {
    height: 220px;
    background-size: cover;
    background-position: center;
}

.project:nth-child(1) .project-img {
    background-image: url("https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&fit=crop&w=1000&q=80");
}

.project:nth-child(2) .project-img {
    background-image: url("https://images.unsplash.com/photo-1565043666747-69f6646db940?auto=format&fit=crop&w=1000&q=80");
}

.project:nth-child(3) .project-img {
    background-image: url("https://images.unsplash.com/photo-1535378917042-10a22c95931a?auto=format&fit=crop&w=1000&q=80");
}

.project-content {
    padding: 22px;
}

.project-content h3 {
    color: #0b4ea2;
    margin-bottom: 8px;
}

/* CTA */

.cta {
    background: linear-gradient(135deg, #0b4ea2, #062d63);
    color: white;
    text-align: center;
}

.cta h2 {
    font-size: 38px;
    margin-bottom: 15px;
}

.cta p {
    margin-bottom: 25px;
}

/* CONTACT */

.contact-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
}

.contact-info {
    padding: 30px;
    background: #f5f8fc;
    border-radius: 10px;
}

.contact-info h3 {
    color: #0b4ea2;
    margin-bottom: 20px;
}

.contact-item {
    margin-bottom: 18px;
}

.contact-item strong {
    display: block;
    color: #172033;
}

.contact-item span {
    color: #667085;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid #d7dce4;
    border-radius: 6px;
    font-size: 15px;
}

.contact-form textarea {
    min-height: 150px;
    resize: vertical;
}

.contact-form button {
    border: none;
    cursor: pointer;
}

/* FOOTER */

footer {
    background: #09182d;
    color: white;
    padding: 35px 0;
    text-align: center;
}

footer p {
    color: #aab5c5;
}

/* FLOATING WHATSAPP */

.whatsapp {
    position: fixed;
    right: 22px;
    bottom: 22px;
    width: 58px;
    height: 58px;
    background: #25D366;
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 29px;
    z-index: 9999;
    box-shadow: 0 5px 18px rgba(0,0,0,.25);
}

/* MOBILE */

@media(max-width: 900px) {

    .nav-links {
        display: none;
        position: absolute;
        top: 76px;
        left: 0;
        width: 100%;
        background: white;
        flex-direction: column;
        padding: 20px 5%;
        gap: 18px;
        box-shadow: 0 8px 15px rgba(0,0,0,.08);
    }

    .nav-links.active {
        display: flex;
    }

    .menu-btn {
        display: block;
    }

    .hero {
        min-height: 580px;
    }

    .hero h1 {
        font-size: 42px;
    }

    .about-grid,
    .contact-grid {
        grid-template-columns: 1fr;
    }

    .service-grid {
        grid-template-columns: repeat(2,1fr);
    }

    .project-grid {
        grid-template-columns: 1fr;
    }

    .expertise-grid {
        grid-template-columns: repeat(2,1fr);
    }
}

@media(max-width: 600px) {

    section {
        padding: 65px 0;
    }

    .hero h1 {
        font-size: 36px;
    }

    .hero p {
        font-size: 17px;
    }

    .service-grid {
        grid-template-columns: 1fr;
    }

    .expertise-grid {
        grid-template-columns: 1fr;
    }

    .section-title h2 {
        font-size: 30px;
    }
}
</style>
</head>

<body>

<header>
    <div class="container navbar">

        <a href="#home" class="logo">
            TLM <span>AUTOMATIONS</span>
        </a>

        <div class="menu-btn" onclick="toggleMenu()">☰</div>

        <ul class="nav-links" id="navLinks">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </div>
</header>

<!-- HERO -->

<section class="hero" id="home">
    <div class="container">
        <div class="hero-content">

            <h1>
                Industrial Automation
                <span>& Engineering Solutions</span>
            </h1>

            <p>
                TLM Automations Pvt. Ltd. provides complete Industrial Automation,
                Mechanical Engineering, Machine Development and Industrial Support Solutions.
            </p>

            <a href="#services" class="btn btn-primary">
                Explore Our Services
            </a>

            <a href="#contact" class="btn btn-outline">
                Contact Us
            </a>

        </div>
    </div>
</section>

<!-- ABOUT -->

<section id="about">
    <div class="container">

        <div class="section-title">
            <h2>About TLM Automations</h2>
            <p>
                Engineering solutions designed for productivity, reliability and industrial performance.
            </p>
        </div>

        <div class="about-grid">

            <div class="about-image"></div>

            <div class="about-text">

                <h3>Your Industrial Engineering Partner</h3>

                <p>
                    TLM Automations Pvt. Ltd. is focused on delivering
                    complete industrial automation and engineering solutions
                    for manufacturing industries.
                </p>

                <p>
                    Our capabilities include automation projects, PLC programming,
                    machine development, mechanical fixtures, control panels,
                    robotic integration and production line modifications.
                </p>

                <p>
                    We work closely with customers to improve productivity,
                    quality, safety and machine reliability.
                </p>

                <a href="#contact" class="btn btn-primary">
                    Talk to Our Team
                </a>

            </div>

        </div>
    </div>
</section>

<!-- SERVICES -->

<section class="services" id="services">

    <div class="container">

        <div class="section-title">
            <h2>Our Services</h2>
            <p>
                Complete engineering and automation solutions from concept to production.
            </p>
        </div>

        <div class="service-grid">

            <div class="service-card">
                <div class="service-icon">⚙️</div>
                <h3>Industrial Automation</h3>
                <p>
                    Automation projects, machine controls, process automation
                    and production line improvements.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">💻</div>
                <h3>PLC Programming</h3>
                <p>
                    Siemens, Schneider, Allen Bradley, Mitsubishi and Delta PLC
                    programming and troubleshooting.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">🔧</div>
                <h3>Machine Development</h3>
                <p>
                    Special purpose machines, assembly machines and machine
                    development from concept to commissioning.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">🏗️</div>
                <h3>Fixtures & Jigs</h3>
                <p>
                    Precision mechanical fixtures, jigs and hydraulic/pneumatic
                    clamping solutions.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">🤖</div>
                <h3>Robotic Integration</h3>
                <p>
                    Robot integration, pick & place, material handling and
                    automated production solutions.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">👁️</div>
                <h3>Vision Inspection</h3>
                <p>
                    Camera-based inspection, quality checking and
                    automated defect detection.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">⚡</div>
                <h3>Control Panels</h3>
                <p>
                    Electrical control panel design, manufacturing,
                    wiring and commissioning.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">🚚</div>
                <h3>Conveyor Systems</h3>
                <p>
                    Conveyor design, manufacturing, installation and
                    production material handling systems.
                </p>
            </div>

            <div class="service-card">
                <div class="service-icon">🛠️</div>
                <h3>AMC & Breakdown Support</h3>
                <p>
                    Preventive maintenance, breakdown support,
                    troubleshooting and machine service.
                </p>
            </div>

        </div>
    </div>
</section>

<!-- EXPERTISE -->

<section>

    <div class="container">

        <div class="section-title">
            <h2>Our Expertise</h2>
            <p>
                Engineering capabilities supporting modern manufacturing operations.
            </p>
        </div>

        <div class="expertise-grid">

            <div class="expertise">⚙️<strong>Mechanical Design</strong></div>
            <div class="expertise">🔌<strong>Electrical Engineering</strong></div>
            <div class="expertise">🧠<strong>PLC & HMI</strong></div>
            <div class="expertise">🤖<strong>Robotics</strong></div>
            <div class="expertise">👁️<strong>Machine Vision</strong></div>
            <div class="expertise">💨<strong>Pneumatics</strong></div>
            <div class="expertise">💧<strong>Hydraulics</strong></div>
            <div class="expertise">🏭<strong>Production Lines</strong></div>

        </div>

    </div>

</section>

<!-- PROJECTS -->

<section class="projects" id="projects">

    <div class="container">

        <div class="section-title">
            <h2>Our Projects</h2>
            <p>
                Engineering solutions developed for industrial production environments.
            </p>
        </div>

        <div class="project-grid">

            <div class="project">
                <div class="project-img"></div>
                <div class="project-content">
                    <h3>Automation Projects</h3>
                    <p>
                        Automated production systems and machine control solutions.
                    </p>
                </div>
            </div>

            <div class="project">
                <div class="project-img"></div>
                <div class="project-content">
                    <h3>Machine Development</h3>
                    <p>
                        Special purpose machines and production equipment.
                    </p>
                </div>
            </div>

            <div class="project">
                <div class="project-img"></div>
                <div class="project-content">
                    <h3>Industrial Engineering</h3>
                    <p>
                        Mechanical, electrical and production line improvement projects.
                    </p>
                </div>
            </div>

        </div>

    </div>

</section>

<!-- CTA -->

<section class="cta">

    <div class="container">

        <h2>Have an Industrial Automation Requirement?</h2>

        <p>
            Talk to TLM Automations about your next automation or engineering project.
        </p>

        <a href="#contact" class="btn btn-primary">
            Send an Enquiry
        </a>

    </div>

</section>

<!-- CONTACT -->

<section id="contact">

    <div class="container">

        <div class="section-title">
            <h2>Contact Us</h2>
            <p>
                Let's discuss your automation and engineering requirements.
            </p>
        </div>

        <div class="contact-grid">

            <div class="contact-info">

                <h3>TLM Automations Pvt. Ltd.</h3>

                <div class="contact-item">
                    <strong>📍 Location</strong>
                    <span>Hyderabad, Telangana, India</span>
                </div>

                <div class="contact-item">
                    <strong>📞 Phone</strong>
                    <span>+91 99598 08885</span>
                </div>

                <div class="contact-item">
                    <strong>✉️ Email</strong>
                    <span>madhu@tlmautomations.com</span>
                </div>

                <div class="contact-item">
                    <strong>🌐 Website</strong>
                    <span>tlmautomations.com</span>
                </div>

            </div>

            <form class="contact-form"
                  onsubmit="sendWhatsApp(); return false;">

                <input type="text" id="name" placeholder="Your Name" required>

                <input type="email" id="email" placeholder="Your Email" required>

                <input type="text" id="company" placeholder="Company Name">

                <textarea id="message"
                    placeholder="Tell us about your requirement..."
                    required></textarea>

                <button class="btn btn-primary" type="submit">
                    Send Enquiry on WhatsApp
                </button>

            </form>

        </div>

    </div>

</section>

<!-- FOOTER -->

<footer>

    <div class="container">

        <h3>TLM AUTOMATIONS PVT. LTD.</h3>

        <p>
            Industrial Automation • Mechanical Engineering • Machine Development
        </p>

        <p style="margin-top:15px;">
            © 2026 TLM Automations Pvt. Ltd. All Rights Reserved.
        </p>

    </div>

</footer>

<!-- WHATSAPP -->

<a class="whatsapp"
   href="https://wa.me/919959808885"
   target="_blank"
   aria-label="WhatsApp">
    ☎
</a>

<script>

function toggleMenu() {
    document.getElementById("navLinks").classList.toggle("active");
}

function sendWhatsApp() {

    const name = document.getElementById("name").value;
    const email = document.getElementById("email").value;
    const company = document.getElementById("company").value;
    const message = document.getElementById("message").value;

    const text =
        "TLM Automations Website Enquiry%0A%0A" +
        "Name: " + encodeURIComponent(name) + "%0A" +
        "Email: " + encodeURIComponent(email) + "%0A" +
        "Company: " + encodeURIComponent(company) + "%0A" +
        "Requirement: " + encodeURIComponent(message);

    window.open(
        "https://wa.me/919959808885?text=" + text,
        "_blank"
    );
}

</script>

</body>
</html>
```
