# Undécima semana, 15 de diciembre

## Objetivo de esta semana


## Otros objetivos

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


## Material de esta semana

[Microservicios](http://jj.github.io/CC/documentos/temas/Microservicios.html) para
todo el mundo.

Se puede entregar ya
el
[quinto hito](http://jj.github.io/CC/documentos/proyecto/5.Microservicio.html),
con plazo hasta el **8 de enero**.

## Siguiente semana

[Duodécima semana](12-semana.md)
