# 📑 Architecture du Projet MedHead

## 📌 Introduction

Ce repository contient la documentation d’architecture pour la **Preuve de Concept (PoC)** du **système d’intervention d’urgence en temps réel** du consortium **MedHead**. L’objectif de cette PoC est de **valider l’architecture cible** en testant l’attribution optimisée des lits d’hôpital pour les urgences.

---

## 🎯 Objectifs

- **Évaluer la faisabilité** de l’architecture cible en conditions réelles.
- **Optimiser le processus d’attribution des lits** pour les patients en urgence.
- **Réduire le temps de traitement des urgences** (objectif : **12 minutes** au lieu de **18,25 minutes**).
- **Garantir un temps de réponse < 200ms** sous **800 requêtes/sec** par service.
- **Respecter les normes et principes architecturaux** (microservices, RGPD, TOGAF).
- **Documenter les enseignements** pour guider le développement futur.

---

## 📁 Structure du Repository

### 🔹 1. Documents d'Architecture
- [`01-Principes_de_l'architecture.pdf`](./01-Principes_de_l'architecture.pdf)  
  → Contient les **principes fondamentaux** guidant la conception du système.
  
- [`02-Document_de_définition_de_l'architecture.pdf`](./02-Document_de_définition_de_l'architecture.pdf)  
  → Détaille l'**architecture cible** et la feuille de route du projet.

- [`03-Déclaration_des_travaux_d'architecture.pdf`](./03-Déclaration_des_travaux_d'architecture.pdf)  
  → Décrit le **périmètre de la PoC** et les livrables attendus.

- [`04-Données_de_référence_sur_les_spécialités_NHS.pdf`](./04-Données_de_référence_sur_les_spécialités_NHS.pdf)  
  → Liste les **spécialités médicales** pour la gestion des lits hospitaliers.

- [`05-Exigences_PoC.pdf`](./05-Exigences_PoC.pdf)  
  → Spécifie les **besoins techniques et fonctionnels** de la PoC.

### 🔹 2. Reporting et Analyse
- [`06-Reporting_PoC.md`](./06-Reporting_PoC.md)  
  → Synthèse des résultats de la PoC : **performances, conformité, apprentissages**.

- [`07-Feuille_de_route.md`](./07-Feuille_de_route.md)  
  → Plan détaillant les **prochaines étapes** du projet après validation de la PoC.

---

## 🛠️ Instructions d’Utilisation

### 📥 1. Cloner le Repository
```bash
git clone https://github.com/votre-repo/architecture-medhead.git
cd architecture-medhead
