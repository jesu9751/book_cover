# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
'''
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Book Cover</title>
  <style>
    body {
      background-color:black;
      text-align: center;
    }

    .book-container {
      position: relative;
      display: inline-block;
    }

    .book-cover {
      height: 700px;
      width: 450px;
    }

    .image {
      position: absolute;
      bottom: 40px;
      right: 10px;
      width: 120px;
      height: 120px;
      border-radius: 100px;
    }

    .author{
      position: absolute;
      bottom:0px;
      right: 0px;
      color:azure;
      font-family: 'Times New Roman', serif;
      font-size:x-large;
      margin: 10px auto;
      width: 50%;
    }
    .title {
    position: absolute;
    top: 40px;
    width: 100%;
    font-family: Georgia, 'Times New Roman', Times, serif;
    text-align: center;
    font-size: 50px;
    font-weight: bold;
    color:darkslategray;
    }

    .oneline{
    position: absolute;
    top: 120px; 
    font-family:Arial, Helvetica, sans-serif;
    width: 100%;
    text-align: center;
    font-size: 20px;
    color:;
    }
    .line{
      height: 1px;
      width: 150px;
      margin-left: 10px;
      margin-top: auto;
      margin-bottom: auto;

    }
    .bottom {
      position: absolute;
      bottom: 1px;
      width: 40%;
      border: 0;
      border-top: 3px solid darkgray;
      margin:0 0 10px 300px; 
      right:20px;
    }

  </style>
</head>
<body>
  <div class="book-container">
    <div class="title">INDIANA JONES</div>
    <div class="oneline" >Adventure, history, booby-trapped tombs, whips, fedoras, and saving the world</div>
    <hr class="bottom">
    <span class="author">GEORGE LUCAS </span>
    <img src="images.jpg"  class="book-cover">
    <img src="image.png" class="image">
  </div>
</body>
</html>
'''
# OUTPUT:

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
