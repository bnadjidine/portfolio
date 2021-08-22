---
title: "Dashboard Appros"
description: "Le projet Dashboard Appros fait parti d'une suite projet BI Supply Chain."
#repo: "#" # delete this line if you want a blog-like page
tags: ["COMMUNICATION", "GESTION DE PROJET", "QLIK", "TECHNIQUE"]
#author: "Nadjidine BOINALI"
weight: 5
draft: false
---


![Dashboard Appros](../../images/project/home_page/dashboard.png)


## Le projet
Dashboard Apppros est le nom d'un projet BI (Business Intelligence) réaliser à <a href="https://bmscircuits.com/" targetv="_blank">BMS CIRCUITS </a>, fillière du groupe <a href="http://allcircuits.com/" target="_blank"> ALL CIRCUITS </a> lors de mes 2 années d'alternance, pour l'obtention de mon titre d'expert en ingénierie logiciel à <a href="https://www.intechinfo.fr/" target="_blank"> IN'TECH-SUD </a>.

La business intelligence ou informatique décisionnelle présente un ensemble de techniques d'analyse de données massive, et de présentation d'informations par des moyens de tableau de bord.

Le projet fait partie de la suite de projets Supply Chain (chaîne d'approvisionnement) BI ALL CIRCUITS, il offre une suite d'indicateurs aux acheteurs et approvisionneurs du groupe, afin de les aider dans leurs tâches quotidiennes.

Le projet m'a également offert une expérience à l'internationale

### Contexte
Le groupe ALL CIRCUITS l'un des leaders mondiaux de l'EMS (Fabricant de composants éléctroniques) souhaite consolider l'ensemble de données supply chain de ses filières, pour cela il dispose d'une infrastructure big data assez importante. A ceci s'ajoute des applications d'analyses de données moderne et rapide tel que <a href="https://powerbi.microsoft.com/" target="_blank">Microsft Power BI</a> et <a href="https://www.qlik.com/" target="_blank">QlikView </a>.

Ces solutions de développement ont la particularité de pouvoir communiquer avec une multitude de base de données, est incorpore un moteur puissant pouvant traiter des millions de données en quelques secondes.
Pour le développement de l'application, c'est QlikView qui a était retenu.

Les acheteurs et approvisionneurs du groupe utilisaient un bon nombre de fichiers Excel pour analysé leurs travailles hebdomadaire pour le suivi des commandes. Pour chaque commande répertorier dans ses même fichier, ils leurs été demandaient d'aller de suivre l'action suggérer par l'ERP (Progiciel de Gestion Intégré) du groupe, et ensuite rapporter le résultat à celui-ci. 

Ceci posait plusieurs problèmes, entre autre :
- Un temps considérable passer par acheteurs / approvisionneurs pour mettre en place ses propres indicateurs;
- Pas d'historisations des tâches effectuer sur les différentes commandes;
- Une vue globale limitée sur le travail effectuer au niveau des managers;
- ...

L'approvisionnement représentant la plus grosse part des dépenses du groupe, il était donc nécessaire de pouvoir suivre chaque dépense, et en même temps pallier les aux surcoûts.


### Objectifs

Pour réussir la mission, consolider les données, et offrir une espace commune pour le traitement des commandes par le biais de Dashbord, il était important de réaliser les étapes suivantes:

- Analyser l'ensembles des données utilisaient par les acheteurs / approvisionneurs;
- Analyser les données manquantes;
- Faire une demande aux responsables ERP de chaque site pour automatiser l'acheminement des données;
- Créer un <a href="#data-mart"> data mart </a> pour le stockage de données;
- Créer un model de données;
- Créer des mesures exploitable pour servir l'application BI;
- Mettre en place les tableaux de bords;
- Mette l'applications à disposition des acheteurs / approvisionneurs.  

Avec ceci venait s'ajouter des missions d'admistrations des principaux serveurs big data.

(<small> Pour plus d'informations voir <a href="https://b-nadji/projets/transition-4.0#migration-zabbix" target="_blank"> projet Transition 4.0</a> </small>.)

### Ma contribution

Pour accomplir une mission de développement BI dans un domaine en particulier, il est important de pouvoir s'imprégner rapidement le métier. Mes premières semaines post développements étaient principalement orientées apprentissage métier, en effet elles étaient partagé entre affinage avec la responsable appros  et identification de données cibles.

Étant le seul développeur pour les développement de l'application, j'ai dû collaborer avec les services métiers (achat et approvision), de gestion de l'ERP, et d'administration BI. 

### Résultats
#### #CREATION MODEL DE DONNEES

![Data Model](../../images/project/DashboardAppros/datamodelQV.jpg)

<br> </br> 
#### #CREATION DU TABLEAU DE BORD
![Dashboadr](../../images/project/DashboardAppros/dashboardappro-result.png)

<br> </br> 
Ce projet a permit aux acheteurs et approvisionneurs de se libérer des fichiers multiples utilisaient toutes les semaines pour effectuer leur travail. En offrant une vue consolidée des commandes, avec une historisation de celles-ci, il est maintenant beaucoup plus facile au manager de suivre l'état des différentes commandes.

### Conclusion

Le projet Dashboard Appros m'a permis d'acquérir de nouvelle compétences en technologie Qlik, notament avec Qlik View. Il m'a aussi permis de voir des techniques avancé de Data Analyst comme la mise en place d'un modèle de données.

Pour le groupe ALL CIRCUITS, cette application et la référence pour le suivi des commandes; les acheteurs et approvisionneurs ayant accès rapidement aux données souhaité, ils peuvent désormais faire leurs travaille rapidement et augmenté d'une mnière considérable leur rentabilité.

Personnelement, ce projet et sans aucun doute celui dont j'ai été le plus fier et excité de mener jusqu'au bout, ce que j'ai appris en une phrase "l'informatique décisionnelle et l'informatique qui prépare les meilleurs lendemains".

<hr>

##### Data Mart
Un data mart est un sous ensemble d'entrpôt de données axé sur un domaine en particulier. Il permet de mettre à disposition des données spécifiques à la disposition d'un groupe d'utilisateur bien défini.


