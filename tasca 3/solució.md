![foto](img/captura1.jpg)


Primer he hagut de crear una nova màquina tal com es veu a la captura


![foto](img/2captura.jpg)

Seguidament a paràmetres, emmagatzematge, hauríem d'afegir el disk dur que en carlos ens ha proporcionat i col·locar-lo a dalt de tot.

![foto](img/3captura.jpg)

La configuració de la màquina es 8000 de placa mare.

![foto](img/4captura.jpg)

I a la part de processadors posem 2.

![foto](img/captura5.jpg)

Un cop configurada la màquina li donem a inicia i a la que et surti amb gran VIRTUALBOX mentres s'obre la màquina has de mantenir el shift i una lletra a la vegada i s’obrira aquest menú i apretem la primera opció. 

![foto](img/captura6.jpg)

Despres s’obrira aquest que em d’inicia la segona el (recovery mode). 

![foto](img/captura7.jpg)

I en aquesta part baixem a on posa “root” i li donem a acceptar.

![foto](img/captura8.jpg?

Un cop aquí hem de fer la comanda “passwd miquel” i et dirà que creeis una contrasenya amb 8 caràcters un cop creada ja pots continuar l'activitat

![foto](img/captura9.jpg)

Amb “control d” es torna obrir aquest menú i es la primera opció per continuar amb l’arrencada normal. 

![foto](img/captura10.jpg)

Reinicias la maquina tornas a entrar i has de posar aquesta comanda (mount -rw -o remount / ) 


FORTIFICAR L'ACCÉS AL GRUB:

Fem “sudo i” per entrar com a root

![foto](img/captura11.jpg)

Ara hem instal·lat al GRUB i li hem donat una contraseña. 

“copiem tot el hash desde grub fins al final de tot del hash” 

![foto(img/captura12.jpg)

Primer entrem a la terminal i farem un /backup de la carpeta home amb la comanda:
“sudo rsync -aAXv /home /root/home-backup-$(date +%F)/”

Ara crearem al fitxer-contenidor amb aquestes comandes:

sudo mkdir -p /root/secure-containers
cd /root/secure-containers


![foto](img/captura13.jpg)

![foto](img/captura14.jpg)

![foto](img/captura15.jpg)

![foto](img/captura16.jpg)

![foto](img/captura17.jpg)




