NOTAS:
@component = a un decorador,
selector indica que el app es personalidado.

MODULOS....
Se recomienda crear modulos para no hacer tan extenso el archivo de app module, ejemplo un modulo de heroes y dentro de ahí crear todo lo relacionado a heroes.ejemplo: heroes.module.ts. (una vez en el archivo creado se importa ngModule y exporta la clase HeroesModule)
lugo se agregan declarations = los componentes que se tienen de heroe.

export = las cosas que quiero hacer visibles dentro de mi modulo.

Co mmonModule = sirve para usar ngFOR y ngIf




# Bases

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

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
