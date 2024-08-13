# problemas
## problema 1

inicio

    leer numero_de_calificaciones
    definir contador= numero_de_calificaciones
    Definir suma_de_calificaciones=0
    definir promedio=0
   
    mientras el contador >0
        leer calificaciones
        suma_de_calificaciones=suma_de_calificaciones+calificaciones
        contador=contador-1
    fin mientras
    promedio=suma_de_calificaciones/numero_de_calificaciones
    
    si promedio>3.0
        print "usted aprobó"
    si no 
        print "usted reprobo"

fin


## problema 4

inicio

    xt(distancia total)=0
    xp(distancia parcial)=0
    leer v(velocidad)
    mientas v>0
        leer v
        leer t(tiempo)
    xp=v*t
    xt=xt+xp
    v=v-1
    fin mientras
    print xt
fin

## problema 6

INICIO

    Definir variables
            dia_actual(del mes), mes_actual, año_actual
            dia_naimiento, mes_nacimiento, año_nacimiento
        si mes_actual>mes_nacimiento
             edad=año_actual-año_nacimiento
        sino
             edad=año_actual-año_nacimiento-1
        print edad
    finsi

    si dia_actual=dia_naimiento, mes_actual=mes_nacimiento, año_actual=año_nacimiento
        print "feliz Cumpleañoz"
    finsi
fin
   

        

