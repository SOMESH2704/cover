# Ex.06 Book Front Cover Page Design
## Date:16/11/25

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
````````````
book.html
book.html
<!DOCTYPE html>
<html>

<head>
  <title>Book Cover</title>
  <style>
    body 
    {
      margin: 0;
      padding: 0;
      background-color:rgb(8, 8, 18);
    }


    .book-cover 
    {
      width: 500px;
      height: 700px;
      background-color:rgb(0, 0, 0);
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }

    
    .book-cover .insight
    {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 35px;
      font-weight: bold;
      font-family: 'Verdana';
      color: rgb(250, 250, 250);
    }



    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }



    .book-cover .title1 
    {
      position: absolute;
      top: 80px;
      left: 20px;
      font-size: 20px;
      font-family: 'Verdana';
      font-weight: bold;
      color:  rgb(202, 224, 247);
    }

    

    .book-cover .subtitle2
    {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 17px;
      font-weight: bold;
      color: rgb(250, 249, 250);
    }



    .book-cover .subtitle3
    {
      position: absolute;
      top: 550px;
      left: 20px;
      font-size: 15px;
      font-weight: bold;
      font-family: 'Verdana';
      color: rgb(244, 245, 247);
    }



    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }



    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }



    .book-cover .college 
    {
      position: absolute;
      bottom: 20px;
      left: 20px;
      font-family: 'Verdana';
      font-weight: bold;
      font-size: 20px;
      color: rgb(255, 249, 249);
    }



    .book-cover .ed
    {
      position: absolute;
      bottom: 50px;
      left: 18px;
      font-family: 'Verdana';
      font-size: 25px;
      color:rgb(202, 224, 247);
    }

 
    .book-cover .end 
    {
      position: absolute;
      bottom: 15px;
      right: 50px;
      font-family: 'Verdana';
      font-size: 18px;
      font-weight: bold;
      color: rgb(255, 255, 255);
    }

    .book-cover .mypic
    {
      position: relative;
      top:520px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image 
    {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  

  </style>

</head>

<body>
    
    <div class="book-cover">
      <img src="c:\Users\ROSHINI\Downloads\images.jpeg" alt="Book Cover" class="image">
      <div class="insight">G.O.A.T</div>
      <div class="title1">LA PULGA</div>
      <div class="subtitle3">FATHER OF RMA<br>& IT'S IDOLO</div>
      <div class="line3"><hr style="width:400%;text-align:left;margin-left:0"></div>
      <div class="mypic"><img src= "c:\Users\ROSHINI\Downloads\POOKIE.jpeg" width="120" height="120" ></div>
      <div class="ed"><b>LEO</b></div>
      <div class="end">SEC</div>
      <div class="college">Someshwar Kumar</div>
    </div>

  </body>

</html>
````````````
## OUTPUT:

<img width="1081" height="814" alt="image" src="https://github.com/user-attachments/assets/2c8fbf65-552a-4f86-aa99-62b4d498ed89" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
