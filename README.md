# Ex03 Time Table
## Date:

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
    <title>slot</title>
</head>
<body>
    <center>
        <img src="logo.png" heigth="150" width="800">
    </center>
     <table align="center" border="8" cellpadding="6" cellspacing="4" bgcolor="lavender">
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>CE</td>
            <td>CE</td>
            <td>ML</td>
            <td>WA</td>
            <td>FP</td>
            <td>ML</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>WA</td>
            <td>FP</td>
            <td>FP</td>
            <td>ML</td>
            <td>ML</td>
            <td>CE</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>FP</td>
            <td>ML</td>
            <td>FP</td>
            <td>CE</td>
            <td>WA</td>
            <td>FP</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FP</td>
            <td>FP</td>
            <td>WA</td>
            <td>FP</td>
            <td>WA</td>
            <td>FP</td>
        </tr>
     </table>
     
</body>
</html>
```

## OUTPUT

<img width="1435" height="867" alt="Screenshot 2025-12-12 140602" src="https://github.com/user-attachments/assets/4fc55051-eb7b-491b-b6c8-a5f372e14a62" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
