# Duodécima semana, 22 de diciembre

Última semana del año.


## Objetivos adicionales:

- Cómo *no* almacenar los datos
  y
  [buscar en los mismos](https://github.com/cr13/RecetaCoctel/commit/63d2eb140a75d5993ab8ba3a3e8670a0a9b3d932).

- Cómo tratar con APIs externos. En una palabra: desacoplar.
  - Hacer un API que llame a otro API no deja de ser un antipatrón, y
    no tiene valor añadido.
    - Si se quiere hacer de todas formas, hay que abstraer el API
      externo con una capa que lo adapte al propio lenguaje y
      aplicación. Adicionalmente, tener mecanismos como cachés
      intermedias u otros mecanismos que ahorren peticiones con una
      latencia desconocida y variable.
- Entender los diferentes modos de acceso de una aplicación y en
  especial el acceso a la lógica de negocio. En particular, no todo lo
  que haga el backend debe ir al API externo. Dado que se va a
  trabajar con una "single source of truth", puede haber diferentes
  "aplicaciones" que trabajen frente a esa SSOT. Por ejemplo, uno que
  lo "pueble" y otro que lo sirva.
  - Tener en cuenta los ritmos de variación y sobre todo los roles de
    cada uno de ellos.
- Errores frecuentes en el 4º hito
  - Entender por qué se usa CI para testear versiones diferentes de un
    lenguaje.
  - Características poco (o nada) usadas:
    - Caché
    - Matrix

## Material de esta semana

[Microservicios](http://jj.github.io/CC/documentos/temas/Microservicios.html) para
todo el mundo.

Se puede entregar ya
el
[quinto hito](http://jj.github.io/CC/documentos/proyecto/5.Microservicio.html),
con plazo hasta el **8 de enero**.

## Siguiente semana

[Décimo tercera semana](13-semana.md)
