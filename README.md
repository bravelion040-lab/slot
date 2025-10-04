# Ex03 Time Table
## Date:04.10.2025

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
~~~
<!DOCTYPE HTML>
<html>
    <head>
        <title>Microsoft</title>
     <link rel="stylesheet" href="index.css">
        
    </head>
    <body>
        <table border="2" cellpadding="10" cellspacing="1" row="1">
            <tr>
                <th>day</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr>
                <td>MONDAY</td>
                <td></td>
                <td><pre>Fundamentals of web development</pre></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>TUESDAY</td>
                <td>web</td>
                <td></td>
                <td>web</td>
                <td></td>
                
            </tr>
            <tr>
                <td>WEDNESDAY</td>
                <td>c</td>
                <td>c</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>THURSDAY</td>
                <td></td>
                <td>c</td>
                <td>c</td>
                <td></td>
            </tr> 
            <tr>
                <td>FRIDAY</td>
                <td></td>
                <td>c</td>
                <td>c</td>
                <td></td>
            </tr> 
            <tr>
                <td>SATURDAY</td>
                <td></td>
                <td>c</td>
                <td>c</td>
                <td></td>
            </tr> 
             
        </table>
     </body>
</html>
~~~

## OUTPUT
![alt text](<Screenshot 2025-10-04 161107.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
