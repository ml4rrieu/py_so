# Python pour la science ouverte
#py_so

`2021-09-03 en construction`

formation URFIST 2021-22 

## Objectif 

Oeuvrer pour la science ouverte avec python

## pré-requis

- Avoir suivi la formation "python, les fondamentaux" de Émilien Schultz ([orcid](http://orcid.org/0000-0002-6215-3606), co-auteur de _Python pour les SHS_ cf. [pyshs.fr](http://pyshs.fr/))
- Avoir les compétences décrites jusqu'au chapitre 4 de  _Python pour les SHS_
- Maîtriser les API de HAL (search, aurehal:structure)
- Bonne connaissance du paysage et des enjeux de la science ouverte


## Formateur

Maxence Larrieu, PhD en informatique et musique, travaille depuis 2015 en université sur la science ouverte. [maxence.larri.eu](https://maxence.larri.eu)

Membre du Comité pour la Science Ouverte : collège Publications.


## Techniques à maîtriser

Prérequis pour aborder des applications métiers

* les différentes façon d'imprimer : directement, `print("ici", "là"), f"{string} encore" , "{} dernière".format("une")`
* créer une fonction avec argument et sortir un résultat structuré
* récupérer des données de l'API de HAL en JSON, les formater en dataframe
* filtrer une dataframe sur les NA, et autres, extraire une liste depuis une dataframe
* identifier son établissement dans une liste non formatée (ANR, Zenodo, portails HAL)
 

## Applications


### Identifier dans HAL les publications issues des projets de recherche qui sont ne pas en accès ouvert (pour rappel de l'obligation)


### Récupérer les projets de recherche ANR portés par son établissememnt

_anr_research_project_

goal : récupérer depuis les jeux de données de l'ANR les descriptions des projets de rech. portés par son établissement

py_skills : requests, données API, read_csv, filtre, 


### Retrouver dans Zenodo les données de la recherche de son établissement



### Niveau de bruit de son établissement dans le référentiel structure de HAL

_aurehal_struct_noise_0.1_

py_skills : récupérer données API, JSON


_aurehal_struct_noise_0.2_

py_skills : définition d'une fonction avec argument

_aurehal_struct_noise_0.3_

py_skills : passer du JSON au dataframe, définir deux fonctions, ajouter une colonne avec `.apply()`

_aurehal_struct_noise_0.4_

py_skills : pandas filtrer, retrouver les identifiants des établissements à partir de leurs noms

comparer le niveau de bruit dans le ref. structure des établissements ayant un portail HAL


### Vérifier à partir d'une source bibliographique externe la disponibilité en accès ouvert dans HAL des publications de son établissement

source externe : ScanR, Scopus ou autre 

Voir le notebook réalisé dans le cadre du [Casuhalathon 2021](https://casuhal2021.sciencesconf.org/resource/page/id/8) :  [github.com/ml4rrieu/halathon](https://github.com/ml4rrieu/halathon)
nota : DOI only

### Représenter ce que le WOS ne référence pas

Récupérer les données du BSO [Univ. Paris](https://github.com/ml4rrieu/bso_univ_paris). Identifier ce qui n'est pas dans le WOS. 
