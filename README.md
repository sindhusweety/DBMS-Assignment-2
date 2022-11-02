# DBMS-Assignment-2


```
You are on the menu pagek
A - Create a table 
B - Include an entry 
C - Delete an entry/ entries 
D - List a table 
1 - Include a new book 
2 - Include a new user 
3 - List library users with books they checked out 
4 - Check out a book 
5 - Return a book 
6 - Exit
type anyone of above mentioned options & click ENTER: 
A
CREATE operation has been chosen
[books, book, people]
Enter table name: 
checkedOutBooks
Enter column name:
SSN
Enter column name:
callNo
Enter column name:

------------------------------------------------------------
Successfully created table
------------------------------------------------------------
------------------------------------------------------------
If you would like to create more tables, Type 'Yes' or 'No' (y/n):
------------------------------------------------------------
n
------------------------------------------------------------
Redirecting to Home Page..
------------------------------------------------------------
------------------------------------------------------------
You are on the menu pagek
A - Create a table 
B - Include an entry 
C - Delete an entry/ entries 
D - List a table 
1 - Include a new book 
2 - Include a new user 
3 - List library users with books they checked out 
4 - Check out a book 
5 - Return a book 
6 - Exit
type anyone of above mentioned options & click ENTER: 
4
CHECKOUT operation has been chosen
[checkedOutBooks, books, book, people]
Enter person's SSN:
1234567
Enter book's call#:
1234
------------------------------------------------------------
Successfully included
------------------------------------------------------------
------------------------------------------------------------
More books checked out (Y/n) ?
y
Enter book's call#:
12456789
Entered callNo doesn't exist & please try again.
do you want to continue trying (Y/n)?:
n
------------------------------------------------------------
Redirecting to Home Page..
------------------------------------------------------------
------------------------------------------------------------
You are on the menu pagek
A - Create a table 
B - Include an entry 
C - Delete an entry/ entries 
D - List a table 
1 - Include a new book 
2 - Include a new user 
3 - List library users with books they checked out 
4 - Check out a book 
5 - Return a book 
6 - Exit
type anyone of above mentioned options & click ENTER: 
5
RETURN_BOOK operation has been chosen
[checkedOutBooks, books, book, people]
Enter checkedOutBooks's SSN:
1234567
Enter checkedOutBooks's callNo:
1234
------------------------------------------------------------
Successfully deleted
------------------------------------------------------------
 Type 'Yes' or 'No' (y/n) to delete more records:
n
------------------------------------------------------------
Redirecting to Home Page..
------------------------------------------------------------
------------------------------------------------------------
You are on the menu pagek
A - Create a table 
B - Include an entry 
C - Delete an entry/ entries 
D - List a table 
1 - Include a new book 
2 - Include a new user 
3 - List library users with books they checked out 
4 - Check out a book 
5 - Return a book 
6 - Exit
type anyone of above mentioned options & click ENTER: 
D
PRINTTABLE operation has been chosen
[checkedOutBooks, books, book, people]
Enter table name: 
checkedOutBooks
------------------------------------------------------------
checkedOutBooks
Printing 0 row from table checkedOutBooks
+-----+--------+
| SSN | callNo |
+-----+--------+

------------------------------------------------------------
 Type 'Yes' or 'No' (y/n) to continue printing:
n
------------------------------------------------------------
Redirecting to Home Page..
------------------------------------------------------------
------------------------------------------------------------
You are on the menu pagek
A - Create a table 
B - Include an entry 
C - Delete an entry/ entries 
D - List a table 
1 - Include a new book 
2 - Include a new user 
3 - List library users with books they checked out 
4 - Check out a book 
5 - Return a book 
6 - Exit
type anyone of above mentioned options & click ENTER: 
3
LIST_LIBRARY operation has been chosen
false
---------------------------------------------------------------------
Name,     Author,     Title 
---------------------------------------------------------------------
---------------------------------------------------------------------
people with no checked out books 
---- ----- -----------------------------------------------------------
sindhu
thakkudu
Anu
------------------------------------------------------------
SQL error occured   : net.ucanaccess.jdbc.UcanaccessSQLException: UCAExc:::5.0.1 connection exception: closed
------------------------------------------------------------
-------------------------------------------------
*******Something went wrong. Please try Again*****
---------------------------------------------------
You are on the menu pagek
A - Create a table 
B - Include an entry 
C - Delete an entry/ entries 
D - List a table 
1 - Include a new book 
2 - Include a new user 
3 - List library users with books they checked out 
4 - Check out a book 
5 - Return a book 
6 - Exit
type anyone of above mentioned options & click ENTER: 
6
EXIT operation has been chosen
Successfully Logged Out

Process finished with exit code 1
```
