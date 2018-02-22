# Mémo

### Liens utiles
- https://github.com/brunoluiz/bbb-preempt-rt-kernel-patch
- https://beagleboard.org/latest-images

### Quelle carte ?
Il faut beaucoup de I/O --> BeagleBone (voir la gamme de produits).

### OS
OS nécessaire car :
- interaction rapide avec le materiel complexe (differents capteurs, besoin de taches s'exécutant en fond).
- prototypage rapide.

### Quel OS
Distribution Linux.
--> Debian (actuel avec version 9.3 ?)

Si contraintes temps réel --> patcher le noyau Linux avec PREEMPT_RT.

# Définir le cadre de la PR
