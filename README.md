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
map.html
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
        <img src="Screenshot 2025-04-24 203459.png" usemap="#image-map">
        <map name="image-map">
    <area target="" alt="TEMPLE" title="TEMPLE" href="temple.html" coords="803,503,964,553" shape="rect">
    <area target="" alt="MURUGAN" title="MURUGAN" href="templemurugan .html" coords="309,634,402,699,472,653,394,585" shape="poly">
    <area target="" alt="PARK" title="PARK" href="park.html" coords="899,361,64" shape="circle">
    <area target="" alt="GREEN THUNDER" title="GREEN THUNDER" href="green.html" coords="442,344,670,357,567,260" shape="poly">
</map>
  </center>
</body>

temple.html
<html>
    <body bgcolor="orange">
        <h1>THIRUVANNAMALAI</h1>
        <h3> Arunachaleswarar Temple  </h3>
<p>
 The Annamalaiyar Temple or Arunachalesvara Temple or Tiruvannamalai Temple is a Hindu temple dedicated to the god Shiva and goddess Parvati. It is located at the base of Arunachala hill in the town of Tiruvannamalai in Tamil Nadu, India.
</p>
</body>
</html>

murugantemple.html
<html>
    <body bgcolor="cyan">
        <h1>THIRUVANNAMALAI</h1>
        <h3> MURUGAN Temple  </h3>
<p>
    The Vilvarani Murugan Temple, also known as Nakshatra Murugan Temple, is a significant Murugan temple located in Tiruvannamalai district, Tamil Nadu. It's situated on a hillock and is a popular pilgrimage site due to its unique, golden-colored idol of Lord Murugan. The temple is known for its powerful energy and is a place of worship for many devotees
</p>
   </body>
</html>

green.html
<html>
    <body bgcolour="blue">
        <h1>THIEUVANNAMALAI</h1>
        <h3>Greenland Ashram</h3>
    <p>
        Greenland Ashram in Tiruvannamalai is a well-known ashram in Tiruvannamalai HO, known for its peaceful atmosphere and as a place for meditation and self-realization. It's a popular spot for both locals and visitors, offering a space for spiritual growth and reflection. The ashram is located in a prominent area of Tiruvannamalai HO and is easily accessible by various modes of transport.
   </p>
    </body>
</html>

park.html
<html>
    <body bgcolor="pink">
        <h1>THIRUVANNAMALAI</h1>
        <h3>Imagica Fun World</h3>
    <p>Imagica Fun World is a family-friendly amusement park located in Kurunji Nagar, Tiruvannamalai, Tamil Nadu. It offers a variety of water-based attractions suitable for all ages, making it a popular destination for locals and tourists alike</p>
    </body>
</html>
   
```

## OUTPUT
![Screenshot 2025-05-15 200155](https://github.com/user-attachments/assets/059a5240-7b1a-4af1-834b-b29184b58c5e)
![Screenshot 2025-05-15 201431](https://github.com/user-attachments/assets/59ad4b86-27b4-49a5-8660-03cd81d0db3e)
![Screenshot 2025-05-15 200829](https://github.com/user-attachments/assets/9da3043f-dfc4-464e-944d-9497b6077abb)
![Screenshot 2025-05-15 201147](https://github.com/user-attachments/assets/5f2d49ab-93a2-4c98-8027-2019ffb87e34)
![Screenshot 2025-05-15 201323](https://github.com/user-attachments/assets/e821f753-31f5-4895-80c1-dd71387ce002)










## RESULT
The program for implementing image maps using HTML is executed successfully.
