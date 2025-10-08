# Ex01 Portfolio
## Date:1-10-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

## INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Istin B | Portfolio</title>
  <link rel="stylesheet" href="index.css">
</head>
<body>

  <header>
    <nav class="navbar">
      <h1 class="logo">Portfolio</h1>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section home">
    <h2>Welcome!</h2>
    <p>Hello, I'm <strong>Istin B</strong>.<br> A passionate learner in <b>Full-Stack Development, SQL, Django, and AI/ML.</b></p>
    <img src="photo.png" alt="Profile Picture" width="100">
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>I am a Computer Science student at Saveetha Engineering College.  
       I have hands-on experience in Django, SQL, React, and automation tools like Selenium.  
       Recently, I completed a full HTML & CSS course by Meta with a perfect grade and enjoy building interactive projects.</p>
  </section>

  <section id="projects" class="section">
    <h2>My Projects</h2>

    <div class="project-card">
      <h3>1. Interactive Image Gallery (Django)</h3>
      <p>A responsive gallery of birds with hover-scale transitions and mobile-friendly layout.</p>
    </div>

    <div class="project-card">
      <h3>2. Traffic Congestion Monitoring System</h3>
      <p>YOLOv8-powered system for real-time vehicle detection, lane counting, and congestion monitoring.</p>
    </div>

    <div class="project-card">
      <h3>3. Restaurant Ordering System</h3>
      <p>Designed an ER model and SQL system for customers, waiters, and chefs, including billing and accountability features.</p>
    </div>

    <div class="project-card">
      <h3>4. Billing System</h3>
      <p>A simple billing system for restaurants and shops with features for generating customer bills and maintaining daily sales records.</p>
    </div>

    <div class="project-card">
      <h3>5. Stock Management Inventory</h3>
      <p>Developed an inventory management system to track stock levels, update product details, and generate inventory reports.</p>
    </div>

  </section>

  <section id="contact" class="section contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:istinb@example.com">istin234@gmail.com</a></p>
    <p>LinkedIn: <a href="#">linkedin.com/in/istinb</a></p>
    <p>GitHub: <a href="#">github.com/istin2005</a></p>
  </section>

  <footer>
    <p>© 2025 Istin B | All Rights Reserved</p>
  </footer>

</body>
</html>

```

## Index.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #f4f4f9;
  color: #333;
  line-height: 1.6;
}

header {
  background: #17cead;
  color: #fff;
  padding: 1rem 0;
}

.navbar {
  max-width: 1000px;
  margin: auto;
  padding: 0 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.6rem;
}

.navbar ul {
  list-style: none;
  display: flex;
}

.navbar ul li {
  margin-left: 20px;
}

.navbar ul li a {
  color: #fff;
  text-decoration: none;
  transition: 0.3s;
  font-weight: bold;
}

.navbar ul li a:hover {
  color: #ff9800;
}

.section {
  max-width: 800px;
  margin: 40px auto;
  padding: 20px;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
}

.section h2 {
  text-align: center;
  margin-bottom: 20px;
  color: #222;
}

.home {
  text-align: center;
}

.home img {
  margin-top: 20px;
  border-radius: 50%;
  border: 3px solid #555;
}

.project-card {
  background: #fafafa;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 15px;
  margin: 15px 0;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.contact a {
  color: #ff9800;
  text-decoration: none;
}

.contact a:hover {
  text-decoration: underline;
}

footer {
  text-align: center;
  padding: 15px;
  background: #222;
  color: #fff;
  margin-top: 20px;
}

```

## OUTPUT

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e998898c-bf2a-48b5-a602-3294912fdf08" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bb4ee9eb-8c76-4fcd-9348-31033e286890" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
