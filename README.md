# AsteroidDrift

**Décor temps réel pour mur LED de production virtuelle — Unreal Engine 5**

AsteroidDrift est un environnement spatial conçu pour être diffusé sur un mur LED de grand format. La séquence propose une dérive lente à travers un champ d'astéroïdes, pensée pour servir de fond de tournage ou d'habillage scénique lors d'événements.

---

## Intention

L'objectif est de produire un décor à la fois immersif et exploitable en conditions réelles :

- **Immersion** : profondeur de champ marquée grâce à la parallaxe entre plans proches et lointains.
- **Lisibilité à grande échelle** : mouvements de caméra lents et maîtrisés, adaptés à une surface de plusieurs mètres et à la captation par caméra.
- **Continuité** : séquence bouclée sans rupture visible, diffusable en continu pendant toute la durée d'un tournage ou d'un événement.
- **Interaction avec le plateau** : une source lumineuse dominante (étoile) colore la scène et, par extension, les personnes placées devant le mur.

## Direction artistique

Ambiance space opera : champ d'astéroïdes dense, nébuleuse en arrière-plan, contraste fort entre le noir profond de l'espace et une lumière stellaire chaude. Les éléments clés de la composition sont placés dans la moitié supérieure du cadre, la partie basse du mur étant souvent occultée par les intervenants ou le décor physique.

## Spécifications techniques

| Paramètre | Valeur |
|---|---|
| Support cible | Mur LED 8,5 m × 3,5 m |
| Ratio | ≈ 2,43:1 |
| Résolution de rendu | 3840 × 1580 |
| Cadence | 25 images/s (compatible captation 50 Hz) |
| Durée | Boucle de 30 à 60 secondes |
| Formats de livraison | MP4 (H.264 / H.265), séquence PNG |

## Outils et technologies

- **Unreal Engine 5** : Lumen (éclairage global), Niagara (particules), Sequencer et Movie Render Queue (rendu)
- **Blender** : modélisation et préparation des assets

## Livrables

- Séquence vidéo bouclée au format du mur LED
- Projet Unreal Engine 5 source, réutilisable et modifiable (cadrage, vitesse, éclairage)

## Perspectives

- Déclinaison pour d'autres formats d'écran (mur 6,5 m × 1,5 m, ratio ≈ 4,33:1)
- Version temps réel avec suivi caméra (nDisplay) pour une parallaxe synchronisée avec les mouvements de la caméra de tournage

---

## Auteur

**Nathan Morel**, ingénieur XR et temps réel
[LinkedIn](https://www.linkedin.com/in/nathan-morel-4b993b1b7) · [GitHub](https://github.com/Nath9666)
