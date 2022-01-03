
![Python pour la science ouverte](./img/py_so_com.png)

_Oeuvrer pour la science ouverte avec Python_ twitter : [#py_so](https://twitter.com/hashtag/py_so?src=hashtag_click)


 
## Exercices & démonstration

* Identifier dans HAL les publications de son établissement issues des projets de recherche qui ne sont pas en accès ouvert

| <!-- -->| <!-- -->|
| ------ | ----------- |
|Difficulté| faible   |
|Exercice | [pub_projet_research_hal_no_oa.ipynb](exo/pub_projet_research_hal_no_oa.ipynb) |
|Compétences| requêtes API HAL, json vers dataframe|
|Objectif | faire respecter l'obligation d'accès ouvert|
|Démo | _à venir_|

<br />


* Représenter l'évolution et les types de dépôts dans HAL d'une structure ou institution

| | |
| -------- |--------|
|Difficulté| faible |
|Exercice | [hal_evol_depots.ipynb](exo/hal_evol_depots.ipynb) |
|Compétences| requêtes API de HAL en série, json vers dataframe, plot histogramme|
|Objectif | Automatiser des rapports statistiques des publications dans HAL|
|Démo | _à venir_|

<br />


* Récupérer les identifiants des projets de recherche ANR portés par son établissemement

| | |
| -------- |--------|
|Difficulté| moyen |
|Exercice | [get_anr_research_project.ipynb.ipynb](exo/get_anr_research_project.ipynb) |
|Compétences| requêtes aurehal structure, données API, read_csv, filtre|
|Objectif | initier une politique de suivi des publications des projets de recherche ANR|
|Démo | _à venir_|

<br />


* Niveau de bruit de son établissement dans le référentiel structure de HAL

_aurehal_struct_noise_0.1.ipynb_

compétences : récupérer données API, JSON

_aurehal_struct_noise_0.2.ipynb_

compétences : définition d'une fonction avec argument

_aurehal_struct_noise_0.3.ipynb_

compétences : passer du JSON au dataframe, définir deux fonctions, ajouter une colonne avec `.apply()`

_aurehal_struct_noise_0.4.ipynb_

/!\ un classement des établissements par taux de propreté dans le référentiel structure

compétences : pandas filtrer, retrouver les identifiants des établissements à partir de leurs noms

<br />

* Vérifier à partir d'une source bibliographique externe la disponibilité en accès ouvert dans HAL des publications de son établissement

source externe : ScanR, Scopus ou autre 

Voir le notebook réalisé dans le cadre du [Casuhalathon 2021](https://casuhal2021.sciencesconf.org/resource/page/id/8) :  [github.com/ml4rrieu/halathon](https://github.com/ml4rrieu/halathon)
nota : DOI only


<br />


* Représenter ce que le WOS ne référence pas

_a_faire_



<!--
    Récupérer les données du BSO [Univ. Paris](https://github.com/ml4rrieu/bso_univ_paris). Identifier ce qui n'est pas dans le WOS. 
    ### Retrouver dans Zenodo les données de la recherche de son établissement
-->


<!--
Identifier dans les chapitres d'ouvrage qui peuvent être déposés en Accès ouvert. pour Springer voir
https://oaamu.hypotheses.org/2197


-->

## Pré-requis

- Avoir suivi la formation [Python, les fondamentaux](https://github.com/pyshs/Formation-URFIST-2021-Toulouse-ScienceOuverte)
- Avoir les compétences décrites jusqu'au chapitre 4 de _Python pour les SHS_
- Maîtriser les APIs de HAL (l'API générale "search" et celle du référentiel Structure de aurehal)
- Bonne connaissance du paysage et des enjeux de la science ouverte



## Techniques à maîtriser

* différentes syntaxes pour imprimer : `print("ici", "là"), print(f"{ma_variable} encore") , print("{} dernière".format("une"))`
* Request, pandas
* fonction avec argument 
* sortir un résultat structuré
* filtrer une dataframe, extraire une liste, ajouter colonne 
* passer des données en JSON en dataframe (Pandas)


## Contexte

En juin 2021 le besoin d'une formation sur Python à destination des publics travaillant pour la science ouverte se fait ressentir. Une première édition est réalisée avec l'URFIST d'Occitanie en deux temps : une formation sur les fondamentaux de Python, assurée par Émilien Schultz co-auteur de _Python pour les SHS_ ([pyshs.fr](http://pyshs.fr/)) sur 1.5 jours, suivie d'une autre sur _Python pour la science ouverte_, assurée par Maxence Larrieu également sur 1,5 jours. 

> Un langage de programmation ne s'apprend pas en trois jours.

En elle même la formation ne vous apprendra pas à programmer en python. Par contre la réalisation des exercices, le livre _Python pour les SHS_, des MOOCs, votre perséverance et votre curiosité, vous permettront de comprendre et écrire du python pour la science ouverte.

