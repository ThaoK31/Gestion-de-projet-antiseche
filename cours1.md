# Gestion de Projet IT - Principaux Concepts

**M1 Fullstack - 2025/2026**
*Pauline Fleury - Dernière version : 06/11/25*

---

## Sommaire
1. Théorie des cycles
2. Méthodes AGILES
3. Identifier les acteurs
4. Exprimer les besoins

---

## 1. Gestion de Projet - Définition

> Ensemble d'activités coordonnées et temporaires, pour atteindre un objectif en respectant des exigences.

**Les 4 contraintes principales :**
- **Qualité**
- **Coûts**
- **Délais**
- **Contenu** (périmètre)

+ **Parties prenantes**

---

## 2. Théorie des Cycles

### 2.1 Cycle en Cascade

| Phase | Livrables |
|-------|-----------|
| **Initialisation** - Cadrage du projet | Plan de Management de Projet (PMP) |
| **Spécifications** - Analyse des besoins | Cahier des charges (CdC) |
| **Conception fonctionnelle** | Maquettes / Charte graphique |
| **Conception technique** | Architecture / Schémas BDD |
| **Développement** - Code | - |
| **Tests** - Unitaires, Intégration, Validation | Cahier de recettes |
| **Déploiement** | - |
| **Exploitation et maintenance** | Corrective, Évolutive, Préventive |

### 2.2 Cycle en V

```
Analyse des besoins ──────────────────────────► Tests de validation
        │                                              ▲
        ▼                                              │
Spécifications fonctionnelles ────────────► Tests d'intégration
        │                                              ▲
        ▼                                              │
Spécifications techniques ────────────────► Tests unitaires
        │                                              ▲
        ▼                                              │
Spécifications détaillées ────────► Développement ────┘
```

- **Vérification** : à gauche (on construit bien)
- **Validation** : à droite (on construit le bon produit)

---

## 3. Méthodes AGILES

### 3.1 Manifeste Agile (2001)

> Rencontre de 17 spécialistes du développement

#### 4 Valeurs
1. **Les individus et leurs interactions** > processus et outils
2. **Logiciels opérationnels** > documentation exhaustive
3. **Collaboration avec le client** > négociation contractuelle
4. **Adaptation au changement** > suivi d'un plan

#### 12 Principes (les plus importants)
- Plus haute priorité = **satisfaction client**
- **Accueillir positivement** le changement
- **Livrables fréquents**, à cycles courts
- Utilisateurs & Développeurs doivent **travailler ensemble**
- À intervalles réguliers, **réflexions sur l'amélioration**

---

### 3.2 SCRUM

#### Rôles SCRUM

| Rôle | Responsabilités |
|------|-----------------|
| **Product Owner (PO)** | Représente le client, vision produit, définit priorités, gère le backlog, valide les incréments |
| **Scrum Master (SM)** | Garant des valeurs SCRUM, fait comprendre et appliquer SCRUM, anime les rituels |
| **Dev Team** | Réalise le produit, estime la charge, transforme besoins en fonctionnalités, maintient la qualité technique, **auto-organisée** |

#### Artefacts SCRUM
- **Product Backlog** : Liste priorisée de toutes les fonctionnalités
- **Sprint Backlog** : User Stories sélectionnées pour le sprint
- **Increment** : Version potentiellement livrable

#### Rituels SCRUM

| Rituel | Quand | Qui | But | Déroulé |
|--------|-------|-----|-----|---------|
| **Planning Meeting** | Avant chaque sprint | PO + SM + Dev Team | Préparer le sprint backlog | Quelles US ? Qui les réalise ? |
| **Daily Review** | Tous les jours | Dev Team + SM (+PO) | Synchroniser l'équipe | 15 min max : hier / aujourd'hui / obstacles |
| **Sprint Review** | Fin de sprint | PO + PP (+SM) | Montrer et valider | Rappel objectifs, démo, feedback |
| **Sprint Retrospective** | Après la review | Dev Team + SM (+PO) | Améliorer le travail d'équipe | + / - / améliorations |

#### SCRUM Board
- **Colonnes** = workflow du sprint (To Do, In Progress, Done...)
- **Carte** = une tâche / une US
- Outils : Trello, Jira, Linear...

---

### 3.3 KANBAN

- **Processus continu**, sans rôles formels
- Visualisation du flux de travail
- **Limites du WIP** (Work In Progress)
- Point d'engagement → Point de livraison

### 3.4 SCRUM vs KANBAN

| Critère | SCRUM | KANBAN |
|---------|-------|--------|
| **Idéologie** | Réfléchir collectivement, s'améliorer en permanence | Utiliser des visuels pour améliorer le travail |
| **Cadence** | Sprints réguliers, durée déterminée | Flux continu |
| **Bonnes pratiques** | Sprint planning, rituels | Visualiser le flux, limiter le WIP |
| **Rôles** | PO, SM, Dev Team | Aucun rôle requis |
| **Livraison** | Chaque fin de sprint | Dès qu'une fonctionnalité est terminée |
| **Board** | Recyclé après chaque sprint | Utilisé tout au long du cycle |

---

### 3.5 SAFe (Scaled Agile Framework)

Framework pour appliquer l'Agile à grande échelle (plusieurs équipes).

---

## 4. Identifier les Acteurs - Matrice RACI

| Lettre | Signification | Description |
|--------|---------------|-------------|
| **R** | Responsible | Réalise la tâche |
| **A** | Accountable | Responsable final (valide) |
| **C** | Consulted | Consulté pour avis |
| **I** | Informed | Informé du résultat |

### Exemple RACI (Jeu vidéo)

| Activité | PO | SM | Dev | Artists | Game Designer | QA | Client |
|----------|----|----|-----|---------|---------------|----| -------|
| Définition vision | R | I | I | C | R | I | A |
| Rédaction backlog | A,R | C | C | C | C | I | I |
| Développement code | A | I | R,C | C | C | C | I |
| Création assets | I | I | C | R,C | R,C | I | A |
| Tests équilibrage | I | I | C | C | A | R | C |
| Validation finale | R | I | I | I | C | C | A |

---

## 5. Exprimer les Besoins

### Hiérarchie des besoins

```
Initiative (Vision stratégique, long terme)
    └── Epic (Fonctionnalité majeure)
            ├── User Story 1
            ├── User Story 2
            └── User Story 3
```

### User Story (US)

**Format :**
> En tant que **[persona]**, je veux **[fonctionnalité]** afin de **[bénéfice]**

**Exemple :**
> En tant que **joueur**, je veux **remonter de 10s** afin d'**éviter un piège**

#### Critères INVEST

| Lettre | Critère |
|--------|---------|
| **I** | Indépendante |
| **N** | Négociable |
| **V** | Valorisable |
| **E** | Estimable |
| **S** | Small Enough (assez petite) |
| **T** | Testable |

### Critères d'acceptation (BDD - Given/When/Then)

```
Given : contexte initial
When  : action
Then  : résultat attendu
```

**Exemple :**
```
Given : joueur en zone piégée
When  : joueur utilise pouvoir
Then  : pièges retour état initial
```

---

## Outils recommandés

| Catégorie | Outils |
|-----------|--------|
| **Board** | Trello, Jira, Linear, Schedule |
| **Tableau blanc** | Klaxoon, Excalidraw, Draw.io |
| **Maquettes** | Balsamiq, Figma |
| **BDD** | Looping |
| **Communication** | Slack, Teams (PAS DISCORD) |
| **Documentation** | Atlassian, OpenClassrooms |
