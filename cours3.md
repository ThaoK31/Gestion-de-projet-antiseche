# Gestion de Projet IT - Production & Maintenance

**M1 Fullstack - 2025/2026**
*Pauline Fleury - Dernière version : 06/11/25*

---

## Planning du module

| Jour | Thème | Contenu |
|------|-------|---------|
| **Jour 1** (05/11) | Cadrage | Sprint 0, Sprint Planning, RACI/SWOT, KPI/US |
| **Jour 2** (06/11) | Prod & Maintenance | Sprint 1, Rituels SCRUM, Daily/Review/Retro, Types de maintenance |
| **Jour 3** (19/12) | Coûts & Pilotage | Estimation des coûts, Planification, **Écrit ~1h** |

---

## Sommaire
1. Théories des maintenances
2. Day One Sprint One
3. Review et Retro

---

## 1. Maintenance Logicielle

### Définition (Norme ISO/IEC 14764)

> La **modification** d'un produit logiciel **après sa livraison** pour :
> - **Corriger** des fautes
> - **Améliorer** les performances
> - **Adapter** le produit à un environnement modifié

### Cycle de vie post-livraison

```
Livraison / Mise en production
        ↓
Phase d'exploitation
        ↓
Détection d'un besoin (bug, évolution, optimisation)
        ↓
Analyse et planification de la maintenance
        ↓
Implémentation et déploiement du correctif/mise à jour
        ↓
(Retour à la phase d'exploitation)
```

> **Important :** Un projet logiciel n'est jamais "terminé" : il évolue avec son environnement et ses utilisateurs.

---

## 2. Types de Maintenance

### 2.1 Maintenance Corrective

> Ensemble des actions visant à **corriger les anomalies** détectées après mise en service.

**Objectif :** Rétablir le fonctionnement normal du logiciel, sans modifier le comportement prévu.

**Question clé :** *"Pourquoi le logiciel ne fonctionne-t-il pas comme prévu ?"*

**Processus :**
1. Signalement du bug
2. Analyse de la cause
3. Priorisation selon la gravité (mineure, majeure, critique)
4. Correction et livraison d'un patch

**Exemples :**
- Corriger un bug qui empêche la sauvegarde d'une partie dans ChronoQuest
- Résoudre une erreur d'affichage d'une carte Pokémon

---

### 2.2 Maintenance Préventive

> Ensemble des actions réalisées **avant** l'apparition d'une panne, pour **réduire les risques futurs**.

**Objectif :** Améliorer la fiabilité et la sécurité du système à long terme.

**Question clé :** *"Que peut-on faire maintenant pour éviter un problème demain ?"*

**Processus :**
1. Planification de tâches techniques dans le backlog
2. Surveillance continue (monitoring, alerting)
3. Mise en place de tests automatisés et d'outils d'audit de code

**Exemples :**
- Nettoyer régulièrement la base de données pour éviter sa saturation
- Mettre à jour les dépendances (framework, bibliothèques, serveurs)
- Revoir les tests unitaires et les performances pour prévenir des bugs

---

### 2.3 Maintenance Évolutive

> Faire évoluer le logiciel pour l'adapter à de **nouveaux besoins**, technologies ou marchés.

**Objectif :** Accroître la valeur métier et la satisfaction utilisateur.

**Question clé :** *"Comment améliorer le logiciel pour répondre à de nouveaux objectifs ?"*

**Processus :**
1. Recueil et priorisation des besoins
2. Étude de faisabilité technique et budgétaire
3. Estimation des coûts et planification (sous forme d'US, Epics…)
4. Développement et livraison via des sprints

**Exemples :**
- Ajouter un mode multijoueur à ChronoQuest
- Intégrer un système de succès pour motiver les joueurs
- Refonte du design du Pokédex pour le rendre mobile-first
- Migration du backend vers une architecture microservices

---

### Récapitulatif des Maintenances

| Type | Quand ? | Pourquoi ? | Exemple |
|------|---------|------------|---------|
| **Corrective** | Après détection d'un bug | Corriger une anomalie | Fix bug sauvegarde |
| **Préventive** | Avant qu'un problème survienne | Éviter les pannes futures | Mise à jour dépendances |
| **Évolutive** | Nouveau besoin identifié | Ajouter de la valeur | Nouveau mode multijoueur |

---

## 3. Sprint 1 - Jour 1

### Organisation de la journée

| Horaire | Activité |
|---------|----------|
| 8h30 → 12h15 | Production - Mise à jour board |
| 12h15 → 12h30 | Daily - Compte rendu |

### Attendus / Livrables
- Screen board **début de sprint** (heure visible) - Annexe
- Screen board **fin de journée** (heure visible) - Annexe
- Compte rendu daily - Annexe

---

## 4. Rituels SCRUM - Rappel

### 4.1 Daily Review (Stand-up)

| | |
|---|---|
| **Quand** | Tous les jours |
| **Qui** | Dev Team + SM (+PO) |
| **But** | Synchroniser l'équipe |
| **Durée** | 15 minutes max |

**Déroulé (3 questions) :**
1. Qu'ai-je fait **hier** ?
2. Que vais-je faire **aujourd'hui** ?
3. Quels sont mes **obstacles / difficultés** ?

---

### 4.2 Sprint Review (Démo)

| | |
|---|---|
| **Quand** | Fin de chaque sprint |
| **Qui** | PO + Parties Prenantes (+SM) |
| **But** | Montrer ce qui a été réalisé, valider |

**Déroulé :**
1. PO rappelle les objectifs du sprint
2. Démo du produit
3. Feedback des parties prenantes

---

### 4.3 Sprint Retrospective

| | |
|---|---|
| **Quand** | Après la Sprint Review |
| **Qui** | Dev Team + SM (+PO) |
| **But** | Améliorer la manière de travailler de l'équipe |

**Déroulé :**
- Points **positifs** (+)
- Points **négatifs** (-)
- Points d'**amélioration** (→)

---

## 5. Clôture de Sprint

### Organisation

| Durée | Activité |
|-------|----------|
| 10 min | Préparation de la review : quelles US accomplies ? |
| 30-40 min | Review avec les PO / Rédaction de la doc pour la dev team |
| ~30 min | Rétrospective |

### Attendus / Livrables
- Compte rendu Review : feedback client - Annexe
- Compte rendu Retro - Annexe

---

## 6. Documents de Cadrage

### 6.1 Plan de Management Projet (PMP)

| Section | Contenu |
|---------|---------|
| **1. Objectifs du PMP** | Formule, objectifs du document en interne |
| **2. Ressources techniques** | Liste des ressources techniques/matérielles nécessaires, justifiées |
| **3. Ressources humaines** | RACI, certains choix justifiés |
| **4. Management projet** | NON (pas demandé) |
| **5. Planification** | NON (pas demandé) |
| **6. Prévention des risques** | SWOT, Matrice de criticité, Plan de prévention |
| **7. Suivi du budget** | NON (pas demandé) |
| **8. Indicateurs de pilotage** | 2 KPI justifiées + screen du KPI après production si possible |

**Annexes :** Comptes rendus réunions, screens

---

### 6.2 Cahier des Charges (CdC)

| Section | Contenu |
|---------|---------|
| **1. Contexte et objectifs** | Description du projet |
| **2. Périmètre fonctionnel** | Description des principales fonctionnalités, maquettes possibles |
| **3. Contraintes techniques** | Exigences techniques spécifiques |
| **4. Livrables attendus** | Prototype, v1, documentation, guide utilisateur... |
| **5. Critères d'acceptation** | Conditions de validation |

**Exemple de justification RACI :**
> "Le PO (A/R) supervise la réalisation des maquettes car il participe à leur élaboration avec le client (C), puis il les transmet à l'équipe de développement (I)."

---

### 6.3 Plan de Maintenance

| Type | Contenu |
|------|---------|
| **Préventive** | Actions mises en œuvre + US techniques si nécessaire |
| **Évolutive** | Améliorations envisagées + US associées |

---

## Checklist des Livrables

- [ ] PMP avec sections 1, 2, 3, 6, 8
- [ ] CdC avec sections 1 à 5
- [ ] SWOT complété
- [ ] Matrice de criticité
- [ ] Plan de prévention des risques
- [ ] 2 KPI choisies et justifiées
- [ ] Board initialisé (Initiatives, Epics, US)
- [ ] Chaque US : attribuée et priorisée
- [ ] Plan de maintenance (préventive + évolutive)
- [ ] Comptes rendus (Daily, Review, Retro)
- [ ] Screenshots du board (début/fin sprint)
