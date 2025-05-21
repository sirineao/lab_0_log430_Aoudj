# lab_0_log430_Aoudj - Hello Worl App

Cette repo contient un projet simple qui affiche "Hello, World!" dans la console. 
Pour ce laboratoire j'ai choisi de faire une application simple avec Node.js.
J'ai choisien JavaScript comme langues puisque c'est laquelle avec je suis la plus a l'aise.
Et donc puisque j'ai pris JS, j'ai utilise Jest pour les tests unitaires.

## Architecture de l'application

├── app.js              # Contient la fonction qui print le message et un appel de la fonction est dans le fichier.
├── app.test.js         # Tests unitaires du fichier app
├── package.json        # Dépendances et scripts npm
├── Dockerfile          # Construction de l'image Docker
├── .dockerignore       # Fichiers a ne pas inclure dans le build
├── .eslintrc / eslint.config.js # Configuration pour ESLint
└── .github/workflows/ci.yml    # Pipeline CI/CD GitHub Actions

## Instruction pour lancer le projet

1. Cloner le projet avec le lien https du repo: `git clone https://github.com/sirineao/lab_0_log430_Aoudj`
2. `cd lab_0_log430_Aoudj`
3. Pour construire et lancer le container: `docker compose up ---build`
4. On devrait voir "Hello, World!" dans la console.
