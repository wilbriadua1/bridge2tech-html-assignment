Week 1 - Homework Assignment
Creating Your Personal Portfolio HTML Page
📋 Assignment Overview
Create a personal portfolio HTML page using only HTML (no CSS styling yet). This assignment will help you practice the fundamental HTML concepts and Git workflow we learned in class.

🎯 Learning Objectives
By completing this assignment, you will:

Practice writing semantic HTML5 structure
Use proper HTML elements and attributes
Follow the Git workflow for version control
Create content that represents your personal brand


📝 Requirements
HTML Structure Requirements
Your HTML page must include:

Proper HTML5 document structure

<!DOCTYPE html>
<html> element with lang="en"
Complete <head> section with required meta tags
<body> element containing all visible content


Head Section Must Contain:
html<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name - Portfolio</title>

Semantic HTML Elements (Use These):

<header> for the top section
<nav> for navigation (even if links don't work yet)
<main> for the primary content
<section> for different content areas
<footer> for bottom information


Required Content Sections:

Header: Your name as an <h1> and navigation placeholder
About Me: Introduction paragraph about yourself
Skills/Interests: List of your hobbies, interests, or skills you want to develop
Goals: What you hope to achieve in this course
Contact: Basic contact information
Footer: Copyright notice or additional info


Required HTML Elements to Practice:

At least 3 different heading levels (<h1>, <h2>, <h3>)
Multiple paragraphs (<p>)
At least one unordered list (<ul>) or ordered list (<ol>)
At least 2 links (<a>) - these can link to social media, GitHub, or be placeholders
At least one image (<img>) with proper alt attribute
Use <strong> or <em> for emphasis somewhere in your content




📁 File Requirements
Files to Create:

index.html - Your main HTML file
Create a folder structure like this:
your-portfolio/
├── index.html
└── images/
    └── (your image files here)


Git Repository Requirements:

Initialize a Git repository in your project folder
Connect it to a new GitHub repository
Make at least 3 separate commits with descriptive messages
Push your final project to GitHub


📋 Step-by-Step Instructions
Step 1: Fork and Clone This Repository
bash# After forking this repo on GitHub, clone it locally
git clone https://github.com/YOUR-USERNAME/FORKED-REPO-NAME.git
cd FORKED-REPO-NAME

# Your HTML file should be created here
touch index.html
Step 2: Create Your HTML Structure
Start with this basic template and expand it:
html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
</head>
<body>
    <header>
        <h1>Your Name Here</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#goals">Goals</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Add your content sections here -->
        
    </main>

    <footer>
        <!-- Add footer content here -->
    </footer>
</body>
</html>
Step 3: Git Workflow Practice
Make commits as you work:
bash# After creating basic structure
git add index.html
git commit -m "Add basic HTML structure and navigation"

# After adding content sections
git add .
git commit -m "Add about me and skills sections"

# After completing the page
git add .
git commit -m "Complete portfolio page with all required sections"

# Push to GitHub
git push origin main

✅ Submission Checklist
Before submitting, make sure your project has:

 Valid HTML5 structure with DOCTYPE, head, and body
 Semantic elements: header, nav, main, section, footer
 Required meta tags in the head section
 Proper heading hierarchy (h1 → h2 → h3)
 All required content sections (about, skills, goals, contact)
 At least one image with descriptive alt text
 At least 2 working links (can be to social media or placeholders)
 Lists (ul or ol) for organizing information
 Emphasis elements (strong, em) used appropriately
 Git repository with meaningful commit messages
 Pushed to GitHub and repository is public


🚀 Stretch Goals (Optional)
If you finish early, try these additional challenges:

Add More Semantic Elements:

Use <article> for a blog post or project description
Add a <figure> and <figcaption> for your image
Include <time> elements for dates


Improve Content:

Write a detailed "My Coding Journey" section
Add a "Why I Want to Learn Web Development" section
Include placeholder project descriptions


Practice More HTML Elements:

Add a simple table with your weekly schedule
Include a form (we'll make it work later)
Use definition lists (<dl>, <dt>, <dd>) for terminology




📤 How to Submit
Submission Requirements:

Push your completed project to GitHub
Make sure your repository is public
Submit the GitHub repository URL
Include a screenshot of your webpage in the browser

Submit This Information:

Your GitHub repository URL: https://github.com/yourusername/repository-name
Screenshot of your HTML page displayed in a web browser
Brief description (2-3 sentences) of what you learned from this assignment


🆘 Getting Help
If You Get Stuck:

Review the class examples and your notes
Use HTML validation: https://validator.w3.org/
Check the Git cheat sheet from class
Ask questions in our class discussion forum
Remember: It's okay if it doesn't look pretty yet - we'll add CSS next class!

Common Issues & Solutions:

Git errors: Make sure you're in the right directory and have initialized the repo
HTML not displaying: Check for missing closing tags or typos
Images not showing: Make sure the file path is correct and the image exists


🏆 Assessment Criteria
Your assignment will be evaluated on:

HTML Structure (40%): Proper use of semantic HTML5 elements
Content Completeness (30%): All required sections included with meaningful content
Git Workflow (20%): Proper use of commits, messages, and GitHub
Code Quality (10%): Clean, readable HTML with proper indentation

Remember: This is about learning, not perfection. Focus on following the requirements and practicing what we learned!
