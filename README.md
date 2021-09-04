# Python pour la science ouverte
#py_so

`2021-09-04 en construction`

Formation URFIST 2021-22

## Objectif 

:snake: :closed_lock_with_key:

Oeuvrer pour la science ouverte avec python



## pré-requis

- Avoir suivi la formation "python, les fondamentaux" de Émilien Schultz ([orcid](http://orcid.org/0000-0002-6215-3606), co-auteur de _Python pour les SHS_ cf. [pyshs.fr](http://pyshs.fr/))
- Avoir les compétences décrites jusqu'au chapitre 4 de _Python pour les SHS_
- Maîtriser les API de HAL (search, aurehal:structure)
- Bonne connaissance du paysage et des enjeux de la science ouverte


## Techniques à maîtriser

Prérequis pour aborder des applications métiers

* différentes syntaxes pour imprimer : directement, `print("ici", "là"), f"{ma_variable} encore" , "{} dernière".format("une")`
* fonction avec argument et sortir un résultat structuré
* passer des données en JSON en dataframe (Pandas)
* filtrer une dataframe, extraire une liste, ajouter colonne 

 
## Applications

#### Représenter l'évolution et les types de dépôts dans HAL d'un structure

_hal_evol_depots.ipynb_

compétences : requêter dans l'API de HAL en série, restructurer les données, graphique pour les représenter


#### Identifier dans HAL les publications issues des projets de recherche qui sont ne pas en accès ouvert (pour rappel de l'obligation)

_pub_projet_research_no_oa.ipynb_

compétences : requêtes API HAL, restructurer les données


#### Récupérer les projets de recherche ANR portés par son établissememnt

_anr_research_project.ipynb_

récupérer depuis les jeux de données de l'ANR les descriptions des projets de rech. portés par son établissement

compétences : requests, données API, read_csv, filtre, 


#### Niveau de bruit de son établissement dans le référentiel structure de HAL

_aurehal_struct_noise_0.1.ipynb_

compétences : récupérer données API, JSON

_aurehal_struct_noise_0.2.ipynb_

compétences : définition d'une fonction avec argument

_aurehal_struct_noise_0.3.ipynb_

compétences : passer du JSON au dataframe, définir deux fonctions, ajouter une colonne avec `.apply()`

_aurehal_struct_noise_0.4.ipynb_

/!\ un classement des établissements par taux de propreté dans le référentiel structure

compétences : pandas filtrer, retrouver les identifiants des établissements à partir de leurs noms


#### Vérifier à partir d'une source bibliographique externe la disponibilité en accès ouvert dans HAL des publications de son établissement

source externe : ScanR, Scopus ou autre 

Voir le notebook réalisé dans le cadre du [Casuhalathon 2021](https://casuhal2021.sciencesconf.org/resource/page/id/8) :  [github.com/ml4rrieu/halathon](https://github.com/ml4rrieu/halathon)
nota : DOI only


#### Représenter ce que le WOS ne référence pas

_a_faire_




<!--
    Récupérer les données du BSO [Univ. Paris](https://github.com/ml4rrieu/bso_univ_paris). Identifier ce qui n'est pas dans le WOS. 
    ### Retrouver dans Zenodo les données de la recherche de son établissement
-->