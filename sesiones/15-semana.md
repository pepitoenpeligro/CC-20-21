# Semana décimo quinta, 25 de enero

## Objetivos de la asignatura

1. Entender los conceptos de medición de prestaciones... de nuevo.
- Aplicar a casos específicos los clústers de contenedores.

## Otros objetivos

- Ponerse al día en la entrega de hitos anteriores.
- [Entender los sistemas de configuración, incluyendo los interfaces comunes](http://jj.github.io/CC/documentos/temas/Configuracion_microservicios).
- [Repaso al concepto de REST](http://jj.github.io/CC/documentos/temas/REST) entender
  el concepto de recurso y cómo usarlo en este contexto. Algunos
  estados interesantes.
- Instalar consul, otro sistema de configuración distribuida.

## Laboratorio, 25 de enero
- Todavía se mantienen malas prácticas en el uso de issues y mensajes
  de commit.
- Entender errores frecuentes en microservicios.
    - Qué es
    el [middleware](http://jj.github.io/CC/documentos/temas/Microservicios.html#rutas-y-middleware) y
    como
    usarlo. Ver
    [este ejemplo actualizado](https://github.com/JJ/tests-python/blob/master/HitosIV/hugitos.py).
    - El API se organiza alrededor del [concepto de
      recurso](http://jj.github.io/CC/documentos/temas/Microservicios.html#rutas-y-middleware). Primero
      se decide qué recursos vamos a usar, luego se definen los
      prefijos de las rutas, luego las operaciones posibles.
      - Los códigos de estado son parte del API. En el diseño del API
      hay que incluirlos.
      - De vuelta con los códigos de
        estado. [Qué hay que devolver en un `delete`](https://stackoverflow.com/questions/2342579/http-status-code-for-update-and-delete).
        
## Laboratorio, 27 de enero

* [Vamos a trabajar con `consul`](http://jj.github.io/CC/documentos/temas/Configuracion_microservicios#consul) para
  usarlo como sistema de configuración distribuida.

## Plazos vigentes

El [sexto hito](http://jj.github.io/CC/documentos/proyecto/6.Compose)
se entregará el 4 de febrero, último día lectivo.

## Siguiente semana

[Décimo sexta semana](16-semana.md)

