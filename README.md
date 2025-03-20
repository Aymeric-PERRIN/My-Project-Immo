# My-Project-Immo
Final project of Le Wagon bootcamp

Bienvenue sur le projet final du bootcamp Le Wagon : My Project Immo ! Ce projet a pour objectif de simplifier la recherche d'investissements immobiliers rentables en exploitant des données publiques et des annonces en ligne.

🔍 Contexte

Trouver un bien immobilier rentable peut s'avérer long et complexe. L'objectif de My Project Immo est de fournir une solution automatisée permettant d'identifier rapidement les 50 biens les plus rentables sur le marché.

🗊 Workflow du projet

Collecte de données :

Analyse des ventes via la base de données DVF (“Demandes de Valeurs Foncières”) disponible sur data.gouv.fr.

Scraping des annonces immobilières sur les sites Le Bon Coin, PAP, et Se Loger.

Nettoyage et consolidation :

Cleaning des données collectées (ventes et annonces).

Concaténation des sources pour obtenir une base unique.

Analyse de rentabilité :

Utilisation de Python sur Google Colab pour calculer la rentabilité de chaque bien.

Extraction des 50 biens les plus rentables.

Enrichissement des données :

Récupération des coordonnées GPS des biens via l'API OpenStreetMap.

Export des résultats finaux vers Google Sheets.

Visualisation :

Intégration de toutes les données dans Looker pour créer un rapport interactif.

🔧 Outils et technologies

Langage : Python

Environnement : Google Colab

Scraping : BeautifulSoup, Selenium

Analyse et traitement des données : Pandas, NumPy

APIs : OpenStreetMap

Export des données : Google Sheets API

Visualisation : Looker

💼 Installation et exécution

Clonez ce repository :

Ouvrez le notebook sur Google Colab.

Installez les dépendances :

Exécutez les cellules dans l'ordre pour réaliser le pipeline complet.

📊 Résultats

Les 50 biens les plus rentables sont disponibles dans un Google Sheet exporté et peuvent être visualisés de manière interactive via le rapport Looker.

📚 Auteurs

Ton Nom (@tonpseudo)

Contributeurs supplémentaires si nécessaire

🛠ï Améliorations futures

Intégration d'autres plateformes d'annonces.

Automatisation complète de la pipeline avec déploiement sur un serveur.

Amélioration des calculs de rentabilité avec de nouveaux paramètres.

💌 Contact

Pour toute question ou suggestion, n'hésitez pas à me contacter via GitHub ou LinkedIn.

