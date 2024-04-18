# GESTOR DE EMPLEADOS

Base de datos de empleados y sus departamentos usando MySQL

* Cardinalidad:

    - Un empleado puede solo puede estar asociado a un departamento. Empleado **1 : N** Departamento.
    - Un departamento puede tener muchos empleados. Departamento **1 : N** Empleado.

## Entidad Departamento
### Modelo lógico
![Descripcion Departamento](/images/desc_departamento.png)
### Datos
![Datos Departamento](/images/tabla_departamento.png)


## Entidad Empleado
### Modelo lógico
![Descripcion Empleado](/images/desc_empleado.png)
### Datos
![Datos Empleado](/images/tabla_empleado.png)


## Consultas sobre una tabla

1. Lista el primer apelldio de todos los empleados
![Primer punto](/images/punto_1.PNG)

2. Lista el primer apellido de los empleados eliminando los apellidos que estén repetidos.
![Segundo punto](/images/punto_2.PNG)

3. Lista todas las columnas de la tabla empleado.
![Tercer punto](/images/punto_3.PNG)

4. Lista el nombre y los apellidos de todos los empleados.
![Cuarto punto](/images/punto_4.PNG)

5. Lista el identificador de los departamentos de los empleados que aparecen en la tabla empleado.
![Quinto punto](/images/punto_5.PNG)

6. Lista el identificador de los departamentos de los empleados que aparecen en la tabla empleado, eliminando los identificadores que aparecen repetidos.
![Sexto punto](/images/punto_6.PNG)

7. Lista el nombre y apellidos de los empleados en una única columna.
![Séptimo punto](/images/punto_7.PNG)

8. Lista el nombre y apellidos de los empleados en una única columna, convirtiendo todos los caracteres en mayúscula.
![Octavo punto](/images/punto_8.PNG)

9. Lista el nombre y apellidos de los empleados en una única columna, convirtiendo todos los caracteres en minúscula.
![Noveno punto](/images/punto_9.PNG)

10. Lista el identificador de los empleados junto al nif, pero el nif deberá aparecer en dos columnas, una mostrará únicamente los dígitos del nif y la otra la letra.
![Decimo punto](/images/punto_10.PNG)

11. Lista el nombre de cada departamento y el valor del presupuesto actual del que dispone. Para calcular este dato tendrá que restar al valor del presupuesto inicial (columna presupuesto) los gastos que se han generado (columna gastos). Tenga en cuenta que en algunos casos pueden existir valores negativos. Utilice un alias apropiado para la nueva columna columna que está calculando.
![Onceavo punto](/images/punto_11.PNG)

12. Lista el nombre de los departamentos y el valor del presupuesto actual ordenado de forma ascendente.
![Punto Doce](/images/punto_12.PNG)

13. Lista el nombre de todos los departamentos ordenados de forma
ascendente.
![Punto Trece](/images/punto_13.PNG)

14. Lista el nombre de todos los departamentos ordenados de forma
descendente.
![Punto Catorce](/images/punto_14.PNG)

15. Lista los apellidos y el nombre de todos los empleados, ordenados de forma alfabética tendiendo en cuenta en primer lugar sus apellidos y luego su nombre.
![Punto Quince](/images/punto_15.PNG)

16. Devuelve una lista con el nombre y el presupuesto, de los 3 departamentos que tienen mayor presupuesto.
![Punto Dieciséis](/images/punto_16.PNG)

17. Devuelve una lista con el nombre y el presupuesto, de los 3 departamentos que tienen menor presupuesto.
![Punto Diecisiete](/images/punto_17.PNG)

18. Devuelve una lista con el nombre y el gasto, de los 2 departamentos que tienen mayor gasto.
![Punto Dieciocho](/images/punto_18.PNG)

19. Devuelve una lista con el nombre y el gasto, de los 2 departamentos que tienen menor gasto.
![Punto Dieciocho](/images/punto_19.PNG)

20. Devuelve una lista con 5 filas a partir de la tercera fila de la tabla empleado. La tercera fila se debe incluir en la respuesta. La respuesta debe incluir todas las columnas de la tabla empleado.
![Punto Veinte](/images/punto_20.PNG)

21. Devuelve una lista con el nombre de los departamentos y el presupuesto, de aquellos que tienen un presupuesto mayor o igual a 150000 euros.
![Punto VeinteUno](/images/punto_21.PNG)

22. Devuelve una lista con el nombre de los departamentos y el gasto, de aquellos que tienen menos de 5000 euros de gastos.
![Punto VeinteDos](/images/punto_22.PNG)

23. Devuelve una lista con el nombre de los departamentos y el presupuesto, de aquellos que tienen un presupuesto entre 100000 y 200000 euros. Sin utilizar el operador BETWEEN.
![Punto VeintiTres](/images/punto_23.PNG)

24. Devuelve una lista con el nombre de los departamentos que no tienen un presupuesto entre 100000 y 200000 euros. Sin utilizar el operador BETWEEN.
![Punto VeintiCuatro](/images/punto_24.PNG)

25. Devuelve una lista con el nombre de los departamentos que tienen un presupuesto entre 100000 y 200000 euros. Utilizando el operador BETWEEN.
![Punto VeintiCinco](/images/punto_25.PNG)

26. Devuelve una lista con el nombre de los departamentos que no tienen un presupuesto entre 100000 y 200000 euros. Utilizando el operador BETWEEN.
![Punto VeintiSéis](/images/punto_26.PNG)

27. Devuelve una lista con el nombre de los departamentos, gastos y presupuesto, de aquellos departamentos donde los gastos sean mayores que el presupuesto del que disponen.
![Punto VeintiSiete](/images/punto_27.PNG)

28. Devuelve una lista con el nombre de los departamentos, gastos y presupuesto, de aquellos departamentos donde los gastos sean menores que el presupuesto del que disponen.
![Punto VeintiOcho](/images/punto_28.PNG)

29. Devuelve una lista con el nombre de los departamentos, gastos y presupuesto, de aquellos departamentos donde los gastos sean iguales al presupuesto del que disponen.
![Punto VeintiNueve](/images/punto_29.PNG)

30. Lista todos los datos de los empleados cuyo segundo apellido sea NULL.
![Punto Treinta](/images/punto_30.PNG)

31. Lista todos los datos de los empleados cuyo segundo apellido no sea NULL.
![Punto TreintayUno](/images/punto_31.PNG)

32. Lista todos los datos de los empleados cuyo segundo apellido sea López.
![Punto TreintayDos](/images/punto_32.PNG)

33. Lista todos los datos de los empleados cuyo segundo apellido
sea Díaz o Moreno. Sin utilizar el operador IN.
![Punto TreintayTres](/images/punto_33.PNG)

34. Lista todos los datos de los empleados cuyo segundo apellido
sea Díaz o Moreno. Utilizando el operador IN.
![Punto TreintayCuatro](/images/punto_34.PNG)

35. Lista los nombres, apellidos y nif de los empleados que trabajan en el departamento 3.
![Punto TreintayCinco](/images/punto_35.PNG)

36. Lista los nombres, apellidos y nif de los empleados que trabajan en los departamentos 2, 4 o 5.
![Punto TreintaySeis](/images/punto_36.PNG)

## Consultas multitabla (Composición interna)

1. Devuelve un listado con los empleados y los datos de los departamentos
donde trabaja cada uno.
![Primer punto](/images/1.1_punto.png)

2. Devuelve un listado con los empleados y los datos de los departamentos
donde trabaja cada uno. Ordena el resultado, en primer lugar por el nombre
del departamento (en orden alfabético) y en segundo lugar por los apellidos
y el nombre de los empleados.
![Segundo punto](/images/2.1_punto.PNG)

3. Devuelve un listado con el identificador y el nombre del departamento,
solamente de aquellos departamentos que tienen empleados.
![Tercer punto](/images/3.1.PNG)

4. Devuelve un listado con el identificador, el nombre del departamento y el
valor del presupuesto actual del que dispone, solamente de aquellos
departamentos que tienen empleados. El valor del presupuesto actual lo
puede calcular restando al valor del presupuesto inicial
(columna presupuesto) el valor de los gastos que ha generado
(columna gastos).
![Cuarto punto](/images/4.1_punto.PNG)

5. Devuelve el nombre del departamento donde trabaja el empleado que tiene
el nif 38382980M.
![Quinto punto](/images/5.1_punto.PNG)

6. Devuelve el nombre del departamento donde trabaja el empleado Pepe Ruiz
Santana.
![Sexto punto](/images/6.1_punto.PNG)

7. Devuelve un listado con los datos de los empleados que trabajan en el
departamento de I+D. Ordena el resultado alfabéticamente.
![Septimo punto](/images/7.1.PNG)

8. Devuelve un listado con los datos de los empleados que trabajan en el
departamento de Sistemas, Contabilidad o I+D. Ordena el resultado
alfabéticamente.
![Octavo punto](/images/8.1_punto.PNG)

9. Devuelve una lista con el nombre de los empleados que tienen los
departamentos que no tienen un presupuesto entre 100000 y 200000 euros.
![Noveno punto](/images/9.1_punto.PNG)

10. Devuelve un listado con el nombre de los departamentos donde existe
algún empleado cuyo segundo apellido sea NULL. Tenga en cuenta que no
debe mostrar nombres de departamentos que estén repetidos.
![Decimo punto](/images/10.1_punto.PNG)

## Consultas multitabla (Composición externa)

1. Devuelve un listado con todos los empleados junto con los datos de los
departamentos donde trabajan. Este listado también debe incluir los
empleados que no tienen ningún departamento asociado.
![Primer punto](/images/1.2_punto.PNG)

2. Devuelve un listado donde sólo aparezcan aquellos empleados que no
tienen ningún departamento asociado.
![Primer punto](/images/2.2_punto.PNG)

3. Devuelve un listado donde sólo aparezcan aquellos departamentos que no
tienen ningún empleado asociado.
![Primer punto](/images/3.2_punto.PNG)

4. Devuelve un listado con todos los empleados junto con los datos de los
departamentos donde trabajan. El listado debe incluir los empleados que no
tienen ningún departamento asociado y los departamentos que no tienen
ningún empleado asociado. Ordene el listado alfabéticamente por el
nombre del departamento.
![Cuarto punto](/images/4.2_punto.PNG)

5. Devuelve un listado con los empleados que no tienen ningún departamento
asociado y los departamentos que no tienen ningún empleado asociado.
Ordene el listado alfabéticamente por el nombre del departamento.
![Quinto punto](/images/5.2_punto.PNG)


## Consultas resumen

1. Calcula la suma del presupuesto de todos los departamentos.
![Primer punto](/images/1_punto.PNG)

2. Calcula la media del presupuesto de todos los departamentos.
![Segundo punto](/images/2_punto.PNG)

3. Calcula el valor mínimo del presupuesto de todos los departamentos.
![Tercero punto](/images/3_punto.PNG)

4. Calcula el nombre del departamento y el presupuesto que tiene asignado,
del departamento con menor presupuesto.
![Cuarto punto](/images/4_punto.PNG)

5. Calcula el valor máximo del presupuesto de todos los departamentos.
![Quinto punto](/images/5_punto.PNG)

6. Calcula el nombre del departamento y el presupuesto que tiene asignado,
del departamento con mayor presupuesto.
![Sexto punto](/images/6_punto.PNG)

7. Calcula el número total de empleados que hay en la tabla empleado.
![Septimo punto](/images/7_punto.PNG)

8. Calcula el número de empleados que no tienen NULL en su segundo
apellido.
![Octavo punto](/images/8_punto.PNG)

9. Calcula el número de empleados que hay en cada departamento. Tienes que
devolver dos columnas, una con el nombre del departamento y otra con el
número de empleados que tiene asignados.
![Noveno punto](/images/9_punto.PNG)

10. Calcula el nombre de los departamentos que tienen más de 2 empleados. El
resultado debe tener dos columnas, una con el nombre del departamento y
otra con el número de empleados que tiene asignados.
![Decimo punto](/images/10_punto.PNG)


11. Calcula el número de empleados que trabajan en cada uno de los
departamentos. El resultado de esta consulta también tiene que incluir
aquellos departamentos que no tienen ningún empleado asociado.
![Onceavo punto](/images/11_punto.PNG)

12. Calcula el número de empleados que trabajan en cada unos de los
departamentos que tienen un presupuesto mayor a 200000 euros.
![Doceavo punto](/images/12_punto.PNG)
