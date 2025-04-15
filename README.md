# Ex03 Time Table
## Date:15-04-2025
## reg: 212224100033
## name: kunati hemanth yadav
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
<!DOCTYPE html>
<html>
<head>
<title>Time Table</title>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 15px;
}
</style>
</head>
<body>

<h2>hemanth 212224100033 Time Table</h2>

<table>
  <tr>
    <th>Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>saturday</th>
  </tr>
  <tr>
    <th>8:00-10:00 AM</th>
    <td>python</td>
    <td>introduction of MEMS</td>
    <td>free class</td>
    <td>free class</td>
    <td>ethical hacking</td>
  </tr>
  <tr>
    <th>10:00-12:00 AM</th>
    <td>edm</td>
    <td>python</td>
    <td>edm</td>
    <td>introduction of MEMS</td>
    <td>free class</td>
    <td>python</td>
  </tr>
  <tr>
    <th>01:00-03:00 AM</th>
    <td>ethical hacking</td>
    <td>fundamentals of web</td>
    <td>mentor meeting</td>
    <td>free class</td>
    <td>fundamentals of web</td>
    <td>python</td>
  </tr>
  <tr>
    <th>03:00-05:00 PM</th>
    <td>free class</td>
    <td>free class</td>
    <td>free class</td>
    <td>iiot</td>
    <td>iiot</td>
    <td>free class</td>
  </tr>
    
</table>
<table>
  <tr>
    <td>course name</td>
    <td>course code</td>
  </tr>
  <tr>
    <td>python </td>
    <td>19AI301C</td>

  </tr>
  <TR>
    <TD>EDM</TD>
    <td>19AI302</td>
  </TR>
  <TR>
    <td>web appilication</td>
    <td>19AI414</td>
  </TR>
  <tr>
    <td>iiot</td>
    <td>19AM509</td>
  </tr>
  <TR>
    <TD>ethical hacking</TD>
    <td>19CS417</td>
  </TR>
  <TR>
    <TD>introduction of MEMS</TD>
    <td>19EC602</td>
  </TR>
</table>
</body>
</html>
~~~

## OUTPUT
![image](https://github.com/user-attachments/assets/9cb01d37-f199-4ba2-9c21-5fd7484c7378)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
