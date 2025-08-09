<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Afeez Atiku — Enterprise & Solutions Architect</title>
  <meta name="description" content="Portfolio of Afeez Atiku — Enterprise Architect & Solutions Architect specializing in AWS, ServiceNow SAM Pro, and Enterprise Architecture.">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@2/css/pico.min.css">
  <style>
    body { background-color: #0d1117; color: #c9d1d9; }
    a { color: #58a6ff; }
    header, footer { text-align: center; }
    section { margin-bottom: 3rem; }
    h1, h2, h3 { color: #f0f6fc; }
    .project-card { border: 1px solid #30363d; padding: 1rem; border-radius: 10px; margin-bottom: 1.5rem; background-color: #161b22; }
  </style>
</head>
<body>
<main class="container">
  <header>
    <h1>👋 Hi, I'm Afeez Atiku</h1>
    <p>Enterprise Architect & Solutions Architect | AWS | ServiceNow SAM Pro | TOGAF</p>
    <nav>
      <a href="#about">About</a> ·
      <a href="#projects">Projects</a> ·
      <a href="#skills">Skills</a> ·
      <a href="#certifications">Certifications</a> ·
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m an innovative and results-driven IT professional with over 10 years of experience bridging business objectives and technical execution. I design and implement secure, scalable, and cost-efficient solutions that enable digital transformation, specializing in cloud migration, enterprise application management, and architectural frameworks like TOGAF and AWS Well-Architected.</p>
  </section>

  <section id="projects">
    <h2>Featured Projects</h2>
    <div class="project-card">
      <h3>High-Availability AWS Web Application Architecture</h3>
      <p>Designed & deployed multi-AZ architecture with ALB, Auto Scaling Group, and RDS Multi-AZ. Achieved 99.95% uptime and ~30% cost savings via autoscaling.</p>
      <p><a href="#">View Repo</a> | <a href="#">YouTube Walkthrough</a></p>
    </div>
    <div class="project-card">
      <h3>ServiceNow SAM Pro Implementation @ ATCO</h3>
      <p>Led SAM Pro rollout for license compliance & cost optimization. Created governance framework to manage software assets and retired redundant licenses.</p>
    </div>
    <div class="project-card">
      <h3>Application Rationalization Dashboard</h3>
      <p>Built Power BI dashboard for 1,000+ apps, identifying redundancies and retiring unused systems to deliver measurable OpEx savings.</p>
    </div>
  </section>

  <section id="skills">
    <h2>Skills & Technologies</h2>
    <ul>
      <li><strong>Cloud & Infrastructure:</strong> AWS (EC2, S3, RDS, Lambda), Azure, Cloud Migration, Networking, VPCs, Containers, API Design</li>
      <li><strong>Enterprise Architecture & Management:</strong> TOGAF, Application Rationalization, ServiceNow SAM Pro, LeanIX, IBM Maximo</li>
      <li><strong>Data & Analytics:</strong> Power BI, Tableau, SQL</li>
      <li><strong>Project Delivery:</strong> Agile, Scrum, Azure DevOps, JIRA</li>
    </ul>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <ul>
      <li>TOGAF 10 Enterprise Architecture Practitioner</li>
      <li>AWS Solutions Architect – Associate (SAA-C03)</li>
      <li>ITIL v4</li>
      <li>Microsoft Certified: Azure Fundamentals</li>
      <li>CIS-SAM (Certified Implementation Specialist – Software Asset Management)</li>
      <li>CBAP (Certified Business Analysis Professional)</li>
      <li>Microsoft Certified: Power BI Data Analyst Associate</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📧 <a href="mailto:funmilolatiku@gmail.com">funmilolatiku@gmail.com</a></p>
    <p>🔗 <a href="https://www.linkedin.com/in/afeezatiku" target="_blank">LinkedIn</a> · <a href="https://github.com/afeez.atiku/github.io" target="_blank">GitHub</a> · <a href="#" target="_blank">YouTube</a></p>
  </section>

  <footer>
    <small>© <span id="year"></span> Afeez Atiku. Built using PicoCSS.</small>
  </footer>
</main>
<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
