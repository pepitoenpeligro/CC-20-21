# Undécima semana, 15 de diciembre

## Objetivo de esta semana

1. Entender los conceptos fundamentales de una arquitectura de
   microservicios.
2. Entender el concepto de *desacoplamiento* y lo que conlleva en el
   diseño de una aplicación.

## Otros objetivos

- [Rutas y middleware](http://jj.github.io/CC/documentos/temas/Microservicios.html),
  y cómo hacer el desacoplamiento de una y de otra.
- Entregar los hitos atrasados y ponerse al día.
- Entender errores frecuentes en el último hito
  - No cuidar el README.md
  - `.travis.yml` minimalistas sin tratar de testear diferentes
    versiones del lenguaje del que se trate.
    - O testeando versiones minor arbitrarias.
    - O testeando el mismo grupo de versiones que otro compañero/a.
  - Configuraciones innecesarias porque no se usan. Por ejemplo,
    definir un lenguaje para luego usar el contenedor Docker.
  - No redefinir (o no justificar) configuraciones por defecto que se
    lanzan siempre, como `install`
  - Usar fases inadecuadas (build: make test, por ejemplo).
  - Descargar en CI cosas que ya están descargadas en el contenedor
    docker.
  - Usar bases de datos.
  - Para tests el target es siempre `test`, no `tests`
  - ¿Para qué sirve `package-lock.json`?

## Práctica 16 de diciembre de 2020

- Antipatrones en HUs: usar un formato incorrecto, no incluir
  condiciones de satisfacción, o simplemente usar como tales 
  [lo que no lo es](https://github.com/cr13/RecetaCoctel/issues/5) [(más ejemplos)](https://github.com/Jumacasni/Terrake/issues/70). Vamos
  a
  [recordar qué es una HU](http://jj.github.io/CC/documentos/proyecto/1.Infraestructura),
  en particular aplicándolo al hito en el que estamos incursos.
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

## Material de esta semana

[Microservicios](http://jj.github.io/CC/documentos/temas/Microservicios.html) para
todo el mundo.

Se puede entregar ya
el
[quinto hito](http://jj.github.io/CC/documentos/proyecto/5.Microservicio.html),
con plazo hasta el **8 de enero**.

## Siguiente semana

[Duodécima semana](12-semana.md)
