# Dreamhouse - Project
## Introduction
DreamHouse est une application de démonstration sur la plateforme Salesforce qui illustre la création d'applications métiers à l'aide de Lightning Web Components (LWC) et Apex. Elle permet aux utilisateurs de visualiser et de gérer des propriétés immobilières via une interface interactive et intuitive.
## 1. 🚀 Créer un modèle de données avec des clics
- Création d'un objet personnalisé House à partir d'une feuille de calcul pour stocker des informations sur des maisons (nom, adresse, coût, etc.).
- Gestion des champs, des types de données et des relations entre objets.
- Importation des données et configuration d'une application Dreamhouse avec des vues de liste, des onglets, et la sécurité des données.
Accès aux données via l'API Salesforce.
## 2. 💻 Écrire les règles métier en Apex
- **Classe :** HouseService
- **Méthode principale :** getRecords
- **Objectif :** Interroger l'objet personnalisé House__c pour récupérer la liste des maisons via SOQL
- Création du fichier dreamhouseapp.apex et Exécution via l'indicateur "Execute Anonymous Apex"
## 3.⚡ Créer un composant réutilisable avec Lightning Web Components (LWC)
- **Composant :** housingMap
- Importation de la méthode getHouses depuis la classe Apex HouseService via @salesforce/apex.
- Utilisation du décorateur @wire pour lier les données de la classe Apex au composant LWC.
- Transformation des données récupérées pour correspondre au format requis par lightning-map.
### 4. Déploiement via SFDX: Deploy Source to Org
### 5. Ajout du Composant à la Page d'Accueil
### Résultat :
![image](https://github.com/user-attachments/assets/c9a323cd-75dc-4e1d-b98b-3393e5e91410)

Ressources :
https://trailhead.salesforce.com/fr/content/learn/projects/get-started-with-salesforce-development?trailmix_creator_id=strailhead&trailmix_slug=quest-get-started-as-a-developer
