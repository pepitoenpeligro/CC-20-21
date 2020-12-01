# Novena semana, 1 de diciembre


## Objetivos a cubrir en esta semana

1. Entender la arquitectura en capas de los microservicios usados en
   despliegues modernos.
3. Comprender el paper fundamental de la infraestructura virtual en
   este proceso.
1. Comprender el tipo de aplicaciones que se despliegan en la nube.
1. Entender el papel de los contenedores en la infraestructura virtual.
2. Comprender los procesos de definición de contenedores.

## Otros objetivos

- Errores *hito 2*:
  - No se explica la configuración de la herramienta de gestión de
    tareas, que es lo que se pedía. Ni siquiera se hace bien en la
    mayoría de los casos. No se usan reglas, ni plugins, ni
    configuraciones por omisión ni conexión entre objetivos (por
    ejemplo, build y test).
  - No uso o uso incorrecto de fixups o setups.
- Errores frecuentes *hito 3*:
  - Se dijo explícitamente que no se hiciera la comparación mínima
    lenguaje, lenguaje-slim, lenguaje-alpine, porque iba a ganar
    alpine. Pero es que si ni siquiera se hace la comparación con
    alpine, es peor todavía.
  - El README es el de un proyecto. Acumular cosas de diferentes hitos
    sin orden y sin que explique lo que hace el proyecto, no
    corresponde a lo que se pide.
  - Algunos habéis puesto que está deshabilitado la reconstrucción
    para imagen base, con lo que una de las ventajas de usar Docker
    Hub la estáis eliminando. Mirad por favor qué significa cada cosa.
  - Por supuesto, hay que usar el usuarion sin privilegios, no sólo
    definirlo.

## Material para la clase

* *Teoría*: Empezamos con el siguiente tema,
  [sobre uso de microservicios](http://jj.github.io/CC/documentos/temas/Microservicios).
