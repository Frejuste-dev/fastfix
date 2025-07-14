
# 🎫 Système de Ticketing Informatique (fastfix) - SIBM

## 🚀 Présentation du projet

Le projet **Système de Ticketing Informatique (fastfix)** vise à offrir à la **SIBM (Société Ivoirienne de Béton Manufacturé)** une solution moderne et centralisée de gestion des incidents IT et des demandes d’assistance, réparties sur ses différents sites géographiques.

Cette application permettra :

- De fluidifier la communication entre utilisateurs et service IT
- D’assurer un meilleur suivi des tickets (création, traitement, résolution)
- D’optimiser la charge de travail des techniciens via des workflows et automatisations
- De générer des statistiques précises pour piloter la performance IT

---

## 📂 Technologies utilisées

### Backend

- Python, Django REST Framework
- JWT Authentication (djangorestframework-simplejwt)
- Redis (Sessions, Notifications temps réel via Django Channels)
- SQL Server (production), MySQL (développement)
- Docker, CI/CD

### Frontend

- React.js (Hooks, Context API)
- WebSocket pour notifications et chat temps réel
- Responsive Web (Desktop / Mobile)

### Autres outils

- Sentry, Prometheus, Grafana (Monitoring)
- GitHub, Docker Hub, Nginx
- Postman (Tests API)

---

## 📦 Fonctionnalités clés

### 🎯 MVP (Minimum Viable Product)

- Authentification JWT & gestion des rôles (Admin, IT, Utilisateur)
- Création / Suivi / Gestion des tickets
- Notifications email
- Priorisation automatique des incidents
- Dashboard utilisateurs & IT
- Responsive design desktop / mobile

### 🔧 Optimisation (Phase 2)

- Upload de fichiers (pièces jointes)
- Notifications en temps réel (WebSocket)
- Chat direct technicien / utilisateur
- Base de connaissances, rapports et statistiques
- Gestion des sites géographiques

### 🌟 Avancé (Phase 3)

- Analytics prédictives
- Inventaire IT, licences, audit trail
- Intégrations (AD, LDAP, Email-to-ticket)
- Application mobile technicien (PWA ou React Native)
- Conformité RGPD, Accessibilité WCAG 2.1, 2FA

---

## 🛠️ Installation (environnement de développement)

### Prérequis

- Docker & Docker-Compose installés

### Lancer le projet localement

```bash
git clone https://github.com/Frejuste-dev/fasrfix.git
cd SITI
docker-compose up --build
```

### Accès

- Frontend : `http://localhost:3000`
- Backend API : `http://localhost:8000/api/`
- Admin Django : `http://localhost:8000/admin/`

---

## 📊 Suivi du projet

### Backlog complet : [Voir le fichier BACKLOG.md](./BACKLOG.md)

### GANTT simplifié : [Voir le fichier GANTT.md](./GANTT.md)

---

## 👥 Auteurs / Contributions

- **Frejuste Kei Prince** - Lead Développement & Pilotage Technique

---

## 🔐 Sécurité

- JWT, 2FA pour rôles sensibles
- Protection XSS, CSRF, audit trail complet
- RGPD : Consentement, droit à l’oubli, exportation des données

---

## 📄 Licence

Projet interne privé - SIBM (Société Ivoirienne de Béton Manufacturé) - 2025
