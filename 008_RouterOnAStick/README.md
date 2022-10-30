#Es 008 Inter VLAN routing: router on a stick

In questo esercizio l'obiettivo è quello di far comunicare tra di loro tutti i dispositivi della rete, nonostante appartengano a VLAN differenti tramite l'utilizzo di un router.
Per fare ciò nella prima versione della rete, abbiamo collegato uno degli switch  al router, utilizzando una singola interfaccia per tutte le VLAN della rete.
Una volta fatto ciò abbiamo proceduto alla configurazione del router tramite CLI. I comandi che abbiamo utilizzato sono: 

`en`

`configure terminal`

`interface fa (numero interfaccia).(numero VLAN)`

`encapsulation dot1q (numero VLAN)`

`ip address (indirizzo ip) (subnet mask)` (l'indirizzo deve appartenere alla VLAN)

`no shutdown`

`exit`

Riperetre la procedura per tutte le interfaccie.