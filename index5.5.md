
## 1. Objective

The objective of this assignment is to style a multi-page college club website using external CSS. The website includes a Home page, About page, Registration page, and Contact page. CSS variables, selectors, reusable styles, forms, tables, navigation, and buttons are used to create a consistent and responsive design.

## 2. Project Folder Structure

Create a folder named `Assignment-5.5` with the following files:

```text
Assignment-5.5/
│
├── index.html
├── about.html
├── registration.html
├── contact.html
├── style.css
└── Assignment-5.5.md
```

All four HTML pages use the same external stylesheet, `style.css`, to maintain a consistent design.

## 3. HTML Code — Home Page (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | College Club</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="site-header">
        <div class="container">
            <a class="logo" href="index.html">CampusConnect</a>
            <p class="header-tagline">Learn Together. Grow Together.</p>
        </div>
    </header>

    <nav class="navbar" aria-label="Main navigation">
        <div class="container nav-links">
            <a class="active" href="index.html" aria-current="page">Home</a>
            <a href="about.html">About</a>
            <a href="registration.html">Registration</a>
            <a href="contact.html">Contact</a>
        </div>
    </nav>

    <main class="container">
        <section class="hero">
            <p class="eyebrow">WELCOME TO OUR CAMPUS</p>
            <h1>Discover Your Potential</h1>
            <p>
                Join our college club to explore your interests,
                develop new skills, participate in activities, and
                build lasting friendships.
            </p>
            <a class="btn btn-primary" href="registration.html">
                Join Our Club
            </a>
            <a class="btn btn-outline" href="about.html">
                Learn More
            </a>
        </section>

        <section class="section">
            <h2 class="section-title">What We Offer</h2>

            <div class="card-grid">
                <article class="card">
                    <h3>Skill Development</h3>
                    <p>
                        Improve communication, teamwork, leadership,
                        and problem-solving skills through club activities.
                    </p>
                </article>

                <article class="card">
                    <h3>Events and Activities</h3>
                    <p>
                        Participate in workshops, competitions,
                        presentations, and cultural events.
                    </p>
                </article>

                <article class="card">
                    <h3>Teamwork</h3>
                    <p>
                        Collaborate with fellow students, share ideas,
                        and learn from different experiences.
                    </p>
                </article>
            </div>
        </section>

        <section class="cta-section">
            <h2>Become a Part of Our Community</h2>
            <p>
                Take the first step toward an exciting college experience.
            </p>
            <a class="btn btn-primary" href="registration.html">
                Register Now
            </a>
        </section>
    </main>

    <footer class="site-footer">
        <div class="container">
            <p>&copy; 2026 CampusConnect College Club. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
```

## 4. HTML Code — About Page (about.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About | College Club</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="site-header">
        <div class="container">
            <a class="logo" href="index.html">CampusConnect</a>
            <p class="header-tagline">Learn Together. Grow Together.</p>
        </div>
    </header>

    <nav class="navbar" aria-label="Main navigation">
        <div class="container nav-links">
            <a href="index.html">Home</a>
            <a class="active" href="about.html" aria-current="page">About</a>
            <a href="registration.html">Registration</a>
            <a href="contact.html">Contact</a>
        </div>
    </nav>

    <main class="container">
        <section class="page-banner">
            <h1>About Our College Club</h1>
            <p>Learn about our purpose, activities, and community.</p>
        </section>

        <section class="section">
            <h2 class="section-title">Who We Are</h2>
            <p>
                CampusConnect is a sample college club website created
                as a web development mini-project. The club represents
                a student community where members can learn, collaborate,
                and participate in educational and extracurricular activities.
            </p>
        </section>

        <section class="section">
            <h2 class="section-title">Our Mission</h2>
            <p>
                Our mission is to encourage creativity, teamwork,
                leadership, and continuous learning among students.
                We aim to provide opportunities for students to discover
                their interests and develop useful skills.
            </p>
        </section>

        <section class="section">
            <h2 class="section-title">Our Activities</h2>

            <div class="card-grid">
                <article class="card">
                    <h3>Workshops</h3>
                    <p>Learn new concepts through interactive sessions.</p>
                </article>

                <article class="card">
                    <h3>Competitions</h3>
                    <p>Test your knowledge and exchange creative ideas.</p>
                </article>

                <article class="card">
                    <h3>Community Projects</h3>
                    <p>Work together on useful student-led initiatives.</p>
                </article>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Club Information</h2>

            <div class="table-wrapper">
                <table>
                    <thead>
                        <tr>
                            <th>Activity</th>
                            <th>Purpose</th>
                            <th>Frequency</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Workshops</td>
                            <td>Learn new skills</td>
                            <td>Monthly</td>
                        </tr>
                        <tr>
                            <td>Competitions</td>
                            <td>Encourage creativity</td>
                            <td>As scheduled</td>
                        </tr>
                        <tr>
                            <td>Team Meetings</td>
                            <td>Plan club activities</td>
                            <td>As scheduled</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <div class="centered-action">
            <a class="btn btn-primary" href="registration.html">
                Become a Member
            </a>
        </div>
    </main>

    <footer class="site-footer">
        <div class="container">
            <p>&copy; 2026 CampusConnect College Club. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
```

## 5. HTML Code — Registration Page (registration.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration | College Club</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="site-header">
        <div class="container">
            <a class="logo" href="index.html">CampusConnect</a>
            <p class="header-tagline">Learn Together. Grow Together.</p>
        </div>
    </header>

    <nav class="navbar" aria-label="Main navigation">
        <div class="container nav-links">
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a class="active" href="registration.html" aria-current="page">
                Registration
            </a>
            <a href="contact.html">Contact</a>
        </div>
    </nav>

    <main class="container">
        <section class="page-banner">
            <h1>Club Registration</h1>
            <p>Complete the form to express your interest in joining.</p>
        </section>

        <section class="form-section">
            <h2 class="section-title">Membership Form</h2>

            <form action="#" method="get">
                <div class="form-group">
                    <label for="fullname">Full Name</label>
                    <input
                        type="text"
                        id="fullname"
                        name="fullname"
                        placeholder="Enter your full name"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input
                        type="email"
                        id="email"
                        name="email"
                        placeholder="student@example.com"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input
                        type="tel"
                        id="phone"
                        name="phone"
                        placeholder="Enter your phone number"
                        pattern="[0-9]{10}"
                        title="Enter a 10-digit phone number"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="course">Course</label>
                    <select id="course" name="course" required>
                        <option value="">Select your course</option>
                        <option value="B.Tech CSE">B.Tech CSE</option>
                        <option value="BCA">BCA</option>
                        <option value="MCA">MCA</option>
                        <option value="Other">Other</option>
                    </select>
                </div>

                <fieldset class="form-group">
                    <legend>Preferred Club Activity</legend>

                    <label class="radio-label">
                        <input
                            type="radio"
                            name="activity"
                            value="Technical"
                            required
                        >
                        Technical Activities
                    </label>

                    <label class="radio-label">
                        <input
                            type="radio"
                            name="activity"
                            value="Cultural"
                        >
                        Cultural Activities
                    </label>

                    <label class="radio-label">
                        <input
                            type="radio"
                            name="activity"
                            value="Sports"
                        >
                        Sports and Fitness
                    </label>
                </fieldset>

                <div class="form-group">
                    <label for="reason">Why do you want to join?</label>
                    <textarea
                        id="reason"
                        name="reason"
                        rows="5"
                        placeholder="Write a short introduction..."
                        required
                    ></textarea>
                </div>

                <label class="checkbox-label">
                    <input type="checkbox" name="agreement" required>
                    I confirm that the information provided is correct.
                </label>

                <button class="btn btn-primary submit-btn" type="submit">
                    Submit Registration
                </button>
            </form>

            <p class="form-note">
                Demo form only: this page does not store or send
                registration details to a server.
            </p>
        </section>
    </main>

    <footer class="site-footer">
        <div class="container">
            <p>&copy; 2026 CampusConnect College Club. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
```

## 6. HTML Code — Contact Page (contact.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact | College Club</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="site-header">
        <div class="container">
            <a class="logo" href="index.html">CampusConnect</a>
            <p class="header-tagline">Learn Together. Grow Together.</p>
        </div>
    </header>

    <nav class="navbar" aria-label="Main navigation">
        <div class="container nav-links">
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="registration.html">Registration</a>
            <a class="active" href="contact.html" aria-current="page">Contact</a>
        </div>
    </nav>

    <main class="container">
        <section class="page-banner">
            <h1>Contact Us</h1>
            <p>We welcome your questions, ideas, and suggestions.</p>
        </section>

        <section class="section">
            <h2 class="section-title">Get in Touch</h2>

            <div class="contact-card">
                <h3>Email</h3>
                <p>
                    <a href="mailto:club@example.com">club@example.com</a>
                </p>
            </div>

            <div class="contact-card">
                <h3>Office Hours</h3>
                <p>Monday to Friday, 10:00 AM to 4:00 PM</p>
            </div>

            <div class="contact-card">
                <h3>Location</h3>
                <p>College Campus, Student Activity Centre</p>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Send Us a Message</h2>

            <form action="#" method="get">
                <div class="form-group">
                    <label for="contact-name">Your Name</label>
                    <input
                        type="text"
                        id="contact-name"
                        name="name"
                        placeholder="Enter your name"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="contact-email">Your Email</label>
                    <input
                        type="email"
                        id="contact-email"
                        name="email"
                        placeholder="Enter your email"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea
                        id="message"
                        name="message"
                        rows="5"
                        placeholder="Write your message"
                        required
                    ></textarea>
                </div>

                <button class="btn btn-primary" type="submit">
                    Send Message
                </button>
            </form>

            <p class="form-note">
                Demo form only: messages are not sent to a server.
            </p>
        </section>
    </main>

    <footer class="site-footer">
        <div class="container">
            <p>&copy; 2026 CampusConnect College Club. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
```

## 7. External CSS Code (style.css)

Create `style.css` in the same folder as all four HTML files.

```css
/* =========================================
   1. CSS VARIABLES / DESIGN TOKENS
   ========================================= */

:root {
    --color-primary: #1d4ed8;
    --color-primary-dark: #1e40af;
    --color-secondary: #0f766e;
    --color-background: #f1f5f9;
    --color-surface: #ffffff;
    --color-text: #1e293b;
    --color-muted: #64748b;
    --color-border: #cbd5e1;
    --color-light: #dbeafe;
    --color-success: #15803d;
    --color-danger: #b91c1c;

    --font-family: Arial, Helvetica, sans-serif;

    --font-size-small: 14px;
    --font-size-base: 16px;
    --font-size-heading: 28px;

    --space-small: 8px;
    --space-medium: 16px;
    --space-large: 32px;

    --container-width: 1100px;
    --radius-small: 6px;
    --radius-medium: 12px;

    --shadow-card: 0 4px 14px rgba(15, 23, 42, 0.07);
}

/* =========================================
   2. RESET AND GENERAL STYLES
   ========================================= */

* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    font-family: var(--font-family);
    font-size: var(--font-size-base);
    line-height: 1.7;
    color: var(--color-text);
    background-color: var(--color-background);
}

.container {
    width: 90%;
    max-width: var(--container-width);
    margin: 0 auto;
}

h1,
h2,
h3 {
    line-height: 1.3;
}

h1,
h2,
h3,
p {
    overflow-wrap: break-word;
}

p {
    margin-top: 0;
    margin-bottom: var(--space-medium);
}

a {
    color: var(--color-primary);
}

a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible {
    outline: 3px solid var(--color-secondary);
    outline-offset: 3px;
}

/* =========================================
   3. HEADER AND LOGO
   ========================================= */

.site-header {
    background-color: var(--color-primary);
    color: var(--color-surface);
    padding: var(--space-large) 0;
    text-align: center;
}

.logo {
    display: inline-block;
    color: var(--color-surface);
    font-size: 32px;
    font-weight: 700;
    text-decoration: none;
    letter-spacing: 0.5px;
}

.header-tagline {
    color: var(--color-light);
    margin: var(--space-small) 0 0;
}

/* =========================================
   4. NAVIGATION
   ========================================= */

.navbar {
    background-color: var(--color-surface);
    border-bottom: 1px solid var(--color-border);
    box-shadow: 0 2px 5px rgba(15, 23, 42, 0.04);
}

.nav-links {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: var(--space-small);
    padding: var(--space-medium) 0;
}

.nav-links a {
    display: inline-block;
    padding: 10px 16px;
    color: var(--color-text);
    text-decoration: none;
    font-weight: 600;
    border-radius: var(--radius-small);
    transition: background-color 0.2s ease, color 0.2s ease;
}

.nav-links a:hover,
.nav-links a.active {
    background-color: var(--color-primary);
    color: var(--color-surface);
}

/* =========================================
   5. HERO AND PAGE BANNER
   ========================================= */

.hero {
    text-align: center;
    padding: 65px 25px;
    margin-top: var(--space-large);
    margin-bottom: var(--space-large);
    background: linear-gradient(135deg, #dbeafe, #ccfbf1);
    border-radius: var(--radius-medium);
}

.eyebrow {
    color: var(--color-secondary);
    font-size: var(--font-size-small);
    font-weight: 700;
    letter-spacing: 2px;
}

.hero h1 {
    font-size: 42px;
    color: var(--color-primary-dark);
    margin: var(--space-small) 0 var(--space-medium);
}

.hero p:not(.eyebrow) {
    max-width: 700px;
    margin: 0 auto var(--space-large);
    color: var(--color-muted);
}

.page-banner {
    text-align: center;
    padding: 42px 20px;
    margin-top: var(--space-large);
    margin-bottom: var(--space-large);
    background-color: var(--color-light);
    border-radius: var(--radius-medium);
}

.page-banner h1 {
    color: var(--color-primary-dark);
    font-size: 34px;
    margin: 0 0 var(--space-small);
}

.page-banner p {
    margin-bottom: 0;
    color: var(--color-muted);
}

/* =========================================
   6. BUTTONS
   ========================================= */

.btn {
    display: inline-block;
    padding: 11px 20px;
    margin: 4px;
    border: 2px solid transparent;
    border-radius: var(--radius-small);
    font-family: var(--font-family);
    font-size: var(--font-size-base);
    font-weight: 700;
    text-align: center;
    text-decoration: none;
    cursor: pointer;
    transition: background-color 0.2s ease, color 0.2s ease;
}

.btn-primary {
    background-color: var(--color-primary);
    color: var(--color-surface);
}

.btn-primary:hover {
    background-color: var(--color-primary-dark);
}

.btn-outline {
    background-color: transparent;
    border-color: var(--color-primary);
    color: var(--color-primary-dark);
}

.btn-outline:hover {
    background-color: var(--color-primary);
    color: var(--color-surface);
}

/* =========================================
   7. MAIN SECTIONS AND CARDS
   ========================================= */

main.container {
    padding-bottom: var(--space-large);
}

.section {
    background-color: var(--color-surface);
    padding: var(--space-large);
    margin-bottom: var(--space-large);
    border: 1px solid #e2e8f0;
    border-radius: var(--radius-medium);
    box-shadow: var(--shadow-card);
}

.section-title {
    font-size: var(--font-size-heading);
    color: var(--color-primary-dark);
    margin: 0 0 var(--space-medium);
}

.card-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: var(--space-medium);
    margin-top: var(--space-large);
}

.card {
    padding: 24px;
    background-color: var(--color-surface);
    border: 1px solid var(--color-border);
    border-top: 4px solid var(--color-primary);
    border-radius: var(--radius-medium);
    box-shadow: var(--shadow-card);
}

.card h3 {
    margin-top: 0;
    color: var(--color-primary-dark);
    font-size: 20px;
}

.card p {
    color: var(--color-muted);
    margin-bottom: 0;
}

.cta-section {
    padding: var(--space-large);
    margin-bottom: var(--space-large);
    text-align: center;
    background-color: var(--color-light);
    border-radius: var(--radius-medium);
}

.cta-section h2 {
    color: var(--color-primary-dark);
}

/* =========================================
   8. TABLE STYLING
   ========================================= */

.table-wrapper {
    width: 100%;
    overflow-x: auto;
}

table {
    width: 100%;
    border-collapse: collapse;
    background-color: var(--color-surface);
    margin-top: var(--space-medium);
}

th,
td {
    border: 1px solid var(--color-border);
    padding: 12px 16px;
    text-align: left;
}

th {
    background-color: var(--color-primary);
    color: var(--color-surface);
    font-weight: 700;
}

tbody tr:nth-child(even) {
    background-color: #f8fafc;
}

tbody tr:hover {
    background-color: var(--color-light);
}

.centered-action {
    text-align: center;
    margin: var(--space-large) 0;
}

/* =========================================
   9. FORM STYLING
   ========================================= */

.form-section {
    max-width: 760px;
    margin: 0 auto var(--space-large);
    padding: var(--space-large);
    background-color: var(--color-surface);
    border: 1px solid #e2e8f0;
    border-radius: var(--radius-medium);
    box-shadow: var(--shadow-card);
}

.form-group {
    margin-bottom: 22px;
    border: 0;
    padding: 0;
}

.form-group > label,
.form-group > legend {
    display: block;
    margin-bottom: var(--space-small);
    color: var(--color-text);
    font-weight: 700;
}

input:not([type="radio"]):not([type="checkbox"]),
select,
textarea {
    display: block;
    width: 100%;
    padding: 12px;
    border: 1px solid var(--color-border);
    border-radius: var(--radius-small);
    background-color: var(--color-surface);
    color: var(--color-text);
    font-family: var(--font-family);
    font-size: var(--font-size-base);
}

textarea {
    resize: vertical;
    min-height: 120px;
}

input::placeholder,
textarea::placeholder {
    color: var(--color-muted);
}

input:focus,
select:focus,
textarea:focus {
    border-color: var(--color-primary);
}

.radio-label,
.checkbox-label {
    display: flex;
    align-items: flex-start;
    gap: var(--space-small);
    margin-bottom: var(--space-small);
    font-weight: 400;
}

.radio-label input,
.checkbox-label input {
    margin-top: 6px;
    accent-color: var(--color-primary);
}

.submit-btn {
    width: 100%;
    margin: var(--space-medium) 0 0;
}

.form-note {
    margin-top: var(--space-medium);
    margin-bottom: 0;
    color: var(--color-muted);
    font-size: var(--font-size-small);
}

/* =========================================
   10. CONTACT CARDS
   ========================================= */

.contact-card {
    padding: var(--space-medium);
    margin-top: var(--space-medium);
    background-color: #f8fafc;
    border-left: 4px solid var(--color-secondary);
    border-radius: var(--radius-small);
}

.contact-card h3 {
    color: var(--color-primary-dark);
    margin: 0 0 var(--space-small);
}

.contact-card p {
    margin-bottom: 0;
}

.contact-card a {
    font-weight: 700;
}

/* =========================================
   11. FOOTER
   ========================================= */

.site-footer {
    background-color: var(--color-text);
    color: var(--color-surface);
    text-align: center;
    padding: 24px 12px;
}

.site-footer p {
    margin: 0;
    font-size: var(--font-size-small);
}

/* =========================================
   12. RESPONSIVE DESIGN
   ========================================= */

@media (max-width: 800px) {
    .card-grid {
        grid-template-columns: 1fr 1fr;
    }

    .hero h1 {
        font-size: 34px;
    }
}

@media (max-width: 560px) {
    .container {
        width: 92%;
    }

    .logo {
        font-size: 26px;
    }

    .nav-links {
        gap: 4px;
    }

    .nav-links a {
        padding: 8px 10px;
        font-size: var(--font-size-small);
    }

    .hero {
        padding: 40px 18px;
    }

    .hero h1,
    .page-banner h1 {
        font-size: 28px;
    }

    .section,
    .form-section {
        padding: var(--space-medium);
    }

    .section-title {
        font-size: 23px;
    }

    .card-grid {
        grid-template-columns: 1fr;
    }

    th,
    td {
        padding: 10px;
    }
}
```

## 8. CSS Variables and Selectors Used

The stylesheet uses CSS variables inside `:root` for reusable colors, font sizes, spacing, border radius, and shadows.

Examples:

```css
:root {
    --color-primary: #1d4ed8;
    --color-background: #f1f5f9;
    --space-medium: 16px;
}

.section {
    background-color: var(--color-surface);
    padding: var(--space-large);
}

.btn-primary {
    background-color: var(--color-primary);
}
```

The following selectors are used:

- **Element selectors:** `body`, `h1`, `p`, `table`, and `input`.
- **Class selectors:** `.navbar`, `.card`, `.btn`, and `.section`.
- **ID selectors:** `id` attributes identify sections and form fields for navigation and labels.
- **Pseudo-classes:** `:hover`, `:focus`, `:focus-visible`, and `:nth-child(even)`.
- **Media queries:** Adjust the layout for mobile and tablet screens.

## 9. How to Run the Website

1. Create the `Assignment-5.5` folder in Visual Studio Code.
2. Create all four HTML files and `style.css`.
3. Copy the relevant code into each file.
4. Save all files using `Ctrl + S`.
5. Make sure all five website files are in the same folder.
6. Open `index.html` with Live Server.
7. Navigate between Home, About, Registration, and Contact.
8. Test the registration form and inspect the table and cards.
9. Resize the browser window to check the responsive layout.

## 10. Debugging with Chrome DevTools

1. Open the website in Google Chrome.
2. Right-click an element and select **Inspect**.
3. In the Elements panel, select the HTML element.
4. Check the Styles panel to confirm that `style.css` is loaded.
5. Change a CSS property temporarily and observe the visual result.
6. If styles are missing, verify the stylesheet link and file name.
7. Open the Console panel to check for errors.
8. Use the device toolbar to test mobile layouts.

**Note:** DevTools changes are temporary. Update the CSS file in Visual Studio Code to keep permanent changes.

## 11. Four-to-Five-Line Explanation of Design Choices

1. A blue, teal, and light-gray color palette was selected to create a clean and professional appearance.
2. Arial was used as the main font because it is simple and easy to read.
3. A shared external stylesheet and CSS variables maintain consistent colors, spacing, buttons, cards, and navigation across all pages.
4. Forms and tables use clear labels, sufficient spacing, borders, and readable text for better usability.
5. Responsive media queries and Chrome DevTools help test the website on different screen sizes and identify styling problems.

## 12. Result

The multi-page college club website was styled successfully using external CSS. The website contains four linked pages with consistent navigation, headings, paragraphs, cards, buttons, forms, and tables. CSS variables and reusable selectors were used to maintain a consistent design, while media queries improved responsiveness.

## 13. Submission

Submit the following files:

1. `index.html` — Home page.
2. `about.html` — About page.
3. `registration.html` — Registration form.
4. `contact.html` — Contact page.
5. `style.css` — Shared external stylesheet.
6. `Assignment-5.5.md` — Assignment documentation.


