# Cahier-des-charges
Cahier des charges GreenRoots
Présentation du site "GreenRoots"
Bienvenue sur GreenRoots, votre plateforme écoresponsable dédiée à la reforestation et à la préservation de notre planète. Notre mission est simple : permettre à chaque individu et à chaque association de contribuer activement à la lutte contre le changement climatique en plantant des arbres.

- **Quoi ?** Développement d'une plateforme d'e-commerce permettant d'acheter des arbres à planter (par GreenRoots et demain des associations tierces) pour contribuer à la reforestation.
- **Qui ?** GreenRoots (fictif) est née de l’urgence de prendre des mesures concrètes pour préserver notre planète face à la déforestation et au changement climatique.
- **Pour qui ?** Public éco-conscient, entreprises responsables, associations engagées, etc.
- **Comment ?** En équipe à définir (positionnement via un formulaire de voeux) par l'équipe pédagogique. Organisation en méthode agile pour la gestion de projet.
- **Quand ?** Pendant 4 semaines correspondant à 4 sprints (conception, code, déploiement, recettage, etc.).
- **Pourquoi ?** Pour la réalisation d'un projet fictif à but pédagogique visant l'obtention du Titre Professionnel.
  
  ## La définition des besoins  et des objectifs  du projet
  ### 1. **Définition des besoins :**

- **Plateforme e-commerce** : Le besoin de créer une plateforme qui permet d’acheter des arbres répond à un objectif central.
- **Catalogue de produits (arbres)** : La nécessité d’un catalogue structuré avec des informations pertinentes est essentielle dans un site e-commerce.
- **Système de dons et d’achats** : Vous identifiez le besoin d’un processus d’achat intuitif, un des piliers d’un site e-commerce.
- **Suivi des arbres** : La demande de transparence et de suivi personnalisé des arbres plantés est un besoin clé pour rassurer l'utilisateur et renforcer son engagement.
- **Espace de gestion pour administrateurs** : Le besoin d’une gestion administrative complète (back-office) est typique dans les exigences fonctionnelles d’un cahier des charges.
- **Éducation et sensibilisation** : En ajoutant une composante éducative, vous répondez à un besoin secondaire mais important, qui enrichit la valeur ajoutée du projet.

### 2. **Objectifs du projet :**

- **Faciliter la reforestation** : Cet objectif fonctionnel répond directement au besoin central du projet.
- **Contribuer à la lutte contre le changement climatique** : Il s’agit d’un objectif global, cohérent avec la mission environnementale du projet.
- **Transparence et engagement** : La transparence avec les utilisateurs est un objectif essentiel qui vient renforcer la confiance.
- **Créer une communauté engagée** : Un objectif stratégique à long terme qui vise à augmenter l’engagement des utilisateurs et à favoriser la collaboration.
- **Sensibiliser le public** : Cet objectif est aligné avec le besoin de créer des ressources éducatives.
- **Éco-conception** : Cet objectif technique s’aligne parfaitement avec les attentes d’une conception durable, respectant les contraintes environnementales.

##Les fonctionnalités du projet
**Présentation du Projet de Développement**

**Besoins Fonctionnels (Minimum Viable Product - MVP)**

- Landing page avec la présentation de GreenRoots et certains arbres à planter.
- Système d'inscription et de connexion.
- Avoir la possibilité (en tant que GreenRoots) de gérer les arbres à proposer : création, édition, suppression, etc.
- Pouvoir consulter les détails d’un arbre disponible à l’achat.
- Pouvoir acheter un arbre (avec un faux tunnel d’achat pour le MVP).
- Pouvoir suivre ses commandes passées en tant qu’utilisateur.

**Propositions d’évolutions possibles**

- Pouvoir suivre l’évolution des arbres que l’on a achetés : lieu, croissance, photos potentielles, etc.
- Back-office pour l'administration, la gestion des profils utilisateurs, le suivi des arbres, etc.
- Ajout de fonctionnalités avancées pour les partenaires : via un rôle spécifique, pouvoir proposer en tant qu’externe un lot d’arbres à planter, etc.
- Intégration d'une API pour le paiement sécurisé, comme [Stripe](https://stripe.com/fr).

  ## Le MVP (Minimum Viable Product)

  **Besoins Fonctionnels (Minimum Viable Product - MVP)**

**Landing Page (Page d’accueil)** :

- Présentation de GreenRoots (mission, vision, objectifs environnementaux).
- Affichage des arbres disponibles à l’achat avec un bref descriptif et une image.
- Menu de navigation avec accès aux différentes sections (connexion, arbres, etc.).
- Pied de page avec liens vers les mentions légales, la politique de confidentialité et les réseaux sociaux.

**Système d’authentification** :

- **Inscription des utilisateurs** : Formulaire pour créer un compte utilisateur avec email et mot de passe.
- **Connexion** : Interface permettant aux utilisateurs de se connecter à leur compte.
- **Réinitialisation du mot de passe** : Option pour récupérer un mot de passe oublié via email.

**Gestion des Arbres (pour l’administrateur GreenRoots)** :

- **Ajout d’arbres** : Interface permettant à GreenRoots de créer de nouveaux arbres à planter avec nom, description, prix, photos, etc.
- **Modification d’arbres** : Possibilité d’éditer les informations des arbres existants.
- **Suppression d’arbres** : Option pour retirer des arbres de la vente.

**Fiche Détail d’un Arbre** :

- Informations complètes sur l’arbre sélectionné, incluant son nom, sa description, son origine, son prix et ses bienfaits environnementaux.
- Image illustrative de l’arbre.
- Bouton "Acheter" pour entamer le processus d’achat.

**Tunnel d'Achat (faux tunnel pour le MVP)** :

- Processus d’achat en plusieurs étapes simulant la sélection et la confirmation de l’achat.
- Vérification des détails de commande (arbre sélectionné, quantité, prix total).
- Page de confirmation d'achat à la fin du processus.

**Tableau de Bord Utilisateur** :

- **Historique des commandes** : Liste des achats effectués avec détails sur chaque arbre acheté (date d’achat, type d’arbre, etc.).
- **Suivi de commande** : Option pour voir l'état de l'achat (en attente, confirmé, etc.).
  
  ## Les évolutions potentielles

  ### 1. **Suivi de l’Évolution des Arbres Achetés**

**Fonctionnalité** : Permettre aux utilisateurs de suivre l'évolution des arbres qu'ils ont achetés, en fournissant des informations sur leur emplacement, leur croissance et des photos mises à jour.

### 2. **Back-office pour l’Administration**

**Fonctionnalité** : Mise en place d'un back-office permettant à l’administrateur (GreenRoots) de gérer la plateforme de manière complète.

### 3. **Fonctionnalités Avancées pour les Partenaires**

**Fonctionnalité** : Permettre à des partenaires externes (associations de reforestation, entreprises éco-responsables) d'ajouter et de gérer des arbres à planter via un rôle spécifique.

### 4. **Intégration d’une API de Paiement Sécurisé (Stripe, PayPal, etc.)**

**Fonctionnalité** : Ajouter un système de paiement sécurisé pour les transactions, permettant aux utilisateurs de payer via carte bancaire ou portefeuille électronique.

## La liste des technologies 

### Technologies

- **Front-end** :
    - React (bibliothèque JavaScript pour UI dynamique)
    - JavaScript (logique applicative)
    - CSS (style et design responsive)
- **Back-end** :
    - Node.js (environnement d'exécution côté serveur)
    - Express.js (framework minimaliste pour API REST)
- **Base de données** :
    - MariaDB (base de données relationnelle)
    - **ORM** : Sequelize (interaction simplifiée avec la base de données)
- **Tests API** :
    - ThunderClient (test des API JSON)

### Sécurité

- **Authentification** :
    - JWT (JSON Web Token) pour authentification basée sur des tokens
    - Bcrypt (hachage sécurisé des mots de passe)
- **Validation des entrées** :
    - Validator (sécurisation des entrées utilisateur)
- **Protection** :
    - Helmet.js (sécurisation des en-têtes HTTP)
    - Rate Limiting (protection contre les attaques DDoS/force brute)
- **Déploiement** :
    - Documentation de la procédure
    - Bonus : CI/CD avec GitHub Actions ou GitLab CI
- **Responsive** : Mobile-first avec CSS, React (ou Bootstrap, TailwindCSS)
- **Accessibilité** : Respect des normes WCAG (tests via Axe DevTools)
- **RGPD** : Politique de confidentialité, mentions légales et consentement utilisateur
- **Versionning** : Git et GitHub
- **API** :
    - Consommation d'une API (interne ou externe)
- **SEO** : Optimisation des balises, URLs, performance des pages
- **Bonus** :
    - conteneurisation (Docker) pour l'environnement de développement voire pour le déploiement,
    - éco-conception (optimisation des images, minification des fichiers, etc.).

## La définition de la cible du projet

### Définition de la cible du projet GreenRoots

Le projet **GreenRoots** vise un public engagé et sensible aux questions environnementales, avec un fort intérêt pour les initiatives de reforestation et de durabilité. La plateforme d'e-commerce proposée permet aux utilisateurs d'acheter des arbres à planter dans le but de contribuer à la reforestation mondiale et à la lutte contre le changement climatique.

### **Public éco-conscient**

- **Description** : Il s'agit principalement d'individus soucieux de l'environnement, qui cherchent à avoir un impact positif sur la planète à travers des actions concrètes.
- **Caractéristiques** :
    - Priorise des actions écologiques dans ses choix de consommation.
    - Souvent actif dans des causes environnementales, notamment la reforestation, la réduction des émissions de carbone, etc.
    - Utilise des plateformes numériques pour s'informer et agir en faveur de l'environnement.

### **Entreprises responsables**

- **Description** : Les entreprises qui cherchent à améliorer leur empreinte écologique et à s'engager dans des actions écoresponsables pour renforcer leur image et contribuer à des causes globales comme la reforestation.
- **Caractéristiques** :
    - Sensibles aux problématiques de développement durable et aux pratiques responsables.
    - Cherchent des solutions pour compenser leurs émissions de CO₂, par exemple en plantant des arbres dans des projets de reforestation.
    - Intéressées par des partenariats pour inclure ces actions dans leur stratégie RSE (Responsabilité Sociétale des Entreprises).

### **Associations environnementales**

- **Description** : Les ONG et associations ayant pour mission de protéger l'environnement et de sensibiliser le public à l’importance de la reforestation et à la préservation des forêts.
- **Caractéristiques** :
    - Partenaires potentiels pour la plateforme, avec la possibilité de proposer leurs propres projets de reforestation via GreenRoots.
    - Actives dans la promotion d’actions concrètes contre la déforestation.
    - Cherchent à étendre leur impact et à toucher un plus large public à travers des projets collaboratifs.

### **Grand public sensibilisé aux enjeux environnementaux**

- **Description** : Une partie de la population générale qui, bien qu'elle ne soit pas toujours activement impliquée dans des actions environnementales, est sensibilisée à ces enjeux et souhaite participer ponctuellement à des initiatives positives.
- **Caractéristiques** :
    - Veut pouvoir contribuer facilement à des projets de reforestation.
    - Intéressée par des démarches simples et accessibles pour avoir un impact sur l’environnement, comme planter un arbre.
    - Peut être motivée par l’aspect symbolique et philanthropique de ces actions.

      ## Les navigateurs compatibles

      Le site doit être compatible avec les navigateurs Google Chrome, Mozilla Firefox, Safari et Microsoft Edge dans leurs versions actuelles ainsi que les deux versions précédentes. Une attention particulière sera portée à l'affichage et aux performances sur les plateformes mobiles.

      ## L'arborescence de l'application

      GreenRoots/
│
├── client/                    # Dossier pour le front-end de l'application (React, HTML, CSS)
│   ├── public/                 # Fichiers publics, assets accessibles à tous
│   │   ├── index.html          # Page HTML principale
│   │   ├── favicon.ico         # Icône du site
│   │   └── assets/             # Dossier des images, polices, et autres ressources
│   │       ├── images/         # Images utilisées dans l'application
│   │       └── fonts/          # Polices
│   │
│   ├── src/                    # Code source du front-end (React)
│   │   ├── components/         # Composants réutilisables
│   │   ├── pages/              # Pages principales (Landing page, profil, achat d'arbre, etc.)
│   │   ├── services/           # Services pour les appels API, gestion des données
│   │   ├── styles/             # Fichiers CSS ou SCSS pour le style
│   │   ├── App.js              # Composant principal de l'application
│   │   ├── index.js            # Point d'entrée de l'application
│   │   └── routes.js           # Gestion des routes dans l'application
│   │
│   ├── package.json            # Dépendances front-end et scripts
│   ├── .env                    # Variables d'environnement front-end
│   └── .gitignore              # Fichiers à ignorer pour Git dans le client
│
├── server/                     # Dossier pour le back-end (Node.js, Express)
│   ├── config/                 # Configuration du serveur et de la base de données
│   │   ├── db.js               # Configuration de la base de données (PostgreSQL, MongoDB, etc.)
│   │   ├── dotenv.js           # Configuration des variables d'environnement
│   │   └── auth.js             # Gestion de l'authentification et de la sécurité
│   │
│   ├── controllers/            # Gestion de la logique métier (CRUD des arbres, utilisateurs)
│   ├── models/                 # Modèles de données (Arbre, Utilisateur, Commande)
│   │   ├── Tree.js             # Modèle de l'arbre
│   │   ├── User.js             # Modèle de l'utilisateur
│   │   └── Order.js            # Modèle des commandes
│   │
│   ├── routes/                 # Routes API (arbre, utilisateur, commande)
│   │   ├── treeRoutes.js       # Routes pour les arbres
│   │   ├── userRoutes.js       # Routes pour les utilisateurs
│   │   └── orderRoutes.js      # Routes pour les commandes
│   │
│   ├── middleware/             # Middleware pour gérer les autorisations, erreurs, etc.
│   ├── server.js               # Point d'entrée du serveur Express
│   ├── package.json            # Dépendances back-end et scripts
│   ├── .env                    # Variables d'environnement back-end
│   └── .gitignore              # Fichiers à ignorer pour Git dans le serveur
│
├── database/                   # Dossier pour la base de données (migrations, seeds)
│   ├── migrations/             # Scripts de migration de la base de données
│   ├── seeds/                  # Fichiers pour peupler la base de données initialement
│   └── schema.sql              # Schéma SQL de la base de données
│
├── tests/                      # Tests pour l'application (unitaires, intégration, end-to-end)
│   ├── client/                 # Tests front-end (Jest, React Testing Library)
│   ├── server/                 # Tests back-end (Jest, Supertest)
│   └── e2e/                    # Tests end-to-end (Cypress, Selenium)
│
├── docs/                       # Documentation du projet (API, déploiement, etc.)
│   ├── api/                    # Documentation API (Postman, Swagger)
│   └── README.md               # Documentation principale du projet
│
├── docker-compose.yml           # Configuration de Docker Compose pour orchestrer les services
├── Dockerfile                   # Fichier Docker pour créer l'image du projet
├── README.md                    # Fichier README avec présentation du projet et instructions
└── .gitignore                   # Fichiers à ignorer pour Git à la racine du projet


