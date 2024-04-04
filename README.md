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
```html
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
    background-image: url(https://static.vecteezy.com/system/resources/previews/001/962/594/large_2x/abstract-wave-element-for-design-stylized-line-art-background-free-vector.jpg);
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
            <h3>Third Edition</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>P.REVANTH</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="c:\Users\revan\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\CDBC9BCA0A9FD93852571CCED0089C4D\WhatsApp Image 2024-04-04 at 22.09.20_eb09af52.jpg" width="150" height="170"alt="">
            </div>  
    </section>
    </body>
</html>
```

## OUTPUT:
![screenshot](https://github.com/Revanth-2717/cover/assets/152462274/9246fde9-c26e-43e5-8c61-5e31e1000c7d)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
