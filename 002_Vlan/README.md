#VLAN Access

L' obiettivo di questo esercizio è stato di configurare una VLAN con l'utilizzo di più switch.
Per prima cosa abbiamo configurato gli indirizzi IP, collegato i PC e i relativi switch tra di loro, in particolare nella prima VLAN abbiamo
utilizzato una predisposizione di tipo access, il che ha comportato un di collegare i due switch tramite due cavi
crossed (uno per ogni VLAN).
Successivamente abbiamo configurato le VLAN e per verificare il loro corretto funzionamento abbiamo effettuato dei ping tramite cmd
sull'indirizzo di broadcast aspettandoci di ricevere risposta solo dai computer della stessa VLAN.

#VLAN Trunk

Il procedimento è analogo per le VLAN trunk, l'unica differenza e che nella configurazione della VLAN bisogna impostare la porta che collegano i
2 switch in modalità trunk, il che consente di utilizzare una sola porta per collegare gli switch.