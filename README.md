# 🔐 Système de Détection d'Intrusions basé sur le Machine Learning

Projet de Fin d'Études réalisé dans le cadre de la Licence en Sciences Mathématiques et Informatiques (SMI) à l'Université Ibn Tofaïl.

## 👩‍💻 Réalisé par :
- **Adam Amzir**
- **Fadwa Sennouni**

## 📘 Encadré par :
- **Pr. Alami Chentoufi Jihane**
- **Pr. Laassiri Jalal (Examinateur)**
- **Pr. Enneya Nourddine (Examinateur)**

---

## 📌 Objectif
Ce projet a pour but de concevoir un **système de détection d'intrusions (IDS)** capable d’identifier différentes menaces comme les attaques DoS, le spoofing IP, etc., à l’aide de **l’algorithme K-Nearest Neighbors (K-NN)**.

---

## 🧪 Technologies et outils
- **Python**
- **Pandas, NumPy, Scikit-learn**
- **Google Colab (pour l'entraînement et les tests)**
- **Matplotlib / Seaborn (visualisation)**

---

## 📂 Fichiers inclus
- `pfe_definitive.py` : script principal avec prétraitement, entraînement et simulation d'attaques.
- `PFE_IDS.ipynb` : notebook Jupyter complémentaire.
- `rapport_pfe.pdf` : le rapport complet du projet.
- `Train_data.csv` & `Test_data.csv` : données d’entraînement/test utilisées.
- `requirements.txt` : dépendances Python.

---

## 🚀 Comment exécuter le projet
1. Cloner le dépôt :
```bash
git clone https://github.com/0xDant3/Systeme-de-Detection-d-Intrusions-base-sur-le-Machine-Learning
```

2. Installer les dépendances :
```bash
pip install -r requirements.txt
```

3. Lancer le script :
```bash
python pfe_definitive.py
```

📝 Résultats
Le modèle KNN atteint un score de précision élevé sur les données simulées et réelles. Il permet de détecter efficacement les comportements anormaux dans un trafic réseau.

📄 Rapport
Le rapport détaillé du projet est disponible dans rapport_pfe.pdf.
