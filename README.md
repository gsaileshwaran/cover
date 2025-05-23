# Ex.06 Book Front Cover Page Design
## Date: 18-04-2025

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
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover Design</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .cover-container {
      width: 400px;
      height: 600px;
      background-image: url('/static/cover.jpg'); 
      background-size: cover;
      background-position: center;
      color: #fff;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 30px 20px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.3);
      border-radius: 12px;
      text-align: center;
    }

    header, footer {
      background-color: rgba(0, 0, 0, 0.5);
      padding: 10px;
      font-weight: bold;
      border-radius: 8px;
      font-size: 1.1rem;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      margin: 20px 0 10px;
    }

    .subtitle {
      font-size: 18px;
      font-style: italic;
      margin-bottom: 30px;
    }

    .author-info {
      margin-top: auto;
    }

    .author-name {
      font-size: 16px;
      font-weight: bold;
    }

    .register-no {
      font-size: 14px;
      margin-bottom: 10px;
    }

    .profile-pic {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #fff;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="cover-container">
    <header>BOOK COVER DESIGN</header>

    <div>
      <div class="title">Python For Beginners</div>
      <div class="subtitle">Coding at your fingertips</div>
    </div>

    <div class="author-info">
      <div class="author-name">Saileshwaran Ganesan</div>
      <div class="register-no">Reg No: 212224230237</div>
      <img src="/static/myself.jpg" alt="Your Photo" class="profile-pic" />
    </div>

    <footer>SAVEETHA ENGINEERING COLLEGE</footer>
  </div>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2025-04-18 202601.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
