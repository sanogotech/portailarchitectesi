# 🧭 PROJET FICTIF COMPLET : « Portail Clients Multicanal d’un Distributeur d’Électricité »

### 🎯 Objectif global :

Mettre à disposition des clients particuliers, entreprises et collectivités un **portail sécurisé, intuitif et multicanal** (Web, Mobile, USSD) pour :

* Consulter leurs factures et historiques.
* Suivre leur consommation (temps réel via IoT).
* Gérer les incidents et dépôts de réclamations.
* Accéder à des services financiers (paiement mobile, report de paiement, simulation).
* Être notifiés en temps réel (SMS/Push/Email).

---

## 🧩 PHASE 1 — **Expression de besoin & Analyse stratégique (Mois 1 à 3)**

### 📌 Activités clés :

* Interviews avec les directions Métiers : commerciale, client, IT, conformité.
* Benchmark de portails similaires (EDF, Enedis, Orange Énergie, etc.).
* Identification des irritants actuels (via centre d’appel, CRM, réseaux sociaux).
* Cartographie des processus métiers existants.
* Étude des contraintes réglementaires (RGPD, eIDAS, loi sur la protection des consommateurs, etc.).

### 🎓 Rôles activés :

| Rôle                     | Contributions détaillées                                                                                        |
| ------------------------ | --------------------------------------------------------------------------------------------------------------- |
| **Architecte Solutions** | Anime les ateliers métier, modélise les exigences métiers (BPMN, SWOT), et formalise les cas d’usage.           |
| **Architecte Logiciel**  | Identifie les capacités fonctionnelles existantes dans les SI actuels (CRM, ERP, mobile app), et les gaps.      |
| **Architecte Technique** | Recense l'infrastructure existante, les zones blanches, la connectivité réseau, et les capacités Cloud/On-prem. |
| **Architecte DevSecOps** | Évalue la maturité DevOps de l'organisation, les outils actuels (GitLab, Jenkins, etc.), et les lacunes CI/CD.  |
| **Architecte Sécurité**  | Recense les exigences de conformité, l’historique des incidents de sécurité, les standards internes.            |

### 📂 Livrables :

* Étude de faisabilité et ROI estimé
* Modèle de besoins fonctionnels et non-fonctionnels
* Cahier des charges structuré
* Note de cadrage d'architecture cible (Haut niveau)

---

## 🧱 PHASE 2 — **Cadrage d’architecture et scénarios cibles (Mois 3 à 6)**

### 📌 Activités clés :

* Élaboration de plusieurs scénarios d’architecture (centralisé, microservices, cloud-native).
* Étude d’impact sur les systèmes existants (ESB, IAM, CRM, HES, MDM, etc.).
* Choix des technologies cibles (React, Flutter, Kafka, Keycloak, MongoDB, OpenShift, etc.).
* Définition de la gouvernance du projet (modes de livraison Agile, cycle de vie, outillage).

### 🎓 Rôles activés :

| Rôle                     | Contributions détaillées                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------------------------- |
| **Architecte Solutions** | Priorise les parcours client et propose une roadmap MVP → v1 → v2.                                      |
| **Architecte Logiciel**  | Modélise l'architecture logicielle cible (diagramme C4, Domain-Driven Design, API REST, microservices). |
| **Architecte Technique** | Propose l'infrastructure cible (Cloud privé, CDN, load balancer, tolérance aux pannes, scalabilité).    |
| **Architecte DevSecOps** | Définit la chaîne CI/CD de bout en bout : GitOps, GitLab Runners, Helm Charts, Prometheus.              |
| **Architecte Sécurité**  | Définit la stratégie Zero Trust, MFA, gestion des habilitations RBAC/ABAC, intégrité et traçabilité.    |

### 📂 Livrables :

* Dossier d’architecture technique (DAT) complet
* Catalogue des exigences techniques, de sécurité et de performance
* Tableau comparatif des scénarios d’architecture
* MVP Scope (Minimum Viable Product)

---

## 🛠️ PHASE 3 — **Conception détaillée & Planification (Mois 6 à 9)**

### 📌 Activités clés :

* Rédaction des spécifications détaillées (interfaces, APIs, logique métier).
* Sélection des partenaires/prestataires (intégrateurs, éditeurs).
* Conception des workflows internes (notification, authentification, paiement).
* Intégration avec le SI (HES-MDM, CRM, Billing, IAM Keycloak).

### 🎓 Rôles activés :

| Rôle                     | Contributions détaillées                                                                                      |
| ------------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Architecte Logiciel**  | Décompose en modules (usagers, factures, incidents, USSD API, notifications, dashboards).                     |
| **Architecte DevSecOps** | Met en place l'environnement de développement conteneurisé avec tests unitaires et d’intégration automatisés. |
| **Architecte Technique** | Spécifie les environnements d’intégration, test, préprod, production et leur supervision.                     |
| **Architecte Sécurité**  | Conçoit le modèle de sécurité : DLP, journalisation, chiffrement TLS/At-Rest, audit SOC.                      |
| **Architecte Solutions** | Maintient l’alignement fonctionnel et la traçabilité des exigences.                                           |

### 📂 Livrables :

* Cahier de spécifications techniques détaillées
* Modèle de données et schéma de base de données
* Plan projet agile (épopées, sprints, backlog produit)

---

## 🧪 PHASE 4 — **Développement, tests et intégration (Mois 9 à 15)**

### 📌 Activités clés :

* Développement incrémental (Scrum, 2 semaines/sprint).
* CI/CD avec contrôle de qualité automatisé.
* Intégration de l’authentification (Keycloak, OpenID Connect).
* Tests fonctionnels, charge, sécurité, UX (accessibilité numérique, mobile-first).

### 🎓 Rôles activés :

| Rôle                     | Contributions détaillées                                                                               |
| ------------------------ | ------------------------------------------------------------------------------------------------------ |
| **Architecte DevSecOps** | Implémente SonarQube, Snyk, Checkmarx, GitLabCI, Vault pour secrets.                                   |
| **Architecte Logiciel**  | Supervise les branches de code, les modèles TDD/DDD, l’implémentation des patterns (adapter, façade…). |
| **Architecte Technique** | Gère les tests de montée en charge, latence réseau, pics de trafic, déploiement sur OpenShift.         |
| **Architecte Sécurité**  | Réalise des tests d’intrusion, analyse OWASP Top 10, contrôle les jetons JWT, logs de session.         |
| **Architecte Solutions** | Valide chaque livraison métier, organise les démos aux sponsors.                                       |

### 📂 Livrables :

* Pipelines CI/CD en production
* Dashboard de qualité code / couverture de test
* Rapport de tests de charge et sécurité

---

## 🚀 PHASE 5 — **Mise en production & Transition vers l’exploitation (Mois 15 à 18)**

### 📌 Activités clés :

* Mise en production avec rollback plan.
* Documentation de l’architecture, des procédures de supervision.
* Transfert de compétences vers l’équipe d’exploitation N1/N2/N3.
* Mise en place des outils de supervision (Prometheus, Grafana, ELK, Zabbix).
* Formation utilisateurs internes (support, service client, agences).

### 🎓 Rôles activés :

| Rôle                     | Contributions détaillées                                                          |
| ------------------------ | --------------------------------------------------------------------------------- |
| **Architecte DevSecOps** | Gère le déploiement GitOps, le suivi post-déploiement via observabilité.          |
| **Architecte Technique** | Supervise le dimensionnement définitif, les bascules DNS, CDN, cache applicatif.  |
| **Architecte Sécurité**  | Assure la continuité de sécurité : surveillance EDR, alerting SIEM, réponses SOC. |
| **Architecte Solutions** | Organise les tests utilisateurs finaux, collecte les feedbacks de terrain.        |

### 📂 Livrables :

* Procédure d’exploitation / supervision
* Journal des accès, rapports SOC
* Tableau de bord SLA/SLO

---

## 🔁 PHASE 6 — **Évolution, REX et capitalisation (Mois 18 à 24)**

### 📌 Activités clés :

* REX auprès des utilisateurs internes/externes.
* Mise à jour des référentiels (patterns, outils validés, bonnes pratiques).
* Déploiement de nouvelles fonctionnalités (chatbot, IA, recommandations).
* Intégration avec d’autres canaux (WhatsApp, partenaires tiers).

### 🎓 Rôles activés :

| Rôle                     | Contributions détaillées                             |
| ------------------------ | ---------------------------------------------------- |
| **Tous**                 | Organisent un retour d’expérience global documenté.  |
| **Architecte Solutions** | Produit un dossier de capitalisation métier.         |
| **Architecte DevSecOps** | Enrichit les bibliothèques d’outils DevOps.          |
| **Architecte Logiciel**  | Crée des modèles de composants réutilisables.        |
| **Architecte Sécurité**  | Propose une évolution de la politique cybersécurité. |

### 📂 Livrables :

* REX officiel
* Mise à jour du catalogue des composants validés
* Feuille de route V2

---

Souhaitez-vous maintenant :

1. Une **présentation PowerPoint illustrée** ?
2. Un **rapport de projet Word/PDF** avec visuels (diagrammes C4, ArchiMate, processus BPMN) ?
3. Un **template de dossier projet complet** réutilisable pour d'autres projets ?

