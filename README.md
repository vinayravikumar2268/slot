# Ex03 Time Table
## Date: 11.12.2025
## Ref no: 25018987

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
~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="2" border="2" bgcolor="WHITE">
<caption><b>SLOT TIME TABLE - VINAY (25018987)</b></caption>
<tr align="center">
<th bgcolor="red">Day/Time</th>
<th bgcolor="blue">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="olive">Wednesday</th>
<th bgcolor="maroon">Thursday</th>
<th bgcolor="white">Friday</th>
</tr>
<tr align="center">
<th bgcolor="red">8-10</th>
<td>PYTHON PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>PYTHON PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
</tr>
<tr>
<th bgcolor="blue">12-1</th>
<td colspan="5" align="center">LUNCH</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>SOFT SKILLS</td>
</tr>
<tr align="center">
<th bgcolor="white">3-5</th>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>SNo.</th>
<th>course Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>PYTHON PROGRAMMING (PYTHON PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
~~~

## OUTPUT
<img width="1872" height="900" alt="Screenshot 2025-12-11 171818" src="https://github.com/user-attachments/assets/e773a6c2-1995-4ade-9f1b-4e5a4f725cb5" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
