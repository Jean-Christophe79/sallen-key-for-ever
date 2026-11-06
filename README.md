# Calculateur Sallen-Key

Outil web pour concevoir des filtres actifs Sallen-Key à gain unitaire :

- passe-bas et passe-haut d'ordre 2 à 5, passe-bande d'ordre 2 et 4 (f₀ et Δf) ;
- réponses Butterworth, Bessel et Tchebychev ;
- choix des composants dans les séries E6 à E96, schéma dessiné automatiquement ;
- réponse idéale comparée à la réponse avec les composants retenus (gain, phase, retard de groupe) ;
- tolérances (pire cas et Monte-Carlo), modèle d'AOP réel et analyse de stabilité ;
- export d'un rapport Excel (schéma, nomenclature, réponse fréquentielle avec dispersion).

Tout tient dans `index.html` : aucune installation, aucun serveur. Les polices (Google Fonts), MathJax et ExcelJS sont chargés depuis des CDN publics.

## Utilisation

Ouvrir `index.html` dans un navigateur, ou la version publiée avec GitHub Pages.
