# Tesi di laurea triennale:
### Analisi di soluzioni di motion control per azionamenti BLDC nel progetto AlmaX

All'interno del repository sono inclusi tutti i documenti utilizzati per lo sviluppo del motion control dei motori BLDC dedicati alla trazione del rover Alma-X.
È inclusa inoltre tutta la documentazione citata nel documento.
#### Capitolo 1

Nel primo capitolo si analizzano i componenti hardware che fanno parte del motion control del Rover: motore, drive, adattatori e alimentatori.

Si mostra inoltre il corretto cablaggio degli adattatori che permettono la comunicazione con il drive da parte del computer di bordo, oltre ai connettori di potenza e di feedback del motore.

#### Capitolo 2

Il secondo capitolo è dedicato ad una introduzione a ROS e CANopen: il primo, un middleware specifico per la robotica, il secondo, uno standard di comunicazione necessario a gestire il drive.

La prima sezione è dedicata a ROS e ai suoi componenti: master, nodi, messaggi e topics. Come ROS li utilizza per permettere la comunicazione tra macchine differenti e per ampliare le sue capacità con strumenti e librerie esterne.

La seconda sezione è dedicata a al bus CAN, attraverso il quale il protocollo CANopen(terza sezione) muove pacchetti di informazione (PDO ed SDO) attraverso i diversi nodi che fanno parte del sistema di motion control. 

#### Capitolo 3

Nel terzo capitolo si elencano i diversi strumenti utilizzati nei successivi tentativi di comunicare con il drive, partendo da quelli a livello più basso, fino ad arrivare ai due candidati più promettenti (due librerie di ROS: ros_canopen e Kacanopen) che possono eseguire il bridging tra messaggi ROS e frame CANopen.
