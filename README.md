# MDAP-EX_01-Portfolio
### Name:Swetha D
### Reg No:212223040222
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
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
    
        <h1>My Portfolio</h1>
        <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="project.html">Projects</a></li>
            <li><a href="contact.html">Contact Details</a></li>
        </ul>
    </nav>
            
    
    </header>

    <h2>About Me</h2>
    
    
    <h3>Name : Swetha.D</h3>
    <h3>Profession : Developer</h3>
    <h3>specialize :Full stack </h3>
    <h3>Degree : B.E Computer Science Engineering</h3>
    <h3>Experience : Fullstack Developer (for 2 years)</h3>


   

</body>
</html>
```
## about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
    
        <h1>My Portfolio</h1>
        <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="project.html">Projects</a></li>
            <li><a href="contact.html">Contact Details</a></li>
        </ul>
    </nav>
            
    
    </header>
    <div id="about" >

        
       

        <p><b>Hello! I'm  Swetha a passionate developer. I have completed my UG in B.E CSe.
        </b>
        </p>
        
       
       
        <p><b>I have done my intership training in web site Designing and Development in HTML,CSS and javascript </b></p>

        
        
        <p><b>I specialize in building web applications and coding Knowledge.And specialized in Full stack development - combine both frontend and backend. </b></p>

       
       
        <p><b>i have built a full stack web app with 1k+ users. I have a experience for 2 year on working as a full stack developer.</b></p>
    </div>
    
</body>
</html>
```
## project.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
    
        <h1>My Portfolio</h1>
        <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="project.html">Projects</a></li>
            <li><a href="contact.html">Contact Details</a></li>
        </ul>
    </nav>
            
    
    </header>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="https://www.designveloper.com/wp-content/uploads/2022/04/web-development-blogs.jpg" alt="Project 1">
            <h3>Dev Blog Website</h3>
            <p><b>Tech :</b>
             Next.js,css,HTML,React
            </p>
            <p><b>Content:</b>
              Write blog posts about coding tutorials,industry insights,or personal experiences.</p>
            </section>
        <section class="project">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhzvfDQ6Uhqp3r5SvYNUJektJI4xbMXOrybg&s" alt="Project 2">
            <h3>Portfolio</h3>
            <p><b>Tech :</b>
            React,javascript,HTML,css</p>
            <p><b>Content :</b>
              showcase your projects,skills,and an Article section for your writings.
            
            </p>
        </section>
    </div>

    
</body>
</html>
```
## contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
    
        <h1>My Portfolio</h1>
        <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="project.html">Projects</a></li>
            <li><a href="contact.html">Contact Details</a></li>
        </ul>
    </nav>
            
    
    </header>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
        <p>LinkedIn: <a href="#">developerfullstack.com</a></p>

        <p><b>CONTACT FORM </b></p>
        <form action="contact.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>

        <p><b> SOCIAL MEDIA LINKS</b></p>

       
         <a href="https://github.com/yourusername" target="_blank">GitHub</a> |  
         <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a> |  
         <a href="https://twitter.com/yourhandle" target="_blank">Twitter</a> |  
         <a href="https://yourwebsite.com" target="_blank">Website</a>
    </section>
    
</body>
</html>
```
## index.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #edd4f0;
    text-align: center;
}

header {
    background: #333;
    color: white;
    padding: 1rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 50px;
}

.project {
    display: inline-block;
    margin: 20px;
    padding: 10px;
    background:lightblue;
    box-shadow: 0px 0px 10px #aaa;
    width: 300px;
}

.project img {
    width: 100%;
    height: auto;
}
.about img{
    width: 100%;
    height: auto;
}


```

## OUTPUT
![image](https://github.com/user-attachments/assets/578acbc7-d794-42e4-a540-436bd2067301)
![{4921D083-1CCA-4E4B-9E1F-3DF984A1056F}](https://github.com/user-attachments/assets/7c064838-321b-4ecd-8167-3318f9919ab8)
![{09A314CE-CE33-425A-9194-3917F76E08FF}](https://github.com/user-attachments/assets/bc3f5c3c-7d2d-41a6-b635-7994fe6e868c)
![{E85F377D-D22E-429F-B758-49DBA0AD14D3}](https://github.com/user-attachments/assets/e42c0135-78b6-4b01-8566-c2e9d46045c9)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
