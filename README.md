Projet réalisé par Chelsea Tchoumbé – Étudiante en Bachelor 1 Data & IA à HETIC (2025-2028)

 Objectif et Mindset
L'objectif de ce projet était de me mettre dans le mindset d'une Data Analyst et Data Scientist pour gérer intelligemment les données d'un catalogue de 71 animés. J'ai voulu transformer une base de données brute en un outil stratégique capable d'orienter les choix d'acquisition de licences.

 Technologies et Environnement
Pour ce travail, j'ai utilisé la suite Anaconda. Je suis passée par Anaconda Navigator pour lancer mon Jupyter Notebook, l'espace dans lequel j'ai réalisé l'intégralité de mes codes et analyses.

Bibliothèques importées :

Pandas : Pour le chargement, le tri et le nettoyage des données.

Matplotlib & Seaborn : Pour générer les histogrammes et les visualisations graphiques.

WordCloud : Pour réaliser des nuages de mots (j'ai réussi à implémenter cette fonction en m'aidant d'une vidéo YouTube pour comprendre la logique technique).

Scikit-Learn : Pour toute la partie Machine Learning et Classification.

 Analyse et Nettoyage des Data
 J'ai commencé par une étape cruciale de nettoyage des animés désordonnés :Conversion des colonnes de notes et d'épisodes en formats numériques exploitables.Gestion des valeurs manquantes et suppression des doublons pour ne pas fausser les statistiques.Formatage des noms d'animés en MAJUSCULES (upper) pour un rendu visuel plus professionnel dans les tableaux finaux.
 
  Classification, Prédictions et MétriquesLa partie Classification a été l'étape la plus technique et la plus difficile du projet. J'ai utilisé une Régression Logistique pour prédire si un animé est "Excellent" (Note $\ge$ 8.5).Performance : Malgré la difficulté, j'ai réussi à obtenir une Accuracy de 95%, ce qui valide la fiabilité de mes prédictions.Métriques : J'ai généré une matrice de confusion et un rapport détaillé pour prouver la robustesse du modèle.

  Contenu du dossier
notebook_final.ipynb : L'intégralité des codes source et analyses.

animes.csv : La base de données propre.

Visualisations/ : Dossier contenant les graphiques (graphiques.png), l'histogramme des notes (histogramme.png) et mon nuage de mots personnalisé (nuage.png).
