# Ex03 Time Table
## Date:28-10-2024

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
    </head>
	<body align="center" bgcolor="WHITE" >
		 <center>
            <img src= "/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="TEAL">
			<caption>SLOT TIME TABLE- NARMADHA SREE S (212223240105) </caption>
            <br>
			<tr>
				<th bgcolor="YELLOW"> Day/Time </th>
				<th bgcolor="YELLOW"> Monday </th>
				<th bgcolor="YELLOW"> Tuesday </th>
                <th bgcolor="YELLOW"> Wednesday </th>
                <th bgcolor="YELLOW"> Thursday </th>
                <th bgcolor="YELLOW"> Friday </th>
                <th bgcolor="YELLOW"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="YELLOW"> 8-10 </td>
                <td> DBMS </td>
                <td>COMPUTER NETWORK</td>
                <td> QUANTATIVE_ABILITY</td>
                <td> WEB </td>
                <td> PMC </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="YELLOW"> 10-12 </th>
				<td> PMC </td>
                <td> INTRO TO ML </td>
                <td> WEB </td>
                <td> COMPUTER_NETWORK </td>
                <td> OS </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="YELLOW"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="YELLOW"> 1-3 </th>
                <td> ADV C </td>
                <td> FREE SLOT </td>
                <td> MENTOR MEET </td>
                <td> PHYSIC </td>
                <td> OS </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="YELLOW"> 3-5 </td>
                <td>  </td>
                <td> PHYSIC </td>
                <td> ADV C </td>
                <td> DBMS </td>
                <td> INTRO TO ML </td>
                <td> FREE SLOT </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="YELLOW">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19AI410 </td>
                    <td align="center"> INTRODUCTION TO MACHINE LEARNING (INTRO TO ML) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> FUNDAMENTAL OF WEB APPLICATION (WEB) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19AI305 </td>
                    <td align="center"> ADVANCE C PROGRAMMING (ADV C) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19PH212 </td>
                    <td align="center"> PHYSICS </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19EE309 </td>
                    <td align="center"> PROGRAMMING MICROCONTROLLER (PMC) </td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19EY710 </td>
                    <td align="center"> QUANTATIVE ABILITY </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19C5405 </td>
                    <td align="center"> DATABASE MANAGEMENT DYSTEM AND ITS APPLICATION (DBMS) </td>
                </tr>
                <tr>
                    <th align="center"> 8. </td>
                    <td align="center"> 19CS406 </td>
                    <td align="center"> OPERATING SYSTEM (OS) </td>
                </tr>
                <tr>
                    <th align="center"> 8. </td>
                    <td align="center"> 19CS404 </td>
                    <td align="center"> COMPUTER NETWORK  </td>
                </tr>
                
                </table>
	</body>

</html>
```
## OUTPUT
![alt text](<Screenshot (27).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
