# Ex04 Places Around Me
## Date:24.04.2025 

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
<head>
    <title> My City</title>
</head>
<body>
    <h1 align="center"> 
    <font color="red"><b> Tiruvannamalai</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>Deepika.R(212224230054)</b></font>
    </h3>
    <center>
    <img src="map.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
    <area shape="circle" coords="700,250,850,400" href="home.html" title="My Home Town">
    <area shape="circle" coords="570,230,45" href="school.html" title="My School">
    <area shape="circle" coords="640,200,30" href="ground.html" title="Ground">
    <area shape="circle" coords="1120,360,25" href="church.html" title="Church">
    </center>
    </map>
</body>
```

## OUTPUT
![Screenshot 2025-04-25 111336](https://github.com/user-attachments/assets/95430e95-4f0d-4ac5-bbaf-a3d323a37c47)
![Screenshot 2024-04-10 144520](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/184dc4c9-f3a9-475e-9adc-2d1ce6a5ee6e)
![Screenshot 2024-04-10 144341](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/e9637689-d1b0-473e-aa71-e554e78fe3c5)
![Screenshot 2024-04-10 144022](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/55c15930-6b0a-4388-80d3-ece2a2a20274)
![Screenshot 2024-04-10 144246](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/93789857-04e4-4929-9f36-677e44c7b942)









## RESULT
The program for implementing image maps using HTML is executed successfully.
