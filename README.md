# Plateforme Sociale Étudiante  
**TP : Gestion Avancée de Sessions & Interactions Ajax**  

---

## 📌 Aperçu du Projet  
Application web de réseau social axée sur :  
- **Gestion d'utilisateurs** (connexion sécurisée, inscriptions)  
- **Réseau social minimaliste** (recherche/ajout d'amis dynamique)  
- **Notifications en temps réel**  
- *Module de publications (en développement)*  

---

## 🎯 Fonctionnalités Clés  

### ✔️ **Authentification**  
- Sessions PHP sécurisées avec contrôle de rôle  
- Protection contre les injections SQL et validation des entrées  

### ✔️ **Système Social**  
1. **Recherche Instantanée**  
   - Auto-complétion Ajax sans rechargement  
   - Filtrage côté serveur par nom/prénom  

2. **Gestion des Relations**  
   - Envoi/annulation d'invitations via Ajax  
   - Statuts dynamiques : *"Inviter"* → *"En attente"*  
   - Liste d'amis mise à jour en temps réel  

3. **Notifications**  
   - Compteur dynamique dans la barre de navigation  
   - Polling Ajax toutes les 5 secondes  

---

## 🛠 Stack Technique  
- **Backend** : PHP 7.4+, MySQL (procédures stockées)  
- **Frontend** : JavaScript Vanilla, Ajax, CSS Grid/Flexbox  
- **Sécurité** : Sanitisation des données, sessions chiffrées  
- **Outils** : XAMPP, phpMyAdmin  

---

## 📥 Installation  
1. **Base de Données**  
   - Importer `social_network.sql` (structure + données de test)  
   - Configurer `db.php` avec vos identifiants  

2. **Serveur**  
   - Accès écriture requis : `uploads/` (photos de profil)  
   - Compatible Apache/Nginx  

---

## 🚧 Travail en Cours  
### Publications & Interactions Sociales  
- **État Actuel** :  
  - Schéma de base de données finalisé (`posts`, `likes`)  
  - Interface HTML/CSS prête à l'intégration  

- **Prochaines Étapes** :  
  - Système de commentaires Ajax  
  - Affichage paginé des publications  



*"Ce TP m'a permis de maîtriser l'orchestration de sessions PHP avec des interactions Ajax fluides."*  

--- 
