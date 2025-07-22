
# Create a downloadable index.html file for Abraham's GitHub Pages website
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="AbrishTechHub - Abraham Tucho's personal tech portfolio website" />
  <title>AbrishTechHub | Abraham Tucho</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #1f2937;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
    }
    section {
      max-width: 960px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }
    h2 {
      color: #1f2937;
    }
    .projects ul {
      list-style: none;
      padding: 0;
    }
    .projects li {
      margin-bottom: 1rem;
    }
    .contact a {
      color: #2563eb;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>AbrishTechHub</h1>
    <p>Abraham Tucho | AI Developer | System Admin | ECE Graduate</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      I'm Abraham Tucho, a passionate AI developer and system administrator with a degree in Electrical and Computer Engineering (Communication Stream). I specialize in Linux system operations, AI tools, and digital transformation with strong knowledge of networks, scripting, and problem-solving.
    </p>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Linux Server Setup:</strong> Configured a virtualized Ubuntu server with firewall, SSH, and web services.</li>
      <li><strong>AI Chatbot Assistant:</strong> Built a basic AI-powered chatbot using Python and Hugging Face transformers.</li>
      <li><strong>Network Monitoring Script:</strong> Automated ping logging and downtime alerts using shell scripts.</li>
    </ul>
  </section>

  <section>
    <h2>Resume</h2>
    <p><a href="resume.pdf" download>Download My Resume (PDF)</a></p>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:abrishtechhub@gmail.com">abrishtechhub@gmail.com</a></p>
    <p>GitHub: <a href="https://github.com/abrishtucho" target="_blank">github.com/abrishtucho</a></p>
    <p>Telegram: <a href="https://t.me/TheDivinelyLife" target="_blank">@TheDivinelyLife</a></p>
  </section>

  <footer>
    &copy; 2025 AbrishTechHub. Built with purpose and code by Abraham Tucho.
  </footer>
</body>
</html>
"""

# Save the file
file_path = "/mnt/data/index.html"
with open(file_path, "w") as f:
    f.write(html_content)

file_path
