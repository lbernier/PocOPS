<<<<<<< HEAD
# PocOPS
=======
Links importants :
Cuenta Heroku + cuenta Git ( no olvidar renombrar branche main to master)
crear proyecto angular
Asociar el folder del proyecto angular a Git : 
            https://www.entechlog.com/blog/general/how-to-add-existing-folder-to-git/
Crear el pipeline en Heroku asociado a Git ( al hacer push en git , se actualiza Heroku )

git push => $ git push -f origin master

Para hacer hablar git con heroku , esta guia puede ser importante :
             https://stanislas.blog/2020/04/deploy-angular-app-heroku/

Y se debe definir la siguiente variable dentro de Heroku:
            NPM_CONFIG_PRODUCTION = false
    Esto en caso que haya problemas entre las dependencies et devdependencies en el archivo package.json


# PocOPS
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.3.

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
>>>>>>> 2680495 (initial commit)
