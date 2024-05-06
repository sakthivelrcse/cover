# Ex.06 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html>

<head>
    <title>BOOK COVER</title>
    <style>
        .bookcover{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(backg.jpeg);
            background-size: cover;
        }
            
        
        .head{
            color:rgb(248, 245, 245);
        
        }
        
        
        .style{
            width:100px;
        }
        .authorname{
        
            display: inline;
            position: relative;
            color:rgb(136, 72, 49);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .title{
            color:rgb(244, 238, 238);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .line {
            width:400px;
            position: relative;
            top:180px;
            
            
        }
        .last{
            color:rgb(174, 96, 106);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .end{
            color:rgba(167, 186, 61, 0.94);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:rgb(158, 124, 114);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookcover">
            <div class="head">
                SEC PUBLICATIONS
            </div>
            <div class="style">
                <hr style="color:rgb(252, 252, 252)">
            </div>
            <div class="title">
                <h1>Programming Languages</h1></div>
            <div class="subtitle">
                Principles and Paradigms
            </div>
            <div class="photo">
                <img src="image.jpg" width="90" height="100">
            </div>
            <div class="line">
                <hr style="color:rgba(144, 203, 219, 0.555)">
            </div>
            <div class="authorname">
               <p><b>Sakthivel R</b></p>
            </div>
            <div class="last">
                SEC
            </div>
            <div class="end">
                <b>REVISED EDITION</b>
            </div>
        </div>
        </body>

```


## OUTPUT:

![SAKTHI123](https://github.com/sakthivelrcse/cover/assets/116993934/6bdac865-c49e-4239-849d-25988053997f)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
