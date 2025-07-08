# 🍽️ SkyRecettes-Front

Frontend de l'application **SkyRecettes** — un carnet de recettes personnel développé avec Angular.

Ce projet a pour objectif de permettre à un utilisateur de :
- Ajouter, modifier et supprimer ses recettes
- Consulter les recettes via une interface claire
- Organiser ses plats par catégories (dessert, entrée, plat, etc.)
- Gérer les ingrédients et étapes de préparation

---

## 🛠️ Stack technique

- ⚙️ **Angular** v18+
- 🎨 **SCSS** pour le style
- 🚀 Architecture modulaire (pages, services, composants)
- 🔗 Connecté à une API Java + Spring Boot (voir [SkyRecettes-Back](https://github.com/<ton-user>/SkyRecettes-Back))

---

## ▶️ Lancer le projet en local

### 1. Prérequis

- Node.js `18+`
- Angular CLI :
```bash
npm install -g @angular/cli

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
