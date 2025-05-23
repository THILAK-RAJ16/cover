# Ex.06 Book Front Cover Page Design
## Date:20/4/2025

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
    <title>Book Cover</title>
    <style>
        body {
            background-color: white;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 400px;
            height: 600px;
            margin: 50px auto;
            border: 2px solid black;
            position: relative;
            overflow: hidden;
        }
        .container img.bg {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }
        .title {
            color: white;
            position: absolute;
            top: 20%;
            left: 48%;
            transform: translateX(-50%);
            font-size: 24px;
            font-weight: bold;
            text-shadow: 2px 2px 5px black;
        }
        .author {
            position: absolute;
            bottom: 300px;
            right: 160px;
            width: 80px;
            height: 90px;
            border-radius: 50%;
            border: 3px solid white;
            object-fit: cover;
            box-shadow: 0 0 8px rgba(0,0,0,0.4);
        }
        .phase2 {
            position: absolute;
            bottom: 0;
            width: 100%;
            text-align: right;
            color: white;
            background: rgb(28, 28, 87);
            text-shadow: 1px 1px 3px black;
            padding: 10px 0;
            margin-right: 15px;
}

    </style>
</head>
<body>
    <div class="container">
        <img class="bg" src="/static/Blue Technology Future Artificial Intelligence Background Wallpaper Image For Free Download - Pngtree.jpg" alt="Background">
        <h1 class="title">AI: A Friend or Foe</h1>
        <img class="author" src="/static/DSC_4086[1].jpg" alt="Photo">
        <div class="phase2">
            <h3  style="color: white;">Thilak Raj .P</h1>
            <h4 style="color: white;">Saveetha Engineering College</h2>
        </div>
    </div>
    
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-04-20 184455.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
