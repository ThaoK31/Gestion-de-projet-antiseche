# FICHE MEMO QCM - Gestion de Projet IT

---

## CYCLES DE VIE

| Cycle | Caractéristique clé |
|-------|---------------------|
| **Cascade** | Séquentiel, chaque phase terminée avant la suivante |
| **Cycle en V** | Gauche = Vérification / Droite = Validation |

---

## AGILE - À RETENIR

### Manifeste Agile (2001) = 17 spécialistes

**4 Valeurs (le "plus que") :**
1. **Individus** > Processus
2. **Logiciel fonctionnel** > Documentation
3. **Collaboration client** > Négociation contrat
4. **Adaptation** > Suivi du plan

---

## SCRUM

### 3 Rôles

| Rôle | Mot-clé |
|------|---------|
| **Product Owner** | CLIENT (vision, backlog, priorités, valide) |
| **Scrum Master** | COACH (garant SCRUM, anime rituels) |
| **Dev Team** | PRODUIT (auto-organisée, estime charge) |

### 4 Rituels

| Rituel | Quand | Qui | Durée/But |
|--------|-------|-----|-----------|
| **Sprint Planning** | AVANT sprint | Tous | Préparer backlog sprint |
| **Daily** | TOUS LES JOURS | Dev+SM | **15 min max** (hier/aujourd'hui/blocages) |
| **Sprint Review** | FIN sprint | PO+PP | Démo + validation |
| **Retrospective** | APRÈS review | Dev+SM | +/- /amélioration |

### Artefacts
- **Product Backlog** = TOUT le projet (priorisé)
- **Sprint Backlog** = US du sprint en cours
- **Increment** = Version livrable

---

## SCRUM vs KANBAN

| | SCRUM | KANBAN |
|-|-------|--------|
| **Cadence** | Sprints fixes | Flux continu |
| **Rôles** | PO, SM, Dev | Aucun |
| **Livraison** | Fin de sprint | Dès que prêt |
| **Board** | Recyclé chaque sprint | Permanent |
| **Limite** | Durée du sprint | WIP (Work In Progress) |

---

## RACI

| Lettre | = | Qui ? |
|--------|---|-------|
| **R** | Responsible | **Réalise** la tâche |
| **A** | Accountable | **Valide** (responsable final) |
| **C** | Consulted | **Consulté** (donne son avis) |
| **I** | Informed | **Informé** (après coup) |

> 1 seul A par tâche !

---

## USER STORY

**Format :** En tant que **[QUI]**, je veux **[QUOI]** afin de **[POURQUOI]**

### INVEST (6 critères d'une bonne US)

| | |
|-|-|
| **I** | Indépendante |
| **N** | Négociable |
| **V** | Valorisable (apporte de la valeur) |
| **E** | Estimable |
| **S** | Small enough (assez petite) |
| **T** | Testable |

### Hiérarchie : Initiative > Epic > User Story

---

## SWOT

|  | **+** | **-** |
|--|-------|-------|
| **INTERNE** | **S**trengths (Forces) | **W**eaknesses (Faiblesses) |
| **EXTERNE** | **O**pportunities | **T**hreats (Menaces) |

> **Interne** = l'équipe contrôle / **Externe** = environnement

---

## MATRICE DE CRITICITÉ

**Formule : Criticité = Probabilité × Impact**

| Niveau | Score | Action |
|--------|-------|--------|
| FAIBLE | 1-6 | OK, continuer |
| MOYENNE | 7-14 | Atténuer |
| EXTRÊME | 15-25 | STOP, agir |

---

## STRATÉGIES RISQUES (négatifs)

| Stratégie | = |
|-----------|---|
| **Acceptation** | On ne peut rien faire, on assume |
| **Atténuation** | Réduire proba ou impact |
| **Transfert** | Déléguer à un tiers (freelance...) |
| **Évitement** | Supprimer le risque |

## STRATÉGIES OPPORTUNITÉS (positifs)

| Stratégie | = |
|-----------|---|
| **Amélioration** | Augmenter proba/impact |
| **Exploitation** | Concrétiser l'opportunité |
| **Partage** | Déléguer à un tiers |
| **Acceptation** | Attendre sans agir |

---

## KPI

| KPI | Définition |
|-----|------------|
| **Vélocité** | Story points moyens par sprint |
| **Lead Time** | Création US → Livraison (TOTAL) |
| **Cycle Time** | In Progress → Livraison (TRAVAIL) |
| **Burndown** | Travail RESTANT (descend) |
| **Burnup** | Travail FAIT vs TOTAL (monte) |
| **Prédictibilité** | Terminé / Prévu |

---

## 3 MAINTENANCES (Norme ISO/IEC 14764)

| Type | Quand | Question clé |
|------|-------|--------------|
| **Corrective** | Bug détecté | "Pourquoi ça marche pas ?" |
| **Préventive** | AVANT problème | "Comment éviter un souci demain ?" |
| **Évolutive** | Nouveau besoin | "Comment ajouter de la valeur ?" |

---

## DOCUMENTS DE CADRAGE

| Document | Contient |
|----------|----------|
| **PMP** (Plan Management Projet) | Ressources, RACI, SWOT, KPI |
| **CdC** (Cahier des Charges) | Contexte, fonctionnalités, contraintes, livrables |

---

## PIÈGES CLASSIQUES QCM

- Daily = **15 min MAX** (pas 30, pas 1h)
- Scrum Master ≠ chef de projet (c'est un **facilitateur**)
- Product Owner = **1 seule personne** (pas un comité)
- Sprint Review = démo aux **parties prenantes**
- Retrospective = amélioration **équipe** (pas du produit)
- KANBAN = **pas de rôles** définis
- Lead Time **>** Cycle Time (toujours)
- Burndown **descend** / Burnup **monte**
- SWOT : Forces/Faiblesses = **INTERNE**
