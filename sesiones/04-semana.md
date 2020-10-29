# Cuarta semana, 27 de octubre

## Objetivos a cubrir en esta semana

1. Entender las claves del desarrollo basado en pruebas.
3. Comprender el paper fundamental de la infraestructura virtual en
   este proceso.
4. Entender cual es la estructura de los programas de test y cómo se
   pueden implementar en los diferentes lenguajes de programación.

## Otros objetivos

* Entender los errores comunes en el hito 1.
  * No enlazar la clase que se ha programado
  * La clase no tiene que tener *todos* los getters y setters...
  * ... y tienen que enlazar las HU.
  * La planificación tiene que ser explícita, no cada elemento por
    separado. 

* Entender la importancia de los flujos de trabajo en el desarrollo de software.

* Entender cómo encaja TDD dentro de la infraestructura virtual.

## Material para la clase

- [Desarrollo basado en tests](https:///jj.github.io/CC/documentos/proyecto/2.Tests),
  el segundo hito de la asignatura. Entrega del hito: 23:59 horas, 8
  de noviembre.


## Clase práctica, 28 de octubre

* Entender los errores comunes en el hito 1.
  * Sobre las clases:
    * No se muestra que la clase es sintácticamente correcta.
    * La clase no tiene que tener *todos* los getters y setters...
    * ... ni tampoco un par de ellos que te parezcan bien.
    * Ni se puede cerrar un issue de "crear clase" con un par de
    métodos. Ni debe haber un issue de "crear clase". Los issues son
    siempre qué es lo que uno quiere conseguir cuando se escriba el
    código.
    * Nadie usa enums.
    * Nadie declara exceptiones.
    * **NO** gestionéis autenticación, y menos con un "password"
      almacenado en texto plano o como sea. La autentiación se hace
      aparte.
    * No pongáis "logearse" (ni nada que sea una palabra correcta) en
      la aplicación. Conectarse a la aplicación es un servicios
      normalmente externo, no es algo que tengáis que incluir en la
      arquitectura ni en las clases definidas (a pesar de lo que os
      hayan hecho creer hasta ahora).
    * Las clases deberían de ser capaces de hacer algo aparte de
      almacenar datos. Si hacéis eso, es porque realmente *no* estáis
      siguiendo los requisitos del diseño y creando una entidad que
      pueda gestionar los datos. Estáis creando un objeto-valor.
  * Nadie muestra que es sintácticamente correcta la implementación
    doe la clase.
  * Sobre las "tecnologías elegidas":
    * Mucho cuidado con la combinación Node/Express. Como la ha
      escogido casi todo el mundo, los puntos de originalidad no están
      garantizados.
## Siguiente semana

[Quinta semana](05-semana.md)
