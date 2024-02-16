DAX FUNCTIONS
  datetime functions:NOW, TODAY, DATE, TIME, DATETIME, YEAR, MONTH, HOUR, MINUTE, SECOND, WEEKDAY,  WEEKNUM,DATEDIFF,EMONTH,EDATE,NOWUTC
  text functions: CONCATENATE, CONCATENATEX, LEFT, RIGHT, MID, LEN, LOWER, UPPER, PROPER, TRIM, SUBSTITUTE, REPLACE, FIND, SEARCH, LEFTPAD, RIGHTPAD, UNICHAR, UNICODE
  information /filter functions:HASONEFILTER, HASONEVALUE, ISBLANK, ISERROR, ISEMPTY, ISFILTERED, ISINSCOPE, ISLOGICAL, ISNONTEXT, ISNUMBER, ISTEXT, USERNAME
  aggregation functions:SUM, AVERAGE, MIN, MAX, COUNT, COUNTA, COUNTROWS, DISTINCTCOUNT, PRODUCT, STDEV.P, STDEV.S, VAR.P, VAR.S, MEDIAN, PERCENTILE.EXC, PERCENTILE.INC
  timeintelligence functions:TOTALYTD, TOTALQTD, TOTALMTD, YTD, QTD, MTD, SAMEPERIODLASTYEAR, DATESYTD, DATESQTD, DATESMTD, YEARFRAC
  
DATETIME FUNCTIONS:
NOW: Returns the current date and time.
TODAY: Returns the current date.
DATE:Returns a table of dates.
TIME:Returns a specific time.
TIME(hour, minute, second)
DATETIME:Returns a datetime value.
DATETIME(year, month, day, hour, minute, second)
YEAR:Returns the year from a datetime value.
MONTH:Returns the month from a datetime value.
HOUR:Returns the hour from a datetime value.
MINUTE:Returns the minute from a datetime value.
SECOND:Returns the second from a datetime value.
WEEKDAY:Returns the day of the week as a number (1 to 7).
WEEKNUM:Returns the week number of the year.
WEEKNUM(datetime, [first_day_of_week])
DATEDIFF:Returns the difference between two dates.
DATEDIFF(start_date, end_date, unit)
EOMONTH:Returns the last day of the month.
EOMONTH(start_date, months)
EDATE:Returns a date that is a specified number of months before or after another date.
EDATE(start_date, months)
NOWUTC:Returns the current UTC date and time 

TEXT:
CONCATENATE:Combines two or more text strings into one.
CONCATENATEX:Concatenates the result of an expression evaluated for each row in a table.
LEFT:Returns a specified number of characters from the beginning of a text string.
RIGHT:Returns a specified number of characters from the end of a text string.
MID:Returns a specific number of characters from a text string, starting at the position you specify.
LEN:Returns the number of characters in a text string.
LOWER:Converts all characters in a text string to lowercase.
UPPER:Converts all characters in a text string to uppercase.
PROPER:Capitalizes the first letter of each word in a text string.
TRIM:Removes leading and trailing spaces from a text string.
SUBSTITUTE:Replaces occurrences of a specified substring with another substring in a text string.
REPLACE:Replaces part of a text string with another text string.
FIND:Returns the starting position of one text string within another text string. If the substring is not found, it returns 0.
SEARCH:Similar to FIND but case-insensitive.
LEFTPAD:Pads a text string on the left with a specified number of characters.
RIGHTPAD:Pads a text string on the right with a specified number of characters.
UNICHAR:Returns the Unicode character that is referenced by the given numeric value.
UNICODE:Returns the Unicode value of the first character of a text string. 

INFORMATION/FILTER FUNCTIONS:
HASONEFILTER:Checks whether there is only one filter context in the current evaluation.
HASONEVALUE:Checks whether there is only one distinct value in a column under the current filter context.
ISBLANK:Returns TRUE if the specified value is blank.
ISERROR:Returns TRUE if the expression generates an error.
ISEMPTY:Returns TRUE if the table is empty.
ISFILTERED:Returns TRUE if any filters have been applied to the specified table.
ISINSCOPE:Returns TRUE if the column is in the current scope.
ISLOGICAL:Returns TRUE if the value is a logical data type.
ISNONTEXT:Returns TRUE if the value is not a text data type.
ISNUMBER:Returns TRUE if the value is a number.
ISTEXT:Returns TRUE if the value is text.
USERNAME:Returns the name of the current user.

AGGEREGATE FUNCTIONS:
SUM:Adds up all the numbers in a column.
AVERAGE:Calculates the average of a column.
MIN:Returns the smallest value in a column.
MAX:Returns the largest value in a column.
COUNT:Counts the number of rows in a table or the number of non-blank values in a column.
COUNTA:Counts the number of non-blank values in a column.
COUNTROWS:Counts the number of rows in a table.
DISTINCTCOUNT:Counts the number of distinct values in a column.
PRODUCT:Multiplies all the numbers in a column.
STDEV.P:Calculates the population standard deviation of a column.
STDEV.S:Calculates the sample standard deviation of a column.
VAR.P:Calculates the population variance of a column.
VAR.S:Calculates the sample variance of a column.
MEDIAN:Calculates the median of a column.
PERCENTILE.EXC:Calculates the exclusive percentile of a column.
PERCENTILE.INC:Calculates the inclusive percentile of a column.

TIMEINTELLEGENCE FUNCTIONS:
TOTALYTD:Calculates the year-to-date total for a given expression.
TOTALQTD:Calculates the quarter-to-date total for a given expression.
TOTALMTD:Calculates the month-to-date total for a given expression.
YTD:Returns a table that contains a column of yearly dates.
QTD:Returns a table that contains a column of quarterly dates.
MTD:Returns a table that contains a column of monthly dates.
SAMEPERIODLASTYEAR:Returns a table that contains a column of dates shifted one year back.
DATESYTD:Returns a table that contains a column of dates for the year-to-date.
DATESQTD:Returns a table that contains a column of dates for the quarter-to-date.
DATESMTD:Returns a table that contains a column of dates for the month-to-date.
YEARFRAC:Returns the fraction of the year represented by the number of whole days between two dates.


LOGICAL FUNCTIONS:IF, SWITCH, AND, OR, NOT, TRUE, FALSE, ISEVEN, ISODD, IFERROR,IFNA

IF:Returns one value if a condition is true and another value if it's false.
SWITCH:Evaluates a series of conditions and returns the result of the first condition that is true.
AND:Returns TRUE if all the arguments are true, and FALSE otherwise.
OR:Returns TRUE if at least one of the arguments is true, and FALSE otherwise.
NOT:Returns the opposite of a logical value. If the argument is TRUE, NOT returns FALSE; if the argument is FALSE, NOT returns TRUE.
TRUE:Returns the logical value TRUE.
FALSE:Returns the logical value FALSE.
ISEVEN:Returns TRUE if the number is even, and FALSE if it's odd.
ISODD:Returns TRUE if the number is odd, and FALSE if it's even.
IFERROR:Returns a value you specify if a formula evaluates to an error; otherwise, it returns the result of the formula.
IFNA:Returns a value you specify if the expression is #N/A, otherwise returns the result of the expression.

OPERATORS 
arithmetic ( +, -, *, /), comparison (e.g., =, <>, >, <, >=, <=), logical (e.g., AND, OR, NOT), and concatenation (&) 
