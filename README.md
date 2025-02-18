# analyse statistique des salaires d'employes

## Objectif du Projet

Ce projet a pour objectif d'analyser les disparités salariales des employés de la ville de San Francisco en fonction de différents facteurs, tels que les années, les départements et les métiers. L'analyse inclut également l'impact des heures supplémentaires sur les salaires, ainsi que la détection d'anomalies dans les données salariales.

### Étapes principales :
1. **Analyse temporelle des salaires** : Suivi de l’évolution des salaires et des avantages de 2013 à 2020.
2. **Comparaison entre départements et métiers** : Identification des départements avec les salaires les plus élevés et comparaison des familles de métiers.
3. **Analyse des disparités salariales** : Comparaison des salaires des employés permanents vs temporaires, ainsi que les écarts au sein des départements.
4. **Analyse des heures supplémentaires** : Étudier l’impact des heures supplémentaires sur les salaires et détecter des anomalies dans les volumes d'heures.
5. **Segmentation des employés (Clustering)** : Regroupement des employés en fonction de leurs salaires et avantages pour identifier des profils types.

## Technologies et Méthodes Utilisées

- **Python** avec les bibliothèques :
  - **Pandas** : pour la manipulation des données.
  - **NumPy** : pour les calculs numériques.
  - **Matplotlib** et **Seaborn** : pour la visualisation des données.
  - **Scikit-learn** : pour la segmentation des employés (clustering).
  - **Scipy** : pour les tests statistiques, notamment le test de Kruskal-Wallis.
- **Jupyter Notebook** : pour réaliser les analyses de manière interactive et documentée.

## Résultats

- **Test de Kruskal-Wallis** : A permis de vérifier s'il existe des différences significatives dans les salaires en fonction des années.
- **Segmentation des employés** : Identification de plusieurs groupes distincts d'employés en fonction des salaires et avantages, avec des profils types pour chaque cluster.
- **Disparités salariales** : Les employés permanents ont des salaires plus élevés que les temporaires, et des différences notables existent entre les départements.
- **Heures supplémentaires** : Certains métiers comme la police et la santé génèrent plus de revenus grâce aux heures supplémentaires.

### Exécution

telecharger le data frame depuis kaggle:

import kagglehub

#Download latest version

path = kagglehub.dataset_download("siddheshera/san-francisco-employee-salary-compensation")
print("Path to dataset files:", path)

Ouvrez le fichier Jupyter Notebook analyse_salaires_heures_supplementaires.ipynb.
Exécutez les cellules pour effectuer l'analyse des données et visualiser les résultats.

## Conclusion
Cette analyse permet de mieux comprendre les disparités salariales parmi les employés de la ville de San Francisco. Elle met en lumière les tendances temporelles, les différences entre départements et métiers, ainsi que l'impact des heures supplémentaires sur les salaires. La segmentation des employés en différents groupes aide à identifier des profils types et à mieux cibler les actions et décisions.

## Développé par Brunel Kompaore
