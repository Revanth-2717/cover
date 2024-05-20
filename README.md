# Ex.06 Book Front Cover Page Design
## Date:04-04-24

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
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    margin:auto;
    position: relative;
    background-image: url(https://th.bing.com/th/id/OIP.XwFg9ja4N4sflP23rjjP6QHaEo?rs=1&pid=ImgDetMain);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: xx-large;
    font-weight:10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    color:#f47027

}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 10px;
    border-top:2px solid #f47027;
    padding-top:0px;
    width:726px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.photo{
            position: relative;
            top: 170px;
            left: 550px;
            width: 120px;
            height: 120px;
            background-size: cover;
        }
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>SPECIAL Edition</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>REVANTH.P</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="REVANTH.jpg" width="150" height="170"alt="">
            </div>  
    </section>
    </body>
</html>
body {
    background-image: url("space.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    margin-left: 100px;
    color:  white;
  }
  
  .edit {
    position: sticky;
    left: 0;
    font-size: 50px;
    color: orange;
      }
  
  h1 {
    color: white;
    font-size: 50px;
  }
  p {
     
     font-size: 100px;
  }
  
  .direct {
    font-size: 50px;
  }
  img {
    bottom: 200px;
    margin-bottom: 100px;
    margin-right: 100px;
    float: right;
  }
  .create {
    position: fixed;
    right: 0;
    margin-bottom: 20px;
    margin-right: 100px;
    bottom: 100px; 
    color: white; 
  }
 .name {
  position: fixed;
  left: 0;
  margin-bottom: 200px;
  margin-left: 100px;
  bottom: 20px; 
  color: white; 
  font-size: 50px;

 }
```
OUTPUT :
![image](https://github.com/Revanth-2717/cover/assets/152462274/7d13d52c-9599-4716-886a-e9ff6052e522)


## Developed By : P.REVANTH
## REGISTER NUMBER : 212223040143

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
