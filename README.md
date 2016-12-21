# ejercicio1promedio

# Inicio: 

# Ingreso datos

- pago_semanal
- pago_hora
- horas_trabajadas
# Proceso

- Pedir horas_trabajadas
- Pedír pago_hora
- Multiplicar horas_trabajadas por pago_hora y almacenar en pago_semanal
- Mostrar resultado
# Fin #

# Inicio: 

# Ingreso datos

- puntosSquad
- maxPuntos
- porcentaje
# Proceso

- Pedir puntos
- Multiplicar puntos por 100 y almacenar en porcentaje
- Mostrar resultado

var puntos = puntosSquad/maxPuntos;
    var porcentaje = puntos*100;
    if (porcentaje >= 80){
        return "Muy bien squad!";
    }
    else {
        return "Pueden hacerlo mejor.";
    }
    

}


# Fin #

tu squad/equipo tiene como objetivo obtener al menos 80% de puntos en el siguiente ejrcicio.Escribe una funcion que de acuerdo a la cantidad de puntos que obtuvo en squad y la cantidad maxima de puntos disponible.Retorne el mensaje "Muy bien squad!" si pasaron o igualaron a 80% o "Pueden hacerlo mejor." si no pasaron pasaron alcanzaron el 80%.