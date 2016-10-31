## Ejercicio 1. Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?

La aplicación que voy a utilizar como ejemplo se trata de una aplicación web propia, llamada MusicShop. Esta aplicación utiliza una arquitectura Microkernel, ya que es monolítica y todas las funcionalidades están en la misma máquina.

Para esta aplicación poder evolucionar a una arquitectura microservicios, deberiamos independizar distintas funcionalidades, por tanto deberiamos reestructurar los servicios ofrecidos de forma que sean independietes, usando alguna tecnología como, por ejemplo, un API REST.
