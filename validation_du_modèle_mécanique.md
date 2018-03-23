Modèle retenu : solution 2 PR précédente. \
--> Pas clair sur le nombre de moteurs/type de moteurs \
--> Certains modèles (moteurs roues traction) ne vont pas avec la modélisation

En tout :
- 8 moteurs pas à pas (traction, escalade des escaliers)
- 4 moteurs pour l'aspiration
- 2 à 4 capteurs de position initiale 

```diff
--> Il reste à corriger/identifier les modèles des moteurs à utiliser
```



Partie informatique :
- 2 cartes de type BB Blue (controleurs moteurs présents de base) où on branche tous les moteurs dédiés à la traction (qui demandent un asservissement).
- les 3 autres moteurs (aspiration) seront branchés sur batterie (pas de controle requis) et activés/désactivés avec I/O d'une des cartes BBB

```diff
--> Il faut faire un schéma technique / modélisation éléctronique du système
```
