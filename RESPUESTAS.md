# Preguntas: ¿qué archivo contiene la regla de cálculo? ¿Qué archivo define la ruta HTTP? ¿En qué se diferencian sus responsabilidades?

El archivo que contiene las reglas de calculo es precios.ts,el que define la ruta HTTP es server.ts.
Se diferencia en que el server.ts solo define el puerto que se utiliza para comunicarse con la demo y precios.ts se encarga de recibir 2 parametros un precio y un porcentaje de descuento y realiza el calculo para sacar dicho descuento.


# Leé la prueba que contiene calcularPrecioFinal(1000, 150). ¿Qué comportamiento exige? ¿Qué hace realmente el código? Todavía no modifiques la implementación.

Exige que al hacer dicho calculo lance un error,El codigo directamente no lo hace solo falla.

# Respondé antes de continuar:  ¿Qué total devuelve actualmente un descuento del 150 % sobre $1.000? ¿Por qué ese resultado no cumple la regla de negocio? ¿Por qué la prueba falla si la función terminó de ejecutarse?

Actualmente un descuento del 150 % sobre $1000 devuelve un resultado de -500, porque esta dice que rechace todo descuento por encima del 100 %,Poque la funcion no valida el caso de que el descuento sea mayor al permitido.

