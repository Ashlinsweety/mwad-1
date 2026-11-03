# Ex01 Portfolio
## Date:30/10/2026

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
```c

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashlin's Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #172554;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 12px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .home {
            min-height: 450px;
            background-color: #dbeafe;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            padding: 40px;
            flex-wrap: wrap;
        }

        .intro {
            max-width: 500px;
        }

        .intro h2 {
            color: #172554;
            font-size: 35px;
            margin-bottom: 15px;
        }

        .intro h3 {
            margin-bottom: 15px;
        }

        .intro p {
            line-height: 1.7;
            margin-bottom: 25px;
        }

        .profile img {
            width: 260px;
            height: 300px;
            object-fit: cover;
            border-radius: 50%;
            border: 6px solid white;
            box-shadow: 0 5px 15px gray;
        }

        .btn {
            background-color: #172554;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #2563eb;
        }

        section {
            padding: 50px 10%;
            text-align: center;
        }

        section h2 {
            color: #172554;
            margin-bottom: 25px;
        }

        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            background-color: white;
            padding: 25px;
            width: 220px;
            border-radius: 10px;
            box-shadow: 0 3px 10px #ccc;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            background-color: #dbeafe;
        }

        #contact {
            background-color: #dbeafe;
            line-height: 2;
        }

        footer {
            background-color: #172554;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 600px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 5px;
                font-size: 13px;
            }

            .home {
                flex-direction: column;
                gap: 30px;
            }

            .intro h2 {
                font-size: 27px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>My Portfolio</h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="home">

        <div class="intro">
            <h2>Hello, I'm Ashlin Sweety</h2>
            <h3>Computer Science Engineering Student</h3>

            <p>
                Welcome to my personal portfolio!
                I am passionate about programming,
                technology and web development.
            </p>

            <a href="#about" class="btn">Know More</a>
        </div>

        <div class="profile">
            <!-- Replace myphoto.jpg with your image name -->
            <img src="c:\Users\ASHLIN SWEETY\Pictures\Screenshots\myphoto.jpg.png" alt="My Profile Picture">

        </div>

    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>

        <p>
            I am a Computer Science Engineering student.
            I enjoy learning programming languages,
            developing websites and exploring new technologies.
            My ambition is to become a successful software developer.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>

        <div class="container">
            <div class="card">HTML</div>
            <div class="card">CSS</div>
            <div class="card">Python</div>
            <div class="card">C Programming</div>
            <div class="card">JavaScript</div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>

        <div class="container">

            <div class="card">
                <h3>Portfolio Website</h3>
                <p>Personal website using HTML and CSS.</p>
            </div>

            <div class="card">
                <h3>Calculator</h3>
                <p>A simple calculator application.</p>
            </div>

            <div class="card">
                <h3>Student Management</h3>
                <p>Student information management system.</p>
            </div>

        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>

        <p>Email: ashlin@example.com</p>
        <p>Phone: 9876543210</p>
        <p>Location: Chennai, Tamil Nadu</p>
    </section>

    <footer>
        <p>© 2026 Ashlin Sweety | All Rights Reserved</p>
    </footer>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2026-11-03 160250.png>)
![alt text](<Screenshot 2026-11-03 160310.png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
