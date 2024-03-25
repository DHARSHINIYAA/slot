# Ex03 Time Table
## Date:19.03.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
   <head>
       <title> TIME TABLE </title>
   </head>
 <body color="black" align="center">
 <table border="6" cellspacing="8" cellpadding="10" align="center" bgcolor="blue">
<caption><b>SLOT TIMETABLE- DHARSHINIYAA KS (23014039605)</b></caption>

   <tr>
        <th bgcolor="yellow">Day/Time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
  </tr>
  <tr>
        <th bgcolor="grey">8-10</th>
        <td>Free Slot</td>
        <td>CE</td>
        <td>FWAD</t>
        <td>Free slot</td>
        <td>CN</td>
 </tr>
 <tr>
        <th bgcolor="grey">10-12</th>
        <td>Free Slot</td>
        <td>FWAD</td>
        <td>CN</t>
        <td>CE</td>
        <td>C Program</td>
 </tr>
 <tr> 
        <th bgcolor="grey">12-1</th>
        <TD colspan="5" Align="center"><B>L U N C H </B></TD> </tr>
 <tr>
        <th bgcolor="grey">1-3</th>
        <td>FWAD</td>
        <td>Free Slot</td>
        <td>CSC</t>
        <td>EDM</td>
        <td>Free Slot</td>
 </tr>
 <tr>
        <th bgcolor="grey">3-5</th>
        <td>C Program</td>
        <td>EDM</td>
        <td>Free Slot</t>
        <td>Free Slot</td>
        <td>Free Slot</td>
</tr>
</body>
</html>
<table cellspacing="8" cellpadding="0" align="center">
<html>
<head>
    <title> subject code </title>
</head>
 <body>
 <table border="6" cellspacing="8" cellpadding="10" align="center">

<tr> 
        <th>S.NO</th>
        <th>Subject Code</th>
        <th>Subject</th>
</tr>        
<tr>
     <td>1</td>
     <td>19AI414</td>
     <td>Fundamentals of Web Application Development(FWAD)</td>
</tr>    
<tr>
     <td>2</td>
     <td>19AI304</td>
     <td>Fundamentals of C Programming(C Program)</td>
</tr> 
<tr>
     <td>3</td>
     <td>19AI302</td>
     <td>Engineering Design and Modelling(EDM)</td>
</tr>     
<tr>
     <td>4</td>
     <td>19CS406</td>
     <td>Computer Networks(CN)</td>
</tr>   
<tr>
     <td>5</td>
     <td>19EN101</td>
     <td>Communicative English(CE)</td>
</tr>  
<tr>
     <td>6</td>
     <td>19EY702</td>
     <td>Creative Skills For Communication(CSC)</td>
</tr>    
</body>
</html>