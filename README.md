# Tp_Svm_Festor_Quentin

Description
L'objectif de ce travail pratique (TP) est de se familiariser avec l'utilisation des machines à vecteurs de support (SVM) pour le classement de données, en utilisant le package scikit-learn en Python et la base de données Iris. Nous avons exploré plusieurs types de noyaux (linéaire et polynomial) afin d'expérimenter différentes méthodes de séparation. De plus, nous avons employé la validation croisée pour évaluer la performance de nos modèles et mettre en évidence l'impact du paramètre de régularisation C sur leurs performances.

Pour approfondir notre compréhension des SVM et du rôle crucial du paramètre C dans la séparation des données, nous avons développé une interface graphique en compilant le code présent dans le fichier svm_gui.py, situé dans le dossier src.

Enfin, nous avons appliqué nos modèles à une base de données de visages pour réaliser de la reconnaissance faciale, examiner l'impact de l'ajout de variables bruitées, et observer comment la réduction des dimensions de nos données bruitées via l'analyse en composantes principales (ACP) peut améliorer les performances.

## Organisation

Le dossier docs contient le pdf final [https://github.com/Qufst/Tp_Svm_Festor_Quentin/blob/main/docs/Tp_apprentissage_statistique.pdf](ici)

Le dossier fichier_python comprend les fichiers suivants :

  - svm_script.py : le script principal du TP
  - svm_source.py : le code source fourni
  - svm_gui.py : le code pour l'interface graphique

Le dossier tex contient :

  - main.tex : le fichier .tex du rapport

L'annèxe du tp se nomme [https://qufst.github.io/Tp_Svm_Festor_Quentin/annexe.html](annexe.qmd)

On retrouve les dépendances du projet dans le fichier environment.yml et le dispositif de publication de l'énnèxe dans le _quarto.yml

Prérequis
Pour exécuter le code de ce projet, il est impératif d'avoir une version récente de Python et d'installer les packages suivants :

  - python=3.10
  - jupyter
  - matplotlib
  - numpy
  - nbformat
  - scikit-learn  
  - seaborn
  - pandas        
  - scipy         
  - ipykernel
  - pyyaml  

De plus, un compilateur LaTeX est requis pour générer le rapport, on peut utiliser overleaf par exemple.

Auteur: Festor Quentin [https://github.com/Qufst](github)