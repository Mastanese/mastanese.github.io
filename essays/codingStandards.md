---
layout: essay
type: essay
title: Coding Professionally
# All dates must be YYYY-MM-DD format!
date: 2020-02-12
labels:
  - Software Engineering
  - Coding Standards
---

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
function in a `FROM` clause. 

One of the above examples deals with code formatting. The other deals
 with program functionality; however, both can improve the readability of the written code.

### Why is Readability Important?
The readability of written code may be one of the most important things
in programming. Poorly formatted code causes problems; it can make
code difficult to understand to both co-workers and and the future self of the code's original author. Unreadable 
code makes debugging and adding functionality to existing code unnecessarily harder.

Having a standardized way of writing code allows others to understand
one's code faster and makes writing code easier--with a 
standardized set of formatting rules, a developer does not have to put
as much thought into writing pretty code. By just following the standards put into place, a developer can assume that their code will be readable.

