# Ex04 Time Table
## Date:17/11/2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>my website</title>
    </head>
    <body>
        <img src="logo.png"   width="1100" >
        <h1 align="center">Timetable</h1>
        <h2 align="center"> M.Yogesh Bala Guru -26018320</h2>
        <table  border="1" align="center" bgcolor="lightblue" >
            <tr>
                <th bgcolor="yellow">time and days</th>
                <th bgcolor="yellow">8:00-9:30</th>
                <th bgcolor="yellow">9:45-11:14</th>
                <th bgcolor="yellow">11:30-12:15</th>
                <th bgcolor="yellow">12:15-1:00</th>
                <th bgcolor="yellow">1:15-2:45</th>
                <th bgcolor="yellow">3:00-4:30</th>
            </tr>
            <tr>
                <th bgcolor="yellow">monday</th>
                <td> python programing</td>
                <td>FWAD</td>
                <td > mentor meet</td>
                <td colspan="3" align="center">-</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Tuesday</th>
                <td>python programing</td>
                <td>CA</td>
                 <td colspan="2" align="center">-</td>
                <td>FWAD</td>
                 <td align="center">-</td>
                
            </tr>
            <tr>
                <th bgcolor="yellow">Wednesday</th>
                <td>FWAD</td>
                <td align="center">-</td>
                <td> mentor meet </td>
                <td  align="center">-</td>
                <td>python programing</td>
                <td>EMPD</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Thursday</th>
                <td>CA</td>
                <td>maths</td>
                <td>mentor meet</td>
                <td align="center">-</td>
                <td> japanese </td>
                <td>EMPD</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Friday</th>
                <td>maths</td>
                <td align="center">-</td>
                <td>mentor meet</td>
                <td align="center">-</td>
                <td>japanese</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Saturday</th>
                <td align="center">-</td>
                <td>mentor meet</td>
                
            </tr>

        </table>
        <table border="1" align="center" >
            <tr>
                <th bgcolor="yellow" >S.NO</th>
                <th bgcolor="yellow">Subject code</th>
                <th bgcolor="yellow">subject</th>
            </tr>
            <tr>
                <th bgcolor="yellow">1</th>
                <td>26ODJ148</td>
                <td>Fundamental of web application(FWAD)</td>
            </tr>
            <tr>
                <th bgcolor="yellow">2</th>
                <td>6G1-1</td>
                <td>computer architecture(CA)</td>
            </tr>
            <tr>
                <th bgcolor="yellow">3</th>
                <td>5A2-2</td>
                <td>mathematics(Maths)</td>
            </tr>
            <tr>
                <th bgcolor="yellow">4</th>
                <td>26ODJ157</td>
                <td>python</td>
            </tr>
            <tr>
                <th bgcolor="yellow">5</th>
                <td>26ODJ084</td>
                <td>japanese</td>
            </tr>
            <tr>
                <th bgcolor="yellow">6</th>
                <td>26ODJ184</td>
                <td>EMPD</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<yogesh/Screenshot (20).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.