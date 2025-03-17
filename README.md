# Ex01 Portfolio
## Date:17.03.25

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> SANDY | Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #000000;
            color: #210039;
        }

        /* Header & Navigation */
        header {
            background-color: #3b023e;
            color: white;
            padding: 15px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: rgb(255, 255, 255);
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffffff;
        }

        /* Sections */
        main {
            margin-top: 80px;
        }
        section {
            padding: 60px 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
        }

        /* Projects */
        .project {
            background-color: #ffffff;
            padding: 15px;
            border-radius: 8px;
            margin: 10px 0;
        }

        /* Contact */
        #contact a {
            color: #177e7b;
            text-decoration: none;
            font-weight: bold;
        }
        #contact a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #011121;
            color: white;
            position: relative;
            width: 100%;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
            section {
                padding: 40px 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>SANDY</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internship">Internship</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm SANDHIYA SREE B , 2nd-year Information Technology Student specializing in Full-Stack </p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Enhancing SAR Image Interpretation</h3>
                <p>Deep learning-based SAR image colorization using Python, TensorFlow, and OpenCV.</p>
            </div>
            <div class="project">
                <h3>Predictive Hiring with Data Science</h3>
                <p>AI-driven recruitment system for bias-free hiring decisions.</p>
            </div>
        </section>

        <section id="internship">
            <h2>Internship</h2>
            <p><strong>Arjun Vision Tech Solutions | 2024</strong></p>
            <p>Worked on predictive modeling, machine learning, and SAR image processing.</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <p><strong>B.Tech in IT </strong> - Saveetha Engineering College (2023-2027) | CGPA: 8.5</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Java, Python, C</li>
                <li>Data Science</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: sandhiyasree123.com</p>
            <p>GitHub: <a href="#" target="_blank">github.com/Sandy</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 SANDHIYA SREE.B All Rights Reserved.</p>
    </footer>

</body>
</html>

```


## OUTPUT
![Screenshot 2025-03-17 161420](https://github.com/user-attachments/assets/91df156b-fd92-4c14-badd-87c9307c1e8b)

![image](https://github.com/user-attachments/assets/f15247b1-40c0-40d6-b667-c8d13f670f2f)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
