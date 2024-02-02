---
remonter vers:
  - "[[Accueil]]"
---
# 😌 Intention
Cet espace est dédié aux **notes atomiques de synthèse écrites à la main qui forment un réseau de connaissances et d'informations à partir du flux que l'on a traité**.

Il aide à **la construction d'un savoir pérenne, complexe, interconnecté et prêt à l'emploi**.


> [!help] À propos de ce dossier
> - Les *atomes* sont des documents qui se concentrent sur un concept, sur une idée ou sur une réflexion personnelle et qui sont très faciles à inter-connecter pour créer un réseau de connaissances.
> 	- par exemple : design pattern, biais cognitif, design system, loi 1901
> - Les *molécules* sont des documents qui contiennent des liens vers des *atomes*, afin de créer un assemblage d'idées concernant un concept plus large.
> 	- par exemple : informatique, histoire, développement web, psychologie, etc

---

# 👀 Dernières notes de savoir crées
```dataview
Table WITHOUT ID file.link as "", file.ctime as "Date et heure"
WHERE contains(file.folder, this.file.folder)
SORT file.ctime DESC 
LIMIT 20
```
