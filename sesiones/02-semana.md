# Segunda semana, 13 de octubre de 2020


## Objetivos a cubrir en esta semana

1. Comprender la metodología de desarrollo, prueba y despliegue en la que se basa la computación en nube.
2. Entender las características de las aplicaciones que se despliegan en la nube.

## Otros objetivos

* Entender los errores cometidos en el hito
  * Entender cómo se hace desarrollo colaborativo en git: resolver conflictos, sincronizar versiones...
  * Entender por qué no se hace `git pull` sino `git pull --rebase` y
  como arreglarlo en ese caso
  usando un squash commits con 
  [`git rebase -i`](https://stackoverflow.com/questions/5189560/squash-my-last-x-commits-together-using-git).
  * Ejemplo de arquitectura basada en eventos: [cliente Slack y Celery](https://github.com/JJ/slack-bot-platzi/blob/master/cliente-con-celery.py) + [servidor de tareas](https://github.com/JJ/slack-bot-platzi/blob/master/PlatziTareas.py).
  * Ejemplo adicional [Gateway](https://github.com/JJ/microservices-broker/blob/master/github-server/server-with-bunny.rb) + [worker](https://github.com/JJ/microservices-broker/blob/master/github-server/worker.go) + [procesador](https://github.com/JJ/microservices-broker/blob/master/github-server/procesa.py) + [store](https://github.com/JJ/microservices-broker/blob/master/github-server/store.p6).
* Entender que las arquitecturas basadas en microservicios necesitan servicios adicionales.
  * Configuración remota
  * Log
  
* Remarcar lo necesario para alcanzar el primer hito del proyecto de
  la asignatura.

* Manejar con soltura los diferentes recursos de línea de órdenes,
  especialmente en Linux.
  * Saber manejar la historia de comandos anteriores.
  * Configurar la línea de órdenes para presentar información de
    repos.
  * Conocer permisos y cuales usar en cada momento.
* Entender lo necesario para entregar el hito 0 del proyecto.

## Material para la clase

[Material del tema de desarrollo basado en pruebas](http://jj.github.io/CC/documentos/temas/Desarrollo_basado_en_pruebas)
y comenzar
con
[hito 1 del proyecto](http://jj.github.io/CC/documentos/proyecto/1.Infraestructura),
que se entrega el 27 de octubre de 2020.

## Siguiente semana

[Tercera semana, desde el 14 de octubre ](03-semana.md)
