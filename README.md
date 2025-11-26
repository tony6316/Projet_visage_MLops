# Projet visage
## Projet MLOps
### Anthony Faizandier & Kylian Rouveure
### Master 2 Informatique parcours Architecture des données

![badge-python](https://img.shields.io/badge/Python-3.12-blue)

## 1. Objectif du projet
Développer une application web qui retourne toutes les images qui ont une ou des caractéristiques sélectionnées par l’utilisateur, parmi les suivantes :
- Pilosité : Barbe/Moustache/Rien
- Couleur cheveux/pilosité : blonds/châtains/roux/brun/gris-bleu
- Lunette : oui/non
- Taille cheveux : chauve/courts/longs

L'objectif est de concevoir une pipeline simple et automatisé à l'arrivé d'une nouvelle donnée. 
Voici les étapes qu'on doit couvrir :
- Prétraitement des images (croq et resize)
- Annotation comparaison Apache Stark
- CNN avec focntion d'activation et de perte
- Entrainement dans un notebook
- DVC
- Entrainement avec MLFLow


## 2. Architecture du projet
```bash
MLOps/
│
├── Data/
│   ├── Lot1/
│       ├── 01_0000.png
│       ├── 01_0001.png
│       └── ...
│
├── config.py                    # chemins principaux
│
├── traitement.py                # traitement des images (croc, resize 64x64)
├── annotation.py                # annotation des données 
│
├── multiprocess.py                      # doit permettre de voir 
├── test.py                      # doit permettre de voir 
│
├── requirements.txt             # dépendances
│
└── README.md
```

## 3. Organisation


## 4. Dataset


## 5. Déroulé des scripts

