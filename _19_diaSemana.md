Algoritmo EjercicioDiaSemana
    Imprimir 'Proporciona el dia de la semana'
    Leer dia_semana

    Si dia_semana == 1 Entonces
        Imprimir 'Lunes'
    Sino
        Si dia_semana == 2 Entonces
            Imprimir 'Martes'
        Sino
            Si dia_semana == 3 Entonces
                Imprimir 'Miercoles'
            Sino
                Si dia_semana = 4 Entonces
                    Imprimir 'Jueves'
                Sino 
                    Si dia_semana == 5 Entonces
                        Imprimir 'Viernes'
                    Sino
                        Si dia_semana == 6 Entonces
                            Imprimir 'Sabado'
                        Sino
                            Si dia_semana == 7 Entonces
                                Imprimir 'Domingo'
                            Sino    
                                Imprimir 'Valor de dia erroneo: ', dia_semana
                            FinSi
                        FinSi
                    FinSi
                FinSi
            FinSi
        FinSi                        
    FinSi
FinAlgoritmo                                             


Algoritmo EstructuraSegunDiaSemana
    Imprimir 'Propone el dia de la semana '
    Leer dia_semana

    Segun dia_semana Hacer
        1 : Imprimir 'Lunes'
        2 : Imprimir 'Martes'
        3 : Imprimir 'Miercoles'
        4 : Imprimir 'Jueves'
        5 : Imprimir 'Vieres'
        6 : Imprimir 'Sabado'
        7 : Imprimir 'Domingo'
        De Otro Modo:
            Imprimir 'Valor erroneo: ', dia_semana
    FinSegun
FinAlgoritmo            