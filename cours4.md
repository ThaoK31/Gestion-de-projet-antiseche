# Cours 4 - Planification

> **Gestion de Projet IT** - M1 Fullstack 2025/2026
> Pauline Fleury - 13/12/2025

---

## Sommaire
1. [Compétences et Formations](#1-compétences-et-formations)
2. [Créer une Roadmap](#2-créer-une-roadmap)
3. [Planifier les Ressources (Coûts)](#3-planifier-les-ressources-coûts)

---

## 1. Compétences et Formations

### Pourquoi évaluer les compétences ?

| Risques si mal évalué | Avantages si bien évalué |
|----------------------|--------------------------|
| Tâches assignées à des gens qui ne peuvent pas les réaliser | Assigner les bonnes tâches aux bonnes personnes |
| Mauvaise organisation du projet | Préparer des formations pour combler les lacunes |
| | Identifier les forces et faiblesses de l'équipe |

### Comment évaluer les compétences ?

| Méthode | Description | Avantages | Inconvénients |
|---------|-------------|-----------|---------------|
| **Auto-évaluation** | Chaque membre s'auto-évalue | Rapide, facile | Dépend de l'honnêteté et confiance en soi, pas toujours fiable |
| **Tests techniques** | Exercices pratiques, mini-projets | Évaluation concrète | Limités en durée/complexité, stress, chronophage |
| **Évaluation par les pairs** | Code review, pair programming, feedbacks | Plus objectif, compétences réelles | Biais subjectifs, tensions si critiques mal formulées |

### Matrice des compétences

| Compétence | Dev 1 | Dev 2 |
|------------|-------|-------|
| React | Avancé | Intermédiaire |
| Node.js | Débutant | Intermédiaire |

---

### Types de formations

#### Formations Internes vs Externes

| Critère | Interne | Externe |
|---------|---------|---------|
| **Animée par** | Senior, Tech Lead, expert interne | Organismes spécialisés, écoles, éditeurs |
| **Format** | Présentations, démos, workshops | Formations structurées |
| **Coût** | Minime | Élevé (finançable via OPCO) |
| **Avantages** | Adapté au contexte, application immédiate | Formateurs experts, contenu à jour, certifiantes |
| **Inconvénients** | Dépend de la pédagogie, risque mauvaises pratiques, pas certifiante | Contenu parfois générique, temps mobilisé |

#### Formations Courtes vs Longues

| Critère | Courte | Longue |
|---------|--------|--------|
| **Durée** | Quelques heures à jours | Plusieurs semaines à mois |
| **Objectif** | Compétence précise | Compétences profondes et durables |
| **Avantages** | Rapide, peu coûteuse, besoins immédiats | Parfois certifiante, reconversions |
| **Inconvénients** | Vision partielle, peu de recul théorique | Coût élevé, mobilisation importante, incompatible avec projets urgents |

---

## 2. Créer une Roadmap

### Vision d'entreprise
> Dépeint un futur idéalisé

**Exemple Doctolib :** *"Améliorer la santé de tous en simplifiant l'accès aux soins"*

| Critère | Validation |
|---------|------------|
| Imaginable | On visualise un système de santé plus simple |
| Désirable | Tout le monde souhaite un meilleur accès aux soins |
| Concentrée | Centrée sur la santé et l'accès aux soins |
| Flexible | Compatible avec nouveaux services (téléconsultation, messagerie, prévention...) |
| Facile à expliquer | Une phrase suffit |

### Mission de l'entreprise
> Précise les moyens pour atteindre la vision

**Exemple :** *"Aider les professionnels de santé à mieux soigner leurs patients grâce à des outils numériques"*

| Élément | Description |
|---------|-------------|
| Activités actuelles | Développement de logiciels de santé |
| Public ciblé | Professionnels de santé et patients |
| Impact | Améliorer l'organisation des soins et le parcours patient |

### Vision produit

| Élément | Exemple (Doctolib) |
|---------|-------------------|
| **Nom du produit** | Plateforme de prise de rendez-vous Doctolib |
| **Public cible** | Patients et professionnels de santé |
| **Problème identifié** | Difficulté à obtenir un RDV, gestion inefficace des agendas |
| **Solution proposée** | Plateforme centralisée de prise de RDV et gestion des consultations |
| **Avantages** | Gain de temps, réduction des RDV manqués, meilleure organisation |

**Axes de roadmap :**
- Amélioration de la recherche de praticiens
- Notifications et rappels automatiques
- Téléconsultation intégrée
- Messagerie sécurisée patient–médecin

---

### Construction de la Roadmap

#### Modèle au trimestre
- Pas de dates précises
- **Règle du 3-3-3** : planifier sur 3 trimestres

#### OKR (Objectives and Key Results)

| Niveau | Objective | Key Results |
|--------|-----------|-------------|
| **Entreprise** | Atteindre une masse critique de joueurs actifs sur le marché français | - 100 000 joueurs actifs mensuels<br>- Réduire de 30% le coût d'acquisition |
| **Produit** | Améliorer l'engagement des nouveaux joueurs lors des 3 premières heures | - +15% taux de joueurs qui terminent le tutoriel<br>- +20% taux de joueurs qui publient leur 1er numéro |

#### Transformation du Backlog en Roadmap

1. **Reprendre le backlog** pour mieux comprendre les besoins et les reformuler
2. **Regrouper par "zones d'effort"**
3. **Ajouter des éléments raisonnés** du backlog à la roadmap

---

## 3. Planifier les Ressources (Coûts)

### Coûts humains

| Rôle | Temps estimé | Coût journalier | Coût total |
|------|--------------|-----------------|------------|
| Dev Full Stack | 60 jours | 300€ | 18 000€ |
| Game Designer | 30 jours | 250€ | 7 500€ |
| UI/UX Designer | 20 jours | 250€ | 5 000€ |
| QA / Tests | 15 jours | 200€ | 3 000€ |
| **Total brut** | | | **33 500€** |

### Formule coût humain

```
Coût humain = Nombre de personnes × Temps de travail × Coût journalier + Charges
```

- Charges patronales : **+45%** ≈ 15 075€
- **Coût RH réel ≈ 48 575€**

### Coûts techniques

| Poste | Coût |
|-------|------|
| Hébergement serveurs | 240€ |
| Base de données & backup | 150€ |
| Outils de dev | 300€ |
| Assets graphiques | 500€ |

---

## Points clés à retenir

| Concept | À retenir |
|---------|-----------|
| **Matrice des compétences** | Évaluer le niveau de chaque membre sur chaque techno |
| **Vision d'entreprise** | Futur idéalisé (imaginable, désirable, concentrée, flexible, simple) |
| **Mission d'entreprise** | Moyens pour atteindre la vision (activités, public, impact) |
| **Vision produit** | Produit + public + problème + solution + avantages |
| **OKR** | Objectives and Key Results (niveau entreprise ET produit) |
| **Règle du 3-3-3** | Planifier sur 3 trimestres, pas de dates précises |
| **Coût RH** | Brut + 45% charges patronales |
