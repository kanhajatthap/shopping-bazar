# Shopping Bazar / Created by Kanha jatthap

This is a test project to demonstrate using Intern with Angular 14.2.9. It contains all of the specs from Angular's test guide as well as some extras. Specs have been reformatted and converted to using Intern best practices as outlined below.

## Get started

## Clone the repo

git clone https://github.com/kanhajatthap/shopping-bazar.git
cd shopping-bazar


## Install npm packages

Install the npm packages described in the package.json and verify that it works:

npm install
npm start
The npm start command builds (compiles TypeScript and copies assets) the application into dist/, watches for changes to the source files, and runs lite-server on port 3000.

Shut it down manually with Ctrl-C.

## NPM Scripts

These are the most useful commands defined in package.json:

npm start - runs the TypeScript compiler, asset copier, and a server at the same time, all three in "watch mode".
npm run build - runs the TypeScript compiler and asset copier once.
npm run build:watch - runs the TypeScript compiler and asset copier in "watch mode"; when changes occur to source files, they will be recompiled or copied into dist/.
npm run lint - runs tslint on the project files.
npm run serve - runs lite-server.
These are the test-related scripts:
npm test - builds the application and runs Intern tests (both unit and functional) one time.
npm run ci - cleans, lints, and builds the application and runs Intern tests (both unit and functional) one time.

## Localhost URL

Run `ng serve` for a dev server. Navigate to `<a href="http://localhost:4200/" target="_blank">http://localhost:4200/</a>`. The application will automatically reload if you change any of the source files.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
