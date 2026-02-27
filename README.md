# Ex01 Portfolio
## Date: 22.01.26

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

HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vicky | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navbar -->
    <header>
        <h1>Vicky</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Hi, I'm Vicky 👋</h2>
        <p>Aspiring Java Full Stack Developer</p>
        <button>Download Resume</button>
    </section>

    <!-- About -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a passionate developer skilled in Java, HTML, CSS, JavaScript and
            currently learning Full Stack Development.
        </p>
    </section>

    <!-- Skills -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Java</li>
            <li>HTML & CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Spring Boot</li>
        </ul>
    </section>

    <!-- Projects -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>Portfolio Website</h3>
            <p>Personal portfolio using HTML & CSS</p>
        </div>

        <div class="project-card">
            <h3>Student Management System</h3>
            <p>Java-based CRUD application</p>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: vicky@example.com</p>
        <p>LinkedIn: linkedin.com/in/vicky</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Vicky | All Rights Reserved</p>
    </footer>

</body>
</html>

```
CSS

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background: #222;
    color: #fff;
    padding: 15px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav a {
    color: #fff;
    margin-left: 20px;
    text-decoration: none;
}


.hero {
    text-align: center;
    padding: 80px 20px;
    background: #007bff;
    color: white;
}

.hero button {
    margin-top: 20px;
    padding: 10px 20px;
    border: none;
    background: white;
    color: #007bff;
    cursor: pointer;
    font-weight: bold;
}


section {
    padding: 50px;
}

h2 {
    margin-bottom: 20px;
}

#skills ul {
    display: flex;
    gap: 15px;
    list-style: none;
}

#skills li {
    background: #ddd;
    padding: 10px 15px;
    border-radius: 5px;
}

.project-card {
    background: white;
    padding: 20px;
    margin-bottom: 15px;
    border-radius: 5px;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}

```

## OUTPUT


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
