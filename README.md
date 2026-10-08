# Projet Poubelle CY TECH - Système de Gestion du Recyclage

## 🇫🇷 Description en Français
**Projet Poubelle** est une application de gestion de déchets et de recyclage intégrant un système de récompenses. Ce projet académique simule un écosystème où les ménages (`Compte`) effectuent des dépôts dans des poubelles spécifiques pour accumuler des points de fidélité. Ces points peuvent être échangés contre des bons de réduction (`BonReduction`) utilisables lors de l'achat de produits dans des commerces partenaires. Le système intègre également des centres de tri (`CentreDeTri`) qui gèrent la collecte des poubelles et les contrats avec les commerces.

### Fonctionnalités Clés
* **Gestion des Utilisateurs :** Connexion au compte via email et mot de passe, dépôt de déchets selon les poubelles autorisées, et consultation de l'historique des dépôts.
* **Système de Fidélité :** Conversion de la valeur des dépôts en points de fidélité et échange contre des bons de réduction.
* **Réseau de Recyclage :** Administration des centres de tri, placement ou retrait de poubelles à des adresses spécifiques, et ramassage des déchets.
* **Réseau Commercial :** Création de contrats de partenariat entre les centres de tri et les commerces, et application de taux de réduction sur des catégories spécifiques de produits.
* **Tests Intégrés :** Couverture du code assurée par une suite de tests unitaires sur les classes et l'architecture DAO.

### Technologies Utilisées
* **Langage :** Java
* **Interface Graphique :** JavaFX avec vues FXML (`LoginView.fxml`)
* **Base de Données :** MySQL (connecteur JDBC `mysql-connector-j-9.3.0`)
* **Architecture :** Pattern d'accès aux données (DAO) et conception Modèle-Vue-Contrôleur

---

## 🇬🇧 EcoBin (Projet Poubelle CY TECH) - Smart Waste Management System

### Description
**EcoBin** is a smart waste management and recycling application featuring a built-in user reward system. This project simulates an ecosystem where households (`Compte`) deposit waste into designated smart bins to earn loyalty points. These points can then be redeemed for discount vouchers (`BonReduction`) applicable to products at partner stores. The architecture also encompasses sorting centers (`CentreDeTri`) responsible for deploying bins, collecting waste, and managing active partnerships with local businesses.

### Key Features
* **User Management:** Secure account login, authorized waste deposits, and deposit history tracking
* **Loyalty & Rewards:** Automatic calculation of deposit value into fidelity points, which can be exchanged for usable discount vouchers
* **Recycling Network:** Operations management for sorting centers, including placing bins at specific addresses and executing waste collection routines
* **Commercial Partnerships:** Establishing active contracts between sorting centers and retail stores to provide dynamic discounts on specific product categories
* **Integrated Testing:** Comprehensive testing suite targeting data access objects (DAO) and core business logic models

### Built With
* **Language:** Java
* **GUI:** JavaFX (FXML files)
* **Database:** MySQL (JDBC Connector `mysql-connector-j-9.3.0`)
* **Architecture:** Data Access Object (DAO) pattern and Model-View-Controller design
