# Ex03 Time Table
## Date:17/03/2024

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table</title>
</head>
<body>
    <img src="logo.png" height="250" width="1250">
    <center><h1>SLOT TIME TABLE-NARASIMHAN</h>
    <hr>
    <table border="10" cellspacing="20" height="100" width="75">
        <tr align="center">
            <th bgcolor="green">Day/Time</th>
            <th bgcolor="green">Monday</th>
            <th bgcolor="green">Tuesday</th>
            <th bgcolor="green">Wednesday</th>
            <th bgcolor="green">Thursday</th>
            <th bgcolor="green">Friday</th>
            <th bgcolor="green">Saturday</th>
        </tr>
        <tr align="center">
            <th bgcolor="green">8-10</th>
            <td bgcolor="cyan">DE</td>
            <td bgcolor="cyan">Adv C</td>
            <td bgcolor="cyan">Eth</td>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Web</td>
            <td bgcolor="cyan">Py</td>
        </tr>
        <tr align="center">
            <th bgcolor="green">10-12</th>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Py</td>
            <td bgcolor="cyan">Com</td>
            <td bgcolor="cyan">Adv C</td>
            <td bgcolor="cyan">Eth</td>
            <td bgcolor="cyan">Com</td>
        </tr>
        <tr align="center">
            <th bgcolor="green">1-3</th>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Web</td>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Web</td>
            <td bgcolor="cyan">Py</td>
            <td bgcolor="cyan">Free Slot</td>
        </tr>
        <tr align="center">
            <th bgcolor="green">3-5</th>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Py</td>
            <td bgcolor="cyan">DE</td>
            <td bgcolor="cyan">Free Slot</td>
            <td bgcolor="cyan">Free Slot</td>
        </tr>
    </table>
    <hr>
    <table border="10" cellspacing="20" height="100" width="500">
        <tr>
            <th>S:No</th>
            <th>Sub Code</th>
            <th>Sun Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI301C</td>
            <td>Python and Linear Algebra(py)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI414</td>
            <td>Fundamental of Web Development(web)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI305</td>
            <td>Advanced C Programming</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS406</td>
            <td>Computer Networks</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS417</td>
            <td>Ethical Hacking</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
    </table>
    <hr>
    </center>
</body>
</html>
```
## OUTPUT
![Screenshot 2024-03-18 202737](https://github.com/Narasimhan05/slot/assets/132819871/38ba115d-0de4-4d1c-a96d-1aa4aa9208c1)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
