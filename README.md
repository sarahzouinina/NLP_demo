# NLP_demo

## Objectifs
- Experimenter avec la base de données pour extraire le maximum d'information possible.

## Exemple d'interaction avec le modèle
Ci-dessous, un exemple de sortie :

```
exemple 1:
entrée: Directeur des ressources humaines
sortie: 
- catégorie: Administratif
- confiance: 96.7%
```
Remarque : La sortie peut être formatée selon votre préférence afin qu'elle montre la catégorie et la confiance que le modèle a évalué

## Jeu de données
Les données se trouvent dans le fichier data-jobs.csv, il respecte le format suivant :

| contract_type | name | office_latitude | office_longitude | category_name |
|---------|:------|:------|:------|:------|
| STRING  | STRING  | FLOAT | FLOAT | STRING

## Etapes
- Exploration des données
- Nettoyage des données
- Mining des données
- Visualisation et réduction de la dimension
