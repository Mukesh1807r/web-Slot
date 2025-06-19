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

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Engineering College Timetable</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
    }
    .header {
      background-color: #0074cc;
      color: white;
      padding: 10px;
    }
    .college-info {
      margin: 20px 0;
    }
    table {
      margin: 0 auto 30px;
      border-collapse: collapse;
      width: 80%;
    }
    table, th, td {
      border: 1px solid #000;
    }
    th, td {
      padding: 10px;
      text-align: center;
    }
    th {
      background-color: #ffd700;
    }
    .lunch {
      background-color: #f3f3f3;
      font-weight: bold;
    }
  </style>
</head>
<body>
    <center>
        <img src="logo.png" height = "180" width="800">
    </center>

  <div class="college-info">
    <h3>SLOT TIME TABLE - Mukesh R (212224240098)</h3>
  </div>

  <table>
    <tr>
        <td bgcolor="Yellow">Day/Time</td>
        <th bgcolor="REd">Monday</th>
        <th bgcolor="REd">Tuesday</th>
        <th bgcolor="REd">Wednesday</th>
        <th bgcolor="REd">Thursday</th>
        <th bgcolor="REd">Friday</th>
        <th bgcolor="REd">Saturday</th>
    </tr>
    <tr>
        <td bgcolor="Yellow">8-10</td>
        <td bgcolor="cyan">DSP</td>
        <td colspan="5" align="center" bgcolor="white">FREE SLOT</td>
    </tr> 
    <tr>
        <td bgcolor="Yellow">10-12</td>
        <td bgcolor="cyan">FWAD</td>
        <td bgcolor="cyan">AOA</td>
        <td bgcolor="cyan">FWAD</td>
        <td bgcolor="cyan">DSP</td>
        <td bgcolor="white">FREE SLOT</td>
        <td bgcolor="cyan">CN</td>
    </tr>
    <tr>
        <td bgcolor="Yellow">12-1</td>
        <td colspan="6" align="center" bgcolor="lightblue">LUNCH</td>
    </tr>
    <tr>
        <td bgcolor="Yellow">1-3</td>
        <td bgcolor="cyan">IML</td>
        <td bgcolor="cyan">CDS</td>
        <td bgcolor="cyan">Mentor Meet</td>
        <td bgcolor="cyan">CN</td>
        <td bgcolor="cyan">C programming</td>
        <td bgcolor="cyan">AOA</td>
    </tr>
    <tr>
        <td bgcolor="Yellow" >3-5</td>
        <td bgcolor="cyan">BEEE</td>
        <td bgcolor="cyan">C programming</td>
        <td bgcolor="cyan">IML</td>
        <td colspan="2" align="center"bgcolor="white">FREE SLOT</td>
        <td bgcolor="cyan">BEEE</td>
    
    </tr>
  </table>

  <table>
    <tr>
      <th>S. No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>1</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19IT405</td>
      <td>Data Structures using python (DSP)</td>
    </tr>
    <tr>
      <td>3</td>
      <td>19AI410</td>
      <td>Introduction to Machine Learning (IML)</td>
    </tr>
    <tr>
      <td>4</td>
      <td>19EE305</td>
      <td>Basic Electrical,Electronics and Meassurement Engineering (BEEE)</td>
    </tr>
    <tr>
      <td>5</td>
      <td>19AI404</td>
      <td>Analysis of ALgorithms (AOA)</td>
    </tr>
    <tr>
      <td>6</td>
      <td>19EY708</td>
      <td>Career Development Skills (CDS)</td>
    </tr>
    <tr>
      <td>7</td>
      <td>19AI406</td>
      <td>Computer Networks (CN)</td>
    </tr>
    <tr>
      <td>8</td>
      <td>19AI304</td>
      <td>Fundamentals of C Programming (C programming)</td>
    </tr>

  </table>

</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-04-21 121838.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
