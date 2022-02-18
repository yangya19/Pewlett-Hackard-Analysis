# Pewlett-Hackard-Analysis

## 1. Overview of Project
Using SQL to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. The eligible employees should currently working for the company and were born between January 1, 1965 and December 31, 1965. 


## 2. Results
* Most retiring employees are at senior levels.
* Since only 2 managers are retiring from 9 departments, the managers are either young or some departments are missing managers.
* There are in total 1,549 employees eligible for the mentorship program (refer to: pic 'eligibility count')
* Employees who are eligible for mentorship program has 6 different titles: Assistant Engineer, Engineer, Senior Enigneer, Senior Staff, Staff, Technique Leader (refer to: pic 'mentorship eligibility titles')

## 3. Summary
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
According to the sum of counts for retiring_titles table, there are in total 72458 roles opening after these employees retired.

### Are there enough qualified, retirement-ready employees in the department to mentor the next generation of Pewlett Hackard employees?
The qualified employees were selected in mentorship_eligibility table, and total counts for eligible employees is 1549. Let's assume one employee could mentor 3 next generation of Pewlett Hackard employees. The total number that can be managed to mentor is 4647. Compare to retiring number of employees (72458) this is not enough for training the new employees.

