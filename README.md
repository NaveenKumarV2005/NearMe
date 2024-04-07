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

<img width="914" alt="out" src="https://github.com/NaveenKumarV2005/NearMe/assets/151476286/cf981a91-47a2-41fe-9bcd-db931b637be1">

![out1](https://github.com/NaveenKumarV2005/NearMe/assets/151476286/d668e157-e945-4b73-af28-b0bde29b873f)

<img width="913" alt="out2" src="https://github.com/NaveenKumarV2005/NearMe/assets/151476286/71d557a1-18a8-41ee-a246-f85c52ccc190">

![out3](https://github.com/NaveenKumarV2005/NearMe/assets/151476286/8e561e82-d82a-4a8b-90ce-e89f525d0a0a)

![out4](https://github.com/NaveenKumarV2005/NearMe/assets/151476286/83248e38-b06e-4c36-a3ca-0f0cf085896d)

![out5](https://github.com/NaveenKumarV2005/NearMe/assets/151476286/ee7989f3-c133-4a54-a08c-eb32ea942cda)

![out6](https://github.com/NaveenKumarV2005/NearMe/assets/151476286/77b047fc-930c-4741-ba6a-8281f44a169d)









## RESULT
The program for implementing image maps using HTML is executed successfully.
