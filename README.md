# Ex03 Time Table
## Date: 21-05-2025

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
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        h5 {
            padding-top: 50px;
            text-align: center;
        }

        table {
            width: 70%;
            font-size: 12px;
            border-collapse: collapse;
            margin: auto;
            background-color: lightgreen;
        }

        th, td {
            border: 1px solid #000;
            padding: 6px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div style="text-align: center; padding-top: 20px;">
        <img src="logo.png" width="500">
    </div>
    <h5>
        SLOT TIME TABLE - V PATRICK (212224240110)
    </h5>

    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>PHY</td>
            <td>CHEM</td>
            <td>PYTHON</td>
            <td>FREE SLOT</td>
            <td>MAT</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>CHEM</td>
            <td>C-PROGRAMMING</td>
            <td>PYTHON</td>
            <td>MAT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td>12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td colspan="2">FREE SLOT</td>
            <td>MAT</td>
            <td>C-PROGRAMMING</td>
            <td>PHY</td>
        </tr>
    </table>
    <br>
    <br>
    <table>
        <tr>
            <td>
                S.NO
            </td>
            <td>
               SUBJECT CODE 
            </td>
            <td>
                SUBJECT NAME
            </td>
        </tr>
        <tr>
            <td>
                1
            </td>
            <td>
               19AI301
            </td>
            <td>
                PYTHON PROGRAMMING
            </td>
        </tr>
        <tr>
            <td>
                2
            </td>
            <td>
               19AI304
            </td>
            <td>
                C-PROGRAMMING
            </td>
        </tr>
        <tr>
            <td>
                3
            </td>
            <td>
               SH3214
            </td>
            <td>
                PHYSICS
            </td>
        </tr>
        <tr>
            <td>
                4
            </td>
            <td>
               19CY205
            </td>
            <td>
                CHEMISTRY
            </td>
        </tr>
        <tr>
            <td>
                5
            </td>
            <td>
               19MA201
            </td>
            <td>
                MAT
            </td>
        </tr>
        
    </table>


</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-05-21 at 8.30.49 AM.png>)
[text](README.md)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
