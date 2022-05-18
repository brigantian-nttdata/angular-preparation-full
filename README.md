# AngularPreparationFull

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## What you have to do
Don't use a component library, you must create every component you need (also simple components like buttons).

Application:
- Create a basic application that uses this rest api https://gorest.co.in/
  - List and open the detail of users, posts and comments
  - Create dedicated routes for show a single user/post
- Integrate this graphql api: https://studio.apollographql.com/public/SpaceX-pxxbxen/home?variant=current 
- Create unit tests (100% coverage)
- Use NGRX for the state management (optional)
- For each component created, create also a storybook story (optional)
