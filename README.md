1. Nombre, apellido y fecha de nacimiento de todos los empleados, ordenado por fecha de nacimiento ascendente.

__SELECT nombre, apellido, fecha_nacimiento FROM PROFESOR order by fecha_nacimiento__

2. Todos los profesores cuyo salario sea mayor o igual a 65000.

__SELECT * FROM PROFESOR WHERE salario >= 65000__

3. Todos los profesores que nacieron en la década del 80.

__SELECT * FROM PROFESOR WHERE fecha_nacimiento BETWEEN '1980-01-01' AND '1990-01-01'__

4. 5 registros.

__SELECT * FROM PROFESOR LIMIT 5__

5. Todos los profesores cuyo apellido inicie con la letra “P”.

__SELECT * FROM PROFESOR WHERE apellido LIKE 'P%'__

6. Los profesores que nacieron en la década del 80 y tienen un salario mayor a 80000.

__SELECT * FROM PROFESOR WHERE fecha_nacimiento > '1980-01-01' AND salario > 80000__
