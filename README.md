<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Laiba AK | Brand Collaborations</title>

<style>
:root {
    --bg: #f7f7f5;
    --card: #ffffff;
    --text: #151515;
    --muted: #666;
    --border: #e5e5e5;
    --accent: #111;
    --green: #25D366;
}

[data-theme="dark"] {
    --bg: #0d0d0f;
    --card: #171719;
    --text: #ffffff;
    --muted: #aaa;
    --border: #2b2b2f;
    --accent: #fff;
}

* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

/* NAVIGATION */

nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background: var(--bg);
    border-bottom: 1px solid var(--border);
}

.nav-container {
    max-width: 1100px;
    margin: auto;
    height: 70px;
    padding: 0 25px;

    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 22px;
    font-weight: 900;
    letter-spacing: -1px;
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 25px;
}

.nav-links a {
    text-decoration: none;
    color: var(--muted);
    font-size: 14px;
}

.theme-btn {
    border: 1px solid var(--border);
    background: var(--card);
    color: var(--text);
    border-radius: 50px;
    padding: 9px 14px;
    cursor: pointer;
}

/* HERO */

.hero {
    max-width: 1100px;
    margin: auto;
    padding: 100px 25px 70px;
}

.badge {
    display: inline-block;
    padding: 7px 14px;
    border: 1px solid var(--border);
    border-radius: 50px;
    color: var(--muted);
    font-size: 13px;
}

h1 {
    font-size: clamp(50px, 9vw, 95px);
    line-height: .95;
    letter-spacing: -5px;
    margin: 25px 0;
}

.gradient {
    background: linear-gradient(90deg,#111,#888);
    -webkit-background-clip: text;
    color: transparent;
}

[data-theme="dark"] .gradient {
    background: linear-gradient(90deg,#fff,#777);
    -webkit-background-clip: text;
    color: transparent;
}

.hero-text {
    max-width: 680px;
    color: var(--muted);
    font-size: 19px;
}

.buttons {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    margin-top: 30px;
}

.btn {
    padding: 14px 20px;
    border-radius: 12px;
    text-decoration: none;
    font-weight: bold;
    border: 1px solid var(--border);
}

.primary {
    background: var(--accent);
    color: var(--bg);
}

.secondary {
    background: var(--card);
    color: var(--text);
}

/* STATS */

.stats {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 15px;
    margin-top: 55px;
}

.stat {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 18px;
    padding: 22px;
}

.stat-number {
    display: block;
    font-size: 25px;
    font-weight: 900;
}

.stat-label {
    color: var(--muted);
    font-size: 13px;
}

/* SECTIONS */

section {
    padding: 70px 25px;
}

.container {
    max-width: 1100px;
    margin: auto;
}

.eyebrow {
    text-transform: uppercase;
    letter-spacing: 2px;
    color: var(--muted);
    font-size: 12px;
    font-weight: bold;
}

h2 {
    font-size: 42px;
    line-height: 1;
    letter-spacing: -2px;
    margin-top: 8px;
}

/* PACKAGES */

.cards {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 18px;
}

.card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 22px;
    padding: 28px;
}

.price {
    font-size: 38px;
    font-weight: 900;
    margin: 15px 0;
}

.card p,
.card li {
    color: var(--muted);
}

.card ul {
    padding-left: 20px;
}

.featured {
    border-color: var(--accent);
}

/* SOCIALS */

.socials {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 15px;
}

.social {
    text-decoration: none;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 18px;
    padding: 22px;
}

.social strong {
    display: block;
    margin-bottom: 5px;
}

.social span {
    color: var(--muted);
    font-size: 13px;
}

/* FORM */

.form-grid {
    display: grid;
    grid-template-columns: .8fr 1.2fr;
    gap: 20px;
}

.panel {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 24px;
    padding: 30px;
}

.panel p {
    color: var(--muted);
}

form {
    display: grid;
    gap: 15px;
}

label {
    font-size: 13px;
    font-weight: bold;
}

input,
select,
textarea {
    width: 100%;
    margin-top: 7px;
    padding: 14px;

    border: 1px solid var(--border);
    border-radius: 12px;

    background: var(--bg);
    color: var(--text);

    font: inherit;
}

textarea {
    min-height: 120px;
    resize: vertical;
}

.whatsapp {
    border: none;
    background: var(--green);
    color: #071b0d;
    cursor: pointer;
    font-size: 15px;
}

.note {
    color: var(--muted);
    font-size: 12px;
}

/* FOOTER */

footer {
    border-top: 1px solid var(--border);
    padding: 30px 25px;
    color: var(--muted);
    font-size: 13px;
}

/* MOBILE */

@media(max-width:800px) {

    .nav-links {
        display: none;
    }

    .stats,
    .cards,
    .socials,
    .form-grid {
        grid-template-columns: 1fr 1fr;
    }

}

@media(max-width:550px) {

    h1 {
        font-size: 55px;
        letter-spacing: -3px;
    }

    .stats,
    .cards,
    .socials,
    .form-grid {
        grid-template-columns: 1fr;
    }

    section {
        padding: 55px 20px;
    }

    .hero {
        padding: 70px 20px;
    }
}
</style>
</head>

<body>

<!-- NAVIGATION -->

<nav>

<div class="nav-container">

<div class="logo">
LAIBA AK
</div>

<div class="nav-links">

<a href="#services">Collaborations</a>

<a href="#socials">Socials</a>

<a href="#contact">Enquire</a>

<button class="theme-btn" id="themeButton">
☾ Dark
</button>

</div>

</div>

</nav>


<!-- HERO -->

<section class="hero">

<span class="badge">
Creator • Vlogger • Azad Kashmir
</span>

<h1>
Put your brand<br>
<span class="gradient">
in the story.
</span>
</h1>

<p class="hero-text">

I'm <strong>Laiba AK</strong>, a creator from Azad Kashmir.
I've been making videos for over 2.5 years and collaborate
with businesses and brands through authentic promotional content.

</p>

<div class="buttons">

<a href="#contact" class="btn primary">
Start a Collaboration
</a>

<a href="#services" class="btn secondary">
View Packages
</a>

</div>


<div class="stats">

<div class="stat">
<span class="stat-number">12.4K+</span>
<span class="stat-label">YouTube audience</span>
</div>

<div class="stat">
<span class="stat-number">2.5+</span>
<span class="stat-label">Years creating</span>
</div>

<div class="stat">
<span class="stat-number">70 KM</span>
<span class="stat-label">Standard radius</span>
</div>

<div class="stat">
<span class="stat-number">4</span>
<span class="stat-label">Social platforms</span>
</div>

</div>

</section>


<!-- SERVICES -->

<section id="services">

<div class="container">

<div class="eyebrow">
Collaboration Packages
</div>

<h2>
Simple. Clear. Professional.
</h2>


<div class="cards">


<div class="card featured">

<div class="eyebrow">
Local Business Promotion
</div>

<div class="price">
PKR 30,000
</div>

<p>
For businesses located within a
<strong>70 km radius.</strong>
</p>

<ul>

<li>Promotional content</li>

<li>Business/product focused video</li>

<li>Social media promotion</li>

<li>Campaign discussion before posting</li>

</ul>

</div>



<div class="card">

<div class="eyebrow">
Outside 70 KM
</div>

<div class="price">
PKR 40,000
</div>

<p>
For businesses located
<strong>more than 70 km away.</strong>
</p>

<ul>

<li>Promotional content</li>

<li>Location-based collaboration</li>

<li>Product/business promotion</li>

<li>Campaign discussion before posting</li>

</ul>

</div>



<div class="card">

<div class="eyebrow">
PR Product Promotion
</div>

<div class="price">
PKR 3,000
</div>

<p>
Promotion for PR products and
brand gifting campaigns.
</p>

<ul>

<li>Product-focused promotion</li>

<li>PR/gifting campaigns</li>

<li>Promotion details confirmed beforehand</li>

</ul>

</div>

</div>

</div>

</section>


<!-- SOCIAL MEDIA -->

<section id="socials">

<div class="container">

<div class="eyebrow">
Find Laiba Online
</div>

<h2>
Social Channels
</h2>


<div class="socials">

<a
class="social"
href="https://youtube.com/@laibaakvlogs?si=9SCgi2G3HHhH5ynb"
target="_blank">

<strong>
YouTube
</strong>

<span>
@laibaakvlogs
</span>

</a>



<a
class="social"
href="https://www.instagram.com/laibaromanak?stkn=OWVvNDEzM29jOGZ5&utm_source=qr"
target="_blank">

<strong>
Instagram
</strong>

<span>
@laibaromanak
</span>

</a>



<a
class="social"
href="https://www.tiktok.com/@laibaakyoutube?_r=1&_t=ZN-9ABe2YbGFeQ"
target="_blank">

<strong>
TikTok
</strong>

<span>
@laibaakyoutube
</span>

</a>



<a
class="social"
href="https://www.facebook.com/share/18oAFtzYZa/?mibextid=wwXIfr"
target="_blank">

<strong>
Facebook
</strong>

<span>
Laiba AK
</span>

</a>

</div>

</div>

</section>


<!-- CONTACT -->

<section id="contact">

<div class="container">

<div class="form-grid">


<div class="panel">

<div class="eyebrow">
Business Enquiries
</div>

<h2>
Let's work together.
</h2>

<p>

Interested in promoting your business or product?

Fill in the enquiry form and your information
will be prepared automatically for WhatsApp.

</p>

<p class="note">

Your exact home location is not displayed
publicly on this website.

</p>

</div>



<div class="panel">

<form id="collaborationForm">


<div>

<label>
Your Name

<input
type="text"
id="name"
placeholder="Your full name"
required
>

</label>

</div>



<div>

<label>
Business / Brand Name

<input
type="text"
id="business"
placeholder="Business name"
required
>

</label>

</div>



<div>

<label>
Business Location

<input
type="text"
id="location"
placeholder="City / area"
required
>

</label>

</div>



<div>

<label>
What would you like to promote?

<select id="promotion" required>

<option value="">
Select an option
</option>

<option>
Business promotion — PKR 30,000
(within 70 km)
</option>

<option>
Business promotion — PKR 40,000
(over 70 km)
</option>

<option>
PR product promotion — PKR 3,000
</option>

<option>
Other / Custom Collaboration
</option>

</select>

</label>

</div>



<div>

<label>
Tell us about your product / campaign

<textarea
id="details"
placeholder="Tell us about your business, product or campaign..."
required
></textarea>

</label>

</div>



<button
type="submit"
class="btn whatsapp"
>

Continue to WhatsApp

</button>


<div class="note">

WhatsApp: 0340-0506456

<br>

Submitting this form does not automatically confirm a collaboration.

</div>

</form>

</div>

</div>

</div>

</section>


<!-- FOOTER -->

<footer>

<div class="container">

©️ 2026 Laiba AK • Brand Collaborations • Azad Kashmir

</div>

</footer>



<script>

/* DARK / LIGHT MODE */

const themeButton =
document.getElementById("themeButton");

const savedTheme =
localStorage.getItem("laibaTheme");

if(savedTheme === "dark") {

document.documentElement
.setAttribute("data-theme","dark");

themeButton.textContent = "☀ Light";

}


themeButton.addEventListener("click",function(){

const current =
document.documentElement
.getAttribute("data-theme");

if(current === "dark"){

document.documentElement
.removeAttribute("data-theme");

localStorage.setItem(
"laibaTheme",
"light"
);

themeButton.textContent =
"☾ Dark";

}

else{

document.documentElement
.setAttribute("data-theme","dark");

localStorage.setItem(
"laibaTheme",
"dark"
);

themeButton.textContent =
"☀ Light";

}

});


/* WHATSAPP FORM */

document
.getElementById("collaborationForm")
.addEventListener("submit",function(event){

event.preventDefault();


const name =
document.getElementById("name").value.trim();

const business =
document.getElementById("business").value.trim();

const location =
document.getElementById("location").value.trim();

const promotion =
document.getElementById("promotion").value;

const details =
document.getElementById("details").value.trim();


const message =

`Hello Laiba AK Collaboration Team!

Name: ${name}

Business / Brand:
${business}

Business Location:
${location}

Promotion:
${promotion}

Product / Campaign Details:
${details}

I would like to discuss a collaboration.`;


const whatsappURL =
"https://wa.me/923400506456?text="
+
encodeURIComponent(message);


/*
The customer only reaches WhatsApp
AFTER completing the enquiry form.
*/

window.open(
whatsappURL,
"_blank"
);

});

</script>

</body>
</html>
