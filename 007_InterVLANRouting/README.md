#Es 007 Inter VLAN routing

In questo esercizio l'obiettivo è quello di far comunicare tra di loro tutti i dispositivi della rete, nonostante appartengano a VLAN differenti tramite l'utilizzo di un router.
Per fare ciò nella prima versione della rete, abbiamo collegato uno degli switch  al router, utilizzando un interfaccia per ogni VLAN.
Una volta fatto ciò abbiamo proceduto alla configurazione del router tramite CLI. I comandi che abbiamo utilizzato sono: 

`en`

`configure terminal`

`interface fa (numero interfaccia).(numero VLAN)`

`encapsulation dot1q (numero VLAN)`

`ip address (indirizzo ip) (subnet mask)` (l'indirizzo deve appartenere alla VLAN)

`no shutdown`

`exit`

Riperetre la procedura per tutte le interfaccie.

Nella seconda versione della rete, abbiamo utilizzto la tecnica del "router on a stick", metodo che permette di utilizzare una singola interfaccia per far comunicare le varie VLAN. Tenere a mente che la prota dello switch deve essere in modalità trunk.
Il procedimento e i comandi sono analoghi a quanto descritto in precedenza.