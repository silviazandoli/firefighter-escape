# firefighter-escape
## Descrizione del progetto
Si vuole progettare ed implementare un sistema composto da due robot autonomi ed eterogenei nell’ambito
della ricerca e soccorso di persone in situazioni di pericolo e in ambienti sconosciuti.
Come scenario si è scelta una casa che si immagina essere in fiamme che verrà simulata, in ARGoS, tracciando
il perimento dell’edificio.
I due robot hanno comportamenti diversi. In particolare:
• robot firefighter: ha il compito di esplorare l’ambiente per trovare il robot survivor.
• robot survivor: aspetta di essere soccorso.
Si immagina che il robot durante lo svolgimento del suo compito sia in grado di schivare le sorgenti luminose
ed eventuali ostacoli che incontrerà.

Si utilizzeranno tecniche di Reinforcement Learning, in particolare il Q-learning con la function approximation

## Installation
Prerequisites to run project:
- install Jupyter Notebook to run "Learning Analysis.ipynb"
- install argos3 from [ARGoS Website](https://www.argos-sim.info/index.php) to run robot controller.

## Run
```$ ./train-script.sh -f "environment.argos" -e <number_of_episode>```
