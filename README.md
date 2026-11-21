# Ex04 Time Table
## Date:21.11.2026

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
    <title>Slot Time Table</title>
</head>

<body>
    <center>
        <img src="logo.png" width="700" height="100">
    </center><br><br>
    <table border="1"  cellpadding="5" cellspacing="5" align="center" bgcolor="lightblue" >
        <caption><b>SLOT TIME TABLE - KASTHURIRAM ROSHAN G B(26018672)</b></caption>
        <tr align="center" bgcolor="yellow">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr align="center">
            <th bgcolor="yellow">8-10</th>
            <td bgcolor="white">FREE SLOT</td>
            <td>CL</td>
            <td>SNM</td>
            <td>PP</td>
            <td>SE</td>
            <td>SNM</td>
        </tr>

        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>PP</td>
            <td>SE</td>
            <td bgcolor="white">FREE SLOT</td>
            <td>CL</td>
            <td bgcolor="white">FREE SLOT</td>
            <td>FWAD</td>
        </tr>

        <tr align="center">
            <th bgcolor="yellow">12-1</th>
            <td colspan="6" bgcolor="white">L U N C H</td>
        </tr>

        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td bgcolor="white">FREE SLOT</td>
            <td>FCC</td>
            <td bgcolor="white">FREE SLOT</td>
            <td>FCC</td>
            <td>FWAD</td>
            <td>FWAD</td>
        </tr>

        <tr align="center">
            <th bgcolor="yellow">3-5</th>
            <td bgcolor="white">FREE SLOT</td>
            <td>PP</td>
            <td colspan="4" bgcolor="white">FREE SLOT</td>
        </tr>
    </table>

    <br>

    <table border="1" cellpadding="5" cellspacing="5" align="center" >
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td>1.</td>
            <td>19AI301</td>
            <td>Python Programming (PP)</td>
        </tr>

        <tr>
            <td>2.</td>
            <td>19CS418</td>
            <td>Cyber Law and Compliance (CL)</td>
        </tr>

        <tr>
            <td>3.</td>
            <td>19CS408</td>
            <td>Software Engineering (SE)</td>
        </tr>

        <tr>
            <td>4.</td>
            <td>19CS547</td>
            <td>Fundamentals of Cryptocurrency (FCC)</td>
        </tr>

        <tr>
            <td>5.</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods (SNM)</td>
        </tr>

        <tr>
            <td>6.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
    </table>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (69).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
