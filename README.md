ON FrontEnd

src/
│
├── assets/           # Images, icônes, styles globaux
│   ├── images/
│   └── styles/
│
├── components/       # Composants réutilisables (boutons, formulaires, cartes…)
│   ├── Button.jsx
│   ├── Navbar.jsx
│   └── ...
│
├── pages/            # Pages principales (routes)
│   ├── Home.jsx
│   ├── About.jsx
│   ├── Contact.jsx
│   └── ...
│
├── layouts/          # Layouts (structure globale : header/footer/sidebar)
│   ├── MainLayout.jsx
│   └── AuthLayout.jsx
│
├── hooks/            # Custom hooks (useAuth, useFetch…)
│   └── useAuth.js
│
├── context/          # Context API (UserContext, ThemeContext…)
│   └── UserContext.jsx
│
├── services/         # API calls, logique métier
│   └── api.js
│
├── utils/            # Fonctions utilitaires (formatage, helpers…)
│   └── formatDate.js
│
├── App.jsx           # Point d’entrée de ton app
├── index.js          # Bootstrap ReactDOM
└── routes.js         # Définition des routes (optionnel)
