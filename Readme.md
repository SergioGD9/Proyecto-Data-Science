# Práctica Abandono de Empleados

Lo primero es decir que este proyecto es obtenido en la web [DS4B](https://ds4b.teachable.com/) donde realmente se aprenden cosas muy interesantes, así que desde aquí mi agradecimiento.

Este proyecto se centra en el análisis del abandono de empleados. Utiliza un conjunto de datos que contiene información sobre los empleados y si han abandonado la empresa o no, y con ese análisis hacer un modelo predictivo de Machine Learning para poder solucionar el problema de la fuga de empleados. 

## Datos

El conjunto de datos `abandono_empleados.csv` contiene las siguientes columnas:

- `id`: Identificador único del empleado.
- `edad`: Edad del empleado.
- `departamento`: Departamento en el que trabaja el empleado.
- `salario`: Salario del empleado.
- `satisfaccion`: Nivel de satisfacción del empleado.
- `ultimo_evaluacion`: Resultado de la última evaluación del empleado.
- `proyecto`: Proyecto en el que está trabajando el empleado.
- `horas_trabajo`: Horas de trabajo del empleado por semana.
- `abandono`: Si el empleado ha abandonado la empresa o no.

## Requisitos

Para ejecutar los scripts de este proyecto, necesitarás las siguientes bibliotecas de Python:

- pandas
- sklearn
- openpyxl

Puedes instalar estas bibliotecas con pip:

```shell
pip install pandas sklearn openpyxl
