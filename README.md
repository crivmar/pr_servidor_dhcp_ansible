# pr_servidor_dhcp_ansible

## Práctica para hacer un playbook con Ansible que configure un servidor DHCP

## Escenario:

* Servidor DHCP: Conectada a una red por dhcp y con dos interfaces conectadas 
a dos redes aisladas distintas

* Cliente1: Conectada a la primera red privada.

* Cliente2: Conectada a la segunda red privada.

## Redes

* Red privada 1:  Reparte configuración en la red 192.168.100.0/24. El tiempo de concesión es de 12 horas.

* Red privada 2: Reparte configuración en la red 192.168.200.0/24. El tiempo de concesión es de 1 hora.

* DNS comunes: 1.1.1.1 y 1.0.0.1


