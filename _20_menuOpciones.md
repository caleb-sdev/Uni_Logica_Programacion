Algoritmo MenuOperacion
    Imprimir 'Proporcione un numero1'
    Leer numero1
    Imprimir 'Proporcione un numero2'
    Leer numero2

    Imprimir 'Seleccione una opcion del menu: '
    Imprimir '1. Sumar'
    Imprimir '2. Restar'
    Imprimir '3. Multiplicar'
    Imprimir '4. Dividir'
    Imprimir '5. Salir'
    
    Leer seleccion

    Si seleccion == 1
        Imprimir 'La suma es ', numero1 + numero2
        Sino
            Si seleccion == 2
                Imprimir 'La resta es: ', numero1 - numero2
                Sino
                    Si seleccion == 3
                        Imprimir 'La division es: ', numero1 * numero2
                        Sino
                            Si seleccion == 4
                                Imprimir 'La division es: ', numero1 / numero2
                                Sino
                                    Si seleccion == 5
                                        Imprimir 'Saliste'
                                    Sino
                                        Imprimir 'no es una opcion'
                                    FinSi
                                FinSi
                        FinSi
                FinSi
        FinSi
FinAlgoritmo                                               