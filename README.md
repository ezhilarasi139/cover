# Ex.06 Book Front Cover Page Design
## Date:14.12.2024

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
<html>
    <head>
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left:auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(back.jpg);
            background-size: cover;
        }
        .insight{
            color: #FF1493;
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display:inline;
            position:relative;
            color: orange;
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color: cyan;
        }
        .id{
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left: 330px;
            color: yellow; 
        }
        .ed {
            color: #00FA9A;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;
        }

        .subtitle{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top:40px;
            color: white;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
            border-radius: 50%; /* Keep the circular shape of the image */
            /* border: 3px solid #FFFFFF; */ /* Remove this line to get rid of the white border */
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body> 
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">   
    <hr style="color: #FFD700;">
</div>
<div class="booktitle">
    <h1>Web Development: The Complete Reference</h1>
</div>
<div class="subtitle">
    with Django and Bootstrap Insights
</div>
<div class="mypic">
    <img src="photo.jpg" width="130" height="145" alt="">
</div>
<div class="id">
    <hr style="color: orange">
</div>
<div class="author">
    <p><b>Ezhilarasi N</b></p>
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

![alt text](<Screenshot (48).png>)


## RESULT:

The program for designing book front cover page using HTML and CSS is completed successfully.

