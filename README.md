 edonaradi.github.io
 my-portfolio/
├── index.html
└── css/
    └── styles.css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/> 
    <title>Edona Radi - Portfolio</title>
    <link rel="stylesheet" href="css/styles.css" />
</head>
<body>
    <header>
        <h1>Edona Radi</h1>
        <p>Social Media Manager | Video Editor | Infographic Designer | Photographer</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#work">My Work</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I’m Edona Radi, a passionate creative professional with a focus on social media management, engaging video content, eye-catching infographics, and compelling photography. My goal is to help brands tell their stories visually and connect with their audiences on a deeper level.</p>
    </section>

    <section id="work">
        <h2>My Work</h2>
        
        <h3>Social Media Management</h3>
        <div class="project-grid">
            <div class="project">
                <h4>Brand Instagram Growth</h4>
                <p>Managed a tech startup’s Instagram account, increasing followers by 30% in 3 months through curated content, targeted hashtags, and strategic posting schedules.</p>
            </div>
            <div class="project">
                <h4>Facebook Community Engagement</h4>
                <p>Led a health & wellness brand’s Facebook page, creating engaging posts, responding to comments, and running interactive live sessions, resulting in stronger community engagement.</p>
            </div>
        </div>

        <h3>Video Editing</h3>
        <div class="project-grid">
            <div class="project">
                <h4>Promo Video</h4>
                <p>Edited a 60-second promotional video for a beauty brand’s summer campaign, integrating dynamic transitions, upbeat music, and on-screen text to highlight product features.</p>
            </div>
            <div class="project">
                <h4>Social Shorts</h4>
                <p>Created short-form vertical videos for TikTok and Instagram Reels, repurposing existing footage into engaging, mobile-friendly clips optimized for shareability.</p>
            </div>
        </div>

        <h3>Infographics</h3>
        <div class="project-grid">
            <div class="project">
                <h4>Marketing Stats Infographic</h4>
                <p>Designed a clean, data-driven infographic summarizing quarterly marketing results, making complex metrics easy to understand at a glance.</p>
            </div>
            <div class="project">
                <h4>How-To Visual Guide</h4>
                <p>Created step-by-step infographic guides for social posts that visually explain how to use products or services, increasing user comprehension and retention.</p>
            </div>
        </div>

        <h3>Photography</h3>
        <div class="project-grid">
            <div class="project">
                <h4>Product Photography</h4>
                <p>Shot lifestyle and studio images for e-commerce, ensuring consistent lighting, styling, and editing to highlight products’ best features.</p>
            </div>
            <div class="project">
                <h4>Brand Photoshoots</h4>
                <p>Conducted on-location photoshoots capturing brand ambassadors and users, creating authentic visual narratives for social feeds and websites.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>I’d love to help you elevate your brand’s social presence and visual storytelling. <br>
        Feel free to <a href="mailto:youremail@example.com">email me</a> to discuss potential collaborations or project inquiries.</p>
    </section>

    <footer>
        <p>&copy; 2024 Edona Radi</p>
    </footer>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 2em 0;
}

header p {
    margin: 0.5em 0 0;
    font-size: 1.1em;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    background: #f4f4f4;
    margin: 0;
    padding: 0.5em 0;
}

nav ul li {
    margin: 0 1em;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

section {
    max-width: 800px;
    margin: 2em auto;
    padding: 0 1em;
}

h2 {
    margin-top: 0;
}

.project-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1em;
    margin-bottom: 2em;
}

.project h4 {
    margin-top: 0;
}

footer {
    text-align: center;
    margin: 2em 0;
    color: #555;
    font-size: 0.9em;
}
