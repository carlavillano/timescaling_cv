WSOLA_CV - README
=================

Questo progetto contiene una app matlab in grado di processare file speech 
col metodo WSOLA.

Il codice è basato sull’implementazione presente sul File Exchange della community MathWorks, all’URL

https://it.mathworks.com/matlabcentral/fileexchange/45451-waveform-similarity-and-overlap-add--wsola--for-speech-and-audio

Il codice è stato modificato:

- per correggere piccoli problemi dell’interfaccia grafica
- per dare la possibilità di scegliere una directory contenente il file
  speech da processare senza accedere al repository MatWorks
- per consentire il salvataggio del file speech processato con un file name
  contenente indicazioni sui parametri usati per il WSOLA processing
- per misurare il tempo di elaborazione (CPU time) necessario per processare il singolo file   
  speech 

Per installare in MatLab la app basta cliccarci sopra. E’ necessaria semplicemente una versione di MatLab >= R2012b (la versione che ha introdotto le apps). E’ inoltre presente qui la licenza originaria e un file pdf che descrive il procedimento adoperato per il processing. Rimandando a tale documento per l’uso guidato dell’applicazione (peraltro dotata di interfaccia grafica estremamente intuitiva), si fa semplicemente presente che, lanciata l’app, si può procedere alla scelta della directory contenente i file speech e successivamente del file, o registrare alcuni secondi di parlato da microfono. A questo punto si potrà lanciare il processing, dopo una opportuna scelta dei parametri. Il file risultato viene salvato nella stessa directory del file originario, e quindi riprodotto.




Carla Villano, 8/1/2017