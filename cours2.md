# Gestion de Projet IT - Cadrage Projet

**M1 Fullstack - 2025/2026**
*Pauline Fleury - Dernière version : 28/10/25*

---

## Planning du module

| Jour | Thème | Contenu |
|------|-------|---------|
| **Jour 1** (05/11) | Cadrage | Sprint 0, Sprint Planning, RACI/SWOT, KPI/US |
| **Jour 2** (06/11) | Prod & Maintenance | Sprint 1, Rituels SCRUM, Daily/Review/Retro, Types de maintenance |
| **Jour 3** (19/12) | Coûts & Pilotage | Estimation des coûts, Planification, **Écrit ~1h** |

---

## Sommaire
1. Théorie des risques
2. Présentation du sujet
3. Recueil des besoins
4. Documents de cadrage
5. Initialisation du board

---

## 1. Management des Risques

### Objectifs
- **Réduire** la probabilité et l'impact des risques négatifs
- **Accroître** la probabilité et l'impact des événements positifs

### Outils de gestion des risques
1. **SWOT** - Analyse des forces/faiblesses/opportunités/menaces
2. **Matrice de criticité** - Évaluer probabilité × impact
3. **Plan de gestion des risques** - Actions à mettre en place

---

## 2. Analyse SWOT

|  | **POSITIFS** | **NÉGATIFS** |
|--|--------------|--------------|
| **INTERNES** (l'équipe a un pouvoir d'action) | **S**trengths (Forces) | **W**eaknesses (Faiblesses) |
| **EXTERNES** (environnement du projet) | **O**pportunities (Opportunités) | **T**hreats (Menaces) |

### Exemple SWOT (Jeu vidéo ChronoQuest)

#### Forces (Internes +)
- Équipe motivée et créative
- Concept original
- Bonne ambiance d'équipe et communication fluide
- Outil interne innovant (simulation temporelle unique)

#### Faiblesses (Internes -)
- Manque d'expérience en gestion de projet agile
- Ressources limitées (peu de graphistes/sound designers)
- Faible expérience sur les BDD et sauvegardes cloud

#### Opportunités (Externes +)
- Intérêt croissant pour les jeux narratifs "indé"
- Mise à jour stable du moteur de jeu avec meilleures performances
- Studio indépendant développe un outil d'animation compatible

#### Menaces (Externes -)
- Concurrence forte sur le marché indépendant
- Dépendance aux ressources graphiques/sonores externes
- Risque de perte de motivation si le projet s'éternise

---

## 3. Matrice de Criticité

### Calcul : Criticité = Probabilité × Impact

| PROBABILITÉ ↓ / IMPACT → | Très faible (1) | Faible (2) | Modéré (3) | Élevé (4) | Très élevé (5) |
|--------------------------|-----------------|------------|------------|-----------|----------------|
| **Très probable** (5)    | 5               | 10         | 15         | 20        | **25**         |
| **Probable** (4)         | 4               | 8          | 12         | 16        | **20**         |
| **Possible** (3)         | 3               | 6          | 9          | 12        | 15             |
| **Peu probable** (2)     | 2               | 4          | 6          | 8         | 10             |
| **Improbable** (1)       | 1               | 2          | 3          | 4         | 5              |

### Niveaux de criticité

| Niveau | Score | Action |
|--------|-------|--------|
| **FAIBLE** | 1-6 | Acceptable, OK pour continuer |
| **MOYENNE** | 7-14 | Prendre des mesures d'atténuation |
| **EXTRÊME** | 15-25 | Intolérable, action immédiate requise |

### Exemple de Matrice de Criticité

| Probabilité | Acceptable | Tolérable | Indésirable | Intolérable |
|-------------|------------|-----------|-------------|-------------|
| **Très probable** | Petites divergences Git | Manque d'expérience Agile | Difficulté comprendre les besoins | Défaillance matérielle majeure |
| **Probable** | Lenteur CI/CD | Mauvaise estimation temps | Difficulté rituels Scrum | Retard assets graphiques |
| **Possible** | Oublis mineurs board Jira | Conflits internes équipe | Bug majeur sauvegarde | Perte du repository |
| **Improbable** | Petite erreur dans texte | Confusion documentation | Perte motivation membre | Rupture communication client |

---

## 4. Stratégies de Gestion des Risques (Négatifs)

### 4.1 Stratégies d'acceptation
> Aucune maîtrise sur la probabilité que le risque se produise

**Exemple :**
- *Mauvaise estimation du temps de développement* → Accepter les retards mineurs sur la livraison d'un niveau secondaire

### 4.2 Stratégies d'atténuation
> Limiter l'impact du risque ou sa probabilité

**Exemples :**
- *Bug majeur sauvegarde* → Tests unitaires automatiques + environnement test Dockerisé
- *Communication difficile* → Rituels Scrum + canaux de communication avec toutes les PP
- *Manque d'expérience Agile* → Atelier Scrum d'accompagnement + suivi pédagogique

### 4.3 Stratégies de transfert
> Déléguer à un tiers la gestion du risque

**Exemple :**
- *Retard livraison assets graphiques* → Externaliser à un graphiste freelance

### 4.4 Stratégies d'évitement
> Solution pour faire disparaître le risque

**Exemples :**
- *Perte du repository* → Dépôt GitHub + sauvegarde automatique quotidienne cloud
- *Difficulté comprendre les besoins* → Ateliers réguliers avec Game Designer et client

---

## 5. Stratégies de Gestion des Opportunités (Positifs)

### 5.1 Stratégies d'amélioration
> Augmenter la probabilité et/ou l'impact

**Exemple :**
- *Outil interne innovant* → L'intégrer au pipeline global, documenter pour open source

### 5.2 Stratégies d'exploitation
> Concrétiser l'opportunité

**Exemples :**
- *Influenceur intéressé* → Contacter et proposer une version démo exclusive
- *Mise à jour moteur de jeu* → Rebaser le prototype pour bénéficier des améliorations

### 5.3 Stratégies de partage
> Déléguer à un tiers la responsabilité de l'opportunité

**Exemple :**
- *Outil d'animation compatible* → Coopération technique, échange de scripts, co-promotion

### 5.4 Stratégies d'acceptation
> Accepter l'opportunité si elle se présente, sans la poursuivre

**Exemple :**
- *Intérêt croissant jeux narratifs* → Continuer communication sans modifier roadmap

---

## 6. Présentation du Sujet : Pokédex

### Le contexte
- **Qui ?** Nina Chen (coordinatrice Pokémon, petite-fille du Professeur Chen)
- **Où ?** Région du KANTO
- **Quoi ?** Développer un Pokédex (encyclopédie)

### Les utilisateurs cibles
- **Dresseurs** : collection de Pokémon
- **Personnel des Centres Pokémon** : suivi des soins

### Organisation du Sprint 0
- Rédaction documents de cadrage (CdC / PMP)
- Initialisation du Board
- Recueil des besoins, gestion des risques, spécifications
- Équipe Agile : Dev Team + 1 PO

---

## 7. Recueil des Besoins

### Méthodes
- **Ateliers** : Mind Mapping, Maquettage, Organisation
- **Entretiens** : Questions préparées, organisées par thématiques (20 min préparation, 30-40 min entretien)

### Livrables
- Comptes rendus (Où ? Quand ? Qui ?) - Validés
- Mise au point et rédaction des fonctionnalités

---

## 8. KPI (Key Performance Indicators)

### 8.1 Vélocité (Velocity)
> Quantité moyenne de travail réalisée par l'équipe au cours d'un sprint (en story points)

**Intérêt :**
- Prévoir la capacité des sprints futurs
- Estimer la durée totale du projet
- Ajuster la planification

### 8.2 Lead Time & Cycle Time

| Indicateur | Définition |
|------------|------------|
| **Lead Time** | Temps total entre création d'une demande (US au backlog) et livraison finale |
| **Cycle Time** | Temps entre début du travail effectif ("In Progress") et livraison |

### 8.3 Burndown Chart
> Quantité de travail **restant** à accomplir

**Intérêt :**
- Visualiser l'avancement du sprint
- Identifier rapidement les retards/blocages
- Faciliter les daily meetings

### 8.4 Burnup Chart
> Quantité de travail **réalisée** comparée à la totalité à produire

**Intérêt :**
- Montre la valeur livrée (vs travail restant)
- Prend en compte les changements de périmètre
- Vision motivationnelle ("on monte vers la réussite")

### 8.5 Cumulative Flow Diagram
> Visualisation du flux de travail (chaque couleur = un état)

**Intérêt :**
- Analyse continue du flux
- Identifier les goulots d'étranglement

### 8.6 Prédictibilité
> Capacité à respecter les engagements planifiés du sprint

**Calcul :** Tâches terminées / Tâches prévues

**Intérêt :**
- Mesurer la fiabilité de l'équipe
- Ajuster les estimations futures

---

## 9. Outils recommandés

| Catégorie | Outils |
|-----------|--------|
| **Board** | Jira, Trello, Linear, Schedule, Miro, Klaxoon, Figma |
| **Maquettes** | Draw.io, Balsamiq, Crayons & Feuilles |
| **Rédaction collective** | Google Drive, Confluence |
| **Tableau blanc / Schémas** | Confluence, Excalidraw, Draw.io, Looping |
| **Communication** | Orale, Teams, Slack, (Discord) |
