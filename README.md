# Ramp Rush ✈️

Jeu de gestion d'aéroport en 3D, jouable dans le navigateur (pensé pour iPhone).

**Jouer :** https://spykatra.github.io/ramp-rush/

- Les avions atterrissent, se garent, sont servis (bagages, carburant, repas, dégivrage) puis repoussés et décollent.
- Construis des portes, achète des véhicules, améliore ton aéroport et fais-le évoluer : régional → international → hub continental.
- À partir de l'aéroport international, la météo (pluie, brouillard, neige, orage) perturbe les opérations.

Version précédente (chargement de soute) : https://spykatra.github.io/ramp-rush/classique/

## Technique
- Un seul fichier HTML par jeu, sans étape de compilation.
- Moteur 3D : [Three.js r128](https://threejs.org/) chargé depuis cdnjs.
- Sauvegarde locale dans le navigateur (localStorage).
