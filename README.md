# Support vector machine contre régression logistique en Médecine

Ce projet GitHub vise à comparer un classifier **SVM (Support Vector Machine)** avec une **Régression Logistique** dans le domaine médical.    
L'objectif est de trier les patients en deux catégories : malades et non malades.   
Pour cela, nous réaliserons une analyse supervisée classique en utilisant les deux algorithmes de classification.    
Le projet comprendra également les étapes de traitement des données pour gérer les valeurs manquantes et la standardisation des données.     
Enfin, nous visualiserons les résultats obtenus pour comparer la performance des deux modèles.

### Contenu du Projet
Le projet est structuré trois grandes parties.    

**Chargement et Exploration des Données**
Dans cette première étape, nous chargerons les données médicales pour les patients et effectuerons une analyse exploratoire pour mieux comprendre la distribution des données.

**Traitement des Données**    
Nous effectuerons des opérations de nettoyage et de prétraitement sur les données, y compris la gestion des valeurs manquantes et la préparation des données pour la classification.

**Standardisation des Données**
Nous standardiserons les données pour mettre toutes les variables à la même échelle et améliorer les performances des algorithmes de classification.

**Classification avec SVM**   
Nous entraînerons un classifier SVM sur les données pour trier les patients en deux catégories : malades et non malades.

**Classification avec Régression Logistique**     
Nous entraînerons une Régression Logistique sur les données pour réaliser le même tri des patients en fonction de leur état de santé.

**Visualisation des Résultats**    
Nous visualiserons les résultats des deux modèles de classification pour comparer leurs performances.

### Prérequis
Nous travaillons dans l'environnement suivant :     

Python 3.x    
pandas     
numpy      
scikit-learn     
matplotlib      
seaborn

### Structure des Fichiers

├── notebook.ipynb     
├── data    
│   ├── medical_data.csv     
└── README.md     

Le dossier "data" contient le fichier CSV des données médicales pour les patients.     
Le fichier notebook.ipynb est un cahier Jupyter contenant tout le code et les analyses du projet.      
Le fichier README.md est le présent document, fournissant une description détaillée du projet.      

### Conclusion
Ce projet permet de comparer deux algorithmes de classification couramment utilisés, SVM et Régression Logistique, dans le domaine médical pour trier les patients en deux catégories : malades et non malades.     
En effectuant une analyse supervisée classique et en visualisant les résultats, nous pourrons évaluer et comparer les performances des deux modèles.    
Le traitement des données pour gérer les valeurs manquantes et la standardisation des données sont des étapes essentielles pour améliorer la qualité des prédictions et permettre une comparaison équitable entre les deux algorithmes de classification.
