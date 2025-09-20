# Ex03 Time Table
## Date:20/09/2025

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
    <title>Class Timetable</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            text-align: center;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
<center> <img src="/static/logo.png" height="100" width="540"> </center>

<h2>Class Timetable</h2>

<table>
    <tr>
        <th>Day</th>
        <th>8-9 AM</th>
        <th>9-10 AM</th>
        <th>10-11 AM</th>
        <th>11-12 PM</th>
        <th>1-2 PM</th>
        <th>2-3 PM</th>
        <th>3-4 PM</th>
        <th>4-5 PM</th>
    </tr>
    <tr>
        <td>Monday</td>
        <td>DataScience</td>
        <td>DataScience</td>
        <td>-</td>
        <td>-</td>
        <td>FWD</td>
        <td>FWD</td>
        <td>Python</td>
        <td>Python</td>
    </tr>
    <tr>
        <td>Tuesday</td>
        <td>DataScience</td>
        <td>DataScience</td>
        <td>Python</td>
        <td>Python</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>Python</td>
    </tr>
    <tr>
        <td>Wednesday</td>
        <td>DataScience</td>
        <td>DataScience</td>
        <td>FWD</td>
        <td>FWD</td>
        <td>-</td>
        <td>-</td>
        <td>FWD</td>
        <td>FWD</td>
    </tr>
    <tr>
        <td>Thursday</td>
        <td>-</td>
        <td>-</td>
        <td>DataScience</td>
        <td>DataScience</td>
        <td>-</td>
        <td>-</td>
        <td>FWD</td>
        <td>FWD</td>
    </tr>
    <tr>
        <td>Friday</td>
        <td>-</td>
        <td>-</td>
        <td>Python</td>
        <td>Python</td>
        <td>-</td>
        <td>-</td>
        <td>DataScience</td>
        <td>DataScience</td>
    </tr>
    <tr>
        <td>Saturday</td>
        <td>Python</td>
        <td>Python</td>
        <td>-</td>
        <td>-</td>
        <td>FWD</td>
        <td>FWD</td>
        <td>Python</td>
        <td>Python</td>
    </tr>
</table>

</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (6).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
