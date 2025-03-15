# TP : Manipulation des formats Avro et Parquet

Ce notebook explore l'utilisation des formats **Avro** et **Parquet** en Python pour stocker et manipuler des données efficacement.

## 📌 Objectifs
- Comprendre le format Avro et son utilisation en Python.
- Lire et écrire des fichiers Avro avec `fastavro` et `pandavro`.
- Convertir des données en format Parquet avec `pyarrow`.

## 📂 Contenu du TP
### 1️⃣ Installation des dépendances
Le notebook commence par installer les bibliothèques nécessaires :
```bash
!pip install fastavro pandavro pyarrow python-snappy pandas
```

### 2️⃣ Manipulation du format Avro
- Définition d'un schéma Avro en JSON.
- Écriture de données au format Avro.
- Lecture des fichiers Avro avec fastavro.
- Utilisation de Pandas pour convertir un DataFrame en Avro.
### 3️⃣ Conversion en format Parquet
- Transformation d'un DataFrame Pandas en table Arrow.
- Écriture et lecture d'un fichier Parquet avec pyarrow.
#### 🔗 Lien vers le Notebook
- Accéder au notebook sur GitHub : https://github.com/gackouhamady/TP1_Parquet_Avro/blob/main/Parquet_Avro.ipynb

### 🛠 Technologies utilisées
- Python
- fastavro / pandavro pour Avro
- pyarrow pour Parquet
- Pandas pour la manipulation des données
### 🚀 Exécution
- Exécutez le notebook sur Google Colab ou localement après avoir installé les dépendances.

📧 Auteur : Hamady Gackou


