# HelloWorld

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.12.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


# Notes

### app folder

- app has module ad component

### assets

- Store static assets

### other files

- main.ts 
    Starting point of the app
- polyfills.ts 
    Scripts for running angular. Angular framework uses features of JS that are not available in the current version of JS supported by most browsers. Polyfills fills the gap of the features of JS and angular needs and the features supported byt the current browser.
- .editorconfig
    for team to follow code styling
- karma.conf.js
    test runner for Js code
- protractor (package.json)
    tool for running e2e test 
- tsconfing.json
    - typescript compiler that converts to js for browsers to render