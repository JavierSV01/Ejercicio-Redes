# Redes:

##  Red 1:

Tres subredes (VLSM), una que soporta 100 host, otra que soporta 30 y por último una para 6 host. 
La ultima subred con 6 host tiene la posibilidad de salir fuera y sus ip son:
* 192.168.0.161/29
* 192.168.0.162/29
* 192.168.0.163/29
* 192.168.0.164/29

##  Red 2:

Tiene 8 ordenadores con DHCP.

##  Red 3:

Tiene 4 ordenadores con DHCP.

## Red 4:

Tiene 4 ordenadores con IP fija, un punto de acceso inalambrico con 5 ordenadores que incluyen ip por DHCP.

Los ordenadores con IP fija tienen las direcciones:
* 192.168.3.20/24
* 192.168.3.21/24
* 192.168.3.22/24
* 192.168.3.23/24

## Red 5:

Tiene 5 ordenadores con IP fija las cuales son:
* 192.168.4.20/24
* 192.168.4.21/24
* 192.168.4.22/24
* 192.168.4.23/24
* 192.168.4.24/24

# Routers

Se han configurado una serie de router para conectar las redes 2, 3, 4, 5 y una de las subredes de la 1. Ademas estan conectados a los servidores

# Servidores

Tenemos una serie de servidores en los que uno de ellos tiene un servicio DNS y HTTP y otros dos con solamente un servicio HTTP. 
Todas las paginas son accesibles desde las redes con acceso mediante los diferentes routers.

Los dns son www.albacete. es, www.wagner. es www.dilar. es