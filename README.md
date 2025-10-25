# Ex03 Time Table
## Date: 25-10-2025

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

    </head>
    <body>
        <center><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-10-16 103322.png" ></center>
        <table border="1" cellpadding="10" align="Center">
            <caption><b>SLOT TIME TABLE - LOKESH S (212224240079)</b></caption>
            <tr> <th>DAy/Time</th><th>Monday</th> <th>tuesday</th> <th>wednesday</th> <th>Thursday</th> <th>Friday</th> <th>Saturday</th></tr>
            <tr><td>8-10</td> <td colspan="3" align="center">FREE</td> <td>OS</td> <td>ADC</td> <td>Free</td> </tr> 
            <tr><td>10-12</td> <td>FREE</td> <td>ADC</td> <td>SE</td> <td>WEB</td> <td>GP</td> <td>Free</td> </tr>
            <tr><td>12-1</td> <td colspan="6" align ="center">LUNCH BREAK</td> </tr>
            <tr><td>1-3</td> <td>CC</td> <td>Free</td> <td>MENTOR MEETING</td> <td>GP</td> <td>OS</td> <td>WEB</td> </tr>
            <tr><td>3-5</td> <td>BFA</td> <td>SE</td> <td>BFA</td> <td>CC</td> <td>Free</td> <td>Free</td> </tr>
        </table><br><br>
        <table border="1" cellpadding="10" align="Center">
           
           <br><br> <tr> <th>S.No.</th><th>Subjectcode</th> <th>Subject Name</th></tr>
            <tr><td>1</td> <td>19AI414</td><td>Fundamental of Web App Development</td>
            <tr><td>2</td> <td>19AI513</td><td>Game Programming</td>
            <tr><td>3</td> <td>19AI541</td><td>Cloud computing</td>
            <tr><td>4</td> <td>19CS408</td><td>Software Engineering</td>
            <tr><td>5</td> <td>19MS154</td><td>Basic Financial Accounting</td>
            <tr><td>6</td><td>19AI305</td><td>Advance C Programming</td>
            <tr><td>7</td> <td>19AI405</td><td>Operating System</td>
        </table>
        
    </body>
</html>
```

## OUTPUT

<img width="1044" height="863" alt="image" src="https://github.com/user-attachments/assets/b2af55cb-3131-4525-a040-0627bcb5dafb" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
