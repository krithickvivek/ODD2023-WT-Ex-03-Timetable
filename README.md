# Ex-05-Timetable
# AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
## STEP 1
Create a simple table using table tag
## STEP 2
Add header row using th tag
## STEP 3
Add your timetable
## STEP 4
Execute the program

# CODE
```html
<!DOCTYPE html>
<html>
    <head></head>
<body>
    <IMG src="C:\Users\admin\ODD2023-WT-Ex-03-Timetable\logo.png"
	height="100" width="788" align="center" border="8">
    <h1>     </h1>

    <table border="14" cellspacing="0" align="left"  >
        
        <tr bgcolor="LightBlue">
            <th align= "center"  colspan="6" height="50" width="100"><h1>TIME TABLE</h1></th>
        </tr>
        <tr bgcolor="#728FCE">
            <th align= "center"  colspan="1"  height="40" width="80"><b>NAME</b></th>
            <th align= "center"  colspan="2"  bgcolor="LightSteelBlue" height="40" width="80"><b>Krithick Vivekananda</b></th>
            <th align= "center"  colspan="1"  height="40" width="80"><b>REF.NO</b></th>
            <th align= "center"  colspan="2"  bgcolor="LightSteelBlue" height="40" width="80"><b>23009445</b></th>
        </tr>
        <tr bgcolor="#A0D6B4">
            <th align= "center"  colspan="6" height="40" width="50"> <b>SEMESTER-1 ODD-JUNIOR(2023-2024)</b></th>
        </tr>
       
        
        <tr bgcolor="LightBlue">
            
            <td align="center"  height="50"
                width="125"><br>
                <b>Day/Period</b></br>
            </td>
            <td align="center" height="50"
                width="125">
                <b>I<br>8:00-10:00</b>
            </td>
            <td align="center" height="50"
                width="125">
                <b>II<br>10:00-12:00</b>
            </td>
            <td align="center" height="50"
                width="125">
                <b>12:00-1:00</b>
            </td>
            <td align="center" height="50"
                width="125">
                <b>III<br>1:00-3:00</b>
            </td>
            <td align="center" height="50"
                width="125">
                <b>IV<br>3:00-5:00</b>
            </td>
        </tr>
        <tr bgcolor="LightSteelBlue">
            <td align="center" height="80">
                <b>Monday</b></td>
            <td align="center" bgcolor="#e7feff "height="50">---</td>
            <td align="center" bgcolor="#e7feff " height="50">19EY701/ Soft Skills</td>
            <td rowspan="5" align="center" height="50">
                <h1>L<br>U<br>N<br>C<br>H</h1>
            </td>
            <td bgcolor="#e7feff " align="center"height="50">19PH214/ Physics for Quantum Computing</td>
            <td align="center" bgcolor="#e7feff " height="50">---</td>
        </tr>
        <tr bgcolor="LightSteelBlue">
            <td align="center"  height="80">
                <b>Tuesday</b>
            </td>
            <td  bgcolor="#e7feff "align="center"height="50">19CY205/ Principles of Chemistry</td>
            <td align="center" bgcolor="#e7feff "height="50">19MA222/ Probabilty and Queuing Models</td>
            <td align="center" bgcolor="#e7feff "height="50">---</td>
            <td align="center" bgcolor="#e7feff " height="50">---</td>
            
        </tr>
        <tr bgcolor="LightSteelBlue">
            <td align="center" height="80">
                <b>Wednesday</b>
            </td>
            <td align="center" bgcolor="#e7feff " height="50">---</td>
            <td align="center" bgcolor="#e7feff "height="50">19AI414/ Web Application</td>
            <td align="center" bgcolor="#e7feff " height="50">---</td>
            <td align="center" bgcolor="#e7feff " height="50">---</td>
        </tr>
        <tr bgcolor="LightSteelBlue">
            <td align="center" height="80">
                <b>Thursday</b>
            </td>
            <td align="center" bgcolor="#e7feff" height="50">19AI414/ Web Application</td>
            <td align="center"  bgcolor="#e7feff "height="50">19AI304/ C-Programming</td>
            <td align="center" bgcolor="#e7feff "height="50">19MA222/ Probability and Queuing Models</td>
            <td  align="center" bgcolor="#e7feff " height="50">---</td>
        </tr>
        <tr bgcolor="LightSteelBlue">
            <td align="center"  height="80">
                <b>Friday</b>
            </td>
            <td align="center" bgcolor="#e7feff "height="50">19CY205/ Principles of Chemistry</td>
            <td align="center" bgcolor="#e7feff "height="50">19AI414/ Web Application</td>
            <td align="center" bgcolor="#e7feff " height="50">19AI304/ C-Programming</td>
            <td align="center" bgcolor="#e7feff " height="50">19PH214/ Physics for Quantum Computing</td>
        </tr>
    </table>
</body>
</html>



```

# OUPUT
![Output](TimeTable.png)

# RESULT
Thus the time table is been displayed using a HTML page successfully.
