

# 🚀 🧠 BACKLOG PRODUIT — PRIORIFY

---

# 🎯 1. OBJECTIF PRODUIT

> Application de gestion de tâches type **Kanban (comme Trello / GitHub Projects)**
> avec priorisation, suivi et authentification utilisateur.

---

# 🧱 2. EPIC 1 — AUTHENTIFICATION 🔐

### 🎯 Objectif : gérer les utilisateurs

#### Features

* [ ] [AUTH] Créer un compte utilisateur
* [ ] [AUTH] Se connecter
* [ ] [AUTH] Se déconnecter
* [ ] [AUTH] Hash password (BCrypt)
* [ ] [AUTH] Gestion session (Spring Security)

#### Avancé

* [ ] [AUTH] JWT Authentication
* [ ] [AUTH] Refresh token
* [ ] [AUTH] Roles (USER / ADMIN)

---

# 🧱 3. EPIC 2 — TASK MANAGEMENT 📝

### 🎯 Objectif : CRUD complet des tâches

#### Base

* [ ] [TASK] Créer une tâche
* [ ] [TASK] Voir toutes les tâches
* [ ] [TASK] Voir une tâche
* [ ] [TASK] Modifier une tâche
* [ ] [TASK] Supprimer une tâche

#### Champs Task

* title
* description
* status (TODO / IN_PROGRESS / DONE)
* priority (LOW / MEDIUM / HIGH)
* createdAt
* updatedAt

---

# 🧱 4. EPIC 3 — KANBAN BOARD 📊

### 🎯 Objectif : affichage visuel

* [ ] [KANBAN] Colonnes (Todo / In Progress / Done)
* [ ] [KANBAN] Drag & drop task
* [ ] [KANBAN] Update status en drag
* [ ] [KANBAN] Affichage dynamique

---

# 🧱 5. EPIC 4 — FILTRES & TRI 🔍

### 🎯 Objectif : organiser les tâches

* [ ] [FILTER] Filtrer par status
* [ ] [FILTER] Filtrer par priorité
* [ ] [FILTER] Recherche par titre
* [ ] [SORT] Trier par date
* [ ] [SORT] Trier par priorité

---

# 🧱 6. EPIC 5 — BACKEND ARCHITECTURE ⚙️

### 🎯 Objectif : code propre

* [ ] [BACKEND] Architecture en couches (Controller / Service / Repo)
* [ ] [BACKEND] DTO (Request / Response)
* [ ] [BACKEND] Mapper DTO ↔ Entity
* [ ] [BACKEND] Exception globale (✔ déjà fait)
* [ ] [BACKEND] Validation (@Valid)

---

# 🧱 7. EPIC 6 — DATABASE 🗄️

### 🎯 Objectif : persistance

* [ ] [DB] Connexion PostgreSQL (✔ presque fait)
* [ ] [DB] Création tables
* [ ] [DB] Relations (User → Task)
* [ ] [DB] Migration (Flyway ou Liquibase)

---

# 🧱 8. EPIC 7 — FRONTEND (React) 🎨

### 🎯 Objectif : interface utilisateur

* [ ] [FRONT] Setup React
* [ ] [FRONT] Page Login
* [ ] [FRONT] Page Register
* [ ] [FRONT] Dashboard
* [ ] [FRONT] Kanban Board UI
* [ ] [FRONT] API calls (fetch / axios)

---

# 🧱 9. EPIC 8 — SECURITY 🔐

### 🎯 Objectif : sécurité

* [ ] [SECURITY] Spring Security config
* [ ] [SECURITY] Protéger routes API
* [ ] [SECURITY] Password encrypté
* [ ] [SECURITY] Gestion erreurs auth

---

# 🧱 10. EPIC 9 — BONUS (LEVEL UP 🚀)

👉 pour faire un projet **CV niveau pro**

* [ ] [BONUS] Notifications
* [ ] [BONUS] Deadline tasks
* [ ] [BONUS] Assign user to task
* [ ] [BONUS] Commentaires sur tâches
* [ ] [BONUS] Dark mode 🌙
* [ ] [BONUS] Export CSV / PDF

---

# 🧠 11. ORGANISATION (IMPORTANT)

## 🟣 Backlog (tout ce que tu viens de voir)

## 🟢 Sprint 1 (ce que tu dois faire MAINTENANT)

👉 FOCUS 🔥

* [ ] Connexion PostgreSQL
* [ ] Entity Task
* [ ] Repository
* [ ] Service
* [ ] Controller `/api/tasks`
* [ ] Test API avec Postman

---

## 🟡 Sprint 2

* [ ] DTO + validation
* [ ] Gestion erreurs propre
* [ ] Enum status / priority

---

## 🔵 Sprint 3

* [ ] Authentification
* [ ] Security

---

## 🟣 Sprint 4

* [ ] Frontend React
* [ ] Kanban UI

---


