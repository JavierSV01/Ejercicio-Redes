# Edificio A

Cada departameto tiene:

- Ochos oredenadores conectados mediante un switch con un servidor DHCP para todos los ordenadores.
- Un router que conecta con los demas departamentos y con los demas edificios incluyendo el edificio C con los diferentes servidores DNS y HTTP

## Deparatamento Economia
- Red interna:192.168.0.0
 - Red router : 10.0.0.0
- Gateway: 192.168.0.20
## Deparatamento Gestio del Pesonal
- Red interna:192.168.1.0
- Red router : 10.0.0.0 y 10.0.1.0
- Gateway: 192.168.1.20
## Deparatamento Finanzas
- Red interna:192.168.2.0
- Red router : 10.0.2.0 y 10.0.1.0
- Gateway: 192.168.2.20

# Edificio B
Cada departameto tiene:

- Ochos oredenadores conectados mediante un switch con un servidor DHCP para todos los ordenadores.
- Un router que conecta con los demas departamentos y con los demas edificios incluyendo el edificio C con los diferentes servidores DNS y HTTP
## Deparatamento Recursos Humanos
- Red interna:192.168.3.0
- Red router : 10.0.2.0 y 10.0.3.0
- Gateway: 192.168.3.20
## Deparatamento Sanidad
- Red interna:192.168.4.0
- Red router : 10.0.3.0 y 10.0.4.0
- Gateway: 192.168.4.20
## Deparatamento Biodiversidad
- Red interna:192.168.5.0
- Red router : 10.0.3.0 y 10.0.4.0
- Gateway: 192.168.5.20
# Edificio C

- Red interna:192.168.6.0
- Red router : 10.0.4.0 y 10.0.5.0
- Gateway: 192.168.5.20

## Servidores

Existen 6 servidores los cuales tienen un servicio HTTP cada uno y uno de ellos un servidor DNS
- Servicio DNS: 192.168.6.1
- Gateway: 192.168.20
DNSs:
- 192.168.6.1 www.economia. es
- 192.168.6.2 www.gestiondelpersonal. es
- 192.168.6.3 www.finanzas. es
- 192.168.6.4 www.recusoshumanos. es
- 192.168.6.5 www.sanidad. es
- 192.168.6.6 www.biodiversidad. es
