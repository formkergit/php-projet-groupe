# PROJETS PHP - GROUPES

## SUJETS DISPONIBLES

### 1. SYSTÈME DE GESTION DE BIBLIOTHÈQUE

- Catalogue de livres (CRUD complet)
- Système d'emprunt/retour
- Recherche multicritères
- Gestion des utilisateurs
- Historique des emprunts

### 2. PLATEFORME DE RÉSERVATION

- Réservation de créneaux horaires
- Calendrier interactif
- Gestion des disponibilités
- Tableau de bord admin

### 3. GESTIONNAIRE DE TÂCHES COLLABORATIF

- Création/assignation de tâches
- Statuts et priorités
- Filtres et tri
- Commentaires sur tâches
- Statistiques d'avancement

### 4. SYSTÈME DE BLOG/CMS MULTI-AUTEURS

- Publication d'articles
- Catégories et tags
- Commentaires modérés
- Système de recherche
- Panneau d'administration

### 5. PLATEFORME DE PETITES ANNONCES

- Publication d'annonces
- Système de catégories
- Recherche avancée
- Messagerie interne
- Gestion des favoris

### 6. APPLICATION DE GESTION D'ÉVÉNEMENTS

- Création d'événements
- Inscriptions en ligne
- Limitation de places
- Export des participants
- Interface de suivi

---

## ORGANISATION DU TRAVAIL EN GROUPE

### RÉPARTITION DES RÔLES
Chaque membre assume une fonction :
- **Dev 1**(Chef de projet) : coordination, planning, git
- **Dev 2** (Développeur back) : logique PHP, base de données
- **Dev 4** (Développeur front) : HTML/CSS, intégration

Les rôles doivent tourner selon les fonctionnalitées développées.

### WORKFLOW GIT
```
main
  ├── dev
  │   ├── feature/nom-fonctionnalite-membre1
  │   ├── feature/nom-fonctionnalite-membre2
  │   └── feature/nom-fonctionnalite-membre3
```

**Procédure de travail :**
1. Créer une branche feature depuis dev
2. Développer la fonctionnalité
3. Commit réguliers avec messages clairs
4. Pull request vers dev
5. Review par un autre membre
6. Merge après validation
7. Merge dev → main en fin de semaine

**Règles Git :**

- Commits atomiques
- Messages en français, impératif présent
- Pas de push direct sur main
- Résolution des conflits en équipe

### STRUCTURE DE PROJET IMPOSÉE

Chaque groupe est libre d'organiser sa structure à sa guise.

### PLANNING SEMAINE (Indicatif)

- **Jour 1 :** Architecture, base de données, setup Git
- **Jour 2-3 :** Développement des fonctionnalités
- **Jour 4 :** Intégration, tests, debugging
-  **Jour 5 :** Finalisation, préparation présentation

---

## LIVRABLES

### 1. DÉPÔT GIT

- Historique complet des commits
- Branches feature visibles
- README.md détaillé du projet

### 2. CODE SOURCE

- Fichier SQL de création de base
- Code commenté si il nécéssite une explicatrion (éviter à tout de mettre des commentaires fa   it par LLM)
- Validation des données (formulaires)
- Protection contre injections SQL

### 3. DOCUMENTATION TECHNIQUE

Fichier `DOCUMENTATION.md` contenant :

- Diagramme de base de données
- Liste des fonctionnalités implémentées
- Difficultés rencontrées
- Répartition du travail (qui a fait quoi)

### 4. SUPPORT DE PRÉSENTATION

Format PDF ou slides (10-12 slides max) :

- Présentation du projet
- Démonstration des fonctionnalités
- Choix techniques justifiés
- Rétrospective d'équipe

### 5. APPLICATION FONCTIONNELLE

- Déployée localement ou en ligne
- Base de données avec données de test
- Fichier `INSTALL.md` avec procédure complète

**Date limite :** Vendredi 
**Passage à l'oral :** 14h00
**Remise :** Lien Git + URL de démo (si en ligne)

---

## PRÉSENTATION ORALE

### FORMAT

- **Durée :** 20 minutes + 5 minutes questions
- **Tous les membres** doivent prendre la parole
- Démonstration en direct obligatoire

### STRUCTURE RECOMMANDÉE

1. **Introduction** (2 min) : Contexte, objectifs
2. **Démonstration** (8 min) : Parcours utilisateur complet
3. **Technique** (3 min) : Architecture, difficultés
4. **Conclusion** (2 min) : Bilan, améliorations futures

### CRITÈRES D'ÉVALUATION ORALE

- Clarté de la présentation
- Maîtrise du sujet
- Qualité de la démonstration
- Répartition équilibrée de la parole
- Réponses aux questions

---

## BARÈME DE NOTATION /20

### CODE ET FONCTIONNALITÉS /10

- **Fonctionnalités complètes** : /4
  - Toutes les features du sujet implémentées
  - Cas d'erreur gérés
  - Cohérence globale
  
- **Qualité du code** : /3
  - Structure claire et logique
  - Nommage cohérent
  - Pas de répétition (DRY)
  - Sécurité (SQL, XSS, CSRF)
  
- **Base de données** : /2
  - Schéma normalisé
  - Relations correctes
  - Requêtes optimisées
  
- **Git et collaboration** : /1
  - Historique propre
  - Branches et PR(Pull Request) utilisées
  - Répartition équilibrée des commits

### PRÉSENTATION ORALE /6

- **Qualité de la démo** : /2
  - Application fonctionnelle
  - Scénario cohérent
  - Gestion des imprévus
  
- **Explication technique** : /2
  - Choix justifiés
  - Compréhension de l'architecture
  - Clarté des explications
  
- **Communication** : /2
  - Répartition de la parole
  - Support visuel pertinent
  - Gestion du temps
  - Réponses aux questions

### DOCUMENTATION /4

- **README.md** : /1
  - Installation claire
  - Présentation du projet
  
- **DOCUMENTATION.md** : /2
  - Diagramme Base de donnée (MCD)
  - Répartition du travail
  - Analyse rétrospective
  
- **Code et structure** : /1
  - Arborescence du projet cohérente
  - Fichiers SQL fournis
  - Procédure d'installation testable

---

## RESSOURCES

### TECHNIQUES

- PDO et prepared statements (sécurité)
- Sessions PHP (authentification)
- Router PHP
- Validation côté serveur
- Gestion d'erreurs

### OUTILS

- Git/GitHub
- PHPMyAdmin ou Adminer
- VSCode + extensions PHP
- XAMPP/WAMP/MAMP , Stack Docker

### AIDE

- Documentation PHP : php.net
- Pair programming entre membres
- Questions au formateur (pas de solution complète)
