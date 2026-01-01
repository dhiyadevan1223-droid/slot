# Ex02 Time Table
## Date:28-11-2025

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - YOUR NAME</title>
</head>
<body>
    <IMG SRC="/static/logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - DHIYA 25018435</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>FREE SLOT</td>
            <td>PYTHON</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>WEB</td>
            <td>PYTHON</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>MENTOR MEET</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI301</td>
            <td>Python Programming</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
<img width="887" height="780" alt="image" src="https://github.com/user-attachments/assets/0ab8eb76-1a50-444a-adb3-259ba0d78e4b" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
