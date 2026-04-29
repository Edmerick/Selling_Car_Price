# 🚀 [Car Model Prédiction] – Machine Learning

📌 Description
Ce projet consiste à développer un modèle de Machine Learning permettant de prédire le prix de vente d'un véhicule en fonction de plusieurs caractéristiques techniques et d'usage, telles que le kilométrage, le prix actuel sur le marché, le type de carburant et l'âge du véhicule.

🎯 Objectif
Construire un modèle performant de régression pour l'estimation de prix.


Optimiser la précision des prédictions financières.


Déployer une interface permettant d'obtenir une estimation instantanée.


📊 Données
Variables principales:


Kms_Driven : Kilométrage parcouru.
Present_Price : Prix actuel du marché (neuf).
Fuel_Type : Essence, Diesel, GNV.
Seller_Type : Particulier ou Revendeur.
Transmission : Manuelle ou Automatique.
Age : Nombre d'années depuis la mise en circulation.
⚙️ Méthodologie
🔹 Étapes

Nettoyage des données et gestion des valeurs manquantes.
Encodage des variables catégorielles (Fuel Type, Transmission, etc.).
Ingénierie des caractéristiques (calcul de l'âge du véhicule).
Séparation Train/Test.
Entraînement et comparaison des modèles de régression.
Évaluation des métriques (MAE, MSE, R²).
Déploiement.
🤖 Modèles utilisés

Random Forest Regressor
XGBoost Regressor
Linear Regression
📈 Résultats (Exemple)

## 📈 Résultats

| Métrique  | Score |
| --------- | ----- |
| R² Score  | 0.92  |
| MAE       | 0.85  |
| RMSE      | 1.20  |
| F1-score  | 0.83  |


🖼️ Aperçu de l’application


🚀 Démo en ligne
👉 GitHub : https://github.com/Edmerick/Car_Price_Prediction
👉 huggingface : https://huggingface.co/spaces/Edmerick/Selling_car


project/
│
├── data/             # Jeu de données (CSV)
├── models/           # Modèles entraînés (.pkl)
├── app.py            # Interface utilisateur (Gradio/Streamlit)
├── train.py          # Script d'entraînement
├── requirements.txt  # Dépendances
└── README.md         # Documentation


🛠️ Technologies utilisées

Python
scikit-learn / XGBoost
Pandas / NumPy
Gradio ou Streamlit (pour l'interface)
📌 Améliorations possibles

Intégration de la marque et du modèle spécifique du véhicule.
Optimisation des hyperparamètres via GridSearchCV.
Ajout d'une analyse de la dépréciation annuelle.

## 👤 Auteur

* Nom : KOUAKOU Edmond Brice
* Email : bricekouakou@gmail.com
* GitHub : https://github.com/Edmerick

---

## 📄 Licence

Ce projet est sous licence DIT.

---
