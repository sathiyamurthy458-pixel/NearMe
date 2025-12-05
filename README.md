# Ex03 Places Around Me
## Date: 5/12/25

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
meowapp.html
<html>
    <head>
        <title>meowapp</title>
    </head>
    <body>
        <h2 align="centre">Kallakuichi-Kallai managaram</h2>
        <br><br>
        <h4 align="centre">Sathiya Murthy K (25006776)</h4>
        <img src="map1.png" usemap="#image-map">
    <map name="image-map">
    <area target="" alt="Raja Talkies" title="Raja Talkies" href="Raja Talkies.html" coords="313,217,472,260" shape="rect">
    <area target="" alt="Mahalakshi Theatre" title="Mahalakshi Theatre" href="Mahalakshi Theatre.html" coords="675,508,522,508,531,552,696,564,748,558,755,525,717,510,747,506,749,508,573,554,739,510,705,503" shape="poly">
    <area target="" alt="KVM jewellers" title="KVM jewellers" href="KVM jewellers.html" coords="646,445,35" shape="circle">
    <area target="" alt="Barbequeen restraurant" title="Barbequeen restraurant" href="Barbequeen restraurant.html" coords="1148,359,974,393" shape="rect">
    <area target="" alt="KTM Husqvama" title="KTM Husqvama" href="KTM Husqvama.html" coords="1347,375,46" shape="circle">
    </map>
    </body>
</html>

Raja Talkies.html
<html>
    <head>
        <title>Raja Talkies</title>
    </head>
    <body bgcolor="pink">
        <h2 alaign="centre" color="red">Kallakuichi-Kallai managaram</h2>
        <br>
        <h4 alaign="centre" color="blue">Raja Talkies</h4>
        <hr color="red">
        <br>
        <h3>Raja Talkies, Gandhi Nagar, Kallakurichi is a chain of theatres in India that exhibit a myriad of movies around the year. Be it a Regional, Bollywood or Hollywood movie, at Raja Talkies, Gandhi Nagar, Kallakurichi you can catch them all.</h3>
        
    </body>
</html>

Mahalakshi Theatre.html
<html>
    <head>
        <title>Mahalakshmi Theatre</title>
    </head>
    <body bgcolor="green">
        <h2 alaign="centre" color="red">Kallakuichi-Kallai managaram</h2>
        <br>
        <h4 alaign="centre" color="blue">Mahalakshi Theatre</h4>
        <hr color="red">
        <br>
        <h3>Mahalakshmi Theatre is A world class FIRST MULTI SCREEN movie theatre experience at kallakurichi. || ML Cinemas offers you the most luxuries seats, screen, sounds and more..</h3>
        
    </body>
</html>

KVM jewellers.html
<html>
    <head>
        <title>K V M Jewellers</title>
    </head>
    <body bgcolor="orange">
        <h2 alaign="centre" color="red">Kallakuichi-Kallai managaram</h2>
        <br>
        <h4 alaign="centre" color="blue">KVM jewellers</h4>
        <hr color="red">
        <br>
        <h3>K V M Jewellers in Kallakurichi is one of the leading businesses in the Jewellery Showrooms. Also known for Jewellery Showrooms, Gold Jewellery Showrooms, Silver Jewellery Showrooms, Gemstone Dealers, Gold Coin Dealers, Diamond Jewellery Showrooms, Gold Bar Manufacturers, Gold Plated Jewellery Showrooms and much more</h3>
    </body>
</html>

Barbeqeen restraurant.html
<html>
    <head>
        <title>Barbequeen restrauant</title>
    </head>
    <body bgcolor="purple">
        <h2 alaign="centre" color="red">Kallakuichi-Kallai managaram</h2>
        <br>
        <h4 alaign="centre" color="blue">Barbequeen restrauant</h4>
        <hr color="red">
        <br>
        <h3>Barbequeen restrauant-One of the best nonveg family restaurant available in Kallakurichi, We expert in Grill, barbeque-style tandoori, indian and chinese cuisine </h3>
        
    </body>
</html>

KTM husqvama.html
<html>
    <head>
        <title>KTM Husqvama</title>
    </head>
    <body bgcolor="blue">
        <h2 alaign="centre" color="red">Kallakuichi-Kallai managaram</h2>
        <br>
        <h4 alaign="centre" color="blue">KTM Husqvama</h4>
        <hr color="red">
        <br>
        <h3>KTM Kallakurichi is an authorized dealership of KTM & Husqvarna motorcycles.</h3>
        
    </body>
</html>


```

## OUTPUT
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (32).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
