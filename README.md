# Ex04 Places Around Me
## Date: 

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
'''

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    {%load static%}
</head>
<body>
    <h1> COMPANYS NEAR ME</H1>
<img src="{%static 'images/map.png'%}" width="1000px" usemap="#MapNew" onmousemove="coordinate (event)"> <br>
<MAP name="MapNew">
    <AREA shape="RECT" coords="5,370,15,390" href="https://saveetha.ac.in/" Title="Saveetha Engineering College">
    <AREA shape="RECT" coords="38,410,65,445" href="https://www.zaubacorp.com/company/HAWKSHAW-DEVELOPERS-PRIVATE-LIMITED/U72501TN2020PTC138341" Title="HAWKSHAW-DEVELOPERS-PRIVATE-LIMITED">
    <AREA shape="RECT" coords="550,152,580,195" href="https://alabtechnology.com/" Title="Alab Technology">
    <AREA shape="RECT" coords="688,260,720,295" href="https://in.linkedin.com/in/indeks-web-maker-926602277" Title="Indeks Web Makers">
    <area shape="RECT" coords="665,220,700,250" href="https://in.worldorgs.com/catalog/chennai/internet-marketing-service/naveen-tech-world-freelancing-software-services" title="Naveen Tech World">
    <AREA shape="RECT" coords="745,50,775,85" href="https://sostechnologies.com/" Title="SOS Technologies">
</MAP>
</body>
</html>

'''

## OUTPUT
![OUTPUT](./out.png)

![OUTPUT](./out1.png)

![OUTPUT](./out2.png)

![OUTPUT](./out3.png)

![OUTPUT](./out4.png)

![OUTPUT](./out5.png)

![OUTPUT](./out6.png)



## RESULT
The program for implementing image maps using HTML is executed successfully.
