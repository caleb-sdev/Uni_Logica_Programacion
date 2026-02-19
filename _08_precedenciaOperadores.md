/*
Prioridad de ejecucion de los operadores
    1. Parentesis ()
    2. Potencia ^
    3. Multiplicacion, Divison o Modulo
    4. Suma y Resta
    5. Operadores Relacionales
    6. Operadores Logicos
*/

Algoritmo PrecedenciaDeOperadores
    a = 12 / 3 + 2 * 3 - 1

    Imprimir 'Resultado a evaluar', a
FinAlgoritmo

/*
    1. Division 12 / 3 = 4
    2. Multiplicacion 2 * 3 = 6
    3. Suma 4 + 6 = 10
    4. Resta 10 - 1 = 9
*/