# B2 Réseau 2019 - TP3 CATALLO 

# 1. Mise en place des machines clients 

J'ai créé 3 VMs ( les clients) avec la configuration suivante : 

* Centos7 
* 10Go de Disque Dur
* 16 Mo de Mémoire Vidéo 

La première VM ( client1.lab1.tp3) a pour adresse ip : `10.1.1.1`

La deuxième VM ( client2.lab1.tp3) a pour adresse ip : `10.1.1.2`

La dernière VM ( client3.lab1.tp3) a pour adresse ip : `10.1.1.3`

Elles ont toutes les trois pour hostname : 'tp3' et parviennent a ping les unes avec les autres ( Youpi ) 

# 2. Configuration et Mise en  place des VLANs 

Sur GNS3, j'ai crée 2 Switchs ( SW1 & SW2 ). J'ai ensuite lancé le SW1, afin d'y créer un VLAN ( Le `vlan10`), que je connecte au port e0/0 du Switch et le port e0 du PC1.

Je fais la même chose avec le `vlan10` et le `PC2`

Je fais ensuite la mise en place du `TRUNK` entre le `SW1` et `Sw2`.

Je termine par mettre n place le VLAN entre le `SW2` et `PC3` 

PC1 : 10.10.10.11

PC2 : 10.10.10.12

PC3 : 10.10.10.13







