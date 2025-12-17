# Ex.06 Book Front Cover Page Design
## Date:17/12/2025

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
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #0c0205;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(187, 194, 184);
      border: 2px solid #c5b1b1;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(19, 8, 8, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 32px;
      font-weight: italic;
      color: #965319;
      text-align: center;
      line-height: 1.4;
    }

    .subtitle {
      font-size: 12px;
      margin-top: 10px;
      text-align: center;
      font-style: bold;
    }

    .image {
      flex: 1;
      background: url('https://images.pexels.com/photos/13095146/pexels-photo-13095146.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500') center/contain no-repeat;
      margin: 50px 0;
    }

    .author {
      font-size: 20px;
      text-align: right aline;
      color: #0a010e;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: #d82e10;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title"><b>LORD OF THE FILES</b></i></div>
      <div class="line"></div>
      <div class="subtitle">BRITISH SCHOOLBOYS STANDARD ON THE DESERTED ISLAND AFTER PLANE CRASH</div>
    </div>
    <div class="image">
        <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-09-27 141645.png" length="20%" width="200%">
    </div>
    <div class="author"><b><i>SANTHOSH SIVAKUMAR</i></b></div>
  </div>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot 2025-12-17 160405.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
