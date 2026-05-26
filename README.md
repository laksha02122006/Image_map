# Ex03 Places Around Me
# Date:26/5/26
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="darkpink"><b>Marthandom</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b>V.B.Laksha(24900349)</b></font>
</h3>
<center>
<img src="map.png.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="1040,481,829,417" href="home.html" title="My Home Town">
<area shape="rect" coords="1382,228,1171,164" href="church.html" title="Marthandom Church">
<area shape="rect" coords="633,603,695,489" href="river.html" title="Thamirabarani River">
<area shape="rect" coords="310,541,99,477" href="school.html" title="Good Shepherd School">
<area shape="rect" coords="348,166,638,260" href="waterfalls.html" title="Thirparappu Waterfalls">
</map>
</center>
</body>
</html>

```

```
home.html


<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lavender">
<h1 align="center">
<font color="darkpink"><b>Marthandom</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b>My Home Town - Marthandom</b></font>
</h3>
<hr size="3" color="black">
<p align="center">
<img src="home.png.png" width="400" height="250" alt="Marthandom">
</p>
<p align="justify">
<font face="Georgia" size="5">
Marthandam is the second-largest town in the district Kanyakumari. It derived its name from the founder and ruler of Travancore, Anizham Thirunal Marthanda Varma. Marthandam is famous for honey, cashew nut processing, rubber and hand-embroidered motifs. The area is among the most fertile lands of Tamil Nadu, with substantial vegetation and a river adjoining. It is also a major trade centre due to its location bordering Kerala.
</p>
</body>
</html>

```

```
church.html


<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
<h1 align="center">
<font color="black"><b>Marthandom</b></font>
</h1>
<h3 align="center">
<font color="darkgreen"><b>Marthandom Church</b></font>
</h3>
<hr size="3" color="black">
<p align="center">
<img src="church.png.png" width="400" height="250" alt="Marthandom church">
</p>
<p align="justify">
<font face="Georgia" size="5">
The Marthandam CSI Church is a prominent, historic district church in the Kanyakumari Diocese of Tamil Nadu. Completed in 1933 under the vision of Scottish missionary Rev. Robert Sinclair, it features striking Gothic-style architecture, a three-faced clock tower, and a rich legacy of community welfare.
</p>
</body>
</html>

```
```
river.html


<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="skyblue">
<h1 align="center">
<font color="darkblue"><b>Marthandom</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b>Thamirabarani River</b></font>
</h3>
<hr size="3" color="black">
<p align="center">
<img src="river.png.png" width="400" height="250" alt="Adyar River">
</p>
<p align="justify">
<font face="Georgia" size="5">
The Thamirabarani River (also referred to locally as the Kodayar River) passes directly through the Marthandam region in Kanyakumari District. Originating in the Western Ghats, it is a vital local lifeline famous for hosting the massive annual Vavubali ritual, where thousands of devotees gather at its banks to pay homage to their ancestors
</p>
</body>
</html>

```
```
waterfalls.html


<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Marthandom</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Thirparrappu</b></font>
</h3>
<hr size="3" color="black">
<p align="center">
<img src="waterfalls.png.png" width="400" height="250" alt="Agastheeshwarar Temple">
</p>
<p align="justify">
<font face="Georgia" size="5">
Thirparappu Waterfalls is a natural waterfall, created by the Pahruli River cascading over rocky terrain. Its tiered formation and clear pools are naturally occurring, offering scenic views and a calm environment for picnics, photography, and short nature walks.
</p>
</body>
</html>
```
```
school.html


<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="brown">
<h1 align="center">
<font color="black"><b>Marthandom</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Good Shepherd School</b></font>
</h3>
<hr size="3" color="grey">
<p align="center">
<img src="good she.png.png" width="400" height="250" alt="Good Shepherd School">
</p>
<p align="justify">
<font face="Georgia" size="5">
Good Shepherd Matriculation Higher Secondary School in Marthandam, established in 1988, is a highly reputed co-educational institution located on North Street. It offers English-medium education from Grades 1 to 12, combining a strong academic curriculum with state-of-the-art facilities and a nurturing, values-based environment.
</p>
</body>
</html>
```
# OUTPUT
<img width="1919" height="1101" alt="Screenshot 2026-05-26 192128" src="https://github.com/user-attachments/assets/013dbd84-7019-4b9f-8173-7cee39727a41" />
<img width="1919" height="1129" alt="Screenshot 2026-05-26 192151" src="https://github.com/user-attachments/assets/badc5783-16dd-4430-b7df-11a9616e07f1" />
<img width="1919" height="1125" alt="Screenshot 2026-05-26 192235" src="https://github.com/user-attachments/assets/35a84e9a-928d-426f-9b6d-7caa4ca70882" />
<img width="1919" height="1132" alt="Screenshot 2026-05-26 192306" src="https://github.com/user-attachments/assets/e38a87a7-706f-4330-b54c-ec57b03b08b0" />
<img width="1919" height="1130" alt="Screenshot 2026-05-26 192328" src="https://github.com/user-attachments/assets/991a567e-01ef-4f69-8238-230c35396db3" />
<img width="1919" height="1135" alt="Screenshot 2026-05-26 192359" src="https://github.com/user-attachments/assets/e719200a-841f-4bae-9725-3b7fc076caf6" />



# RESULT
The program for implementing image maps using HTML is executed successfully.
