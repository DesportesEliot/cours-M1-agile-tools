# US-EPIC-1-FM-001 : Créer un compte artisan

## Type
- [x] Fonctionnelle
- [ ] Technique

## Description
En tant qu'**artisan**,
Je veux **créer un compte**,
Afin de **pouvoir vendre mes produits**.

## Complexité estimée
**Story Points** : 3 pts

## Critères d'acceptation

### ☑️ Critère 1 : Formulaire d'inscription fonctionnel
- **Catégorie** : _Aucune_
- **Valeur du dé** : 🎲 **1**
- **Statut** : ⬜ Non validé
- **Permanent** : ❌ Non

**Description** : Le formulaire contient les champs email, nom, prénom, mot de passe et confirmation mot de passe avec validation côté client.

---

### ☑️ Critère 2 : Validation des données
- **Catégorie** : `[SECU]`
- **Valeur du dé** : 🎲 **4**
- **Statut** : ⬜ Non validé
- **Permanent** : ❌ Non (✅ Oui si bonus `[SECU]` actif)

**Description** : L'email est unique en base, le mot de passe respecte les règles (min 8 caractères, 1 majuscule, 1 chiffre). Messages d'erreur clairs affichés.

---

### ☑️ Critère 3 : Compte créé en base de données
- **Catégorie** : _Aucune_
- **Valeur du dé** : 🎲 **3**
- **Statut** : ⬜ Non validé
- **Permanent** : ❌ Non

**Description** : Les données sont enregistrées en base avec mot de passe hashé (bcrypt). L'utilisateur reçoit un message de confirmation.

---

### ☑️ Critère 4 : Email de bienvenue envoyé
- **Catégorie** : _Aucune_
- **Valeur du dé** : 🎲 **5**
- **Statut** : ⬜ Non validé
- **Permanent** : ❌ Non

**Description** : Un email de bienvenue est envoyé automatiquement à l'artisan après création du compte.

---

## Notes

### Dépendances
- Aucune (première story à implémenter)

### Bonus débloqué
_Aucun (US fonctionnelle)_

### Historique des tentatives

| Sprint | type | Dés lancés | Critères validés | Statut | valeur metier|
|--------|------|------------|------------------|--------|--------------|
| 0 | FM01 | Critère 1 | - **Valeur du dé** : 🎲 **1**  |  terminer 1 coup | |
| 0 | FM01 | Critère 2 | - **Valeur du dé** : 🎲 **4**  |  terminer 4 coup | |
| 0 | FM01 | Critère 3 | - **Valeur du dé** : 🎲 **3**  |  terminer 2 coup | |
| 0 | FM01 | Critère 4 | - **Valeur du dé** : 🎲 **5**  |  terminer 8 coup | +3 |
| 0 | FM02 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **2 ou +**  |  terminer 2 coup | |
| 0 | FM02 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 2 coup | |
| 0 | FM02 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 1 coup | +4 |
| 1 | FM03 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **5**  |  terminer 1 coup | |
| 1 | FM03 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 1 coup | |
| 1 | FM03 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 3 coup | |
| 1 | FM03 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 1 coup | |
| 1 | FM03 | Critère 5 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 1 coup | |
| 1 | FM03 | Critère 6 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 2 coup | |
| 1 | FM03 | Critère 7 | - **Valeur du dé** : 🎲 Tirer **1**  |  terminer 1 coup | |
| 1 | FM03 | Critère 8 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 2 coup | |
| 1 | FM03 | Critère 9 | - **Valeur du dé** : 🎲 Tirer **pair**  |  terminer 1 coup | +3 |
| 1 | FM04 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **2 ou +**  |  terminer 1 coup | |
| 1 | FM04 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 1 coup | |
| 1 | FM04 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **4 ou +** |  terminer 2 coup | |
| 1 | FM04 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 10 coup | |
| 1 | FM04 | Critère 5 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 12 coup | +3 |
| 1 | FM05 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **2 ou +**  |  terminer 1 coup | |
| 1 | FM05 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer2 coup | |
| 1 | FM05 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 3 coup | +2 |
| 1 | FM06 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **2 ou +**  |  terminer 2 coup | |
| 1 | FM06 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 1 coup | |
| 1 | FM06 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 1 coup | +5 |
| 2 | FM07 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **5**  |  terminer 1 coup | |
| 2 | FM07 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 1 coup | |
| 2 | FM07 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 6 coup | |
| 2 | FM07 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 16 coup | |
| 2 | FM07 | Critère 6 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 1 coup | |
| 2 | FM07 | Critère 7 | - **Valeur du dé** : 🎲 Tirer **1**  |  terminer 9 coup | |
| 2 | FM07 | Critère 8 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer7 coup | |
| 2 | FM07 | Critère 9 | - **Valeur du dé** : 🎲 Tirer **pair**  |  terminer 1 coup | |
| 2 | FM07 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **5**  |  terminer 1 coup | |
| 2 | FM07 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 1 coup | |
| 2 | FM07 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 2 coup | |
| 2 | FM07 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 3 coup | |
| 2 | FM07 | Critère 5 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 1 coup | |
| 2 | FM07 | Critère 6 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 5 coup | |
| 2 | FM07 | Critère 7 | - **Valeur du dé** : 🎲 Tirer **1**  |  terminer 1 coup | |
| 2 | FM07 | Critère 8 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 6 coup | |
| 2 | FM07 | Critère 9 | - **Valeur du dé** : 🎲 Tirer **pair**  |  terminer  coup | |
| 2 | FM07 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **5**  |  terminer 5 coup | |
| 2 | FM07 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 2 coup | |
| 2 | FM07 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 8 coup | |
| 2 | FM07 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 5 coup | |
| 2 | FM07 | Critère 6 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 2 coup | |
| 2 | FM07 | Critère 7 | - **Valeur du dé** : 🎲 Tirer **1**  |  terminer 1 coup | |
| 2 | FM07 | Critère 8 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 3 coup | |
| 2 | FM07 | Critère 9 | - **Valeur du dé** : 🎲 Tirer **pair**  |  terminer 2 coup | +38.5 |
| 3 | BUG1 | Critère 1 | - **Valeur du dé** : 🎲 **1**  |  terminer 2 coup | |
| 3 | BUG1 | Critère 2 | - **Valeur du dé** : 🎲 **3**  |  terminer 4 coup | |
| 3 | BUG1 | Critère 3 | - **Valeur du dé** : 🎲 **2**  |  terminer 5 coup | |
| 3 | BUG1 | Critère 4 | - **Valeur du dé** : 🎲 **4**  |  terminer 2 coup | |
| 3 | BUG1 | Critère 5 | - **Valeur du dé** : 🎲 **5**  |  terminer 2 coup | +0 |
| 3 | BUG2 | Critère 1 | - **Valeur du dé** : 🎲 **1**  |  terminer 2 coup | |
| 3 | BUG2 | Critère 2 | - **Valeur du dé** : 🎲 **3**  |  terminer 3 coup | |
| 3 | BUG2 | Critère 3 | - **Valeur du dé** : 🎲 **2**  |  terminer 3 coup | |
| 3 | BUG2 | Critère 4 | - **Valeur du dé** : 🎲 **4**  |  terminer 1 coup | |
| 3 | BUG2 | Critère 5 | - **Valeur du dé** : 🎲 **5**  |  terminer 12 coup | +0 |
| 3 | FM08 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **5**  |  terminer 4 coup | |
| 3 | FM08 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 3 coup | |
| 3 | FM07 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 2 coup | |
| 3 | FM08 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 4 coup | |
| 3 | FM08 | Critère 6 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 1 coup | |
| 3 | FM08 | Critère 7 | - **Valeur du dé** : 🎲 Tirer **1**  |  terminer 6 coup | |
| 3 | FM08 | Critère 8 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 3 coup | |
| 3 | FM08 | Critère 9 | - **Valeur du dé** : 🎲 Tirer **pair**  |  terminer 1 coup | |
| 3 | FM08 | Critère 1 | - **Valeur du dé** : 🎲 Tirer **5**  |  terminer 5 coup | |
| 3 | FM08 | Critère 2 | - **Valeur du dé** : 🎲 Tirer **4 ou +**  |  terminer 2 coup | |
| 3 | FM08 | Critère 3 | - **Valeur du dé** : 🎲 Tirer **5 ou +**  |  terminer 1 coup | |
| 3 | FM08 | Critère 4 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 2 coup | |
| 3 | FM08 | Critère 6 | - **Valeur du dé** : 🎲 Tirer **3 ou +**  |  terminer 1 coup | |
| 3 | FM08 | Critère 7 | - **Valeur du dé** : 🎲 Tirer **1**  |  terminer 10 coup | |
| 3 | FM08 | Critère 8 | - **Valeur du dé** : 🎲 Tirer **6**  |  terminer 5 coup | |
| 3 | FM08 | Critère 9 | - **Valeur du dé** : 🎲 Tirer **pair**  |  terminer 3 coup | +22.5 |

---

## Définition of Done (DoD)
- [ ] Tous les critères d'acceptation sont validés (4/4)
- [ ] Code reviewé et mergé
- [ ] Tests unitaires passent
- [ ] Démo préparée pour la revue de sprint
