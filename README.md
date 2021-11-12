# solvewithdev-angular12-app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.0.

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

## Creating Angular Project

Install Angular   		: npm install -g @angular/cli
Create Angular Project 	: ng new solvewithdev-ui-app
Install Bootstrap 		: npm install --save @ng-bootstrap/ng-bootstrap
Devtools Install 		: npm install --save-dev @angular-devkit/build-angular


## References :
https://stackoverflow.com/questions/55459663/return-json-from-angular-service-to-component
https://gist.github.com/mindplace/b4b094157d7a3be6afd2c96370d39fad



## ######################################################################################
## Project Properties

## Network Drive
Network Drive Name = X:
Network Drive Path = \\DPAIO-DELL\Songs

NETWORK_DRIVE_BASE_CMD = "cmd.exe /c net use"
MAP_CORNELLAD_NETWORK_DRIVE = "cmd.exe /c net use X: \\\\DPAIO-DELL\\Songs /persisten:yes";
MAP_NON_CORNELLAD_NETWORK_DRIVE = "cmd.exe /c net use X: \\\\DPAIO-DELL\\Songs password /user:domain\\username /persisten:yes";
DELETE_NETWORK_DRIVE = "cmd.exe /c net use X: /delete";

## Windows Language List
INSTALLED_LANGUAGE_LIST_PS = "powershell.exe Get-WinUserLanguageList"

## Windows TimeZone
CHANGE_TIMEZONE_CMD = "cmd.exe /c tzutil /s \"%s\"";
CHANGE_TIMEZONE_CMD1 = "cmd.exe /c tzutil /s \"" India Standard Time "\"";
TIMEZONE_LIST_ALL_CMD = "cmd.exe /c tzutil /l ";
