# 🛡️ Conception & Implémentation d'une Base de Données pour la Détection de Fraude et la Gestion AML/KYC

## 🏫 Cadre du Projet
* **Établissement :** École Supérieure des Communications de Tunis (SUP'COM)
* **Année Universitaire :** 2025-2026
* **Projet :** Ingénierie des Bases de Données (MCD / MLD / SQL)

---

## 📝 Présentation du Projet
Ce projet consiste à modéliser et déployer un moteur de base de données relationnelle robuste sous **Oracle SQL**, spécialement conçu pour répondre aux exigences réglementaires strictes de la finance moderne (directives **AML - Anti-Money Laundering** et procédures **KYC - Know Your Customer**).

Le système centralise et analyse en continu d'importants volumes de données financières afin d'automatiser l'identification d'anomalies, d'atténuer les risques bancaires et de bloquer les tentatives de fraude.

---

## 🛠️ Contenu du Repository
Ce dossier centralise l'ensemble des livrables de notre ingénierie :
* **`cahier_des_charges.pdf`** : Le document de spécification détaillant le contexte général, les règles de gestion bancaire et les contraintes réglementaires.
* **`Presentation_projet.pdf`** : Le support visuel complet détaillant les apports, objectifs et résultats du système.
* **`Looping1 (1).jpg`** : Le modèle conceptuel et logique des données (MCD/MLD) généré sur Looping pour cartographier les interactions complexes (Clients, Comptes, Transactions, Logs KYC, Dispositifs d'Alerte).

---

## 🧠 Algorithmes & Requêtes SQL Clés Déployés
La base de données intègre plus de 30 scripts d'analyse de données complexes et d'audits de sécurité. Parmi les requêtes majeures implémentées, on retrouve :

1. **Détection du *Structuring* (Fractionnement de fonds) - [Requête 29] :**
   Algorithme SQL détectant les transactions répétées s'approchant volontairement du seuil légal déclaratif (montants ciblés entre **9 000 € et 9 999 €** sur une fenêtre glissante de 7 jours).
   
2. **Audit de Sécurité Interne (Espionnage de données) - [Requête 27] :**
   Identification immédiate des employés accédant à des dossiers clients hors de leur périmètre géographique ou d'agence (complicité interne ou fuite de données).

3. **Violation des Règles de Conformité KYC - [Requêtes 28 & 30] :**
   * Filtrage et isolation des transactions initiées par des clients dont les documents d'identité réglementaires sont expirés.
   * Traçabilité et scoring des acteurs ayant accumulé plusieurs refus successifs lors de la vérification de leur identité (suspicion d'usurpation).

---

## 🛠️ Technologies Utilisées
* **SGBDR :** Oracle SQL (PL/SQL)
* **Modélisation :** Looping (Génération des MCD / MLD)
* **Réglementations cibles :** FATF/GAFI Recommendations, Directives Européennes AML/KYC, Loi Tunisienne de lutte contre le blanchiment d'argent.
