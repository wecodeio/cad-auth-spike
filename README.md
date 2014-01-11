# cadence authentication spike

El objetivo de este spike es poder entender cuales son los parámetros mínimos de configuración para dar suficiente confianza al método de autenticación por medio de la cadencia de tipeo.

## Cómo funciona

Todos tipeamos con nuestro teclado, pero es bajo el nivel de colisión entre los que lo hacen del mismo modo. Si se detectase la forma de tipear de una persona, podría verificarse su autenticidad en forma biométrica (sin incurrir en costos ni riesgos adicionales).

La cadencia de tipeo es el ritmo con el que se lo hace. Al medir los tiempos en los que se presiona cada tecla puede tenerse una referencia de esta cadencia.

Efectuando una cantidad mínima de medidas sobre el tipeo de la misma palabra se puede conocer un promedio de tiempos, y las desviaciones estándar de esos tiempos.

## Limitaciones e interrogantes

* Es imposible proceder si el usuario tipea y se equivoca. Se debe volver a comenzar, ya que la muestra habría sido "contaminada".
* Es posible que se necesiten más datos para poder concretar la autenticación: los tiempos que las teclas están presionadas, el tiempo total, etc. Habrá que evolucionar conforme más pruebas.

## Sobre esta investigación

Esta investigación es de código abierto, por lo que se puede contribuír con ella de todos los modos conocidos.

## Más información y referencias

* [Firm uses typing cadence to finger unauthorized users](http://arstechnica.com/tech-policy/2010/02/firm-uses-typing-cadence-to-finger-unauthorized-users/)
* [Typing 'cadence' used to identify authorized database users, lock everyone else out](http://www.engadget.com/2010/02/20/typing-cadence-used-to-identify-authorized-database-users-loc/)
* [Could the cadence of your typing be used to identify you?](http://www.dvice.com/archives/2010/02/could_the_caden.php)

* [Habit ID](http://habitid.com/solution/)