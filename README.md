# Ex03 Time Table
## Date:21/04/2025

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
<html >
    <head>
        <title>Timetable </title>
    </head>
    <body >
        <center>
            <img src="logo.png" height = "180" width="400">
        </center>
        <table align="Center" border="3">
            <caption><b>My Time Table (HARISH KUMAR S - 212224230091)</b></caption>
            <tr  bgcolor="Pink" cellspacing="10" cellpadding="20">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th  bgcolor="Pink">8-10</th>
                <td  bgcolor="White">Free </td>
                <td  bgcolor="White">FWAD</td>
                <td  bgcolor="White">Python & Math</td>
                <td  bgcolor="White">Free</td>
                <td  bgcolor="White">Free</td>
                <td  bgcolor="White">English</td>
            </tr>
            <tr>
                <th  bgcolor="Pink">10-12</th>
                <td  bgcolor="White">Free</td>
                <td  bgcolor="White">Free</td>
                <td  bgcolor="White">English</td>
                <td  bgcolor="White">Python</td>
                <td  bgcolor="White">Soft Skills</td>
                <td  bgcolor="White">Python & Math</td>
            </tr>
            <tr>
                <th  bgcolor="Pink">12-1</th>
                <td    bgcolor="Lavender"colspan="6" align="center">LUNCH BREAK</td>
            </tr>

            <tr>
                <th  bgcolor="Pink">1-3</th>
                <td  bgcolor="White">Chemistry</td>
                <td  bgcolor="White">Python</td>
                <td  bgcolor="White">Mentor Meet</td>
                <td  bgcolor="White">Chemistry</td>
                <td  bgcolor="White">FWAD</td>
                <td  bgcolor="White">FWAD</td>
            </tr>
            <tr>
                <th  bgcolor="Pink">3-5</th>
                <td  bgcolor="Lavender" colspan="6" align="center">FREE SLOT</td>

        </table>    

    </body>
</html>
<br>
<hr>
<br>

<html>
    <head>
        <title>courses</title>
    </head>
    <body>
        <table align="Center" border="3" >
        <caption><b>My courses</b></caption>

            <tr bgcolor=" Pink">
                <th>S.NO</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <th bgcolor="Pink">1</th>
                <td bgcolor=" White">19A13414</td>
                <td bgcolor=" White">Fundamentals of web application development (FWAD)</td>
            </tr>
            <tr>
                <th bgcolor="Pink">2</th>
                <td  bgcolor=" White">19AI301C</td>
                <td  bgcolor=" White">Python adn Linear Algebra</td>
            </tr>
            <tr>
                <th bgcolor="Pink">3</th>
                <td  bgcolor=" White">19EN101</td>
                <td  bgcolor=" White">Communicative English</td>
            </tr>
            <tr>
                <th bgcolor="Pink">4</th>
                <td  bgcolor=" White">19CY205</td>
                <td  bgcolor=" White">Principle of Chemistry in Engineeing </td>
            </tr>
            <tr>
                <th bgcolor="Pink">6</th>
                <td  bgcolor=" White">ECA-M-SCOFT</td>
                <td  bgcolor=" White">Mentor Meet</td>
            </tr>
            <tr>
                <th bgcolor="Pink">8</th>
                <td  bgcolor=" White">19EY708</td>
                <td  bgcolor=" White">Carrer development skill(Soft skill)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/1ed1fc7f-4835-44c4-960a-898b29d440db)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
