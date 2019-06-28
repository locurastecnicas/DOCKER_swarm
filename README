# Docker Swarm

Este repositorio contiene todos los scripts, configuraciones y playbooks de Ansible necesarios para desplegar un swarm de Docker.

* La configuracion se realiza sobre un grupo de 4 nodos virtuales con 2 tarjetas de red.
 * Cada host tiene una tarjeta de red para el trafico del swarm entre los nodos - interfaz CLUSTER.
 * Cada host tiene una tarjeta de red para el trafico de datos de los contenedores - interfaz SERVICIO.

Los playbooks incluyen ahora la variable hostsgroup para indicar sobre que grupo de hosts o host individual debe lanzarse
el playbook. Para ello el comando a utilizar es:

```
 ansible-playbook --extra-vars "hostsgroup=Nombre_de_host_o_grupo" Nombre_del_playbook
```

