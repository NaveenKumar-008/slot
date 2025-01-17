# Ex03 Time Table
# DATE:06/10/23

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

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: peru;
            border-color: red;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: blueviolet;
        }
        .c1{
            background-color: plum;
        }
    </style>
</head>
<body>
    <img src = "logo.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - NAVEEN KUMAR M (212221040113)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <th colspan="1">DPSD</th>
            <td>FWAD</td>
            <td>CD</td>
            <td>DPSD</td>
            <td>Free</td>
            <td>Free</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <td>Free</td>
            <th >CD</th>
            <td>Free</td>
            <td>GP</td>
            <td>DPSD</td>
            <td>CNS</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>EES</td>
            <td>Free</td>
            <td>GP</td>
            <td>Free</td>
            <td>Free</td>
            <td>Free</td>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>CNS</td>
            <td>Free</td>
            <td>DAA</td>
            <td>FWAD</td>
            <td>DAA</td>
            <td>FWAD</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (WEB)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS409</td>
            <td>Compiler Design (CD)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS521</td>
            <td>Cryptography and Network Security (CNS)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19EC303</td>
            <td>Digital Priciples and System Design (DPSD)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS402</td>
            <td>Design and Analysis of Algorithm (DAA)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY705</td>
            <td>Employment Enhancement skills (EES)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19AI513</td>
            <td>Game Programming (GP)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![Alt text](<Ex3 Output.jpeg>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
