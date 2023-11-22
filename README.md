# Ex04 Places Around Me
## Date: 18.11.2023

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
<title> my city </title>
</head>
<body>
<h1 align="center">
<font color="red"><b> TRICHY </b></font>
</h1>
<h2 align="center">
<font color="lime"><b> CHANDRAPRIYADHARSHINI C (23013626)</b></font>
</h2>
<center>

<img src="img.jpeg" width="1500" height="650" usemap="#trichymap">

<map name="trichymap">
<area  shape="rectangle"  coords="650,400,800,550"  href ="Uchi Pillaiyar Kovil.html"  title="Uchi Pillayar Kovil" >
<area  shape="rectangle"  coords="790,50,900,100"  href ="Srirangam.html"  title="Srirangam" >
<area  shape="rectangle"  coords="950,250,1050,300"  href ="Kaveri River.html"  title="Kaveri River" >
<area  shape="CIRCLE"  coords="500,120,50,"  href ="Teppakulam.html"  title="Teppakulam" >
<area  shape="CIRCLE"  coords="670,330,70,"  href ="Chathiram.html"  title="Chathiram bus stand" >

</map>
</body>
</html>

Chathiram.html

<html>
<body bgcolor="yellow">
<h2 align="center"> CHATHIRAM BUS STAND </h2>
Chathiram Bus Stand, Tiruchirappalli, old name Chinnaiya Pillai Chathiram also popularly known Chathiram Perundu Nilayam or Chathiram Bus Stand, is one of the bus termini of Trichy, other being the Central Bus Stand.
Chinnaiya Pillai Chathiram (Choultry) Choultry is a resting place, an inn or caravansary for travelers, pilgrims or visitors to a site.
This 'D'-graded terminus, taking its name from the nearby Chinnaiya Pillai Chathiram,[2] became functional since 1979 and officially recognised in 2005.
The terminus prominently featured in Tamil Film, Sathiram Perundhu Nilayam (2013).
</body>
</html>

Kaveri River.html

<html>
<body bgcolor="coral">
<h2 align="center"> KAVERI RIVER </h2>
           In ancient Tamil literature,the river was also called Ponni(the golden mother,in refrence to the fine silt it deposits).
The Kaver is a sacred river to the people of southern India and isworkshipped as the GoddessKaveriamma(Mother Cauvery).It is
considered to be among the seven holy rivers of india.
</body>
</html>

Srirangam.html

<html>
<body bgcolor="lime">
<h2 align="center"> SRIRANGAM </h2>
Sri Ranganathaswamy Temple is a Hindu temple dedicated to Ranganatha (a form of Vishnu), located in Srirangam, Tiruchirapalli, Tamil Nadu, India.
It is the most illustrious Vaishnava temples in South India rich in legend and history.
The Deity finds a mention in the great Sanskrit epic Ramayana which is dated around 800 to 400 BCE which also pushes the existence of deity to the same era,which shows that the temple is minimum 2500 to 3000 years old archeologically and traditionally 30 lakh years old.
</body>
</html>

Teppakulam.html

<html>
<body bgcolor="green">
<h2 align="center"> TEPPAKULAM </h2>
Trichy Teppakulam is an ancient water tank located in Trichy, Tamil Nadu, India. It was built by King Thirumalai Nayak in the 17th century (1645) and is one of the largest tanks in India. The tank covers an area of about 5 acres and is surrounded by a stone wall.
Teppakulam is a locality near the centre of the Indian city of Tiruchirappalli. It consists of a large artificial tank surrounded by bazaars, prominent among which is a flower market.It contains the Thayumanavar Temple and the Sri Naganathar Swamy Temple, the St. Joseph College Church and Holy Cross Church, and Srimathi Indira Gandhi College for Women.The historic Rockfort is situated nearby.A large monolithic figure of Ganesh, Mukkuruni Vinayaka, was reportedly found during an excavation of the Mariamman Teppakulam tank.The Teppam Floating Festival is held here on boats in January or February and it is a common time and place for marriages.
</body>
</html>

Uchi Pillaiyar Kovil.html

<html>
<body bgcolor="magenta">
<h2 align="center"> UCHI PILLAIYAR TEMPLE </h2>
<h3 align="center"> (ROCKFORT) </h3>
This temple is beleived to have been constructed in the 6th century by Mahendra Varman of Pallava dynasty.The fort is also known as Pillaiyar Kovil and 
draws huge footfalls during the Chittiraifestivel,celabratedin the months of April and May for 15 days.
</body>
</html>
```


## OUTPUT
![trichy copy 2](https://github.com/Bosevennila/NearMe/assets/144870486/7de21032-b128-4e96-8951-c6dbbb72c138)
![chathiram 1](https://github.com/Bosevennila/NearMe/assets/144870486/be10a392-da0d-4fbf-b80f-c9d0e6d34173)
![kaveri 2](https://github.com/Bosevennila/NearMe/assets/144870486/89e60c16-acca-4264-82d4-86ec7615cae0)
![srirangam 3](https://github.com/Bosevennila/NearMe/assets/144870486/83950d7a-909c-4c3c-bd49-a4abcc2dac2e)
![tepakulam 4](https://github.com/Bosevennila/NearMe/assets/144870486/08f50ead-b1da-42db-8061-180045dc9d3f)
![rockfort 5](https://github.com/Bosevennila/NearMe/assets/144870486/37c282aa-ae28-4cb3-87a8-01f6c1860a1d)








## RESULT
The program for implementing image maps using HTML is executed successfully.
