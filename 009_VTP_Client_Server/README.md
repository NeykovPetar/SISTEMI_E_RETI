#Es 009 VTP Client Server

In questo esercizio l'obiettivo è quello di configurare gli switch della rete (client / server) della rete tramite CLI. 
Una volat acollegati i vari dispositivi, associato loro i rispettivi indirizzi IP e configurato le VLAN, abbiamo configurato gli switch client e server tramite i seguenti comandi:

Configurazione Switch(Server):

`en` 
`conf t` 
`vtp mode server`
`vtp domain (nome domain)`
`vtp password (nome password)`


Configurazione Switch(Client):

`en`
`conf t`
`vtp mode client`
`vtp domain (nome domain)`
`vtp password (nome password)`