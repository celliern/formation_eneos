---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.3.3
  kernelspec:
    display_name: Python [conda env:root] *
    language: python
    name: conda-root-py
---

# Formation Python, analyse de donnée et interfaçage E⁺

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/celliern%2Feneos_formation/master)

## Partie 1 (7 h) - les fondamentaux

- [Introduction au langage Python (1h)](notebooks/D01-fondamentaux_01/fonda_00-introduction.ipynb)
  - Petite perspective
  - Installation de via [anaconda](https://www.anaconda.com/)
  - Premier contact : utilisation des notebooks [jupyter](https://jupyter.org/)
  - Aparté sur les conventions de style ([PEP8](https://www.python.org/dev/peps/pep-0008/))
- Apprentissage par l'exemple : lecture et analyse de fichiers de donnée (5h30-6h)
  - [Utilisations des variables](notebooks/D01-fondamentaux_01/fonda_01-variables.ipynb)
  - [Analyser des données tabulaires](notebooks/D01-fondamentaux_01/fonda_02-donnees_tabulaires.ipynb)
  - [Affichage des données](notebooks/D01-fondamentaux_01/fonda_03-simple_vizu.ipynb)
  - [Répétition d'action avec les boucles](notebooks/D01-fondamentaux_01/fonda_04-boucles.ipynb)
  - [Stockage de valeurs dans les listes](notebooks/D02-fondamentaux_02/fonda_05-listes_tuples.ipynb)
  - [Application au traitement de nombreux fichiers](notebooks/D02-fondamentaux_02/fonda_06-app_multiples_fichiers.ipynb)
  - [Programmation conditionnelle : des actions différentes pour différentes valeurs](notebooks/D02-fondamentaux_02/fonda_07-conditions.ipynb)
  - [Structurer le code avec les fonctions](notebooks/D02-fondamentaux_02/fonda_08-fonctions.ipynb)
  - [Rendre son code plus robuste, gestion des erreurs et debug](notebooks/D02-fondamentaux_02/fonda_09-robustesse_erreur_debug.ipynb)
- Debriefing (15 min)

## Partie 2 (7h) - outils d'analyse de donnée

- [Mise en contexte : le stack scientifique python (45 min)](notebooks/D03-analyse_num_01/num_00-contexte.ipynb)
- Introduction au calcul scientifique en python (2h)
  - [La brique de base : `numpy`](notebooks/D03-analyse_num_01/num_01-scistack_numpy.ipynb)
  - [La boîte à outil : `scipy`](notebooks/D03-analyse_num_01/num_02-scistack_scipy.ipynb)
  - [Statistique et données tabulaires : `pandas`](notebooks/D03-analyse_num_01/num_03-scistack_stats_pandas.ipynb)
  - [La visualisation : `matplotlib`, `pyviz`](notebooks/D03-analyse_num_01/num_04-scistack_visualisation.ipynb)
- [`pandas` pour l'analyse de séries temporelles (4h)](notebooks/D04-analyse_num_02/num_06-pandas_intro.ipynb)
  - [Lecture et écriture de set de donnée](notebooks/D04-analyse_num_02/num_07-pandas_io.ipynb)
  - [Sélection des données : indexation simple et avancé](notebooks/D04-analyse_num_02/num_08-pandas_indexation.ipynb)
  - [Renforcement des données : gestion des données manquantes](notebooks/D04-analyse_num_02/num_09-pandas_donnees_manquantes.ipynb)
  - [Gestion des données temporelles, rééchantillonage](notebooks/D04-analyse_num_02/num_10-pandas_serie_temporelles.ipynb)
- Debriefing (15 min)

## Partie 3 (3h) - manipuler E⁺ en python

- [Lancement d'une simulation E⁺ : `subprocess` et `plumbum` (1h)](notebooks/D05-eplus/e+_01-lancement_process_externe.ipynb)
- [Récupération des résultats (30min)](notebooks/D05-eplus/e+_02-lire_resultats_eplus.ipynb)
- [Le cas complexe de la parallélisation et d'E⁺ (30min)](notebooks/D05-eplus/e+_03-paralleliser_eplus.ipynb)
- [Une solution: utilisation d'une librairie tierce spécialisé : `energyplus_wrapper` (30 min)](notebooks/D05-eplus/e+_04-energyplus_wrapper.ipynb)
- Debriefing (15 min)


```python

```
