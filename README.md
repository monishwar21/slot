# Ex03 Time Table
## Date:5/3/2025

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
        <title>Slot timetable-25014914</title>
    </head>
    <body>
        <center>
        <img src="logo.png" width="900" height="130">
        <h1 align="centre">SLOT TIME TABLE - MONISHWAR K (25014914)</h1>
        <table border="10" cellspacing="7" cellpadding="10">
        <tr>
            <th bgcolor="red">Day/Time</th>
            <th bgcolor="orange">Monday</th>
            <th bgcolor="orange">tuesday</th>
            <th bgcolor="orange">wednesday</th>
            <th bgcolor="orange">Thursday</th>
            <th bgcolor="orange">Friday</th>
            <th bgcolor="orange">Saturday</th>
        </tr>
        <tr>
            <td bgcolor="orange" >8-10 A.M.</td>
            <td bgcolor="gray" colspan="2" align="center">FREE</td>
            <td bgcolor="gray">WEB</td>
            <td bgcolor="gray" colspan="2" align="center">FREE</td>
            <td bgcolor="gray">WEB</td>
        </tr>
        <tr>
            <td bgcolor="orange">10-12 A.M.</td>
            <td bgcolor="gray">PYTHON</td>
            <td bgcolor="gray">ENGLISH</td>
            <td bgcolor="gray">WEB</td>
            <td bgcolor="gray">ENGLISH</td>
            <td bgcolor="gray" colspan="2" align="center">FREE</td>
        </tr>
        <tr>
            <td bgcolor="orange">12-1 P.M.</td>
            <td bgcolor="gray" colspan="6" align="center">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="orange">1-3 P.M.</td>
            <td bgcolor="gray"colspan="2" align="center">PYTHON</td>
            <td bgcolor="gray">MENTOR</td>
            <td bgcolor="gray">PYTHON</td>
            <td bgcolor="gray">WEB</td>
            <td bgcolor="gray">WEB</td>
        </tr>
        <tr>
            <td bgcolor="orange">3-5 P.M.</td>
            <td bgcolor="gray" colspan="3" align="center">ENGLISH</td>
            <td bgcolor="gray">PYTHON</td>
            <td bgcolor="gray">FREE</td>
            <td bgcolor="gray">WEB</td>  
        </tr>
        </table>
        <br>
        <table border="3" cellpadding="10" cellspacing="7" width="700">
            <tr>
                <th bgcolor="green">S.No</th>
                <th bgcolor="green">Subject Code</th>
                <th bgcolor="green">Subject Name</th>
            </tr>
            <tr>
                <td bgcolor="green">1</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application Developement(FWAD) </td>
            </tr>
            <tr>
                <td bgcolor="green">2</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td bgcolor="green">3</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
        </table>
        </center>

    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (34).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
