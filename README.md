# Portfolio-PowerBi 
 Tableaux de bord créés à l'aide de l'outil Power BI.
- [Tableau de bord des Ressources Humanes](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Tableau%20de%20bord%20des%20RHumanes/RapportRessourcesHumanes.pbix)
- [Tableau de bord de production](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Tableau%20de%20bord%20des%20Production/RapportProduction.pbix)
- [Tableau de bord des ventes](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Tableau%20de%20bord%20des%20ventes/Rapport%20Magasin.pbix)
- [Tableau de bord des ventes 2](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Ventes%202/Rapport%20Ventes.pbix)

### Tableau de bord des Ressources Humanes
![ressourcesh](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Tableau%20de%20bord%20des%20RHumanes/Video_230509161031.gif)

Accédez au tableau de bord complet [Dans ce lien](https://app.powerbi.com/view?r=eyJrIjoiMzZhNDAyZjQtM2NjYS00ZjI3LWJjNmEtYTE3ZmQ1NmNmOGQxIiwidCI6IjRiN2IwYjZhLWIzNDAtNDc5MS1iNTg5LTA1NDVkZDIwYWQzNiJ9)

#### Structure de la base de données

Fichier Excel contenant initialement les colonnes suivantes
- ID RH
- Nom
- état civil
- Genre
- Date de Naissance
- Date d'embauche
- Date de départ
- Salaire
- Poste
- Domaine de travail
- Évaluation des employés
- Ville

Expressions DAX créées à partir des données :
- Employés Actifs
- Employés Ayant Quitté Entreprise
- Nouvelles embauches
- Percent Turnover
- Salaire Employés Actifs

**Quantité de données: 234** 

### Tableau de bord de production
![ressourcesh](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Video_230509214946.gif)

Accédez au tableau de bord complet [Dans ce lien](https://app.powerbi.com/view?r=eyJrIjoiYjA0ZGJhYjktNmYzZC00ODJkLTkxNmQtZDg0MTRmZWE4M2JiIiwidCI6IjRiN2IwYjZhLWIzNDAtNDc5MS1iNTg5LTA1NDVkZDIwYWQzNiJ9)

#### Structure de la base de données

Fichier Excel contenant initialement les colonnes suivantes
- Numéro d'Ordre
- Opérateur
- Produit
- Incident
- Début
- Heures Début
- Fin
- Heures Fin
- Total des heures
- Quantité Produite
- Quantité Rejetée


Expressions DAX créées à partir des données :
- Heures de production
- Heures d'arrêt
- Pourcentage de disponibilité
- Pourcentage de qualité
- Quant Produite
- Quant Rejetée 

**Quantité de données: 31617** 

### Tableau de bord des ventes

![ventes](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Tableau%20de%20bord%20des%20ventes/Video_230507204904.gif)

Accédez au tableau de bord complet [Dans ce lien](https://app.powerbi.com/view?r=eyJrIjoiODZjY2FmZDctYzVkOS00YjhmLWJlYmItNTE3MTM3NjE0M2JjIiwidCI6IjRiN2IwYjZhLWIzNDAtNDc5MS1iNTg5LTA1NDVkZDIwYWQzNiJ9)

#### Structure de la base de données

Fichier Excel contenant initialement les colonnes suivantes
- SKU
- Produit
- Quantité vendue 
- Prénom
- Nom de famille 
- Date
- Magasin
- Prix unitaire 


Colonnes créées à partir des données :
La colonne "Nom" a été créée à partir des colonnes "Prénom" et "Nom de famille"
La colonne "Moins" a été créée à partir des colonnes "Date"
**Quantité de données: 10.000** 



### Tableau de bord des ventes 2

![ventes](https://github.com/Cidavieira/Portfolio-PowerBI/blob/main/Tableau%20de%20bord%20des%20ventes%202/Video_230509075926.gif)

Accédez au tableau de bord complet [Dans ce lien](https://app.powerbi.com/view?r=eyJrIjoiZTFhNWQzNmYtODQxZC00MjljLWI4N2UtZWM4MGU4YjdlNGM5IiwidCI6IjRiN2IwYjZhLWIzNDAtNDc5MS1iNTg5LTA1NDVkZDIwYWQzNiJ9)

#### Structure de la base de données

Fichier Excel contenant initialement les colonnes suivantes
- Catégorie
- Prix unitaire
- Coût unitaire
- Marque
- Quantité vendue
- Nom Client
- localité


Colonnes créées à partir des données:
- pays 
- Continente

Les colonnes "pays" et "continent" ont été créées à partir de la colonne "localité".

**Quantité de données: 203.883 ** 

Avez-vous des suggestions d'amélioration ou avez-vous trouvé un bogue ? Veuillez laisser votre problème (issue) ici.😉
