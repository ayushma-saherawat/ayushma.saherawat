<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayushma Saherawat | Athlete, Judge, Leader</title>
    <meta name="description" content="Ayushma Saherawat is a national-level gymnast, an FIG-certified international judge, and a leader with an MBA from BITSoM.">
    <meta name="author" content="Ayushma Saherawat">
    <link rel="canonical" href="https://ayushma.github.io/index.html">

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ayushma.github.io/index.html">
    <meta property="og:title" content="Ayushma Saherawat | Athlete, Judge, Leader">
    <meta property="og:description" content="Ayushma Saherawat is a national-level gymnast, an FIG-certified international judge, and a leader with an MBA from BITSoM.">
    <meta property="og:image" content="https://ayushma.github.io/og-image.jpg">

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://ayushma.github.io/index.html">
    <meta property="twitter:title" content="Ayushma Saherawat | Athlete, Judge, Leader">
    <meta property="twitter:description" content="Ayushma Saherawat is a national-level gymnast, an FIG-certified international judge, and a leader with an MBA from BITSoM.">
    <meta property="twitter:image" content="https://ayushma.github.io/og-image.jpg">
    
    <style>
        :root {
            --color-primary: #1e3a8a; /* soft blue */
            --color-secondary: #334155; /* charcoal */
            --color-accent: #60a5fa;
            --color-text: #1f2937;
            --color-background: #f8fafc;
            --color-card-bg: #e2e8f0;
            --font-family-sans: -apple-system, Segoe UI, Roboto, Inter, sans-serif;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --color-text: #f8fafc;
                --color-background: #0f172a;
                --color-card-bg: #1e293b;
            }
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: var(--font-family-sans);
            color: var(--color-text);
            background-color: var(--color-background);
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 1rem;
        }

        header {
            background-color: transparent;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 1rem;
        }

        .nav-link a {
            text-decoration: none;
            color: var(--color-primary);
            font-weight: 600;
        }

        .hamburger {
            display: none;
            cursor: pointer;
            font-size: 2rem;
            color: var(--color-primary);
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
                flex-direction: column;
                position: absolute;
                top: 60px;
                left: 0;
                width: 100%;
                background-color: var(--color-background);
                padding: 1rem;
                border-bottom: 1px solid var(--color-card-bg);
            }
            .nav-links.open {
                display: flex;
            }
            .hamburger {
                display: block;
            }
        }

        section {
            padding: 4rem 1rem;
        }

        h1, h2, h3 {
            line-height: 1.2;
            color: var(--color-secondary);
        }

        h1 {
            font-size: clamp(2rem, 5vw, 4rem);
        }

        h2 {
            font-size: clamp(1.5rem, 4vw, 3rem);
            margin-bottom: 2rem;
            text-align: center;
        }

        h3 {
            font-size: clamp(1.25rem, 3vw, 2rem);
        }

        .hero {
            text-align: center;
            padding: 6rem 1rem;
        }
        
        .hero .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1.5rem;
            border: 4px solid var(--color-primary);
            padding: 4px;
        }

        .hero-title {
            margin-bottom: 0.5rem;
        }

        .hero-subtitle {
            font-size: clamp(1rem, 2.5vw, 1.5rem);
            color: var(--color-primary);
            font-weight: 400;
            margin-bottom: 2rem;
        }

        .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
        }

        .btn {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 9999px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 2px solid var(--color-primary);
        }

        .btn-primary {
            background-color: var(--color-primary);
            color: white;
        }
        .btn-primary:hover {
            background-color: transparent;
            color: var(--color-primary);
        }

        .btn-secondary {
            background-color: transparent;
            color: var(--color-primary);
        }
        .btn-secondary:hover {
            background-color: var(--color-primary);
            color: white;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }

        .story-content {
            max-width: 700px;
            margin: 0 auto;
            text-align: justify;
        }
        .story-content p {
            margin-bottom: 1rem;
        }

        .highlights-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .highlight-card {
            background-color: var(--color-card-bg);
            padding: 1.5rem;
            border-radius: 0.5rem;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .highlight-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0,0,0,0.15);
        }
        .highlight-card .icon {
            font-size: 2.5rem;
            color: var(--color-primary);
            margin-bottom: 1rem;
        }
        .highlight-card h3 {
            margin-bottom: 0.5rem;
        }
        .highlight-card p {
            font-size: 0.9rem;
            color: var(--color-secondary);
        }

        .timeline-item {
            display: flex;
            margin-bottom: 2rem;
        }
        .timeline-year {
            font-weight: 600;
            color: var(--color-primary);
            min-width: 80px;
        }
        .timeline-content {
            position: relative;
            padding-left: 2rem;
        }
        .timeline-content::before {
            content: '';
            position: absolute;
            left: 0;
            top: 5px;
            width: 10px;
            height: 10px;
            background-color: var(--color-primary);
            border-radius: 50%;
        }
        .timeline-content::after {
            content: '';
            position: absolute;
            left: 4px;
            top: 15px;
            height: calc(100% - 10px);
            width: 2px;
            background-color: var(--color-primary);
        }
        .timeline-item:last-child .timeline-content::after {
            display: none;
        }
        .timeline-content p {
            margin-bottom: 0.5rem;
        }
        .timeline-content ul {
            list-style: none;
            padding-left: 0;
            margin-top: 0.5rem;
            font-size: 0.9rem;
        }
        .timeline-content li {
            margin-bottom: 0.25rem;
        }

        .media-grid, .awards-list {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .media-item {
            background-color: var(--color-card-bg);
            padding: 1rem;
            border-radius: 0.5rem;
            text-align: center;
            flex-basis: 250px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        .media-item a {
            text-decoration: none;
            color: var(--color-secondary);
            font-weight: 600;
        }
        
        .awards-list {
            list-style: none;
            padding: 0;
            gap: 0.5rem;
        }
        .award-item {
            background-color: var(--color-card-bg);
            padding: 0.75rem 1rem;
            border-radius: 9999px;
            font-size: 0.9rem;
        }

        .coaching-content {
            max-width: 700px;
            margin: 0 auto;
            text-align: justify;
        }
        .coaching-content h3 {
            color: var(--color-primary);
            text-align: center;
            margin-bottom: 1rem;
        }
        .coaching-content p {
            margin-bottom: 1rem;
        }
        .coaching-content ul {
            margin-left: 1.5rem;
            margin-bottom: 1rem;
        }

        .contact-form {
            max-width: 500px;
            margin: 0 auto;
        }
        .contact-form label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.75rem;
            margin-bottom: 1rem;
            border: 1px solid var(--color-secondary);
            border-radius: 0.25rem;
            background-color: var(--color-background);
            color: var(--color-text);
        }
        .contact-form button {
            background-color: var(--color-primary);
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 9999px;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .contact-form button:hover {
            background-color: var(--color-accent);
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        .social-icon {
            font-size: 2rem;
            color: var(--color-primary);
            transition: transform 0.2s ease;
        }
        .social-icon:hover {
            transform: scale(1.1);
        }
        .social-icon svg {
            fill: currentColor;
            width: 1em;
            height: 1em;
        }

        .footer {
            text-align: center;
            padding: 2rem 1rem;
            font-size: 0.8rem;
            color: #64748b;
        }

        .to-verify-panel {
            background-color: #fef3c7;
            border-left: 4px solid #fbbf24;
            padding: 1rem;
            margin-top: 2rem;
            color: #92400e;
        }
        .to-verify-panel h3 {
            color: #92400e;
        }
        .to-verify-panel ul {
            list-style-type: disc;
            margin-left: 1.5rem;
            margin-top: 0.5rem;
        }

        /* Print Stylesheet */
        @media print {
            body {
                font-family: 'Times New Roman', serif;
                background: white;
                color: black;
            }
            header, .nav, .hamburger, .cta-buttons, .social-icons, .to-verify-panel, footer {
                display: none !important;
            }
            section {
                padding: 1rem;
            }
            .container {
                padding: 0;
            }
            .hero {
                padding: 1rem 0;
                text-align: left;
            }
            .hero-title, .hero-subtitle {
                text-align: left;
            }
            .hero .avatar {
                float: right;
                margin-left: 2rem;
                border: none;
            }
            .story {
                page-break-after: always;
            }
            .highlights-grid {
                display: block;
            }
            .highlight-card {
                background: none;
                box-shadow: none;
                padding: 0.5rem 0;
                text-align: left;
                border-bottom: 1px dashed #ccc;
            }
            .highlight-card:last-child {
                border-bottom: none;
            }
            .highlight-card:hover {
                transform: none;
            }
            .timeline-item {
                display: flex;
            }
            .timeline-year {
                font-weight: bold;
                color: black;
                min-width: 100px;
            }
            .timeline-content::before, .timeline-content::after {
                background-color: black;
            }
            .awards-list {
                background: none;
                box-shadow: none;
                padding: 0.5rem 0;
            }
            .awards-list {
                display: block;
            }
            .award-item {
                background: none;
                border: 1px solid #ccc;
                border-radius: 0;
                margin-bottom: 0.25rem;
                padding: 0.25rem 0.5rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container nav">
            <span style="font-size: 1.5rem; font-weight: 700; color: var(--color-primary);">Ayushma.</span>
            <div class="hamburger" onclick="toggleMenu()">☰</div>
            <nav class="nav-links">
                <a href="#story" class="nav-link">Story</a>
                <a href="#highlights" class="nav-link">Highlights</a>
                <a href="#timeline" class="nav-link">Timeline</a>
                <a href="#resume" class="nav-link">Resume</a>
                <a href="#contact" class="nav-link">Contact</a>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero" class="hero">
            <h1 class="hero-title">Ayushma Saherawat</h1>
            <p class="hero-subtitle">Gymnast • International Judge • MBA • Leader</p>
            <div class="cta-buttons">
                <a href="mailto:ayushma.work25@gmail.com" class="btn btn-primary">Email</a>
                <a href="https://www.instagram.com/ayushma.saherawat/?hl=en" class="btn btn-secondary" target="_blank">Instagram</a>
                <a href="https://www.linkedin.com/in/ayushma-saherawat-764671236/" class="btn btn-secondary" target="_blank">LinkedIn</a>
            </div>
        </section>

        <section id="story" class="story">
            <div class="container">
                <h2 class="section-title">The Story</h2>
                <div class="story-content">
                    <p>I am a national-level gymnast and FIG-certified international judge from Haryana. My career in sport taught me resilience and discipline, skills I've carried forward as a leader and MBA student at BITSOM. I've served on the Technical Committee for the Gymnastics Federation of India, appointed as its youngest member.</p>
                    <p>My journey is about applying an athlete-first mindset to business. I've led strategic projects and managed end-to-end operations for large events, including a 1.5CR athlete funding proposal to the Sports Authority of India. My work focuses on building sustainable ecosystems for sports, bridging the gap between athletic excellence and professional management.</p>
                </div>
            </div>
        </section>

        <section id="highlights">
            <div class="container">
                <h2 class="section-title">Highlights</h2>
                <div class="highlights-grid">
                    <div class="highlight-card">
                        <span class="icon">⚖️</span>
                        <h3>FIG International Judge</h3>
                        <p>Certified as a Category 3 International Judge, one of six nationwide.</p>
                    </div>
                    <div class="highlight-card">
                        <span class="icon">🏅</span>
                        <h3>Youngest GFI Technical Committee Member</h3>
                        <p>Appointed the youngest member of the National Women's Gymnastics Technical Committee.</p>
                    </div>
                    <div class="highlight-card">
                        <span class="icon">🎓</span>
                        <h3>BITS School of Management</h3>
                        <p>Pursuing an MBA from BITS School of Management, graduating in 2026.</p>
                    </div>
                    <div class="highlight-card">
                        <span class="icon">📚</span>
                        <h3>Academic Excellence</h3>
                        <p>Ranked in the top 0.1% of students in Class XII and was formally felicitated for being the District Topper in Faridabad.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="timeline">
            <div class="container">
                <h2 class="section-title">Timeline</h2>
                <div class="timeline-container">
                    <div class="timeline-item">
                        <div class="timeline-year">2026</div>
                        <div class="timeline-content">
                            <h3>MBA</h3>
                            <p>Graduating from BITS School of Management.</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2025</div>
                        <div class="timeline-content">
                            <h3>Gymnastics Federation of India</h3>
                            <p>Appointed the youngest member of the National Women's Gymnastics Technical Committee.</p>
                            <ul>
                                <li>Became a Category 3 International Judge, 1 of 6 in India.</li>
                                <li>Appointed as an Expert Faculty at the National Judges Course.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2024</div>
                        <div class="timeline-content">
                            <h3>The Gymnastics Academy</h3>
                            <p>Became Manager, achieving 14% revenue growth in 6 months.</p>
                            <ul>
                                <li>Achieved 71% growth in social media reach.</li>
                                <li>Achieved All India Rank 6 at the 52nd Senior National Gymnastics Championship.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2023</div>
                        <div class="timeline-content">
                            <h3>National Games Finalist</h3>
                            <p>Achieved All India Rank 7th and 8th in the Artistic Gymnastics Finals at National Games.</p>
                            <ul>
                                <li>Completed PG Diploma in Yoga Therapy from Guru Nanak Khalsa College.</li>
                                <li>Conducted sports training for underprivileged students.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2022</div>
                        <div class="timeline-content">
                            <h3>University of Delhi</h3>
                            <p>Graduated with a BA in Economics and Political Science from Lady Shri Ram College.</p>
                            <ul>
                                <li>Captained the LSR College team at the All India University Championship.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2019</div>
                        <div class="timeline-content">
                            <h3>Khelo India Youth Games</h3>
                            <p>Represented Haryana at the Khelo India Youth Games in Pune & Guwahati.</p>
                            <ul>
                                <li>Secured First & Second Position at the CBSE National Gymnastics Championship.</li>
                                <li>Achieved 98.8% in Higher Secondary Certificate Exam, becoming District Topper.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2017</div>
                        <div class="timeline-content">
                            <h3>Modern Delhi Public School</h3>
                            <p>Achieved a 9.2/10 in Senior Secondary Examination, ranking in the top 10%.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="resume">
            <div class="container">
                <h2 class="section-title">Resume & Credentials</h2>
                <div class="awards-list">
                    <span class="award-item">All Rounder Award (MDPS, 2019)</span>
                    <span class="award-item">District Topper, Faridabad (2019)</span>
                    <span class="award-item">All India Rank 6 (Senior National Gymnastics, 2024)</span>
                    <span class="award-item">All India Rank 7th & 8th (National Games, 2023)</span>
                    <span class="award-item">Category 3 International Judge (FIG)</span>
                    <span class="award-item">All India Rank 9th (Selection Trials, 2023)</span>
                    <span class="award-item">All India top 0.1% in Political Science & Psychology (AISSCE)</span>
                    <span class="award-item">Merit Scholarships (2.5L+ in 4 years)</span>
                    <span class="award-item">CBSE National Gymnastics Championship First & Second (2019)</span>
                </div>
            </div>
        </section>

        <section id="contact">
            <div class="container">
                <h2 class="section-title">Get in Touch</h2>
                <div class="contact-form">
                    <form action="#" method="post">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                        
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                        
                        <label for="message">Message</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                        
                        <button type="submit">Send Message</button>
                    </form>
                    <div class="social-icons">
                        <a href="mailto:ayushma.work25@gmail.com" aria-label="Email">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M22 6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6zm-2 0l-8 5-8-5h16zm0 12H4V8l8 5 8-5v10z"/></svg>
                        </a>
                        <a href="https://www.linkedin.com/in/ayushma-saherawat-764671236/" target="_blank" aria-label="LinkedIn">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                        </a>
                        <a href="https://www.instagram.com/ayushma.saherawat/?hl=en" target="_blank" aria-label="Instagram">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07c3.252.148 4.607 1.499 4.756 4.756.058 1.265.07 1.646.07 4.85s-.012 3.584-.07 4.85c-.149 3.252-1.503 4.607-4.756 4.756-1.265.058-1.646.07-4.85.07s-3.584-.012-4.85-.07c-3.252-.149-4.607-1.503-4.756-4.756-.058-1.265-.07-1.646-.07-4.85s.012-3.584.07-4.85c.149-3.252 1.503-4.607 4.756-4.756 1.265-.058 1.646-.07 4.85-.07zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.211-6.78 2.636-6.992 6.992-.058 1.28-.072 1.688-.072 4.947 0 3.259.014 3.668.072 4.948.21 4.357 2.635 6.78 6.992 6.992 1.28.058 1.688.072 4.947.072s3.668-.014 4.948-.072c4.357-.212 6.78-2.636 6.992-6.992.058-1.28.072-1.689.072-4.948 0-3.259-.014-3.667-.072-4.947-.212-4.358-2.636-6.78-6.992-6.992-1.28-.058-1.688-.072-4.947-.072zM12 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.162 6.162 6.162 6.162-2.759 6.162-6.162c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4s1.791-4 4-4 4 1.79 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.442.646-1.442 1.442s.646 1.442 1.442 1.442 1.442-.646 1.442-1.442-.646-1.442-1.442-1.442z"/></svg>
                        </a>
                    </div>
                </div>
            </section>
        </main>

        <footer>
            <div class="container footer">
                <p>Designed and built by a friendly AI. Content by Ayushma Saherawat. Located in India.</p>
            </div>
        </footer>

        <script>
            function toggleMenu() {
                const navLinks = document.querySelector('.nav-links');
                navLinks.classList.toggle('open');
            }
        </script>
    </body>
    </html>
