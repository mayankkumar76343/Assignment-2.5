 Assignment 2.5 — HTML Foundations Mini-Project.1. Complete HTML code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Introduction</title>
</head>
<body>

    <header>
        <h1>Welcome to My Personal Website</h1>
        <p>A little introduction about me</p>
    </header>

    <main>
        <section id="about-me">
            <h2>About Me</h2>
            <p>
                Hello! My name is Your Name. I am a student who is
                passionate about learning new things and improving my skills.
                I enjoy exploring technology and working on creative projects.
            </p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <ul>
                <li>
                    <strong>School:</strong> Your School Name
                </li>
                <li>
                    <strong>College/University:</strong> Your College Name
                </li>
                <li>
                    <strong>Course:</strong> Your Course or Degree
                </li>
            </ul>
        </section>

        <section id="technical-skills">
            <h2>Technical Skills</h2>
            <ul>
                <li>HTML</li>
                <li>Basic Programming</li>
                <li>Computer Fundamentals</li>
                <li>Problem Solving</li>
            </ul>
        </section>

        <section id="hobbies">
            <h2>Hobbies</h2>
            <ul>
                <li>Reading books</li>
                <li>Listening to music</li>
                <li>Learning new technologies</li>
                <li>Playing games</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact Information</h2>
            <p>
                <strong>Email:</strong>
                <a href="mailto:your.email@example.com">
                    your.email@example.com
                </a>
            </p>
            <p>
                <strong>Location:</strong> Your City
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Your Name. All rights reserved.</p>
    </footer>

</body>
</html>
2. Project structure
Your project folder should look like this:

Assignment-2.5/

index.html

Complete webpage source code

3. How to run the project
Create a folder named Assignment-2.5.

Create a file named index.html inside it.

Copy the code above into the file.

Replace the sample name, education, skills, hobbies, and contact details with your own information.

Open index.html in your web browser to see the webpage.

4. Upload the project to GitHub
Open a terminal inside your project folder and run:


bash
git init
git add index.html
git commit -m "Complete Assignment 2.5 HTML Foundations"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/Assignment-2.5.git
git push -u origin main
Before running the commands, create a new repository named Assignment-2.5 on GitHub and replace YOUR-USERNAME with your GitHub username.

5. Assignment checklist

Page title and main heading

About Me section

Education section

Technical Skills section

Hobbies section

Contact Information section

Correct HTML document structure

Semantic headings and sections

HTML only, without CSS

File named index.html

Commit and push the code to GitHub

Submit the GitHub repository link