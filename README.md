# Ex01 Portfolio
## Date: 13/08/2025

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
portfolio.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <title>My Portfolio</title>
</head>
<body>
    <nav class="header">
        <h1>Porfolio</h1>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#project">Project</a></li>
            <li><a href="#contact">Contact us</a></li>
        </ul>
    </nav>



    <div id="about">
        <center>
       
        <h1>Hi, I'm Harshavarthan</h1>
        <h3>I am a passionate learner exploring the exciting world of programming and web development. 
            I’m currently building my skills in Java, HTML, CSS, JavaScript.
            I enjoy creating interactive, user-friendly websites and applications while continuously expanding my knowledge 
            of both frontend and backend technologies. My goal is to turn ideas into functional, creative digital solutions.</h3>


        </center>
      
    </div>

    <div id="education">
        <center><h1>My Education</h1></center>
        <div id="level">
        <div class="standard">
            <h4>VICTORIA MATRICULATION HIGHER SECONDARY SCHOOL</h4>
            <h4>2021-2022</h4>
            <h4>SSLC</h4>
        </div>
        <div class="standard">
            <h4> VICTORIA MATRICULATION HIGHER SECONDARY SCHOOL</h4>
            <h4>2023-2024</h4>
            <h4>HSC</h4>
        </div>
        <div class="standard">
            <h4>Saveetha Engineering College</h4>
            <h4>2024-2028</h4>
            <h4>B TECH - IT</h4>
        </div>
     </div>
    </div>

    <div id="skills">
        <center><h1>My Skills</h1></center>
        <div id="skillset">
            <div class="skill">
                <h4>Java</h4>
            </div>
            <div class="skill">
                <h4>HTML</h4>
            </div>
            <div class="skill">
                <h4>CSS</h4>
            </div>
            <div class="skill">
                <h4>JavaScript</h4>
            </div>
            <div class="skill">
                <h4>Communication</h4>
            </div>
            <div class="skill">
                <h4>Java</h4>
            </div>
            <div class="skill">
                <h4>Python</h4>
            </div>
            <div class="skill">
                <h4>C</h4>
            </div>

        

        
        
     </div>
    </div>

    <div id="project">
        <center><h1>My Projects</h1></center>
        <div id="projects">
            <div class="project-item">
                <h4>Portfolio</h4>
                <h4>A personal portfolio website showcasing my skills, education, and projects.</h4>
                <h4>Technologies used: HTML,CSS</h4>
            </div>
            <div class="project-item">
                <h4>Employee Management System</h4>
                <h4>A web-based system to manage employee records (CRUD), attendance, and performance tracking.</h4>
                
            </div>



        </div>
    </div>
    <div id="contact">
    <center><h1>Contact Us</h1></center>

    <div class="data-item">
        <h4>Phone: 9999999999</h4>
    </div>
    <div class="data-item">
        <h4>Email: harshavartha01@gmail.com</h4> 
    </div>

   <center> <p>Feel free to react out for any inqurites or collaborations</p></center>

    

    <div class="social-links">
        <a href="https://github.com/your-username" target="_blank" class="github">
            <i class="fab fa -github"></i>
            
        </a>
        <a href="https://linkedin.com/in/your-username" target="_blank" class="linkedin">
            <i class="fab fa-linkedin"></i>
        </a>
    </div>
</div>
</body>
</html>
```
portfolio.css

```
*{
    margin:0;
    padding:0;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.header{
    background-color: black;
    color:white;
    display:flex;
    padding:15px;
    justify-content: space-between;
}

.header h1{
    margin-left:30px;
    font-size: 29px;
}

nav ul{
    display:flex;
    margin: 10px;
    font-size: 20px;
    list-style: none;
}

nav ul li{
    margin-left:20px;
    background-color:white;
    padding:10px;
    border-radius: 10px;
   
    
}

nav ul li a{
    text-decoration: none;
    color:black;
}


nav ul li:hover{
    background-color: black;
   
}

nav ul li a:hover{
     color:white;
}

#about{
    width:800px;
    display: flex;
    flex-direction: column;

    justify-content: space-between;
   

    margin-left: 350px;
    margin-top:100px;
    border:3px solid black;
    border-radius: 10px;
    height:190px;
    padding:25px;
    box-shadow: 2px 2px 2px 2px black;
    
   
}

#education{
    margin-top:50px;

}

#level{
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 20px;
}
.standard{
    display:flex;
    flex-direction: column;
    justify-content: center;
    background-color:white;
    color:black;
    width:400px;
    padding:20px;
    border-radius: 15px;
    box-shadow: 2px 2px 2px 2px black;

}

#skills{
    margin-top:50px;

}

#skillset{
    display:grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    grid-gap: 20px;


    margin-right: 5px;
    margin-top:30px;
    margin-left:150px;
  
    
    
}
.skill{
   
   
    background-color: black;
    color:white;
    width:90px;
    padding:20px;
    border-radius: 15px;
    box-shadow: 2px 2px 2px 2px black;

}


#project{
    margin-top:100px;

}

#projects{
    display:grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    grid-gap: 20px;


    margin-right: 5px;
    margin-top:30px;
    margin-left:100px;
  
    
    
}
.project-item{
    display:flex;
    flex-direction: column;
    align-items: center;
    background-color:white;
    color:black;
    border:2px solid white;
    width:400px;
    padding:20px;
    border-radius: 15px;
    box-shadow: 2px 2px 2px 2px black;

}

#contact{
    background-color: black;
    color:white;
    position:absolute;
    top:180%;
    height:230px;
    width:100%;
}

.data-item{
    display:flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

.social-links {
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

.social-links a {
    font-size: 2.5rem;
    margin: 0 15px;
    color: white;
    transition: transform 0.2s, color 0.3s;
}

.social-links a.github:hover {
    color: #999; 
    transform: scale(1.2);
}

.social-links a.linkedin:hover {
    color: #0077b5; 
    transform: scale(1.2);
}


#contact center p{
    font-size: 20px;
    color: white;
    margin-top: 10px;
}
```
## OUTPUT
<img width="1906" height="926" alt="image" src="https://github.com/user-attachments/assets/7c6d5e45-880a-4fdf-825d-4b3233eed1dd" />
<img width="1919" height="931" alt="image" src="https://github.com/user-attachments/assets/6d3bcd58-ae0f-4d73-8f0d-1f55f6bd6d10" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
