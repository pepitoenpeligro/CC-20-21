# Quinta semana, 3 de noviembre

## Objetivos a cubrir en esta semana

1. Entender las claves del desarrollo basado en pruebas.
3. Comprender el paper fundamental de la infraestructura virtual en
   este proceso.
4. Entender cual es la estructura de los programas de test y cómo se
   pueden implementar en los diferentes lenguajes de programación.

## Otros objetivos

* Entender los errores comunes en el hito 1, como [se vieron en la
  clase práctica](04-semana.md). Adicionalmente:
  * Uno no debe añadir a una clase o módulo lo que se ocurra
    "inspirado" por lo que pone en una HU. Por ejemplo, si no hay
    ninguna HU que diga que se puede borrar algo, no se puede añadir
    una función para hacerlo. Las clases en conjunto no son lo que se
    debe añadir refiriendo a las HU, es la funcionalidad específica.
        * Por
          ejemplo,
          [en este caso](https://github.com/Jumacasni/Terrake/blob/main/src/controlador.go) se
          deberían haber creado issues específicos para las
          funcionalidades que se han añadido, y no ponerse lo de
          borrar. Realmente no parece que haya ninguna relación entre
          una y otra, porque la acción principal (consultar) no
          aparece ningún sitio, ni se justifica la elección de la
          estructura de datos (un array) por la
          consulta. Específicamente se deben evitar mensajes de commit
          repetitivos y que no añadan nada. Ya se sabe que se ha
          creado un fichero. Lo que tienes que explicar es cómo y por
          qué lo has creado de esta forma y no de otra.
  * Los mensajes de commit son la documentación de un cambio. Deben
    cuidarse, justificarse por qué se ha hecho así, y todo lo
    necesaroi para entenderlo.
  

## Material para la clase


## Siguiente semana

[Sexta semana](06-semana.md)
