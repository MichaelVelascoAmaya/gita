# Gita - Gestor Inventario Tienda Autónoma / Autonomous Store Inventory Manager

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.3.

## Start

To start proyect you can run:

* npm run start
* npm run start:staging
* npm run start:production

## Build

To build project you can run: 

* npm run build
* npm run build:staging
* npm run build:production

those commands make a corresponding folder into ./dist directory

## Deployment

This project is deployed in a [FireBase](https://firebase.google.com/ "FireBase") project

### Configurations

* Change firebase variable values into *./src/environments/environment.*.ts* to set the values of your own FireBase project
* Change "projects.default" section into ./.firebaserc file, by the name of your own FireBase project
* Change "targets" section into ./.firebaserc to match the hosting targets in the ./firebase.sjon file (also change the hosting tags in the file firebase.json)

### FireBase Project Requeriments

* One FireBase project with two [web apps](https://firebase.google.com/learn/pathways/firebase-web) an Production and Staging.
* Hosting configuration in both [web apps](https://firebase.google.com/learn/pathways/firebase-web)
* Authentication configuration with the providers: email/password, google
* Firestore Database configuration

### Deploy Commands

To deploy the proyect you can run: 

* npm run deploy:staging (Note that this environment also uses the production database) (only to validate changes with the final user)
* npm run deploy:production

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
