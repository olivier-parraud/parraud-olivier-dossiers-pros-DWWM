# Dossier de Certification — Titre Professionnel Développeur Web & Web Mobile (DWWM)

Bienvenue sur le dépôt de présentation des dossiers d'évaluation et de soutenance d'**Olivier PARRAUD** pour le passage du **Titre Professionnel Développeur Web et Web Mobile (DWWM)** — Session 2026.

---

## 👤 À propos du Candidat

**Olivier PARRAUD**  
*Développeur Full-Stack Web & Web Mobile*  
🎓 Formation : **Titre Professionnel DWWM (Niveau 5 / Bac+2)** — [La Plateforme_](https://laplateforme.io) (Marseille)  
📜 Référentiel REAC — Ministère du Travail, du Plein emploi et de l'Insertion  
🎯 Formation initiale : Baccalauréat Professionnel Systèmes Numériques (SN) — Option Réseaux (2016-2019)

### Parcours & Profil
Issu d'une formation initiale en systèmes numériques et réseaux informatiques, j'ai consolidé au fil de mes expériences une grande rigueur méthodologique, le sens de l'organisation et une capacité affirmée à résoudre des problèmes techniques complexes.

Ma reconversion vers le développement web s'est concrétisée au sein de l'école **La Plateforme_**, où j'ai pu acquérir et affirmer mes compétences dans les deux volets fondamentaux du métier :
- **Front-end & UX/UI** : Maquettage axé *Mobile-First* (Figma / FigJam), composants réactifs et modulaires (React 18, Vite, Tailwind CSS), gestion fine de l'asynchronisme et manipulations dynamiques du DOM.
- **Back-end & Persistance** : Modélisation relationnelle rigoureuse (MCD, MLD, SQL MySQL), développement d'API RESTful robustes et sécurisées (Node.js/Express, PHP MVC), contrôle d'accès RBAC et jetons JWT, mécanismes de résilience (failover, cache) et déploiement continu via Git.

---

## 📂 Présentation des 3 Documents du Dépôt

Ce répertoire rassemble les trois livrables documentaires officiels soumis à l'évaluation du jury d'examen :

```
📁 parraud-olivier-dossiers-pros-DWWM/
├── 📄 parraud-olivier-resume.pdf          # Synthèse exécutive du projet Cicados (4 pages)
├── 📄 parraud-olivier-dossier-projet.pdf   # Rapport technique & projet final Cicados (74 pages)
└── 📄 parraud-olivier-dossier-pro.pdf      # Dossier Professionnel (DP) ministériel officiel (37 pages)
```

---

### 1. 📋 [`parraud-olivier-resume.pdf`](parraud-olivier-resume.pdf) — Résumé de Projet : CICADOS
> **Format** : Synthèse exécutive de 4 pages  
> **Projet présenté** : **CICADOS** — Plateforme Web de Réservation de Tables & Gestion d'Événements pour Bar à Jeux et Duels TCG.

Ce document offre une vision synthétique et percutante de l'application conçue et développée en totale autonomie :
- **Problématique & Valeur ajoutée** : Résolution des contraintes logistiques d'un bar à jeux physique (capacité limitée à 4 tables), élimination du risque de surbooking et centralisation des tournois TCG (*Magic: The Gathering*, *Pokémon*, *Yu-Gi-Oh*, etc.).
- **Architecture technique découplée** :
  - **Front-end** : Single Page Application (SPA) réactive construite avec **React 18**, **Vite 7**, **Tailwind CSS** et **Lucide Icons**.
  - **Back-end** : API REST sous **Node.js / Express** avec requêtes SQL préparées (`mysql2`).
  - **Persistance & Résilience** : Base de données **MySQL 8.0** couplée à un mécanisme de secours automatique (**Failover local JSON**) garantissant la haute disponibilité du catalogue en cas de panne de l'API externe ou de la BDD.
  - **Intégrations externes** : Proxy d'interrogation et conversion de catalogue en flux XML vers JSON depuis l'API officielle **BoardGameGeek (BGG)**.
- **Fonctionnalités clés** : Algorithme anti-surbooking basé sur l'intersection temporelle de créneaux, messagerie/support multi-tours en temps réel avec badges dynamiques de notifications, gestion de stock boutique en direct, tests automatisés de bout en bout (**Puppeteer E2E**).

---

### 2. 📘 [`parraud-olivier-dossier-projet.pdf`](parraud-olivier-dossier-projet.pdf) — Dossier de Projet Complet : CICADOS
> **Format** : Rapport technique exhaustif de 74 pages  
> **Rôle** : Document de référence technique, méthodologique et organisationnel du projet d'examen.

Ce rapport final détaille pas à pas l'intégralité du cycle de vie du projet **Cicados**, illustrant la maîtrise de bout en bout d'un projet informatique d'envergure :
- **Genèse, contexte et cahier des charges** : Analyse du secteur ludique hybride (boutique, café, jeu sur place), identification des personas, cas d'utilisation et contraintes métier.
- **Spécifications fonctionnelles & techniques** :
  - Algorithme d'allocation et de vérification d'overlap de réservation de tables en temps réel.
  - Module support client bidirectionnel (utilisateur / admin) avec architecture événementielle (`messages_updated`).
  - Gestion des stocks en boutique avec mise à jour asynchrone AJAX et pastilles dynamiques de disponibilité.
  - Service proxy d'interfaçage avec le catalogue international BoardGameGeek.
- **Conception & Modélisation de données** :
  - Schématisation conceptuelle et logique : Dictionnaire de données, **MCD** (Modèle Conceptuel de Données), **MLD** (Modèle Logique) et **MPD** (Modèle Physique).
  - Intégrité relationnelle, indexation et script SQL complet de création et d'amorçage des tables.
- **Design UX/UI & Prototypage** :
  - Démarche *Mobile-First*, wireframes et planches graphiques haute-fidélité réalisées sous **Figma**.
  - Architecture des composants React et découpage modulaire du style avec Tailwind CSS.
- **Qualité, Sécurité & Validation** :
  - Authentification par jetons sécurisés **JWT** et contrôle d'accès basé sur les rôles (**RBAC**).
  - Campagne de tests automatisés E2E scriptés avec **Puppeteer** validant les flux utilisateurs critiques.
  - Fiches de configuration d'environnements et variables `.env`.

---

### 3. 📑 [`parraud-olivier-dossier-pro.pdf`](parraud-olivier-dossier-pro.pdf) — Dossier Professionnel (DP)
> **Format** : Document réglementaire officiel du Ministère du Travail (37 pages)  
> **Rôle** : Justification des compétences professionnelles acquises (Activités-Types AT1 et AT2 du Référentiel REAC).

Le Dossier Professionnel rassemble les preuves concrètes d'exercice professionnel mobilisées sur plusieurs projets réalisés au cours du parcours :

#### 🔹 Activité-type 1 : Développer la partie front-end d'une application web ou web mobile sécurisée
* **Exemple 1 (CP 1)** — *Installer et configurer son environnement de travail en fonction du projet web ou web mobile* :
  - Projet : `reservations-salle` (Full-Stack React & Node.js/Express).
  - Mise en place de dépôts Git, arborescence découplée `/frontend` et `/backend`, gestion des variables d'environnement (`.env`), initialisation du schéma MySQL et orchestration des serveurs de développement locaux.
* **Exemple 2 (CP 2 & CP 3)** — *Maquetter des interfaces utilisateur & Réaliser des interfaces utilisateur statiques web ou web mobile* :
  - Projet : `MarsAI Festival` (Festival international de courts-métrages réalisés par IA).
  - Conception de parcours utilisateurs pour 4 profils (visiteurs, réalisateurs, jury, admin) via FigJam et Figma selon la démarche *Mobile-First*.
  - Développement de l'UI statique responsive avec **React**, **Tailwind CSS**, mise en place des layouts réutilisables, navigation avec **React Router Dom (v7)** et internationalisation avec **i18next**.
* **Exemple 3 (CP 4)** — *Développer la partie dynamique des interfaces utilisateur web ou web mobile* :
  - Projet : Jeu de `Memory` en ligne (Architecture MVC, JavaScript moderne ES6+ et PHP).
  - Écoute d'événements DOM, conditions de garde, animations CSS dynamiques, communication asynchrone via l'**API Fetch** native et mise à jour de l'interface en temps réel sans rechargement de page.

#### 🔹 Activité-type 2 : Développer la partie back-end d'une application web ou web mobile sécurisée
* **Exemple 1 (CP 5 & CP 6)** — *Mettre en place une base de données relationnelle & Développer des composants d’accès aux données SQL et NoSQL* :
  - Projet : `Médiathèque` (Catalogue de livres et gestion de prêts).
  - Conception du schéma relationnel MySQL, script SQL d'initialisation, implémentation d'une couche d'accès aux données avec **PDO** et requêtes préparées pour contrer les injections SQL, patron de conception **Singleton** pour la connexion à la base de données, et modularité ouvrant vers le NoSQL.
* **Exemple 2 (CP 7 & CP 8)** — *Développer des composants métier côté serveur & Documenter le déploiement d’une application dynamique web ou web mobile* :
  - Projet : `MarsAI Festival` & Application `Memory`.
  - Conception d'une **API RESTful** sous Node.js/Express (architecture Controllers / Services / Models), système de tokens **JWT**, téléversement de médias, intégration de services tiers transactionnels (**API Brevo**).
  - Procédure pas à pas documentée du déploiement continu d'une application dynamique sur serveur de production hébergé sous **Plesk** via liaisons sécurisées de clés SSH et synchronisation automatique avec GitHub.
* **Annexes & Justificatifs** :
  - Planches de maquettes Figma complètes du festival MarsAI (versions mobile & desktop, tableaux de bord).
  - Schémas relationnels de base de données (Memory, Médiathèque).
  - Extraits de scripts SQL, déclaration sur l'honneur et copie du diplôme initial en Systèmes Numériques.

---

## 🛠️ Stack Technique & Compétences Maîtrisées

| Domaine | Technologies, Outils & Méthodes |
| :--- | :--- |
| **Front-end** | React 18, Vite, JavaScript (ES6+), Tailwind CSS, HTML5 sémantique, CSS3 (animations/transitions), Lucide Icons, React Router |
| **Back-end** | Node.js, Express.js, PHP (orienté objet, architecture MVC, PDO), Composer (PSR-4), Architecture en couches (Controllers / Services / Models) |
| **Bases de données** | MySQL 8.0, SQL relationnel (MCD / MLD / MPD), requêtes préparées, modélisation logique, HeidiSQL |
| **Sécurité & Authentification** | JWT (JSON Web Tokens), Bcrypt (hachage des mots de passe), RBAC (contrôle d'accès basé sur les rôles), requêtes préparées anti-injections SQL |
| **DevOps, Outils & Déploiement** | Git, GitHub, Plesk, Linux/Bash, PowerShell, Puppeteer (tests E2E automatisés), gestion multi-environnements (`.env`) |
| **Conception UX / UI** | Figma, FigJam, démarche *Mobile-First*, Wireframing, prototypage interactif, Atomic Design |
| **Méthodologies** | Méthodes Agiles / Scrum, découpage en User Stories, spécifications fonctionnelles et techniques |

---

## 📬 Contact

Pour toute question ou échange relatif à ces dossiers ou à mes réalisations :

- **Candidat** : Olivier PARRAUD
- **Formation** : La Plateforme_ — Marseille
- **Dossiers disponibles** :
  - [Résumé de projet (PDF)](parraud-olivier-resume.pdf)
  - [Dossier de projet complet (PDF)](parraud-olivier-dossier-projet.pdf)
  - [Dossier professionnel - DP (PDF)](parraud-olivier-dossier-pro.pdf)
  
