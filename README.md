
![Python pour la science ouverte](./img/py_so_com.png)

_Oeuvrer pour la science ouverte avec Python_ twitter : [#py_so](https://twitter.com/hashtag/py_so?src=hashtag_click)


 
## Applications

### Identifier les publications HAL de son établissement issues des projets ANR qui ne sont pas en accès ouvert

| <!-- -->| <!-- -->|
| ------ | ----------- |
|Difficulté| faible   |
|Exercice | [pub_projet_research_hal_no_oa.ipynb](exo/pub_projet_research_hal_no_oa.ipynb) |
|Compétences| requêtes API HAL, json vers dataframe|
|Objectif | faire respecter l'obligation d'accès ouvert|
|Démo | _demo/pub_projet_research_hal_no_oa.ipynb_|

<br />


### Représenter l'évolution et les types de dépôts dans HAL d'une structure ou institution

| | |
| -------- |--------|
|Difficulté| faible |
|Exercice | [hal_evol_depots.ipynb](exo/hal_evol_depots.ipynb) |
|Compétences| requêtes API de HAL en série, json vers dataframe, plot histogramme|
|Objectif | Automatiser la production de statistiques pour les unités de recherche|
|Démo | _demo/hal_evol_depots.ipynb_|

<br />


### Récupérer les identifiants des projets de recherche ANR portés par son établissemement

| | |
| -------- |--------|
|Difficulté| moyen |
|Exercice | [get_anr_research_project.ipynb](exo/get_anr_research_project.ipynb) |
|Compétences| requêtes aurehal structure, données API, read_csv, filtre|
|Objectif | initier une politique de suivi des publications des projets de recherche ANR|
|Démo | _demo/get_anr_research_project.ipynb_|

<br />


### Niveau de bruit de son établissement dans le référentiel structure de HAL

| | |
| -------- |--------|
|Difficulté| faible |
|Exercice | [aurehal_struct_noise.ipynb](exo/aurehal_struct_noise.ipynb) |
|Compétences| requêtes aurehal structure, données API, fonction|
|Objectif | Mesurer le niveau de bruit de son établissement dans le référentiel HAL structure|
|Démo | _demo/aurehal_struct_noise_|

<br />

### Extraire un tableau des structures non valides de son étab. avec le nombre de documents associés

| | |
| -------- |--------|
|Difficulté| moyen |
|Exercice | [aurehal_struct_incoming_list.ipynb](exo/aurehal_struct_incoming_list.ipynb) |
|Compétences| requêtes aurehal struct, données API, fonction apply|
|Objectif | Nettoyer les structures de son établissement dans le référentiel AureHAL|
|Démo | _demo/aurehal_struct_incoming_list.ipynb_|


<br />

### Effectuer un classement des établissements FR selon leur niveau de bruit dans le référentiel structure

| | |
| -------- |--------|
|Difficulté| moyen  |
|Exercice | [aurehal_struct_noise_ranking.ipynb](exo/aurehal_struct_noise_ranking.ipynb) |
|Compétences| requêtes aurehal struct, données API, fonction|
|Objectif | Sensibiliser les adminsitrateurs HAL à la propreté du référentiel structure|
|Démo | _à venir_|


<br />


### Vérifier à partir d'une source externe la présence en accès ouvert dans HAL des publications de son établissement

| | |
| -------- |--------|
|Difficulté| forte  |
|Compétences| API ScanR, Permissions, Module python|
|Objectif | Identifier les publications de son établissement pouvant être déposées en accès ouvert #HALathon|
|Démo | [github.com/ml4rrieu/halathon](https://github.com/ml4rrieu/halathon)|

Notebook réalisé dans le cadre du [CasuHalathon 2021](https://casuhal2021.sciencesconf.org/resource/page/id/8) 

<br />


<!--

* Représenter ce que le WOS ne référence pas

_a_faire_


Récupérer les données du BSO [Univ. Paris](https://github.com/ml4rrieu/bso_univ_paris). Identifier ce qui n'est pas dans le WOS. 
### Retrouver dans Zenodo les données de la recherche de son établissement


_a_faire_


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

Ces formations ne vous premettront pas de programmer en python. Par contre la réalisation des exercices, le livre _Python pour les SHS_, des MOOCs, votre perséverance et votre curiosité, vous permettront de comprendre et écrire du python pour la science ouverte.

