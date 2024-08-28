SELECT name, bonus 
<br>
FROM Employee
<br>
LEFT JOIN Bonus
<br>
ON Employee.empId = Bonus.empId
<br>
WHERE
<br>
bonus < 1000 OR bonus IS null;
