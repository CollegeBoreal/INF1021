# CICSO RIPv2 Basic Configuration Lab 

## Objectifs d'apprentissage:
```
Aprés avoir complété ce lab, vous serez capable de:
•	Cabler un réseau conformément au diagrame de topologie
•	Charger des scripts sur les routeurs
•	Observer le statut courrant du réseau
•	Configurer RIPv2 sur tous les routeurs.
•	Observer la sommarisation automatique des routes.
•	Observer la mise à jour des routages avec debug ip rip.
•	Annuler la sommarisation automatique des routes.
•	Observer le routage des tables.
•	Verifier la connectivité.
•	Documenter la configuration RIPv2.
```

## Scenario
```
Le réseau représenté dans le diagramme de topologie contient un réseau non contigu , 172.30.0.0 .
Ce réseau a été subnetté utilisant VLSM .
Les 172.30.0.0 sous-réseaux sont physiquement et logiquement divisés par au moins un autre réseau classful ou majeur, dans ce cas, les deux réseaux série 209.165.200.228/30 et 209.165.200.232/30. 
Cela peut être un problème lorsque le protocole de routage utilisé ne comprend pas suffisamment d'informations pour distinguer les sous-réseaux individuels . 
RIPv2 est un protocole de routage sans classe qui peut être utilisé pour fournir des informations de masque de sous-réseau dans les mises à jour de routage. 
Cela permettra à l'information de sous-réseau VLSM de se propager dans tout le réseau .
```
