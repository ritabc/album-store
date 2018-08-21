# AlbumStore

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## Notes on Recreation
A Firebase account will be needed. Log in or create one at (firebase.google.com)
Create a new project and from the Overview Dashboard, CLick to add Firebase to your web app.
Run the following:
- $ npm install angularfire2@4.0.0-rc.0 firebase@^3.6.6 --save
- Add to tsconfig.json after the "lib" array, add: '"types": [ "firebase" ]'
Add a new file: src/app/api-keys.ts to your project and to .gitignore
From the modal on the Firebase website, fill in the 'xxx's below with your credentials
![image](https://user-images.githubusercontent.com/11031915/44380946-ee189800-a4c2-11e8-85c2-1d41ad108f11.png)


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
