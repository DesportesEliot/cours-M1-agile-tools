# 🏆 Système de Scoring - Jeu Agile

Ce document définit comment calculer le score final des équipes à la fin du jeu.

---

## 📊 Composantes du Score



### 1️⃣ Valeur métier livrée

**Calcul** : Valeur métier accumulée sur chaque sprints

#### Scoring
- **1 point de valeur métier = 1 point de score** (pour tailles S et M uniquement)
- **⚠️ Pénalité XL réussie** : Les tâches XL comptent seulement **50% de leur valeur métier** (floues, difficiles à estimer, valeur métier incertaine)
- **❌ Malus échouée** : AU DEUXIEME TOUR et suivants: **-50% de la valeur métier** de la tâche non terminée
- **📉 Malus US ouvertes** : retrancher 2 × valeur métier pour chaque US **non commencée** en fin de sprint (work-in-progress excessif)
- **📈 Malus vélocité non alignée** : à la 2e itération vous devez appliquer la vélocité constatée à la 1ère itération (= votre capacité à produire). Si en fin de sprint, votre vélocité n'est pas atteinte, c'est à dire que vous avez moins de points effectués que prévu, **retrancher cette différence de points au score**.  

> US ouvertes veut dire: non commencées

#### Formule de calcul
```
Score = Σ(valeur métier S/M livrées × multiplicateur DORA)
      + Σ(valeur métier XL livrées × 0.5 × multiplicateur DORA)
      - Σ(story points échouées × 0.5)
      - (story points des US ouvertes en fin de sprint × 2)

Valeur Multiplicateur DORA :
 = 1 si DORA-1 non complétée
 = 2 pour toutes les US terminées APRÈS la complétion de DORA-1
```


**💡 Conseil** : On récompense l'**investissement technique** et la **vision long terme**.

---

### 4️⃣ Excellence opérationnelle  
- 
- **🚀 BONUS DORA** : Si l'US technique **DORA-1** est complétée, **toutes les valeurs métier** des US terminées **après son achèvement** sont **multipliées par 2** !



---

## 📋 Feuille de Score (Template)

### Équipe : Nisrine - Myriam - Eliot

#### 1️⃣ Valeur métier livrée (/40)

| Sprint | Valeur business livrés (S/M) | XL livrés (50%)| XL échouées (-50%) | Cumul |
|--------|------------------------------|-----------------|-------------------|-------|
| Sprint 0 | 7 | 0 | 0 | 4 |
| Sprint 1 | 13 | 0 | 0 | 20 |
| Sprint 2 | 0 | 38.5 | 0 | 58.5 |
| Sprint 3 | 3 | 22.5 | 0 | 74 |




## 🎓 Débriefing - Questions de réflexion

À la fin du jeu, l'animateur pose ces questions aux équipes :

### Sur la valeur métier
- Qu'avez-vous priorisé et pourquoi ?
Epic 1, car c'est le premier.
- Auriez-vous pu livrer plus de valeur ? Comment ?
Oui, avec plus de personnes et en répartissant davantage les tâches. 

### Sur le découpage
- Avez-vous bien estimé la complexité des tâches ?
Ça a été fait au dé
- Quelles tâches auraient dû être découpées différemment ?
Les tâches XL n'ont pas été découpées, ce qui les a rendues longues malgré la chance avec les dés.

### Sur la dette technique
- Quand avez-vous investi dans les US techniques ?
- Les bonus ont-ils eu un impact sur votre vélocité ?
Nous n'avons pas joué sur les bonus et avons juste continué les user stories pour avant le plus possible sur le projet.

### Sur l'excellence opérationnelle
- Comment s'est passée la collaboration dans l'équipe ?
L'équipe était au clair sur les tâches à réaliser et a pu faire tout ce qui lui était demandé.
- Qu'auriez-vous fait différemment ?
Le plus gros problème était la répartition des tâches : le Scrum Master avait beaucoup à gérer sur Jira et la modification du Git.

---



## 🎯 Objectifs pédagogiques

Ce système de scoring vise à faire comprendre :

 - ✅ L'importance de **livrer régulièrement de la valeur**
 - ✅ L'art du **bon découpage** ()
 - ✅ L'**investissement technique** paie sur le long terme
 - ✅ La **discipline** et la **collaboration** sont essentielles

**Bonne chance ! 🚀**
