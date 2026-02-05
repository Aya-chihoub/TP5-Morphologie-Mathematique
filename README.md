# TP5 - Morphologie Mathématique

**Réalisé par :** Aya Chihoub  
**Module :** Analyse d'Image  
**GitHub :** https://github.com/Aya-chihoub/TP5-Morphologie-Mathematique

## Description

Ce TP implémente les opérations fondamentales de morphologie mathématique sur des images binaires :

1. **Dilatation** - Agrandit les objets (maximum local)
2. **Érosion** - Réduit les objets (minimum local, via dualité)
3. **Ouverture** - Érosion + Dilatation (supprime petits éléments)
4. **Fermeture** - Dilatation + Érosion (bouche les trous)
5. **Gradient Morphologique** - Dilatation - Érosion (détection de contours)

## Structure

```
tp5/
├── src/
│   └── tp5morphology.ipynb    # Notebook avec le code
├── originals/
│   └── binary.png             # Image de test
├── results/
│   └── *.png                  # Images résultats
├── Compte_Rendu_TP5.docx      # Rapport Word
├── Compte_Rendu_TP5.md        # Rapport Markdown
└── README.md
```

## Exécution

Ouvrir `src/tp5morphology.ipynb` dans Jupyter et exécuter les cellules dans l'ordre.
