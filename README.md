# ZethOne.github.io

# Define the HTML content for Jonathan Saldivar's custom homepage
html_content = """<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jonathan Saldivar</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      text-align: center;
    }
    header {
      padding: 60px 20px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2em;
      margin-top: 0;
    }
    nav {
      margin: 30px 0;
    }
    nav a {
      color: #00d8ff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
    }
    footer {
      background-color: #111;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Jonathan Saldivar</h1>
    <p>Customer Lead | Passionate about People, Strategy & Innovation</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Welcome to my personal site! I'm a Customer Lead focused on driving impact through leadership, collaboration, and customer-centric strategies.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Coming soon: a showcase of my work, initiatives, and contributions.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Feel free to reach out via <a href="mailto:your.email@example.com" style="color:#00d8ff;">email</a> or connect with me on <a href="https://www.linkedin.com" style="color:#00d8ff;">LinkedIn</a>.</p>
  </section>

  <footer>
    <p>&copy; 2025 Jonathan Saldivar. All rights reserved.</p>
  </footer>
</body>
</html>
"""

# Write the HTML content to a file
with open("index.html", "w", encoding="utf-8") as file:
    file.write(html_content)

print("The custom homepage HTML file has been generated as 'index.html'.")

