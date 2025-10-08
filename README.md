# Ex.06 Book Front Cover Page Design
## Date:8/10/25

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html
<html>
<head>
    <title>Book Cover</title>
    <link rel="stylesheet" type="text/css" href="style1.css">
</head>
<body>
    <div class="bookpage">
            <div class="insight">
               SEC insights
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>3D Animation</h1></div>
            <div class="subtitle">
                <h3>For Beginners</h3>  
            </div>
            <div class="text">
                <p>
                    This book is for beginners who want to learn 3D Animation from scratch. 
                    It covers the basics of 3D modeling, texturing, lighting, and rendering.
                    The book also includes practical examples and exercises to help readers 
                    apply their knowledge and develop their skills.

                    <li>A practical guide to animating characters with a focus on performance</li>
                    <li>
                    Covers the principles of animation, character design, and storytelling
                    </li>
                    <li>Includes tips and techniques from industry professionals</li>
                    <li>Suitable for beginners and experienced animators alike</li>
                </p>
            </div>
            <div class="mypic">
                <img src="Screenshot 2025-10-08 075829.png" width="80" height="100" align="bottom" />
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>Devesh C (25011036)</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>3<sup>rd</sup>EDITION</b>
            </div>
        </div>
        </body>
</html>

style1.css
.bookpage{

            width: 400px;
            height: 625px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('Screenshot%202025-10-05%20193158.png');
            background-size: cover;
        }
            
        
.insight{
        color:whitesmoke;
        
    }
        
        
.hrstyle{
            width:100px;
        }
.author{
        
            display: inline;
            position: relative;
            color:rgb(48, 212, 136);
            top:10px;
            
            font-family:Georgia;
            font-size: medium;
        }
.booktitle{
            color:rgb(0, 0, 0);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 10px;
        
        }
.id {
            width:400px;
            position: relative;
            top:55px;
            
        }
.pub{
            color:whitesmoke;
            font-size: medium;
            position: relative;
            top:25px;
            left:330px;
        }
.ed{
            color:whitesmoke;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            
        
        }
.subtitle{
            color:rgb(88, 66, 25);
            font-family: 'Courier New', Courier, monospace;
            font-size: large;
            position: relative;
            left: 250px;
           
        }
.mypic{
            position: relative;
            top: 10px;
            left:300px;
            width: 80px;
            height: 100px;
            background-size:contain;
            border: 3px solid black;
        }
.text{
            color:rgb(240, 153, 31);
            font-family: "Trebuchet MS", Helvetica, sans-serif;
            font-size: medium;
            position: relative;
            top: 20px;
        }        
 ```       

## OUTPUT:
![alt text](<Screenshot (28).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
