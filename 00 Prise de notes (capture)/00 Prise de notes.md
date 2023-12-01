---
up:
  - "[[Accueil]]"
---
# 😌 Intention
Cet espace est dédié à **la prise de note, à la consommation "passive" de l'information.**

Il aide à **récupérer les mots des autres pour les compiler, les questionner, mais surtout se préparer à la construction de savoir dans l'*espace* suivant.**

Les notes possédant le tag `status/en-cours` seront affichées ci-dessous.

# 👀 Contenus en cours de capture
```dataview
Table WITHOUT ID file.link as ""
from #status/en-cours
WHERE contains(file.folder, this.file.folder)
```