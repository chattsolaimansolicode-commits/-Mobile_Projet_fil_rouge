---
marp: true
theme: default
size: 16:9
paginate: true
style: |
  section {
    font-family: "Aptos", "Segoe UI", sans-serif;
    background: #f8fafc;
    color: #172033;
    padding: 48px 64px;
  }
  h1, h2 {
    color: #243b6b;
  }
  h1 {
    font-size: 2.4em;
  }
  h2 {
    font-size: 1.8em;
    margin-bottom: 0.7em;
  }
  ul {
    font-size: 1.25em;
    line-height: 1.65;
  }
  section.title-slide {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    gap: 12px;
    padding: 32px 48px 40px;
  }
  section.title-slide .brand-row {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 28px;
    width: 100%;
    margin: 8px 0 18px;
  }
  section.title-slide .brand-row img {
    max-height: 88px;
    width: auto;
    object-fit: contain;
    filter: drop-shadow(0 3px 8px rgba(36, 59, 107, 0.12));
  }
  section.image-only {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 12px;
    padding: 24px;
  }
  section.image-only img {
    max-width: 96%;
    max-height: 78%;
    object-fit: contain;
  }
  section.diagram-slide img {
    display: block;
    max-width: 90%;
    max-height: 440px;
    width: auto;
    margin: 0 auto;
    object-fit: contain;
  }
---

<!-- _class: title-slide -->

# Rapport de projet TradeSim

### Virtual Stock Trading Platform

<div class="brand-row">
  <img src="ofppt.png" alt="Logo OFPPT" />
  <img src="solicode.png" alt="Logo SOLICODE" />
</div>

**Solaiman Chatt**

Encadrant : ES-Sarraj Fouad

Année de formation : 2026–2027

---

## Remerciements

---

## Introduction

- Présentation du domaine de la bourse et du trading.
- Importance de l'apprentissage des marchés financiers.
- Présentation générale de TradeSim.
- Objectifs du projet.

---

## Contexte du projet

- Difficulté pour les débutants de découvrir le marché boursier.
- Risques financiers liés à la pratique du trading réel.
- Besoin d'un environnement d'apprentissage accessible.
- Nécessité de proposer une solution de simulation sans risque financier.

---

## Méthode de travail

- Organisation du travail.
- Méthodologie de développement.
- Analyse et conception.
- Développement et validation.

---

<!-- _class: image-only -->

## Scrum

![Méthode Scrum](../rapport/SCRUM/scrum.png)

---

<!-- _class: image-only -->

## Processus 2TUP

![Processus 2TUP](../rapport/2TUP/images.jpg)

---

<!-- _class: image-only -->

## Design Thinking

![Design Thinking](../rapport/design_thinking/design_thinking.jpg)

---

## Planification

- Analyse des besoins.
- Conception de la plateforme.
- Développement des fonctionnalités.
- Intégration des données boursières.
- Tests et validation.

[Insérer le planning prévisionnel du projet.]

---

## Branche fonctionnelle

**Acteurs principaux :**

- Visiteur.
- Utilisateur.
- Administrateur.

**Fonctionnalités principales :**

- Gestion des comptes utilisateurs.
- Consultation des actions boursières.
- Suivi des prix et des évolutions.
- Gestion du portefeuille virtuel.
- Simulation des achats et ventes.
- Consultation de l'historique des transactions.

---

## Carte d'empathie

**Utilisateur cible : Débutant en trading**

- Que pense-t-il et ressent-il ?
- Que voit-il sur le marché financier ?
- Qu'entend-il sur le trading ?
- Que dit-il et fait-il ?
- Quels sont ses besoins et ses difficultés ?

[Insérer la carte d'empathie de TradeSim.]

---

## Définition du problème

**Problématique :**

Comment permettre aux personnes débutantes de découvrir et de pratiquer le trading dans un environnement accessible, pédagogique et sans risque financier réel ?

**Besoin identifié :**

Une plateforme permettant de suivre les actions et de simuler des opérations boursières à l'aide d'un portefeuille virtuel.

---

## Idéation

**Solution proposée : TradeSim**

- Créer un compte utilisateur.
- Consulter les actions disponibles.
- Visualiser l'évolution des prix.
- Disposer d'un solde virtuel initial.
- Simuler des opérations d'achat et de vente.
- Suivre les performances du portefeuille.
- Consulter l'historique des transactions.

---

<!-- _class: diagram-slide -->

## Diagramme de cas d'utilisation

![Diagramme de cas d'utilisation](diagramme-cas-utilisation.png)

---

## Stack technologique

- **Backend** · PHP / Laravel [à confirmer]
- **Frontend** · HTML · Tailwind CSS · JavaScript
- **Base de données** · MySQL
- **Visualisation** · Chart.js
- **Données financières** · API boursière / Données simulées
- **Modélisation** · Mermaid · PlantUML
- **Versionnement** · Git · GitHub

---

## Architecture

![diagram architecture](image.png)

---

## Maquettes

[Insérer les maquettes UI/UX de TradeSim.]

- Page d'accueil.
- Page de connexion et inscription.
- Dashboard.
- Liste des actions.
- Détails d'une action.
- Portefeuille virtuel.

---

<!-- _class: diagram-slide -->

## Diagramme de classes

![Diagramme de classes](diagramme-classes.png)

---

## Réalisation

**Présentation des fonctionnalités développées :**

- Interface utilisateur.
- Authentification.
- Consultation des actions.
- Gestion du portefeuille virtuel.
- Simulation des transactions.
- Calcul des profits et des pertes.
- Historique des opérations.

[Insérer les captures d'écran de l'application.]

---

## Conclusion
