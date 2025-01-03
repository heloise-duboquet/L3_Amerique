# Structure de la base de données (Geoffroy Zhang)
## Présentation du MCD
    - Inclure le schéma
    - Explication du choix des entités, de leurs attributs et de leurs relations
    - Explication des cardinalités
    - Utilisation des identifiants ARK comme clés primaires
## Dictionnaire des données
## Recodage des données
    - Siècles des éditions
    - Régions couvertes par les ouvrages
    - Fonctions/métiers des auteurs

# Structure de la base de données (Geoffroy Zhang)

Inventée par le mathématicien Edgar F. Codd, la base de données relationnelle se définie comme : "un ensemble structuré de données reliées entre elles et stockées de manière cohérentes, sans redondance inutile" (Marc Humbert, *Les bases de données*, Paris, Hermes, 1991). 
Notre base de données relationnelle se structure, comme toutes les bases, d'un ensemble de tables et de vivers autres éléments que nou 

## Le modèle conceptuel des données (MCD) de notre corpus
Le MCD est l'étape préalable à la conception d'une base de données. En effet, celui-ci nous a permis, dans le cadre de ce projet, de modéliser les données du corpus au sein d'une structure organisée qui indique différents éléments :
- Les **entités** : la chose que l'on décrit ;
- Les **attributs** : ce qui décrit ou caractérise une chose ;
- Les **relations** : les relaations entre les entités.

Le MCD est composé de : 
- Les **tables** ;
- Leurs **champs** ;
- Leur **type de donnée** ; 
- Les **clés primaires** et **étrangères** ;
- Les **relations entre les tables** et leur **signification** ;
- Les **cardinalités**.

<ins>Schéma du MCD d'apès le corpus Amérique du catalogue de la BnF : </ins>
![MCD_Corpus_Amérique](https://github.com/user-attachments/assets/9480eb4f-377d-4c63-b89c-f94cfed6cb01)

Tout d'abord nous avons identifié les entités, les attributs et leur relation, après l'analyse d'un document. Cette ébauche nous a permis de dresser notre MCD. Les entités sont représentées par des tables en forme de boîte aux angles à 90 degrés ; alors que les relations sont caractérisées par des boîtes aux angles plus arrondis et contiennent souvent des verbes (Ex. "Parle de" pour la relation de l'entité "TEXTE" et "SUJET_RAMEAU").

Ainsi, la base de données est composées de diverses tables que sont : la table EDITION, FONCTION, TEXTE, AUTEUR, FONCTION et ECRIT_PAR. 

Le choix des entités a été le produit d'une réflexion en classe après avoir analyser la structure du corpus. En effet, chaque nom d'entité (Ex. Texte) caractérise l'élément que nous décrivons. Ces entités sont décritent par des champs (Ex. Titre). Autrement dit, le champ "titre" correspond au titre du texte qui correspond à l'entité "texte". 


## Dictionnaire des données 

Le dictionnaire des données est un référentiel d'informations relatif aux bases de données. 

## Recodage des données 
