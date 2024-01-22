Q.3.1 Quel est le matériel réseau A ?
Quel est son rôle sur ce schéma vis-à-vis des ordinateurs ?

Q.3.2 Quel est le matériel réseau B ?
Quel est son rôle pour le réseau 10.10.0.0/16 ?

Q.3.3 Que signifie f0/0 et g1/0 sur l’élément B ?

Q.3.4 Pour l'ordinateur PC2, que représente /16 dans son adresse IP ?

Q.3.5 Pour ce même ordinateur, que représente l'adresse 10.10.255.254 ?

Q.3.6 Pour les ordinateur PC1, PC2, et PC5 donne :

L'adresse de réseau
La première adresse disponible
La dernière adresse disponible
L'adresse de diffusion
Q.3.7 En t'aidant des informations que tu as fourni à la question 3.6, et à l'aide de tes connaissances, indique parmi tous les ordinateurs du schéma, lesquels vont pouvoir communiquer entre-eux.

Q.3.8 De même, indique ceux qui vont pouvoir atteindre le réseau 172.16.5.0/24.

Q.3.9 Quel incidence y-a-t'il pour les ordinateurs PC2 et PC3 si on interverti leur ports de connexion sur le matériel A ?

Q.3.10 On souhaite mettre la configuration IP des ordinateurs en dynamique. Quelles sont les modifications possible ?
Fichier 1 :

Q.3.11 Sur le paquet N°5, quelle est l'adresse mac du matériel qui initialise la communication ? Déduis-en le nom du matériel.

adresse mac 00 50 79 66 68 00
Il s'agit du PC1

Q.3.12 Est-ce que la communication enregistrée dans cette capture a réussi ? Si oui, indique entre quels matériel, si non indique pourquoi cela n'a pas fonctionné.
oui entre (00:50:79:66:68:00) et (00:50:79:66:68:03) . Entre PC1 et PC4

Q.3.13 Dans cette capture, à quel matériel correspond le request et le reply ? Donne le nom, l'adresse IP, et l'adresse mac de chaque materiel.
Ethernet II, Src: Private_66:68:00 (00:50:79:66:68:00), Dst: Private_66:68:03 (00:50:79:66:68:03)

Q.3.14 Dans le paquet N°2, quel est le protocole encapsulé ? Quel est son rôle ?

protocol ARP qui permet qui permet de retrouver un adresse MAC à partir d'une adresse IP

Q.3.15 Quels ont été les rôles des matériels A et B dans cette communication ?


Fichier 2 :

Q.3.16 Dans cette trame, qui initialise la communication ? Donne l'adresse IP ainsi que le nom du matériel.
initialisation de la communication ->  IP 10.10.80.3  MAC Source: (00:50:79:66:68:02) 


Q.3.17 Quel est le protocole encapsulé ? Quel est son rôle ?
Protocol de PING ICMP qui permet de diagnostiquer les problèmes de communication du réseau.

Q.3.18 Est-ce que cette communication a réussi ? Si oui, indique entre quels matériel, si non indique pourquoi cela n'a pas fonctionné.

Non. nous avons les messages d'erreur "no response found" et "host unreachable"

Q.3.19 Explique la ligne du paquet N° 2

Q.3.20 Quels ont été les rôles des matériels A et B ?
Internet Protocol Version 4, Src: 10.10.80.3, Dst: 10.11.80.2

Fichier 3 :

Q.3.21 Dans cette trame, donne les noms et les adresses IP des matériels sources et destination.
PC4 / ROUTEUR 
Q.3.22 Quelles sont les adresses mac source et destination ? Qu'en déduis-tu ?

Q.3.23 A quel emplacement du réseau a été enregistré cette communication ?
