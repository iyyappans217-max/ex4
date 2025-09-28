# Ex04 Places Around Me
## Date:28/09/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>
            My City_town </title>
    </head>
    <body>
        <h2 style="color:cadetblue;text-align: center;"><b>Chidambaram<br></b></h2>
        <h2 style="text-align: center;color:blueviolet;">IYYAPPAN S (25014014)</h2>
   


<img src="map.png" usemap="#image-map" >

<map name="image-map">
    <area target="_blank" alt="Natarajar_Temple" title="Natarajar_Temple" href="natarajar.html" coords="15,54,369,256" shape="rect">
    <area target="_blank" alt="Annamalai_University" title="Annamalai_University" href="annamalai.html" coords="1247,726,127" shape="circle">
    <area target="_blank" alt="Pasupatheeshwarar_Temple" title="Pasupatheeshwarar_Temple" href="pasupatheeshawaar.html" coords="1523,565,1830,706" shape="rect">
</map>
     
    </body>
</html>



annamalai.html

<center><h1 style="color: violet;">Annamalai University - Chidambaram</h1>
    <img src="annamalaipic.png" height="50%">
<h3><pre>university Name: Annamalai University
Location: Chidambaram, Tamil Nadu, India (very close to Natarajar Temple).
Established: 1929
Founder: Dr. Rajah Sir,
S. R. M. Annamalai Chettiar,
they are a philanthropist and educationist.
Type: State Public University (taken over by Government of Tamil Nadu in 2013).
Campus Size: Approximately 800-1000 acres
Accreditation: NAAC recently gave it an A+ grade in its 4th cycle.
Student Population: Tens of thousands; large residential campus. Many hostels (for students). 
Quality variations: As with many large universities, standards may vary across departments / affiliated colleges.
Admissions: On-campus and Distance Education admissions are open for various programmes. 
Annamalai University
+1
Fees & Scholarships: There are various scholarships (merit, state govt, etc.). Course fees vary significantly depending on the programme (e.g. B.Pharm, MSc etc.) 
collegedunia.com
</h1></pre>
</center>


natarajar.html

<center><h1 style="color: blue;"><b>Natarajar temple  </b>located in chidambaram </h1>
    <h1>Shivaya Nama!!<br></h1>

<h3>Most of the people know about this Temple that is located at center of our Earth</h2>
<h2><pre>Thillai natarajar Temple Spread across 40 acres, with four tall gopurams (gateway towers).

Contains five sabhas (halls) where different rituals and festivals happen.

Represents Dravidian temple architecture at its finest.

Shiva killed the tiger (wearing its skin), tamed the serpent, and crushed the demon under his foot.

Then he performed the Ananda Tandava (cosmic dance of bliss) in the forest.

The sages realized their ego and surrendered. This place became Chidambaram, the site of the eternal dance.
<img src="natarajarpic.png" width="60%" height="600cm">
</pre></h2></center>


pasupatheeswarar.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pasupatheeshwarar_Temple</title>
</head>
<body>
    <center><h1 style="color: crimson;"> Pasupathyeeswarar Temple</h1>
    <h2>The Pasupatheeswarar Temple is situated in Chidambaram, Cuddalore District, Tamil Nadu.<br> It is one of the ancient temples dedicated to Lord Shiva.</h1>
    <pre><h2>Festivals  Celebration 

            1. Maha Shivaratri and Margazhi Thiruvadhirai are celebrated grandly.
            2. Annual temple festivals attract devotees from nearby regions.</h2>
</pre>
<center><img src="pasupathytemplepic.png"></center>
     <pre>   <h2>Main Deity: Lord Shiva, worshipped here as  <q>Pathupatheeswarar.</q>

The name means “Lord of Ten Directions” (Pathu = Ten, Patheeswarar = Lord Shiva).

Goddess Parvati is also worshipped here as Periyanayaki Amman.</h2> </pre>   </center>
</body>
</html>

```
## OUTPUT

![alt text](../resmap.png)

![alt text](../resannamalai.png)

![alt text](../resnatarajar.png)

![alt text](../respasupathy.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
