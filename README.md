# Ex03 Time Table
## Date:16/03/2025

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
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Time Table</title>
    <style>
        body {
            font-family: 'Poppins', Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .top-right, .top-left {
            position: absolute;
            top: 20px;
            font-size: 16px;
            font-weight: 600;
            color: #555;
        }

        .top-right {
            right: 40px;
        }

        .top-left {
            left: 40px;
        }

        h2 {
            color: #ff8c00;
            font-size: 28px;
            margin-bottom: 20px;
            letter-spacing: 1px;
            text-transform: uppercase;
            border-bottom: 3px solid #ff8c00;
            display: inline-block;
            padding-bottom: 5px;
        }

        table {
            width: 100%;
            max-width: 800px;
            border-collapse: collapse;
            margin-top: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: #ffffff;
            border-radius: 12px;
            overflow: hidden;
        }

        th, td {
            padding: 15px;
            text-align: center;
            border: 1px solid #ddd;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        th {
            background-color: #ffa500;
            color: white;
            text-transform: uppercase;
            font-weight: bold;
        }

        td {
            background-color: #fafafa;
        }

        tr:nth-child(even) td {
            background-color: #f9f9f9;
        }

        td:hover {
            background-color: #f1f1f1;
            cursor: pointer;
        }

        .highlight {
            background-color: #ff8c00;
            color: white;
            font-weight: bold;
        }

        .mentor-meet {
            background-color: #4caf50;
            color: white;
            font-weight: bold;
        }

        img {
            margin-bottom: 20px;
            border-radius: 8px;
        }
    </style>
</head>
<body>

<div class="top-right">212224040128</div>
<div class="top-left">P Janardhan</div>

<center>
    <img src="/static/logo.png" height="100" width="1000" alt="Logo">
    
</center>
<h2>Prime Time Table</h2>
<table>
    <tr>
        <th colspan="4" class="highlight">Web Development and Fundamental of AI - Batch</th>
    </tr>
    <tr>
        <td class="highlight"></td>
        <td class="highlight">8-10</td>
        <td class="highlight">10-12</td>
        <td class="highlight">1-3</td>
    </tr>
    <tr>
        <th>Monday</th>
        <td>Web Development</td>
        <td>Task Assignment</td>
        <td>Fundamental of AI</td>
    </tr>
    <tr>
        <th>Tuesday</th>
        <td>Task Completion</td>
        <td>Web Development</td>
        <td>Module Completion</td>
    </tr>
    <tr>
        <th>Wednesday</th>
        <td>Assessment Hour</td>
        <td>Task Completion</td>
        <td class="mentor-meet">Mentor Meet</td>
    </tr>
    <tr>
        <th>Thursday</th>
        <td>Module Completion</td>
        <td>Fundamental of AI</td>
        <td>Task Presentation</td>
    </tr>
    <tr>
        <th>Friday</th>
        <td>Task Completion</td>
        <td>Web Development</td>
        <td>Task Completion</td>
    </tr>
    <tr>
        <th>Saturday</th>
        <td colspan="3" class="highlight">Module Assessment Completion</td>
    </tr>
</table>

</body>
</html>
```

## OUTPUT
![alt text](slot.png)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
