# Ex03 Time Table
## Date:18/03/2023

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="3" cellspacing="6" cellpading="6">
<caption>SLOT TIMETABLE - SHIV SUJAN(212223040194)</caption>
<tr>
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday</th>
<th bgcolor="cyan">Tuesday</th>
<th bgcolor="cyan">Wednesday</th>
<th bgcolor="cyan">Thursday</th>
<th bgcolor="cyan">Friday</th>
</tr>
<tr>0 
<td bgcolor="pink">8-10</td>
<td  bgcolor="pink">ENGLISH</td>
<td bgcolor="green">FREE</td>
<td bgcolor="green">TAMIL</td>
<td bgcolor="green">FRENCH</td>
<td bgcolor="green">WEB APPLICATION</td>
</tr>
<tr>
<td bgcolor="lightblue">10-12</td>
<td bgcolor="green">COMPUTER NETWORK</td>
<td bgcolor="green">FREE</td>
<td bgcolor="green">PHYSICS</td>
<td bgcolor="GERMAN">FREE</td>
<td bgcolor="green">FRENCH</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<td colspan="5" bgcolor="gold">!!!!!!!!!! BREAK-TIME !!!!!!!!!</td>
</tr>
<tr>
<td bgcolor="green">1-3</td>
<td bgcolor="lightblue">MATHS</td>
<td bgcolor="lightblue">WEB APPLICATION</td>
<td bgcolor="lightblue">FRENCH</td>
<td bgcolor="lightblue">GERMAN</td>
<td  bgcolor="lightblue">SS</td>
</tr>
<tr>
<td bgcolor="pink">3-5</td>
<td bgcolor="lightblue">MATHS</td>
<td colspan="2" bgcolor="lightblue">LEISURE</td>
<td bgcolor="lightblue">BREAK</td>
<td bgcolor="lightblue">GERMAN</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19MA206</td>
<td>MATHS</td>
</tr>
<tr>
<td>2.</td>
<td>19AI304</td>
<td>PHYSICS</td>
</tr>
<tr>
<td>3.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development(WEB)</td>
</tr>
<tr>
<td>4.</td>
<td>19EE305</td>
<td>French</td>
<tr>
<td>5.</td>
<td>19CS406</td>
<td>COMPUTER NETWORKS(CN)</td>
</tr>
<tr>
<td>6.</td>
<td>19EY701</td>
<td>GERMAN</td>
</tr>
<tr>
<td>7.</td>
<td>22HS102</td>
<td>Tamil</td>
</tr>
</table>
</center>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-03-18 144157.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
