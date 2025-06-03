# 🥊 Initialisation de la base de données avec des boxeurs olympiques

Ce projet recense des boxeurs olympiques dans les catégories **Poids mouche** et **Poids lourd**, en utilisant un fichier JSON pour initialiser la base de données de manière automatique.

## ✅ Objectif

Utiliser le fichier `boxers_jo.json` pour insérer automatiquement 10 boxeurs dans la base de données avec leurs caractéristiques (attaque, défense, nationalité, etc.).

## 📦 Contenu attendu du fichier JSON

Le fichier JSON contient une liste de boxeurs avec les champs suivants :

- name : nom du boxeur  
- nationality : nationalité  
- weight_class : catégorie de poids  
- olympic_year : année de participation aux JO  
- attack_points : points d’attaque (sur 100)  
- defense_points : points de défense (sur 100)  

## 🛠️ Étapes générales

1. Placer le fichier `boxers_jo.json` dans le dossier de l'application.
2. S'assurer que le modèle `Boxer` existe avec les champs correspondants.
3. Adapter le fichier `seeds` de l'application pour lire ce fichier JSON et créer les enregistrements en base de données.
4. Exécuter les seeds pour initialiser la base.
5. Vérifier que les boxeurs sont bien affichés dans la liste de l'application.

## 📁 Fichier fourni

Le fichier `boxers_jo.json` est joint à ce projet et doit être utilisé pour l’import.
