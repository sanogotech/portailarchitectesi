
# 🔍 **PHASE 1 – Expression du besoin & Analyse stratégique (Mois 1 à 3)**

## 🎯 **Objectif principal**

Comprendre les attentes des parties prenantes internes et externes, modéliser les processus métiers existants, identifier les irritants et les opportunités d’amélioration, analyser les contraintes techniques, réglementaires et de sécurité, et produire un **cadrage initial du besoin et de l’architecture cible**.

---

## 🗂️ **Sous-phases détaillées**

| N° | Sous-phase                                  | Détails                                                                                                                                                                                  |
| -- | ------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | **Analyse stratégique & alignement métier** | Cadrage avec la Direction Générale, DSI, métiers, conformité. Objectif : aligner le projet avec la stratégie d’entreprise (digitalisation, qualité client, optimisation opérationnelle). |
| 2  | **Recueil des besoins métier**              | Ateliers, interviews, questionnaires avec les directions concernées : relation client, facturation, IT, exploitation, agences, support, marketing.                                       |
| 3  | **Étude de l’existant**                     | Analyse des portails existants, SI connectés (CRM, ERP, MDM, HES), infrastructures réseaux (agences, clients, IoT), outils actuels (applications mobiles, USSD, etc.).                   |
| 4  | **Analyse des irritants clients**           | Étude des réclamations, logs du centre d’appel, forums, réseaux sociaux, NPS/CSAT.                                                                                                       |
| 5  | **Étude réglementaire & sécurité**          | RGPD, loi protection des consommateurs, CNIL, exigences légales de facturation et de confidentialité, exigences cyber, normes internes SSI.                                              |
| 6  | **Benchmark & inspiration**                 | Études des leaders (EDF, Engie, Orange Energie, Senelec, etc.), modèles africains (mobile money, interface USSD), tendances UX/UI.                                                       |
| 7  | **Modélisation des besoins**                | Diagrammes BPMN, parcours utilisateurs, user stories, SWOT, matrice MoSCoW.                                                                                                              |
| 8  | **Synthèse & recommandations**              | Cahier des charges, dossier de cadrage fonctionnel et technique, premières recommandations d’architecture cible.                                                                         |

---

## 👥 **Contributions des membres de la cellule d’architecture**

| Rôle                     | Actions détaillées                                                                                                                                                                                                                                                                               |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Architecte Solutions** | - Anime les ateliers avec les métiers.<br>- Modélise les parcours clients (BPMN, UML, User Journey).<br>- Formalise les user stories et les exigences métier.<br>- Hiérarchise les cas d’usage (MoSCoW).<br>- Rédige la première version du *Product Vision Document*.                           |
| **Architecte Logiciel**  | - Identifie les capacités applicatives existantes (ex. : CRM, mobile app, portail agence).<br>- Évalue la dette technique et la qualité logicielle actuelle.<br>- Réalise un mapping fonctionnel SI / besoins exprimés.<br>- Propose les premiers patterns applicatifs cibles.                   |
| **Architecte Technique** | - Fait l’inventaire des infrastructures (serveurs, cloud, réseau, datacenter, connectivité clients).<br>- Évalue la couverture mobile / internet du parc client.<br>- Identifie les contraintes d’interopérabilité (ESB, API Manager).<br>- Vérifie la capacité de résilience et de scalabilité. |
| **Architecte DevSecOps** | - Audite les outils DevOps actuels (Git, Jenkins, Docker, Nexus…).<br>- Évalue la maturité de l’organisation DevOps et propose un modèle cible.<br>- Recense les besoins de CI/CD dès la phase d’exploration.<br>- Prépare une pipeline d’expérimentation pour les PoC futurs.                   |
| **Architecte Sécurité**  | - Vérifie la conformité RGPD, ISO 27001, exigences internes de la DSSI.<br>- Identifie les données sensibles manipulées (comptes, contrats, paiements).<br>- Évalue les risques potentiels (IAM, USSD, API, M2M).<br>- Propose un cadre de sécurité dès le départ (Zero Trust, MFA, etc.).       |

---

## 📄 **Livrables produits (Phase 1)**

| Livrable                                                      | Description                                                           |
| ------------------------------------------------------------- | --------------------------------------------------------------------- |
| 📘 **Note de cadrage stratégique**                            | Synthèse des enjeux métiers, attentes, objectifs et contraintes.      |
| 📋 **Catalogue des besoins**                                  | Fiches besoins fonctionnels et non fonctionnels.                      |
| 🧭 **Carte des parcours utilisateurs**                        | Représentation visuelle des interactions client / SI / agents.        |
| 📉 **Analyse SWOT & MoSCoW**                                  | Priorisation des cas d’usage, forces/faiblesses/opportunités/risques. |
| 🏛️ **Cartographie des systèmes existants**                   | Vue d’ensemble des applications et interactions techniques.           |
| 🔐 **Étude de conformité et risques cybersécurité**           | Premières recommandations pour sécurité dès la conception.            |
| 📊 **Benchmark**                                              | Comparatif des portails similaires + recommandations.                 |
| 🧱 **Première version de l’architecture cible fonctionnelle** | Cartographie haut niveau (macroservices, modules).                    |

---

## ⚙️ **Outils mobilisés**

| Domaine                    | Outils proposés                         |
| -------------------------- | --------------------------------------- |
| Modélisation fonctionnelle | Draw\.io, ArchiMate, Bizagi, Lucidchart |
| Expression des besoins     | Jira, Trello, Confluence, Excel         |
| Interviews utilisateurs    | Miro, Forms, Notion                     |
| Documentation              | Word, PowerPoint, Notion                |
| Collaboration équipe       | Teams, Slack, SharePoint, GitLab Wiki   |

---

## ✅ **Critères de validation de la phase 1**

| Critère                                | Objectif                                       |
| -------------------------------------- | ---------------------------------------------- |
| 🚀 Alignement stratégique              | Validé par la Direction Générale / Métier      |
| 🎯 Exhaustivité des besoins            | Au moins 80% des cas d’usage couverts          |
| 🧭 Vision fonctionnelle cible claire   | Appuyée par les parcours utilisateurs          |
| 🔒 Sécurité & conformité               | Premiers points de contrôle RGPD, IAM, données |
| 🧠 Maturité DevSecOps initiale mesurée | Pour prévoir l’outillage futur                 |

---

## 📆 **Calendrier indicatif de la Phase 1**

| Semaine | Activité                                            |
| ------- | --------------------------------------------------- |
| S1–S2   | Kick-off projet, interviews métiers                 |
| S3–S4   | Ateliers métiers et mapping SI                      |
| S5      | Étude réglementaire et sécurité                     |
| S6      | Benchmark, inspiration UX/UI                        |
| S7      | Modélisation et priorisation des besoins            |
| S8–S9   | Revue d’équipe architecture + production livrables  |
| S10     | Présentation à la direction + validation Go Phase 2 |

---

Souhaitez-vous maintenant :

* Un **modèle de document Word/Confluence** prêt à remplir pour cette phase ?
* Un **template PowerPoint** pour présenter cette phase au comité de pilotage ?
* Un **outil automatisé d’analyse de maturité DevSecOps/Sécurité** à proposer ?

