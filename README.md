# Ex03 Time Table
## Date:15/11/2023

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
    <title> image map </title>
     <body>
        <center>
            <img src="/static/logo.png" height="100" width="500"
        </center>
       <br>
          <table border="4" cellspacing="15" cellspacing="15">
            <caption="centre"> MY TIME TABLE Muthulakshmi D (23013566) </caption>
             <tr>
                 <th bgcolor="lightgreen">Monday</th>
                 <td bgcolor="cyan">Free</td>          
                 <td bgcolor="cyan">Free</td>
                 <td bgcolor="cyan">Free</td>
                 <td bgcolor="cyan">Free</td>          
                 <td bgcolor="light blue">Lunch</td>          
                 <td bgcolor="pink">Calculus and matrix algebra</td>          
                 <td bgcolor="pink">Calculus and matrix algebra</td>
                 <td bgcolor="cyan">Free</td>
                 <td bgcolor="cyan">Free</td>                    
              </tr>
              <tr>
                 <th bgcolor="lightgreen">Tuesday</th>
                 <td bgcolor="cyan">Free</td>             
                 <td bgcolor="cyan">Free</td>
                 <td bgcolor="pink">Calculus and matrix algebra</td>             
                 <td bgcolor="pink">Calculus and matrix algebra</td>             
                 <td bgcolor="light blue">Lunch</td>             
                 <td bgcolor="cyan">Engineering Design and Modelling</td>             
                 <td bgcolor="cyan">Engineering Design and Modelling</td>             
                 <td bgcolor="cyan">Physics for Quantum Computing</td>
                 <td bgcolor="cyan">Free</td>                          
              </tr>
              <tr>
                 <th bgcolor="lightgreen">Wednesday</th>
                 <td bgcolor="pink">Fundamental of web application</td>          		
                 <td bgcolor="pink">Fundamental of web application</td>
                 <td bgcolor="pink">Computer Architecture</td>
                 <td bgcolor="pink">Computer Architecture</td>
                 <td bgcolor="light blue">Lunch</td>
                 <td bgcolor="cyan">Free</td>
                 <td bgcolor="cyan">Free</td>
                 <td bgcolor="pink">Soft skill</td>
                 <td bgcolor="pink">Soft skill</td>
              </tr>
              <tr>
                 <th bgcolor="lightgreen">Thurday</th>
                 <td bgcolor="cyan">Engineering Design and Modelling</td>
                 <td bgcolor="cyan">Engineering Design and Modelling</td>
                 <td bgcolor="pink">Fundamental of web application</td> 
                 <td bgcolor="pink">Fundamental of web application</td> 
                 <td bgcolor="light blue">Lunch</td> 
                 <td bgcolor="cyan">Physics for Quantum computing</td> 
                 <td bgcolor="cyan">Physics for Quantum computing</td> 
                 <td bgcolor="cyan">Python programming</td> 
                 <td bgcolor="cyan">Python programming</td>  
              </tr>
                  <th bgcolor="lightgreen">Friday</th>
                  <td bgcolor="cyan">Free</td>
                  <td bgcolor="cyan">Free</td>
                  <td bgcolor="pink">Computer architecture</td>
                  <td bgcolor="cyan">Free</td>
                  <td bgcolor="light blue">Lunch</td>
                  <td bgcolor="pink">Fundamental of web application</td>
                  <td bgcolor="pink">Fundamental of web application</td>
                  <td bgcolor="cyan">Python programming</td>
                  <td bgcolor="cyan">Python programming</td>
              </tr>
             </table border>
<br>
             <table border="5" cellspacing="7" cellspacing="7">
                 <caption="center">MY SUBJECTS AND SLOTS</caption>
                   <tr>
                    <th bgcolor="lightblue">Slot</th>
                    <th bgcolor="lightblue">Subject code</th>
                    <th bgcolor="lightblue">Subject name</th>
                  </tr> 
                  <tr>
                    <th bgcolor="pink">4W3</th>
                    <th bgcolor="lightgreen">19AI301</th>
                    <th bgcolor="cyan">Python programming</th>
                  </tr> 
                  <tr>
                    <th bgcolor="pink">4T1-1</th>
                    <th bgcolor="lightgreen">19AI301</th>
                    <th bgcolor="cyan">Engineering Design and Modelling</th>
                  </tr>  
                  <tr>
                    <th bgcolor="pink">6B1-1</th>
                    <th bgcolor="lightgreen">19AI414</th>
                    <th bgcolor="cyan">Fundamentals of web Application Developement</th>
                  </tr>     
                  <tr>
                    <th bgcolor="pink">3K1-2</th>
                    <th bgcolor="lightgreen">19CS305</th>
                    <th bgcolor="cyan">Computer Architecture</th>
                  </tr>  
                   <tr>
                    <th bgcolor="pink">2B15</th>
                    <th bgcolor="lightgreen">19EY701</th>
                    <th bgcolor="cyan">Soft skill</th>
                  </tr> 
                   <tr>
                    <th bgcolor="pink">4C1-2</th>
                    <th bgcolor="lightgreen">19MA201</th>
                    <th bgcolor="cyan">Calculus and Matrix Algebra</th>
                  </tr> 
                   <tr>
                    <th bgcolor="pink">3B1-1</th>
                    <th bgcolor="lightgreen">19PH214</th>
                    <th bgcolor="cyan">Physics for Quantum Computing</th>
                  </tr>  
     </body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (3).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
