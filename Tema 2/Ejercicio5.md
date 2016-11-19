## Ejercicio 5. Desplegar los fuentes de una aplicación cualquiera, propia o libre, que se encuentre en un servidor git público en la máquina virtual Azure (o una máquina virtual local) usando ansible.

En primer lugar instalamos en nuestra maquina ansible con la siguiente orden:

<pre>sudo apt-get install ansible</pre>

Ahora añadimos el host que tenemos creado en azure con el siguiente par de comandos:

![](./img/5.1)

Y vemos tambien como la máquina está añadida al fichero ansible.

![](./img/5.2)

Finalmente ejecutamos la orden

<pre>ansible azure -m git --ask-pass -u mortega87 -a "repo=https://github.com/mortega87/Desarrollo-de-aplicaciones-de-Internet.git dest=~/DAI version=HEAD"</pre>

Y ya tendremos el repositorio en nuestra máquina virtual.
