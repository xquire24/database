The image is a model of a database of an organisation, with departments and project. Below are the queries that could be run

INSERT INTO departments (department_id, department_name) 2 VALUES (1010,'Collections'); this inserts two values into the department id and department name folder respectively.

SELECT * employee_id, first_name from employees; this selects all the first name and id from the employees table

UPDATE employees SET lastname='' WHERE id=''; this query updates the last name of a particular employee id 


DELETE FROM organisations WHERE id='' this deletes a particular data with the specified id in the organisations table

DROP TABLE teams; this deletes an entire table
