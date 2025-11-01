# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Veronika Nastasy - Resume</title>
  <style>
    /* ======== BASIC STYLES ======== */
    body {
      font-family: "Segoe UI", sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #222;
    }

    header, main, footer {
      max-width: 900px;
      margin: 0 auto;
      background: #fff;
      padding: 1.5rem;
      border-radius: 16px;
    }

    header {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
      margin-top: 1rem;
    }

    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
    }

    .info {
      flex: 1;
    }

    h1 {
      margin: 0;
      font-size: 1.6rem;
    }

    .contact {
      font-size: 0.9rem;
      color: #555;
    }

    /* ======== SECTIONS ======== */
    section {
      margin-top: 2rem;
    }

    h2 {
      border-bottom: 2px solid #ddd;
      padding-bottom: 0.3rem;
    }

    .experience-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1rem;
    }

    article {
      background: #f9f9f9;
      border-radius: 12px;
      padding: 1rem;
      box-shadow: 0 1px 4px rgba(0,0,0,0.05);
    }

    .skills-grid, .education-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }

    ul {
      list-style-type: none;
      padding-left: 0;
    }

    li {
      margin-bottom: 0.3rem;
    }

    footer {
      text-align: center;
      margin-top: 2rem;
      font-size: 0.8rem;
      color: #666;
      background: none;
      box-shadow: none;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }
      .info {
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <!-- ======== HEADER SECTION ======== -->
  <header class="resume-header">
    <img src="profile.jpg" alt="Profile photo of Veronika Nastasy">
    <div class="info">
      <h1>Veronika Nastasy</h1>
      <p>18 years old</p>
      <p class="contact">
        <a href="mailto:veronikanastasy07@gmail.com">veronikanastasy07@gmail.com</a>
      </p>
      <p><strong>Interests:</strong> SMM, Coding, Art & Design</p>
    </div>
  </header>

  <!-- ======== MAIN CONTENT ======== -->
  <main class="resume">
    <!-- Apps section -->
    <section aria-labelledby="apps">
      <h2 id="apps">Apps I made</h2>
      <ul>
        <li>Coin Titan</li>
        <li>Other mobile & web projects</li>
      </ul>
    </section>

    <!-- Experience section -->
    <section aria-labelledby="experience">
      <h2 id="experience">Experience</h2>

      <!-- Experience grid -->
      <div class="experience-grid">
        <!-- Each article is a semantic job entry -->
        <article>
          <h3>Edlighten &ndash; Graphic Designer</h3>
          <p><strong>Design:</strong> Posts, highlights, stories</p>
          <p><strong>Identity:</strong> Brand book creation</p>
          <p><strong>Tools:</strong> Figma, Photoshop, Telegram</p>
        </article>

        <article>
          <h3>2smart.academy &ndash; Graphic Designer</h3>
          <p><strong>Growth:</strong> Acrobat Pro purchase funnel optimization</p>
          <p><strong>Pro Web Design:</strong> Redesign &amp; optimization of adobe.com pages</p>
          <p><strong>Tools:</strong> Figma, Teams, Photoshop, Illustrator</p>
        </article>

        <article>
          <h3>Appexoft &ndash; Python Developer</h3>
          <p><strong>Development:</strong> Backend, automation, data processing</p>
          <p><strong>Languages:</strong> Python, SQL</p>
          <p><strong>Skills:</strong> API integration, debugging, clean code, problem solving</p>
          <p><strong>Tools:</strong> Git, VS Code, Docker</p>
        </article>
        <article>
          <h3>Pwc_Ukraine &ndash; SMM Manager</h3>
          <p><strong>Management:</strong> Content strategy, audience growth, engagement</p>
          <p><strong>Identity:</strong> Maintaining consistent brand voice and style</p>
          <p><strong>Analytics:</strong> Insights, reach, engagement rate</p>
        </article>
      </div>
    </section>

    <!-- Skills section -->
    <section aria-labelledby="skills">
      <h2 id="skills">Skills</h2>
      <div class="skills-grid">
        <div>
          <h4>Design Tools</h4>
          <ul>
            <li>Figma</li>
            <li>Adobe Illustrator</li>
            <li>Photoshop</li>
            <li>Canva</li>
          </ul>
        </div>

        <div>
          <h4>Coding</h4>
          <ul>
            <li>Python</li>
            <li>SQL</li>
            <li>HTML</li>
            <li>CSS</li>
          </ul>
        </div>

        <div>
          <h4>Languages</h4>
          <ul>
            <li>English</li>
            <li>Spanish</li>
            <li>Korean</li>
            <li>Ukrainian</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Education section -->
    <section aria-labelledby="education">
      <h2 id="education">Education</h2>
      <div class="education-grid">
        <div>
          <h4>Cybersecurity</h4>
          <p>SUTE, 2024&ndash;2028</p>
        </div>
        <div>
          <h4>Courses</h4>
          <ul>
            <li>Coursera</li>
            <li>Prometheus</li>
            <li>Cisco Genius.Space</li>
          </ul>
        </div>
      </div>
    </section>
  </main>

  <!-- ======== FOOTER ======== -->
  <footer>
    <p>&copy; 2025 Veronika Nastasy. All rights reserved.</p>
  </footer>
</body>
</html>
