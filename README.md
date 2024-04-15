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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    * { margin: 0;}
</style>
<script>
    function coordinate(event) {
        let x=event.clientX;
        let y=event.clientY;
        document.getElementById("text1").value=x;
        document.getElementById("text2").value=y;

    }
</script>

<body>
    <img src="C:\New folder\image.png.png" width="1485" height="650" usemap="#MapNew" onmousemove="coordinate(event)">
    <MAP name="MapNew">
        <area shape="rect" coords="214,500,450,600" href="https://www.rajalakshmi.org/" title="Rajalakshmi Engineering college">
        <area shape="rect" coords="424,334,576,420" href="https://saveetha.ac.in/" title="Saveetha Engineering college ">
        <area shape="rect" coords="1238,84,1392,127" href="https://in.bookmyshow.com/buytickets/gokulam-cinemas-4k-dolby-atmos-poonamalle/cinema-chen-SUTC-MT/20240412" title="Gokulam Cinemas">
        <area shape="rect" coords="126,250,293,282" href="https://apolloartsandsciencecollege.ac.in/admission.html">
        <area shape="rect" coords="403,246,586,272" href="http://apolloengineeringcollege.ac.in/#/index">
        <area shape="rect" coords="796,239,992,273" href="https://ritchennai.org/">
        
    </MAP>  
    <br>
    <center>
    X-coordinate
    <input type="text" id="text1">
    <br>
    <br>
    Y-coordinate
    <input type="text" id="text2">
</center>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-04-15 200525](https://github.com/vishal23000591/NearMe/assets/147139719/3f6ad4ae-7d0b-4426-a5df-28c5cd615d4a)







## RESULT
The program for implementing image maps using HTML is executed successfully.
