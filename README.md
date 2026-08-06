# dB et dBm

Ce depot contient des supports pedagogiques consacres aux decibels (dB), aux puissances en dBm et aux calculs usuels en electronique hyperfrequence.

Il est destine a des etudiants de niveau bac en electronique. Les contenus sont rediges avec [Quarto](https://quarto.org/) puis publies automatiquement sur GitHub Pages.

## Contenus proposes

Le projet est organise autour de quatre types de support :

| Dossier | Contenu |
| --- | --- |
| `COURS/` | Presentation de cours au format diaporama Reveal.js |
| `TD/` | Exercices avec une version etudiant et une version corrigee |
| `FAQ/` | Reponses aux questions frequentes sur les dB, dBm et dBuV |
| `FICHE/` | Fiche de synthese des formules et reperes essentiels |

Le contenu de ces suuports est diponible via :

* [COURS](https://fdaout.github.io/dB_dBm/COURS/cours.html)
* [TD - version étudiant](https://fdaout.github.io/dB_dBm/TD/etudiant/td_etudiant.html)
* [TD - avec correction](https://fdaout.github.io/dB_dBm/TD/corrige/td_corrige.html)
* [FAQ](https://fdaout.github.io/dB_dBm/FAQ/faq.html)
* [Fiche de révision](https://fdaout.github.io/dB_dBm/FICHE/fiche.html)

Les supports expliquent notamment :

- la difference entre un rapport en dB et une puissance absolue en dBm ;
- les conversions entre puissance lineaire, dBm et tension ;
- les gains, pertes et bilans de puissance ;
- les bilans de liaison radio et le bruit thermique ;
- les calculs associes aux composants RF, comme les amplificateurs et les coupleurs.

## Technologie utilisee

- **Quarto** pour ecrire et rendre les documents ;
- **Markdown** et **LaTeX** pour le texte et les equations ;
- **Reveal.js** pour le diaporama du cours ;
- **Python** et Jupyter pour les futurs calculs et figures generees dans les documents ;
- **GitHub Actions** pour automatiser le rendu et la publication.

## Organisation des fichiers

Chaque support est ecrit dans un fichier `.qmd` :

```text
COURS/cours.qmd
TD/td.qmd
FAQ/faq.qmd
FICHE/fiche.qmd
```

Le dossier `TD/` contient egalement les profils Quarto qui produisent les deux versions du document :

- profil `etudiant` : enonce sans les corriges ;
- profil `corrige` : enonce et corriges.

Les feuilles de style `custom.css`, presentes dans chaque dossier, adaptent l'apparence des pages produites.

## Generer les documents sur son ordinateur

### Prerequis

Installer :

1. [Python 3.11](https://www.python.org/) ;
2. [Quarto](https://quarto.org/docs/get-started/) ;
3. les bibliotheques Python necessaires.

### Rendu des supports

Depuis la racine du depot :

```bash
quarto render COURS
quarto render FAQ
quarto render FICHE
quarto render TD --profile etudiant
quarto render TD --profile corrige
```

Quarto cree les fichiers HTML correspondants dans les dossiers rendus.

## Publication automatique

Le workflow `.github/workflows/publish.yml` est execute a chaque envoi sur la branche `main`.

Il effectue les actions suivantes :

1. installe Python et les dependances definies dans `requirements.txt` ;
2. installe Quarto ;
3. rend le cours, la FAQ, la fiche et les deux versions du TD ;
4. publie les fichiers HTML sur GitHub Pages.

## Licence et contributions

Les ameliorations pedagogiques, corrections et nouvelles figures sont les bienvenues.
