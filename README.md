# Carte de référence LaTeX

![CI](../../actions/workflows/ci.yml/badge.svg?branch=master)

Cette carte de référence est destinée à accompagner l'étudiant durant ses études d'ingénieur.

## Preview

La carte de référence est une feuille A4 recto-verso supposément imprimée sur du papier 120g satiné orange clair :

[![Preview](../../releases/download/latest/preview.png)](../../releases/latest/download/refcard.pdf)

L'impression via la reprographie de l'école peut être demandée avec la description suivante:

```text
papier: A4 160g gris clair
format: recto-verso, reliure petit-côté à gauche
```

## Build

L'écosystème de compilation s'appuie sur Docker, la compilation est automatique à chaque commit depuis les GitHub Actions.

Une compilation locale est possible avec les outils suivants :

- texlive-full
- latexmk
- git
