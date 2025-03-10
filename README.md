# Ex01 Portfolio
## Date: 10-03-2025

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
NAME:Senthil kumaran c
REG.NO:212223220103
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio</title>
    <style>
        body
        {
            background-image:url(img.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            height: 100vh;
            margin: 0;
        }
    
        .sk
        {
            font-size: 36px; 
            font-weight: bold;
            color: #fffefe;
            text-align: center; 
            text-transform: uppercase;
            letter-spacing: 2px; 
            background-color: deepskyblue;
            padding: 10px 20px; 
            border-radius: 8px;
            box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.1); 
        }
        .cc1
        {
            width: 100px; 
            height: 100px; 
            border-radius: 50%;
            object-fit: cover; 
            border: 3px solid #333; 
            box-shadow: 2px 2px 10px rgb(240, 236, 236);

        }
        .hq{
            color: aliceblue;
            font-family: 'Times New Roman', Times, serif;
        }
        #zz{
            font-size: large;
            font-family: 'Times New Roman', Times, serif;
        }
        #ss{
            font-size: large;
            font-family: 'Times New Roman', Times, serif;
        }
        .main{
            display: flex;
            gap: 30px;
            justify-content: space-around;
        }
        .cccc{
            box-shadow: 2px 2px 10px rgb(240, 236, 236) ;
            background-color: #f8fafa30;
        }
        .ccc{
            display: inline-flex;
            flex-direction: column;
            gap: 5px;
            box-shadow: 2px 2px 10px rgb(240, 236, 236) ;
            background-color: #f8fafa30;
        }
        .cc{
            display: inline-flex;
            justify-content: right;
            gap: 20px;
            background-color: deepskyblue;
            
        }
        .qe{
            display: flex;
            flex-direction: row;
            gap: 12px;
            justify-content: center;
            background-color:  deepskyblue;
        }
        .ft{
            
            width: 50px; 
            height: 50px; 
            border-radius: 50%;
            object-fit: cover; 
            border: 3px solid #333; 
            box-shadow: 2px 2px 10px rgb(240, 236, 236);
        }
        .abc{
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .qw{
            display: flex;
            flex-direction: column;
        }
    </style>
</head>
<body>
    <h1 class="sk hq" >SENTHIL'S portfolio</h1>
    <div class="main">
        <div class="ccc">
            <div class="cc">
                <img class="cc1" src="c:\Users\admin\Desktop\WEB EX1\immg3.jpg" alt="goku">
                <h1 class="abc hq" >SENTHIL KUMARAN C</h1>
                <br>
                <h2 class="abc hq">(Web developer)</h2>
            </div>
            
            <div class="abc">
                <h3 class="abc hq">ABOUT ME:</h3>
                <pre class="hq" id="zz">                    Hi, I am Senthil and I work as a web developer.
                    I am a software engineer who loves to create websites as well as apps for people. 
                    I think that people should look at the bigger picture when they are building something. 
                    I love to work in groups where everyone can voice their opinions and ideas.</pre>
            </div>
            <div class="job">
                <h3 class="hq">CERTIFICATION:</h3>
                <ul>
                    <li class="hq"><strong>UG:</strong>
                        <ul>
                            <li class="hq"><strong>Degree:</strong> B.Tech Information Technology</li>
                            <li class="hq"><strong>College:</strong> Saveetha Engineering College</li>
                        </ul>
                    </li>
                
                    <li class="hq"><strong >Career:</strong>
                        <ul>
                            <li class="hq">Meta Front-End Developer Certificate</li>
                            <li class="hq">Google UX Design Professional Certificate</li>
                            <li class="hq">Full-Stack Web Development with React (by The Hong Kong University of Science and Technology)</li>
                            <li class="hq">JavaScript Algorithms and Data Structures Certification (freeCodeCamp)</li>
                        </ul>
                    </li>
                </ul>
                
            </div>
            <div class="qw">
                <h3 class="hq">CONTACT ME:</h3>
                <pre class="hq">
                   >gmail:<a href="google.com">senthilkumaran54577@gmail.com</a>
                   >LinkedIn Id:senthil1234567
                   >ph.no:63xxxxxxx
                   >github:senthil77k
                   >address: No:12(fake)/a sbcc street chennai-602001</pre>
            </div>
            <div class="qe">
                <img class="ft" src="c:\Users\admin\Desktop\WEB EX1\1200x600wa.png" alt="goo">
                <img class="ft" src="c:\Users\admin\Desktop\WEB EX1\fb.webp" alt="fb">
                <img class="ft" src="c:\Users\admin\Desktop\WEB EX1\ins.png" alt="insta">
                <img class="ft" src="x-app-logo1.webp" alt="x app">
                <img class="ft" src="linkedin_hero_1200_675.avif" alt="in">
            </div>

    
        </div>
        <div class="cccc">
            <h1 class="hq"> skill learned:</h1>
            <ul>
                <li class="hq"><strong>Programming Languages:</strong>
                    <ul>
                        <li class="hq">HTML</li>
                        <li class="hq">CSS</li>
                        <li class="hq">JavaScript</li>
                        <li class="hq">(Optional depending on role) Python, PHP, Ruby</li>
                    </ul>
                </li>
            
                <li class="hq"><strong>Front-End Frameworks:</strong>
                    <ul>
                        <li class="hq">React</li>
                        <li class="hq">Angular</li>
                        <li class="hq">Vue.js</li>
                    </ul>
                </li>
            
                <li class="hq"><strong>Back-End Frameworks (if applicable):</strong>
                    <ul>
                        <li class="hq">Node.js</li>
                        <li class="hq">Django</li>
                        <li class="hq">Laravel</li>
                    </ul>
                </li>
            
                <li class="hq"><strong>Other Technical Skills:</strong>
                    <ul>
                        <li class="hq">Responsive design</li>
                        <li class="hq">Cross-browser compatibility</li>
                        <li class="hq">REST APIs</li>
                        <li class="hq">Version control systems (Git)</li>
                        <li class="hq">Build tools (Webpack, Gulp)</li>
                    </ul>
                </li>
            
                <li class="hq"><strong>Soft Skills:</strong>
                    <ul>
                        <li class="hq">Problem-solving</li>
                        <li class="hq">Communication</li>
                        <li class="hq">Teamwork</li>
                        <li class="hq">Adaptability</li>
                    </ul>
                </li>
            </ul>
            <ul>
                <li class="hq" id="ss">
                    <strong>Problem-solving:</strong> A soft skill that can help you handle tasks, mitigate risks, and improve productivity.
                </li>
                <li class="hq" id="ss">
                    <strong>Time management:</strong> A personal skill that can help you prioritize tasks, manage your schedule, and meet deadlines.
                </li>
                <li class="hq " id="ss">
                    <strong>Leadership:</strong> A professional skill that can help you organize people to achieve goals.</li>
                <li class="hq" id="ss"><strong>Interpersonal skills:</strong> A skill that can help you work with others, solve problems, and lead projects.
                </li>
                <li class="hq" id="ss">
                    <strong>Adaptability:</strong> A skill that can help you adapt to changing requirements, circumstances, and strategies.
                </li>
                <li class="hq" id="ss">
                    <strong>Communication:</strong> A skill that can help you express your opinions and convey your messages clearly.
                </li>
                <li class="hq" id="ss">
                    <strong>Active listening:</strong> A skill that can help you focus on a speaker, understand their message, and respond thoughtfully.
                </li>
                <li class="hq" id="ss">
                    <strong>Creativity:</strong> A skill that can help you think unconventionally and originate novel concepts.
                </li>
            </ul>
        </div>
        
    </div>
</body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/bc1bc700-d20e-4ca4-a421-1c714aa53bf2)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
