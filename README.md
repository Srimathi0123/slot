# Ex03 Time Table
## Date:20/03/2024

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
 <!DOCTYPE html>
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
      
        <center>
         <img src="logo.png" width="600" height="130">
         
         
        </center>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" bgcolor="Orange">
<caption><b>SLOT TIME TABLE -   Srimathi V(212221040162)</b></caption>
<tr align="center">
<th bgcolor="lightgreen">Day/Time</th>
<th bgcolor="lightgreen">8-10</th>
<th bgcolor="lightgreen">10-12</th>
<th bgcolor="lightgreen">12-1</th>
<th bgcolor="lightgreen">1-3</th>
<th bgcolor="lightgreen">3-5</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Monday</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">AP</th>
<th bgcolor="pink" rowspan="6" align="center">LUNCH BREAK</th>
<th bgcolor="pink">FWAD</th>
<th bgcolor="pink">AQLR</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">TuesdaY</th>
<th bgcolor="pink">CNS</th>
<th bgcolor="pink">FWAD</th>
<th bgcolor="pink">HS</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Wednesday</th>
<th bgcolor="pink">FWAD</th>
<th bgcolor="pink">AP</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Thrusday</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">JAVA</th>
<th bgcolor="pink">CNS</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Friday</th>
<th bgcolor="pink">FREE SLOT</th>
<th bgcolor="pink">JAVA</th>
<th bgcolor="pink">Emp</th>
<th bgcolor="pink">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="lightgreen">Saturday</th>
<th bgcolor="pink">FREE</th>
<th bgcolor="pink">FREE</th>
<th bgcolor="pink">FREE</th>
<th bgcolor="pink">FREE </th>
</tr>

</table>

<br>
<table align="center" cellspacing="2" cellpadding="4" border="4">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>

<tr>
<td align="center">2.</td>
<td align="center">19CS412</td>
<td>Cryptography and network security</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19CE512</td>
<td>Air pollution engineering</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19CS403</td>
<td>java</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19EY704</td>
<td>Advance quantitative and logical terminologies</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19EY705</td>
<td>Employment enhancement Skills</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![image](https://github.com/Srimathi0123/slot/assets/118673240/19617891-8d8c-4f59-988f-e02802932c2b)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
