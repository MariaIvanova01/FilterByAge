# FilterByAge

Write a program that reads an integer N on the first line. And on next N lines read pairs of "{name}, {age}". Then read three more lines:

•	Condition - "younger" or "older"

•	Age - Integer

•	Format - "name", "age" or "name age"

Depending on the condition, print the pairs in the right format.
Don’t use any built-in functionality. Write your methods.

Examples
----------

Input |	Output
------|--------
5 | Peter - 20
Peter, 20 | Maria - 29
George, 18 | Idan - 31
Maria, 29 |
Idan, 31 |
Simeon, 16 |
older |
20 |
name age |


Input |	Output
------|--------
5 | Peter
Peter, 20 | George
George, 18 | Simeon
Maria, 29 |
Idan, 31 |
Simeon, 16 |
younger |
20 |
name |

Input |	Output
------|--------
5 | 20
Peter, 20 | 18
George, 18 | 29
Maria, 29 | 31
Idan, 31 |16
Simeon, 16 |
younger |
50 |
age |

