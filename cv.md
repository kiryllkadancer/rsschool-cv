## Kiryl Buyak
### Contacts:
**Phone:** +375257285180  
**E-mail:** karal.icecream@gmail.com  
**Telegram:** kirillkadancer

*********

### Something about me:
...

*********

### Skills:
* Python
* Postgresql
* Git, Github
* HTML, CSS
* Datagrip, Pycharm, VS Code

*********

### Code example:
Problems 184. Department Highest Salary from leetcode
```
SELECT d.name AS Department, e.name AS Employee, m.max_salary AS Salary
FROM Department AS d
JOIN (SELECT MAX(salary) AS max_salary, departmentid FROM Employee GROUP BY departmentid) AS m
    ON d.id = m.departmentid
JOIN Employee as e
    ON e.salary = m.max_salary AND e.departmentid = m.departmentid
```

*********

### Languages:
* Russian - Native
* Belarussian - Intermediate
* English - Pre-intermediate