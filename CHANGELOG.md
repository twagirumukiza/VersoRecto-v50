# Changelog

## v50.0.0

- Ajout de `VR50Memory` et migration automatique de la mémoire v48.
- La mémoire ne choisit plus directement le coup avant le Victory Planner.
- Transmission des statistiques de la position courante au Web Worker IA.
- Intégration des résultats appris dans l'ordre des coups et le départage des scores.
- Pondération prudente par moyenne, variance, nombre d'essais et confiance.
- Influence mémoire plafonnée pour empêcher un ancien mauvais apprentissage de masquer une victoire ou une défense forcée.
- Ajout du compteur « Coups fiables (3+ essais) ».
- Préparation des profils IA stable/candidate et de la promotion Champion.
- Conservation des correctifs multijoueur de la v48.3 et du Victory Planner v49.
