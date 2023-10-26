# Ex03 Time Table

## DATE: 14-09-2023

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

## CODE
```

  <!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - Rakesh Kumar.S(212221040137)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td colspan="3">FREE SLOT</td>
<td>CD</td>
<td>AI</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>GER</td>
<td> FREE SLOT </td>
<td>FWAD</td>
<td>FWAD</td>
<td>CD</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td colspan="2"> FREE SLOT </td>
<td>MAD</td>
<td>MAD</td>
<td>EES</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="2"> FREE SLOT </td>
<td>GER</td>
<td>AI</td>
<td>FWAD</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
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
<td align="center">19EN612</td>
<td>German Basic (GER)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS409</td>
<td>Compiler Design (CD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS413</td>
<td>Artificial Intelligence (AI)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS414</td>
<td>Mobile Application Development (MAD)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY705</td>
<td>Employment Enhancement Skills (EES)</td>
</tr>
</table>
</body>
</html>
```



## OUTPUT
![image](https://github.com/Rakesh2k23/slot/assets/141472158/8962ef0a-19aa-4eff-85bf-dcd89f8316c5)



## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
