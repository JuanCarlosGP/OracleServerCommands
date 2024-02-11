# OracleServerCommands
#### Creamos servidor cloud en oracle (ubuntu) y nos conectamos por SSH (establecemos ip publica fija)
# Comandos usados
clear
-
sudo su
-
apt-get update
apt-get upgrade
-
Revisamos si esta instalada la librería screen para mantener el servidor abierto aunque no estemos conectados
-
Para cambiar configuración de firewall y privacidad de puertos 
apt install firewalld
firewall-cmd --permanent --zone=public --add-port={port}/{protocol}
