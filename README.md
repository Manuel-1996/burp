# RETA
RETA is a system python base that use ansbile for recheck automation
## Prerequisites
Operating System = Ubuntu
You need to have python and pip installed.
version:
* Python 3.8.5
* pip 20.0.2 
## Description
[Fai sapere alle persone cosa può fare nello specifico il tuo progetto. Fornisci il contesto e aggiungi un collegamento a qualsiasi riferimento con cui i visitatori potrebbero non avere familiarità. È inoltre possibile aggiungere qui un elenco di funzionalità ]

## Badges
[aggiungere immagini tramite Shields : http://shields.io/]
## Visuals
[A seconda di ciò che stai realizzando, può essere una buona idea includere screenshot]
## Installation
[All'interno di un particolare ecosistema, potrebbe esserci un modo comune di installare cose, come l'utilizzo di Yarn, NuGet o Homebrew. Tuttavia, considera la possibilità che chiunque stia leggendo il tuo README sia un principiante e desideri ulteriori indicazioni. Elencare passaggi specifici aiuta a rimuovere l'ambiguità e induce le persone a utilizzare il tuo progetto il più rapidamente possibile. Se viene eseguito solo in un contesto specifico come una particolare versione del linguaggio di programmazione o sistema operativo o ha dipendenze che devono essere installate manualmente, aggiungere anche una sottosezione Requisiti.]


* Create a new enviroment in root directory:
```python
sudo apt-get install python3-virtualenv
virtualenv myenv
source myenv/bin/activate
pip install -r requirements.txt
```
## Usage
 [Usa gli esempi liberamente e mostra l'output atteso se puoi. È utile avere in linea il più piccolo esempio di utilizzo che puoi dimostrare, fornendo al contempo collegamenti ad esempi più sofisticati se sono troppo lunghi per essere ragionevolmente inclusi nel README.]
* Avviare l'ambiente di TEST
 ```python
cd docker_compose_test
docker-compose up
```
* convertire le sessioni in ricette
```python
cd RETA_DATA_CONVERTIRE
python from_json_to_yaml.py
```
* rieffettuare i passi di quella sessione
```python
cd RETA_TARGET_CONTEXT_MODULE
ansible-playbook users.yaml
```
## Support
[Spiega alle persone dove possono rivolgersi per chiedere aiuto.]
## Roadmap
[Se hai idee per le versioni future, è una buona idea elencarle nel README.]
## Contributing
[Per le persone che desiderano apportare modifiche al proprio progetto, è utile disporre di documentazione su come iniziare.]
## Authors and acknowledgment

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Project status