![2](https://github.com/user-attachments/assets/ef7ebb5c-3633-48a8-8677-ad286978476a)# Ex04 Places Around Me
## Date: 13-12-2024

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
    <link rel="stylesheet" href="./locations/theni.html">
    <link rel="stylesheet" href="./locations/bodi.html">
    <link rel="stylesheet" href="./locations/chinnamanur.html">
    <link rel="stylesheet" href="./locations/kombai.html">
    <link rel="stylesheet" href="./vaigai.html">
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>theni</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>kirupasagar s (24006810)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map" height="500px"> 
<map name="image-map">
    <area target="_self" alt="Theni" title="Theni" href="./locations/theni.html" coords="972,432,813,301" shape="rect">
    <area target="_self" alt="Bodi" title="Bodi" href="./locations/bodi.html" coords="382,274,554,410" shape="rect">
    <area target="_self" alt="Kombai" title="Kombai" href="./locations/kombai.html" coords="204,834,353,955" shape="rect">
    <area target="_self" alt="Chinnamanur" title="Chinnamanur" href="./locations/chinnamanur.html" coords="503,884,674,997" shape="rect">
    <area target="_self" alt="Vaigai" title="Vaigai" href="vaigai.html" coords="1133,100,1326,249" shape="rect">
</map>
</center>

</body>
</html>

vaigai.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="NearMe\theni\mapapp\static\vaigai.html">
    <title>vaigai</title>
</head>
<body bgcolor="yellow">
    <h1>vaigai</h1>
    The Vaigai Dam is built across the Vaigai River near Andipatti, in the Theni district (Madura district, before British India) of Tamil Nadu, South India. Near the dam, the Government of Tamil Nadu has constructed an Agricultural Research Station to research the cultivation of various crops, including rice, sorghum, black gram, cowpea and cotton.[
</body>
</html>

kombai.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="NearMe\theni\mapapp\static\map.html">
    <title>kombai</title>
</head>
<body bgcolor="red">

    <h1>kombai</h1>
    Kombai is a panchayat town in Theni District in the Indian state of Tamil Nadu, in the foot hills of the Western Ghats

Kombai is also well known for dogs. Kombai dog and Rajapalayam dog are also employed in police department
</body>
</html>

bodi.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./bodi.html">
    <title>bodi</title>
</head>
<body bgcolor="green">
    <h1>bodinayakanur</h1>
    Bodinayakanur, a town in Tamil Nadu, India, was fondly dubbed the 'Kashmir of the South,' by India's first PM Jawaharlal Nehru.[1] Despite its modest size, Bodinayakanur has played a significant role in Tamil Nadu's political arena, having been the constituency for 2 of 12 reigning Chief Ministers of the state
</body>
</html>

chinnamanur.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./chinnamanur.html">
    <title>chinnamanur</title>
</head>
<body bgcolor="blue">
    <h1>chinnamanur</h1>
    Chinnamanur is a town and a municipality in Theni district in the state of Tamil Nadu, India. As of 2011, the town had a population of 42,305. The town is one of the major trade centers in the district and supports basic needs for a population of more than 1,00,000 people in and around the town. Chinnamanur in recent times is known for banana marketing. Processed banana from more than twenty units in Chinnamanur are exported to various countries. Chinnamanur also holds the most jewel shops in the entire Theni district. Chinnamanur is the fourth largest town in the district by population and second largest town in the district by area.
</body>
</html>

theni.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./theni.html">
    <title>theni</title>
</head>
<body bgcolor="orange">
    <h1>theni</h1>
    Theni District is one of the 38 districts of Tamil Nadu state in India. Well protected by the scenic hill locks, the district is located besides Madurai district. The town of Theni is the district headquarters. The district is divided into two natural divisions: The hilly areas are constituted by parts of the five taluk's Theni, Bodinayakanur, Periyakulam, Uthamapalayam and Andipatti with thick vegetation and perennial streams from the hills on the western side and Cumbum valley which lies in Uthamapalayam taluk. As of 2011, Theni district had a population of 1,245,899 with a sex ratio of 980 females for every 1,000 males.
</body>
</html>
```

## OUTPUT

![Screenshot 2024-12-04 163225](https://github.com/user-attachments/assets/6b001431-676f-4743-b631-14c6eca10678)
![1](https://github.com/user-attachments/assets/a0358a14-94aa-43ca-a144-660d4221a939)
![2](https://github.com/user-attachments/assets/ac81c8e5-4c5d-4f67-8140-f3b2e0dff899)
![3](https://github.com/user-attachments/assets/01ecf53e-b6ca-43ca-bd6e-44cf6a08d91f)
![4](https://github.com/user-attachments/assets/0b285899-f5e6-441d-a2d8-639ea694efbe)
![5](https://github.com/user-attachments/assets/69c3b7bd-63f3-41ed-a03a-cffe86d68409)


## RESULT
The program for implementing image maps using HTML is executed successfully.
