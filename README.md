# DATE-AND-TIME-FUNCTION

<b> What are DATE AND TIME Function?</b><br>
-Date and Time Function are set of Function in Microsoft Excel that are useful to work with dates.<br>
-And used to schedule payroll and payments,track employee performance reviews,years of service and keep track of orders and payments.<br>

# CREATING DATE AND TIME FUNCTION

<b>The function listed below are grouped into DATE and TIME category.</b><br>
-DATE()<br>
-TIME()<br>
-DATEVALUE()<br>
-TIMEVALUE()<br>

# DATE FUNCTION 

-<b>The Excel DATE function creates a valid date from individual year,month,and day components.</b><br>
-<b>The DATE function is useful for assembling dates that need to change dynamically based on onther values in a worksheet<./b><br>

*Syntax=Date(Year,Month<Day)

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/b7d8c881-0429-45d9-9a2e-e90b15c2b01d)

# TIME FUNCTION
<b>-The Excel TIME function is a built in function that allows you to create a time with individual hour,minute,and second components.</b><br>
<b>-Useful when you want to assemble a proper time inside another formula.</b><br>

*Syntax=TIME(Hour,Minute,Second)

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/5de67859-cdf2-4c16-a82d-088d266cf77b)


# DATEVALUE FUNCTION
<b>-The Excel DATEVALUE function converts text that appears in a recognized format(i.e.a Number,Date,or Time format) into a numeric value.</b><br>

*Syntax=Datevalue("year-month-day")

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/9da956d3-162d-4ccc-b316-ba5e6e15315a)

# TIMEVALUE FUNCTION
<b>-The Excel TIMEVALUE function converts a time represented as text into a proper Excel time.</b><br>
*Syntax=TIMEVALUE("Time_text")

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/93b8bdd7-6d50-4f58-ba8c-13ee27b2b5d7)

# CURRENT DATE AND TIME
<b>-The functions listed below are grouped into Current Date and Time category.</b><br>
-NOW()<br>
-TODAY()<br>
![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/c7425ad2-937a-48f6-ae69-e87d8a0ca14b)

# NOW AND TODAY FUNCTION
<b>-The Excel NOW() function returns the current date and time,updated continuously when a worksheet is changed or opened.<br>
-The Excel TODAY() function returns the current date, updatedcontinuously when a worksheet is changed or opened.
</b><br>

*NOTE:<br>
-Both function takes no arguments.<br>
*Syntax<br>
=NOW()<br>
=TODAY()<br>

# EXTRACTING THE COMPONENTS OF A TIME
<b>-The functions listed below are grouped into Extracting The Components of a Time category</b><br>
*HOUR()<br>
*MINUTE()<br>
*SECOND()<br> 

# HOUR FUNCTION-
<b>-The Excel HOUR function returns the hour component of a time
as a number between 0 23. For example, with a time of 9:30 AM,
HOUR will return 9.</b><br>
*Syntax=HOUR(serial_number)<br>

<b>Serial Number</b><br>
-Microsoft Excel stores dates as sequential serial numbers so
they can be used in calculations.<br>
-By default, January 1, 1900 is serial number 1, and January
At 2008 is serial number 39448 because it is 39,448 days
after January 1, 1900.<br>

# MINUTE FUNCTION
<b>The Excel MINUTE function extracts the minute component of a time as a number between 0 59,</b><br>
-For example, with a time of 9:34 AM, minute will return 34.
*Syntax=MINUTE(serial_number)<br>

# SECOND FUNCTION
<b>The Excel SECOND function returns the second component of a time as a number between 0 59.</b>
-For example, with a time of 9:10:15 AM, second will return 15.<br>
*Syntax=SECOND(serial_number)

# Extracting The Components of a Date
<b>-The functions listed below are grouped into Extracting The
Components of a Date category.</b><br>
*DAY()<br>
*MONTH()<br>
*YEAR()<br>
*WEEKNUM()<br>
*WEEKDAY()<br>

# DAY FUNCTION
<b>-The Excel DAY function returns the day of the month as a
number between 1 to 31 from a given date.<br>
-You can use the DAY function to extract a day number from a
date into a cell.</b><br>
*Syntax=DAY(serial_number)

# MONTH FUNCTION
<b>-The Excel MONTH function extracts the month from a given date as number between 1 to 12.</b><br>
*Syntax=MONTH(serial_number)

# YEAR FUNCTION
<b>-The Excel YEAR function returns the year component of a
date as a 4 digit number.</b><br>
*Syntax=YEAR(serial_number)

# WEEKNUM FUNCTION
<b>-The Excel WEEKNUM function takes a date and returns a week number (1 54) that corresponds to the week of year.<br>
-The WEEKNUM function starts counting with the week that contains January 1.<br>
-By default, weeks begin on Sunday.</b><br>
*Syntax=WEEKNUM(serial_number)

# WEEKDAY FUNCTION
<b>-The Excel WEEKDAY function takes a date and returns a number between 1 7 representing the day of week.<br>
-By default, WEEKDAY returns 1 for Sunday and 7 forSaturday.</b><br>
*Syntax=WEEKDAY(serial_number)

# EOMONTH FUNCTION
<b>-The Excel EOMONTH function returns the last day of the month.</b><br>
*Syntax=EOMONTH(serial_number)

# WORKDAY FUNCTION
<b>-The Excel WORKDAY function takes a date and returns the nearest working day in the future or past.<br>
-You can use the WORKDAY function to calculate things like ship dates, delivery dates, and completion dates that need to take into account working and non working days</b><br>
*Formula=WORKDAY(start_date,days,[holidays])<br>
<b>-Parameters<br>
start_date - The date from which to start.<br>
days - The working days before or after start_date<br>
holidays - [optional] A list dates that should be considered non working days.</b><br>

# WORKDAY.INTL FUNCTION
<b>-The Excel WORKDAY.INTL function takes a date and returns the nearest working in the future or past, based on an offset value you provide. <br>
-Unlike the WORKDAY, WORKDAY.INTL allows you to customize which days are considered weekends (non working days).</b><br>
*Syntax=WORKDAY.INTL(start_date,days,[weekend],[holidays])<br>
<b>-Parameters
-start_date The start date.<br>
-days - The end date.<br>
-weekend - [optional] Setting for which days of the week should be considered weekends.<br>
-holidays - [optional] A list of one or more dates that should be considered non working days.</b><br>

# DAYS FUNCTION
<b>-The Excel DAYS function returns the number of daysbetween two dates.<br>
-With a start date in A1 and end date in B1, =DAYS(B1,A1) will return the days between the two dates.</b><br>
*Syntax=DAYS(end_date,start_date)














