Here’s an upgraded **portfolio code** with a **dark mode toggle** and a **downloadable PDF resume button**. This way recruiters can view your site in light/dark mode and also download your resume directly.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abhishek Kumar | Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f4f4f9; color: #333;
      transition: background 0.3s, color 0.3s;
    }
    header {
      background: #2c3e50; color: #fff;
      padding: 20px; text-align: center;
    }
    header h1 { margin: 0; }
    section {
      padding: 20px; max-width: 900px;
      margin: auto;
    }
    h2 {
      border-bottom: 2px solid #2c3e50;
      padding-bottom: 5px; color: #2c3e50;
    }
    ul { list-style: none; padding: 0; }
    li { margin-bottom: 8px; }
    .skills span {
      display: inline-block; background: #3498db;
      color: #fff; padding: 5px 10px;
      margin: 5px; border-radius: 4px;
    }
    footer {
      background: #2c3e50; color: #fff;
      text-align: center; padding: 10px;
    }
    /* Dark mode styles */
    .dark-mode {
      background: #1e1e1e; color: #ddd;
    }
    .dark-mode header {
      background: #111; color: #eee;
    }
    .dark-mode h2 {
      border-bottom: 2px solid #eee; color: #eee;
    }
    .dark-mode .skills span {
      background: #555; color: #fff;
    }
    .button-container {
      text-align: center; margin: 20px;
    }
    button {
      padding: 10px 20px; margin: 5px;
      border: none; border-radius: 4px;
      cursor: pointer; font-size: 14px;
    }
    .toggle-btn { background: #3498db; color: #fff; }
    .resume-btn { background: #2ecc71; color: #fff; }
  </style>
</head>
<body>
  <header>
    <h1>Abhishek Kumar</h1>
    <p>Patna, Bihar | +91 6201077217 | Abhishekkr62010@gmail.com</p>
    <p><a href="https://github.com/yourgithub" style="color:#fff;">GitHub</a> | 
       <a href="https://linkedin.com/in/yourlinkedin" style="color:#fff;">LinkedIn</a></p>
  </header>

  <div class="button-container">
    <button class="toggle-btn" onclick="toggleDarkMode()">Toggle Dark Mode</button>
    <button class="resume-btn" onclick="downloadResume()">Download Resume (PDF)</button>
  </div>

  <section>
    <h2>Professional Summary</h2>
    <p>Data Analyst & Technology Professional with expertise in Python, SQL, Power BI, and Excel. Skilled in data cleaning, visualization, and reporting automation. Experienced in project implementation and client-focused solutions.</p>
  </section>

  <section>
    <h2>Core Skills</h2>
    <div class="skills">
      <span>Python</span><span>SQL</span><span>Power BI</span><span>Excel</span>
      <span>Java</span><span>JavaScript</span><span>HTML</span><span>CSS</span>
      <span>MySQL</span><span>Git</span><span>Cloud Computing</span><span>Cybersecurity</span>
    </div>
  </section>

  <section>
    <h2>Work Experience</h2>
    <ul>
      <li><strong>Implementation Manager – CHL Group (6 Months)</strong><br>
      Coordinated end-to-end project implementation, ensured smooth deployment, issue resolution, and client satisfaction.</li>
    </ul>
  </section>

  <section>
    <h2>Projects</h2>
    <ul>
      <li><strong>Customer Churn Prediction | Python, SQL</strong> – Achieved 85% accuracy in identifying at-risk customers.</li>
      <li><strong>Sales Dashboard | Power BI, Excel</strong> – Automated reporting, reducing manual effort by 30%.</li>
      <li><strong>Cybersecurity Simulation | J.P. Morgan Chase</strong> – Identified vulnerabilities and proposed mitigation strategies.</li>
    </ul>
  </section>

  <section>
    <h2>Certifications</h2>
    <ul>
      <li>Python – Great Learning, IIT Bombay</li>
      <li>Microsoft Discover Data Analysis</li>
      <li>Big Data & Hadoop – CIMAGE</li>
      <li>AI Engineer, Data Analyst, Excel – One Roadmap</li>
    </ul>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li>Bachelor of Computer Applications – CIMAGE, AKU Patna (2024)</li>
      <li>Intermediate (12th CBSE) – Himalayan Residential School (2021)</li>
      <li>Matriculation (10th CBSE) – Gyanodaya Gurukul (2019)</li>
    </ul>
  </section>

  <section>
    <h2>Languages</h2>
    <p>Hindi (Fluent), English (Professional)</p>
  </section>

  <footer>
    <p>&copy; 2026 Abhishek Kumar | Portfolio</p>
  </footer>

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle("dark-mode");
    }
    function downloadResume() {
      // Replace with actual resume file path
      window.open("Abhishek_Kumar_Resume.pdf", "_blank");
    }
  </script>
</body>
</html>
```

---

### 🔑 What’s New
- **Dark Mode Toggle** → Switch between light and dark themes.  
- **Download Resume Button** → Opens your PDF resume (replace `"Abhishek_Kumar_Resume.pdf"` with your actual file path).  

---

Would you like me to also add a **project showcase section with live demo links** (e.g., GitHub repos, dashboards) so recruiters can interact with your work directly?
