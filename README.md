# 🚀 TooCool - La Plateforme No-code  

## 📌 Présentation  

**TooCool** est une application développée pour générer une IHM via des fichiers Excel et CSV.  
L’outil permet de convertir ces fichiers en **bases de données exploitables**, en générant automatiquement les **structures nécessaires** pour les projets métiers, sans intervention manuelle sur le schéma des bases.  

> **Objectif 🎯** : Offrir un moyen flexible et dynamique de **gérer les données**, en partant de fichiers bruts pour générer des outils et **centraliser les informations**.

---

## 🎯 Contexte & Enjeux  

Dans des environnements où les fichiers **Excel et CSV** sont largement utilisés, plusieurs défis émergent :  

❌ **Données non structurées** – Pas de normalisation ni de contraintes définies.  
❌ **Difficulté de collaboration** – Écriture concurrente non gérée, pertes de données possibles.  
❌ **Absence de suivi** – Impossible de tracer les modifications effectuées sur les fichiers.  
❌ **Problèmes de performances** – Manipuler de grands fichiers Excel devient inefficace.  

📌 **Solution apportée par TooCool** :  

✅ **Parsing et structuration des fichiers de données** (Excel / CSV).  
✅ **Génération dynamique de bases de données et de tables adaptées aux fichiers importés**.  
✅ **Automatisation des imports, historisation et gestion des accès**.  
✅ **Outils métiers accessibles en interface web** à partir des données transformées.  

---

## 🛠️ Fonctionnalités Techniques  

### 📂 1. Parsing et Transformation de Données  
- **Lecture et extraction automatique des données** des fichiers Excel et CSV.  
- **Identification des types de colonnes** pour optimiser le stockage en base.  
- **Nettoyage et validation des données** avant intégration.  

### 🏗️ 2. Génération Dynamique de Bases de Données  
- **Création automatique des schémas SQL** en fonction des fichiers importés.  
- **Définition des types de colonnes** (INT, VARCHAR, DATE…) pour optimiser les requêtes.  
- **Gestion de la cohérence et des contraintes d'intégrité** (clés primaires, relations…).  

### 🔄 3. Automatisation de l'Import & Suivi des Modifications  
- **Chargement et stockage des données en base** en conservant l’historique des imports.  
- **Suivi des modifications** (versioning des données et logs d’activité).  
- **Gestion des accès utilisateurs** et des permissions sur les bases créées.  

### 🌐 4. Interface Web pour Exploiter les Données  
- **Consultation, modification et export des données** depuis une interface.  
- **Création de portails pour regrouper plusieurs bases et outils générés**.  
- **Gestion des utilisateurs et des rôles d’administration**.  

---

## 📼 Démonstration Vidéo  

📹 **Présentation des fonctionnalités en vidéo** :  

1️⃣ [Connexion et authentification](#) – `1.-TooCool-Connexion.mp4`  
2️⃣ [Vue globale de l’application de la plateforme](#) – `2.-TooCool-Présentation Plateforme.mp4`  
3️⃣ [Importation et parsing de fichiers Excel](#) – `3.-TooCool-Import-xlsx.mp4`  
4️⃣ [Importation et parsing de fichiers CSV](#) – `3.1-TooCool-Import-csv.mp4`  
5️⃣ [Utilisation des outils générés](#) – `4.-TooCool-Présentation-Outil_Généré.mp4`  
6️⃣ [Création et gestion de portails](#) – `5.-TooCool-Portail.mp4`  
7️⃣ [Administration et gestion des bases](#) – `6.-TooCool-Admin.mp4`  


---

## 📖 Guide d'Utilisation  

📕 **Le document [Guide TooCool.pdf](Guide TooCool.pdf)** détaille l'utilisation de l’application :  

✔️ **Présentation de l’outil et de ses cas d’usage**.  
✔️ **Connexion et inscription des utilisateurs**.  
✔️ **Import et paramétrage des fichiers de données**.  
✔️ **Utilisation des outils générés et suivi des modifications**.  
✔️ **Gestion des bases et administration des portails**.  

---

## 🏗️ Technologies Utilisées  

🔹 **Base de Données** : MySQL, PostgreSQL 🗄️  
🔹 **Backend** : PHP (Symfony) 🖥️  
🔹 **Interface Web** : HTML, CSS, JavaScript 🌍  
🔹 **Automatisation & Scripts** : Python 🛠️  

---

## ⚠️ Confidentialité & Mentions Légales  

🔒 **Ce projet a été développé en 2021 dans un cadre professionnel chez EDF**.  
🔒 **Les codes sources ne sont pas publiés ici** pour des raisons de confidentialité.  
