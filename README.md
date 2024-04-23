--levantar rabbit
C:\Program Files\RabbitMQ Server\rabbitmq_server-3.12.8\sbin

ejecuto en cmd ADMINISTRADOR -- rabbitmq-plugins.bat enable rabbitmq_management

luego ejecutar rabbitmq-service (en el mismo path de antes) , ir abrowser  http://localhost:15672/ y user-pass guest-guest-g


TAG v.0.1.0
section 3

7. Publishing Message To Queue
crear queue desde rabbitUI(QUEUES), ejecutar Publisher class, y ver en la UI el message desde tal queue.

8. Consuming Message From Queue
9. 

0.0.2

9. Multiple Consumers Scenario & Round Robin Fashion

0.0.4

Section 4: Real Time Example With JSON Message

12. Publishing JSON Message To Queue

Se agrego dependencia org.json y se creo CLase RealTimeExample.

Prueba:
la misma, levantar rabbit , ejecutar clase RealTimeExplorer y luego Consumer


0.5.0
Section 5 - Direct Exchange

DirectConsumer  -ojo con parametros queue
DirectPublisher - ojo con los parametros exchange y queue

Pruebas- la misma.