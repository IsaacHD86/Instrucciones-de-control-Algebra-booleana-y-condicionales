# Instrucciones-de-control-Algebra-booleana-y-condicionales
Algebra booleana y condicionales.

# Cálculo de Pago Semanal para Trabajadores

## Descripción
Este programa en Python calcula el total a pagar a un trabajador según el número de horas laboradas en una semana y su tarifa de pago por hora. 
Utiliza estructuras condicionales y pruebas lógicas para aplicar distintas tarifas dependiendo de las horas trabajadas. 
Además, el programa maneja errores en la entrada de datos mediante la sentencia `try/except`, asegurando un manejo robusto de posibles errores de usuario.

## Funcionamiento
El programa sigue estas reglas:
1. **Entrada**:
   - Solicita al usuario dos valores:
     1. Número de horas trabajadas en una semana.
     2. Tarifa de pago por hora.

2. **Cálculos**:
   - Si las **horas trabajadas** son menores o iguales a 40:
     - El pago es simplemente horas trabajadas multiplicado por la tarifa.
   - Si las **horas trabajadas** están entre 41 y 50:
     - El pago por las primeras 40 horas es a la tarifa normal.
     - Las horas adicionales (41 a 50) se pagan a una tarifa 10% mayor.
   - Si las **horas trabajadas** superan las 50:
     - El pago por las primeras 40 horas es a la tarifa normal.
     - Las horas entre 41 y 50 se pagan a una tarifa 10% mayor.
     - Las horas adicionales (más de 50) se pagan a una tarifa 20% mayor.

## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
