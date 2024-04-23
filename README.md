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

map.html
<!DOCTYPE html>
<html>
    <head>
        <title>nellore</title>

    </head>
    <body>
        <h1 align="center">
            <font color="RED"><b>NELLORE</b></font>
        </h1>
        <h3 align="center"><font color="blue"><b>P.REVANTH (212223040143)</b></font></h3>
        <center><img src="Screenshot 2024-04-02 201810.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="MGB mall" title="MGB mall" href="mall.html" coords="632,613,444,583" shape="rect">
    <area target="" alt="Hotel minerva grand" title="Hotel minerva grand" href="hotel.html" coords="653,486,829,529" shape="rect">
    <area target="" alt="ISKCON temple" title="ISKCON temple" href="temple.html" coords="616,692,771,738" shape="rect">
    <area target="" alt="Apollo hospitals" title="Apollo hospitals" href="hospital.html" coords="841,502,1067,555" shape="rect">
    <area target="" alt="AVM function hall" title="AVM function hall" href="hall.html" coords="1158,129,1327,171" shape="rect">
</map>
       </center>
    </body>
</html>

mall.html

<html>
    <head>
        <title>MALL</title>
    </head>
    <body bgcolor="YELLOW">
        <h1 align="center">
            <font color="BLUE"><b>NELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="RED"><b>MGB MALL</b></font>
        </h3>
        <hr size="5" color="GREEN">
        <p align="justify">
            <font face="Georgia" size="5">

                We opened for business on June 24, 2016. And, in the short span of time it has traversed between then and now, patrons and the mall management have together turned MGB Felicity Mall into a trendsetter in the region. It is a vibrating and well-frequented space of 320,000 sq. ft. spanning six floors—the only organized mall in and around an 180kms radius of Nellore, covering four districts (Nellore, Prakasam, Kadapa, and Chittoor). In a span of 36 months, MGB Felicity Mall has received over 13 million visitors and has achieved a very strong YOY growth record with business conversion seeing double digit growth over the previous year. With plentiful options for entertainment, dining, and modern-day shopping, MGB Felicity Mall is a thoughtfully laid out destination—a family entertainment center that is today Andhra Pradesh’s largest mall!</font>
        </p>

    </body>
</html>

hotel.html
<html>
    <head>
        <title>hall</title>
    </head>
    <body bgcolor="BLUE">
        <h1 align="center">
            <font color="GREEN"><b>NELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="YELLOW"><b>MINERVA HOTEL</b></font>
        </h3>
        <hr size="5" color="BLACK">
        <p align="justify">
            <font face="Georgia" size="5">

                Hotel Minerva Grand has conference and convention spaces, which make it an ideal choice for business meetings and official parties. 
The famous Lord Vishnu Sri Ranganathaswamy Temple is just a 10-minute drive away from the hotel.
Minerva Grand is located at a 10-minute driving distance from the Nellore Railway Station. 
Its on-site bar has a private seating area. </font>
        </p>

    </body>
</html>

temple.html
<html>
    <head>
        <title>hall</title>
    </head>
    <body bgcolor="ORANGE">
        <h1 align="center">
            <font color="RED"><b>NELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="BLUE"><b>ISKCON TEMPLE</b></font>
        </h3>
        <hr size="5" color="CYAN">
        <p align="justify">
            <font face="Georgia" size="5">

                The ISKCON Nellore, Sri Sri Radha Shyamasundar Temple is a significant spiritual and cultural destination located in the city of Nellore, Andhra Pradesh, India. This temple is part of the International Society for Krishna Consciousness (ISKCON), a movement known for its dedication to the practice and promotion of Bhakti Yoga, with temples all around the world.
Established as a part of the global ISKCON network, the ISKCON Nellore temple was constructed to provide a space for devotees to worship and to spread the teachings of Lord Krishna as outlined in the ancient texts of the Bhagavad Gita and Srimad Bhagavatam. The temple's primary deities, Sri Sri Radha Shyamasundar, represent the divine love between Lord Krishna and his consort Radha.</font>
        </p>

    </body>
</html>

hospital.html
<html>
    <head>
        <title>hall</title>
    </head>
    <body bgcolor="PINK">
        <h1 align="center">
            <font color="BLACK"><b>NELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="GREEN"><b>APOLLO HOSPITALS</b></font>
        </h3>
        <hr size="5" color="BLUE">
        <p align="justify">
            <font face="Georgia" size="5">

                Established by Dr Prathap C Reddy in 1983, Apollo Healthcare has a robust presence across the healthcare ecosystem. From routine wellness & preventive health care to innovative life-saving treatments and diagnostic services, Apollo Hospitals has touched more than 200 million lives from over 120 countries.</font>
        </p>

    </body>
</html>

hall.html
<html>
    <head>
        <title>hall</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
            <font color="blue"><b>NELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="red"><b>AVM FUNCTION HALL</b></font>
        </h3>
        <hr size="5" color="cyan">
        <p align="justify">
            <font face="Georgia" size="5">

                Banquet Halls is an enclosed space suitable for hosting a variety of events such as birthday parties, corporate events, engagement ceremonies, weddings, receptions, etc. They are beautifully designed and decorated to create an elegant ambience for any event you are hosting. Banquet halls can be booked for a stipulated time period during which the event has to take place. There are many banquet halls available in Nellore that you can use based on your requirements.
                
                you are on the hunt for a beautiful, well-connected hall, then get in touch with AVM Function Hall in Nawabpet, Nellore. It provides many other services apart from event space and has a rating of 4.4 for its services.</font>
        </p>

    </body>
</html>

## OUTPUT:
![alt text](https://github.com/Revanth-2717/cover/assets/152462274/c504aa8a-b447-42c5-b793-65eea754dbe7)
![alt text](https://github.com/Revanth-2717/cover/assets/152462274/dc3a84c5-3a74-4046-9787-a61de8c52e60)
![alt text](https://github.com/Revanth-2717/cover/assets/152462274/b95956ce-75be-40ca-9ed5-98a0ab64c283)
![alt text](https://github.com/Revanth-2717/cover/assets/152462274/4c812d24-9366-4451-b91b-d03c744b878d)
![Walt text](https://github.com/Revanth-2717/cover/assets/152462274/24dd6c4d-cf5e-4c91-afad-b85d64481f85)
![alt text](https://github.com/Revanth-2717/cover/assets/152462274/9f97a94f-6550-4c6a-8f25-0451ad80a4dd)

## Developed By : P.REVANTH
## REGISTER NUMBER : 212223040143

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
