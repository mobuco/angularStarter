# AngularStarter
Basic Angular Project with SCSS, Bootstrap

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.3.



Steps to rebuild:

1. Create Project
`ng new angularStarter`

2. Add Bootstrap 5
`npm install bootstrap@next popper.js --S`

3. Update angular.json in the `build` and `test` sections
```
"styles": [
   "src/styles.scss",
   "node_modules/bootstrap/scss/bootstrap.scss",
 ],
 "scripts": [
   "./node_modules/popper.js/dist/umd/popper.min.js",
   "./node_modules/bootstrap/dist/js/bootstrap.min.js"
 ]
```



## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
