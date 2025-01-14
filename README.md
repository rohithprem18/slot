# Ex03 Time Table
## Date: 14-03-2024

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
        <title>My Time Table</title>
    </head>
    <body>
       
     <center><img src="logo.png" height="200" width="800" > <br>
        
        <br>
        <table border="1" height="450" width="800">
            <caption> <b>SLOT TIME TABLE - ROHITH PREM S(212223040172)</b></caption>
            <tr>
                <th bgcolor="yellow" >Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                <th bgcolor="yellow">Saturday</th>
                
            </tr>

            <tr>
                <td align="center" bgcolor="yellow"><b> 8-10</b></th>
                <td align="center" bgcolor="cyan"> FREE SLOT </td>
                <td align="center" bgcolor="cyan">DE</td>
                <td align="center" bgcolor="cyan">ADVANCE C</td>
                <td align="center" bgcolor="cyan">FREE SLOT</td>
                <td align="center" bgcolor="cyan">WEB APPL</td>
                <td align="center" bgcolor="cyan">PROB</td>
            </tr>
            <tr>
                <td align="center" bgcolor="yellow"> <b>10-12</b></td>
                <td align="center" bgcolor="cyan">ADVANCE C</td>
                <td align="center" bgcolor="cyan">GERMAN</td>
                <td align="center" bgcolor="cyan">DE</td>
                <td align="center" bgcolor="cyan">PROB</td>
                <td align="center" bgcolor="cyan">EDM</td>
                <td align="center" bgcolor="cyan">INTRO TO ML</td>
            </tr>
            <tr>
                <td align="center" bgcolor="yellow"> <B>12-1</B></td>
                <td colspan="3" align="center"> Lunch break</td>
                <td align="center" bgcolor="magenta">Mentor Meet</td>
                <td colspan="2" align="center">Lunch break</td>
            </tr>
            <tr>
                <td align="center" bgcolor="yellow"><B>1-3</B></td>
                <td align="center" bgcolor="cyan">INTRO TO ML</td>
                <td align="center" bgcolor="cyan">WEB APPL</td>
                <td align="center" bgcolor="cyan">CREATIVE</td>
                <td align="center" bgcolor="cyan">WEB APPL</td>
                <td align="center" bgcolor="cyan">GERMAN</td>
                <td align="center" bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr>
                <td align="center" bgcolor="yellow"><b>3-5</b></td>
                <td align="center" bgcolor="cyan">FREE SLOT</td>
                <td align="center" bgcolor="cyan">FREE SLOT</td>
                <td align="center" bgcolor="cyan">GERMAN</td>
                <td align="center" bgcolor="cyan">EDM</td>
                <td align="center" bgcolor="cyan">FREE SLOT </td>
                <td align="center" bgcolor="cyan">FREE SLOT </td>
            </tr>
        </table>
        
        <br>

        <table border="1" height="340" width="800">
            <tr>
                <th bgcolor="yellow">S.NO</th>
                <th bgcolor="yellow">Subject Code</th>
                <th bgcolor="yellow">Subject Name</th>
            </tr>
            <tr>
                <th align="center">1.</th>
                <td align="center" >19AI302</td>
                <td align="center" >ENGINEERING DESIGNING AND MODELLING (EDM)</td>
            </tr>
            <tr>
                 <th align="center" >2.</th>
                 <td align="center" >19AI305</td>
                 <td align="center">ADVANCED C PROGRAMMING</td>
            </tr>
            <tr>
                <th align="center" >3.</th>
                <td align="center" >19AI410</td>
                <td align="center" >INTRODUCTION TO MACHINE LEARNING (INTRO TO ML)</td>
           </tr>
            <tr>
                <th align="center" >4.</th>
                <td align="center" >19AI414</td>
                <td align="center" >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (WEB APPL)</td>
           </tr>
           <tr>
            <th  align="center" >5.</th>
            <td  align="center" >19EE404</td>
            <td  align="center" >DIGITAL ELECTRONICS (DE)</td>
       </tr>
       <tr>
        <th align="center" >6.</th>
        <td align="center" >19EN613C</td>
        <td align="center" >GERMAN BASIC AND ADVANCED (GERMAN)</td>
   </tr>
   <tr>
    <th align="center" >7.</th>
    <td align="center" >19EY702</td>
    <td align="center" >CREATIVE SKILLS (CREATIVE)</td>
</tr>

<tr>
    <th align="center" >8.</th>
    <td align="center" >19MA222</td>
    <td align="center" >PROBABILITY AND QUEUEING MODELS (PROB)</td>
</tr>
<tr>
    <th align="center" >9.</th>
    <td align="center" >ECA-M</td>
    <td align="center" >MENTOR MEET</td>
</tr>

        </table>
    
        </center>
        
    </body>
</html>
```

## OUTPUT
![alt text](experiment_03.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
