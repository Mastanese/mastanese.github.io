## Coding Professionally
### What are Coding Standards?
Coding standards are "best practices," implemented throughout a company 
or language. They are implemented to standardize code and improve 
readability. Coding standards can range from formatting (e.g. indents) 
to having acceptable/unacceptable ways to carry out various actions. 

For example, a job working with SQL may require programmers to separate the join condition from the rest of a query with comment lines:
```tsql
FROM db1
INNER JOIN db2
---------------------------------------
ON db1.a = db2.a
---------------------------------------
WHERE 1 <> 1
```
The workplace may also recommend using temp tables instead of having a
function in a `FROM` clause. One of these examples deals with code
formatting while the other deals with how a program is created. Both
can improve readability and one may improve the efficiency of the
code being written.

### Why is Readability Important?
The readability of written code may be one of the most important things
in programming. Poorly formatted code causes problems as it can make
code difficult to understand to co-workers and difficult to understand 
to the code's author if revisiting the code in the future. Unreadable 
code makes debugging and adding functionality harder.

Having a standardized way of writing code allows others to understand
one's code more quickly and makes writing code easier--with a 
standardized set of formatting rules, a coder does not have to put
as much thought into writing pretty code. By just following the standards put into place, a developer can assume that their code will be readable.

