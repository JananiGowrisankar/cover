# Ex.04 Book Front Cover Page Design
## Date:27-04-2025

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

<html>
    <head>
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:700px;
                width:600px;
                margin-left:30%;
                background-image: url("cover1.jpg");
                padding:10px;
                background-size: cover;
                align:center;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:yellow;
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:white;
                font-size: large;
            }
            
            .mypic{
                position: relative;
                top:90px;
                left:470px;
                height: 100px;
                width: 70px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            .ed{
                position:relative;
                top: 80px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-50px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:white">EXPERT INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>NextWave Computing for Future Engineers</h1></div>
            <div class="subtitle">Mastering AI, Cloud, and Quantum Systems</div>
            <div class="mypic"><img src="janani.jpg" width="120px" height="140px" ></div>
            <div class="ed" style="color: rgb(235, 231, 231);">NEW EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author">
            <div style="color:white" >Janani G (212224100022)</div>
            <div class="pb" style="color:white"> <h3>SEC</h3></div>
        </div>
        </body>
    </head>
</html>

```
## OUTPUT:

![alt text](<Screenshot 2025-04-27 163856.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
