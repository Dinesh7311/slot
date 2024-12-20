# Ex03 Time Table
## Date:18.11.24

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable and Subject Details</title>
    <style>
        body {
            font-family: Arial, sans-serif;
             margin: 30px;
        }
        h2 {
            text-align: center;
            color: black;
        }
        .table-container {
            margin-top: 20px;
            margin-bottom: 20px;
        }
        table {
            border: collapse 2px;;
            width: 100%;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: yellow;
        }
        td {
            background-color: cyan;
        }
        .lunch {
            background-color: rgb(23, 249, 249);
            font-weight: bold;
        }
        .subject-table th {
            background-color: lightgray;
        }
        .subject-table td {
            background-color: white;
            text-align: left;
        }
    </style>
</head>
<body>
    <center><img src="logo.png" height="100" width="590"><center>
    <h2>SLOT TIME TABLE - DINESH S  (24900464)</h2>
    <div class="table-container">
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
                <td colspan="3">FREE SLOT</td>
                <td>PHY</td>
                <td>CHE</td>
            </tr>
            <tr>
                <td>10-12</td>
                <td>GER</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>PHY</td>
            </tr>
            <tr>
                <td>12-1</td>
                <td colspan="5">L U N C H</td>
            </tr>
            <tr>
                <td>1-3</td>
                <td colspan="2">FREE SLOT</td>
                <td>MAT</td>
                <td>MAT</td>
                <td>SS</td>
            </tr>
            <tr>
                <td>3-5</td>
                <td colspan="2">FREE SLOT</td>
                <td>GER</td>
                <td>CHE</td>
                <td>FWAD</td>
            </tr>
        </table>

        <table class="subject-table">
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
                <td>19EN612</td>
                <td>German Basic (GER)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19PH206</td>
                <td>Physics for Information Technology (PHY)</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering (CHE)</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra (MAT)</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY701</td>
                <td>Soft Skills (SS)</td>
            </tr>
        </table>
    </div>
</body>
</html>
'''

## OUTPUT
![alt text](<Screenshot 2024-11-22 214450.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
