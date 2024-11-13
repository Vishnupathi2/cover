# Ex.06 Book Front Cover Page Design
## Date: 25/10/2024

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
book.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(10, 10, 10);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('BOOK.jpg');
            background-size: cover;
        }

        .insight{
            color:rgb(13, 6, 6) ;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(76, 137, 29);
            display: inline;
            position: relative;
            color: rgb(32, 174, 176);
            top: 220px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 60px;
        }

        .id{
            width: 410px;
            position: relative;
            top: 210px;

        }

        .pub{
            font-size: large;
            position: relative;
            top: 170px;
            left: 300px;
        }
        .ed{
            color: rgb(133, 34, 118);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 110px;

        }
        .subtitle{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 70px;
        }
        .mypic{
            position: relative;
            top: 180px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="EXPERT INSIGHT">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(10, 10, 10);">
            </div>
            <div class="booktitle">
                <h1>BASICS OF WEB DEVELOPMENT</h1>
            </div>
            <div class="subtitle">
            Basic Guide For Beginners
            </div>
            <div class="mypic">
                <img src="my image.jpg" width="120" height="120" alt="Error">
            </div>
            <div class="id">
                <hr style="color:rgb(10, 10, 10);">
            </div>
            <div class="author">
                <p><b>PRIYADHARSHINI.P</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![vp (1)](https://github.com/user-attachments/assets/6a1fb5f4-a439-4ad5-a42d-0c45cc886ecc)








## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
