# Ex03 Time Table
## Date:20/4/2-25

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
~~~html
<html>
    <head>
        <title><b>COURSE SCHEDULE</b></title>
    </head>
    <body>
        <center><img  src="logo.png" height="100" weidth="540"></center>
        
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="5" border="5" bgcolor="cyan">
        <caption><b>SCHEDULE OF ALL COURCES</b></caption>
        <tr align="center">
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
            <th bgcolor="yellow">Saturday</th>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">8-10</th>
            <td>DIGITAL ELECTRONICS</td>
            <td colspan="5">free</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>PYTHON PROGRAMMING</td>
            <td>EMBEDDER BOARD DESIGN</td>
            <td>ENGINEERING MECHANICS PRODUCT DEVELOPMENT</td>
            <td>EMBEDDER BOARD DESIGN</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
            <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
        </tr>
        <tr>
            <th bgcolor="yellow">12-1</th>
            <td colspan="6" align="center">L U N C H</td>
        </tr>
        <tr>
            <th bgcolor="yellow">1-3</th>
            <td>PHYSICS FOR QUANTUM COMPUTING</td>
            <td>REASONING ABILITY</td>
            <td>MENTOR MEET</td>
            <td>PROBABILTY AND QUEUEING MODELS</td>
            <td>DIGITAL ELECTRONICS</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
        <tr>
            <th bgcolor="yellow" align="center">3-5</th>
            <td>FREE</td>
            <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
            <td>PHYSICS FOR QUANTUM COMPUTING</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
            <td>FREE</td>
            <td>PROBABILITY AND QUEUING MODELS</td>
        </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr>
            <th>S.no</th>
            <th>COURSE CODE</th>
            <th>COURSR NAME</th>
        </tr>
        <tr>
            <th>1.</th>
            <td>19EE204</td>
            <td>DIGITAL ELCTRONICS</td>
        </tr>
        <tr>
            <th>2.</th>
            <td>19A301</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
        <tr>
            <th>3.</th>
            <td>19EE204</td>
            <td>PHYSICS FOR QUANTUM COMPUTING</td>
        </tr>
        <tr>
            <th>4.</th>
            <td>19CS403</td>
            <td>EMBEDDED BOARD DESIGN</td>D
        </tr>
        <tr>
            <th>5.</th>
            <td>19TS901</td>
            <td>REASONING ABLITY</td>
        </tr>
        <tr>
            <th>6.</th>
            <td>19ME304</td>
            <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
        </tr>
        <tr>
            <th>7.</th>
            <td>19AI304</td>
            <td>FUNDAMENTALS OF WEB APPLICATOIN</td>
        </tr>
        <tr>
            <th>8.</th>
            <td>19ME304</td>
            <td>HUMAN VALUES AND PROFESSOINAL ETHICS</td>
        </tr>
        </table>
    </body>
</html>
~~~

## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
