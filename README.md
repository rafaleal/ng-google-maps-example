# ng-google-maps-example

Working example of Angular 7 + Google Maps v3.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.4.

## Features

This example contains:
- Autocomplete search box
- Directions displayed in map
- Calculate distance of the route
- Set markers alphabetically

## Install dependencies

Run `npm i` on console to create `node_modules` directory.

## How to start
**Note** that this seed project requires  **node >=v6.9.0 and npm >=3**.

In order to start the project use:
```bash
$ git clone https://github.com/rafaleal/ng-google-maps-example
$ cd ng-google-maps-example
# install the project's dependencies
$ npm i
```
Replace `'YOUR API KY HERE'` at `src/app/config.ts` by your personal Google Maps API key.

> Guide to get a Google Maps API key [here](https://developers.google.com/maps/documentation/javascript/get-api-key)

After replacing the API key use:

```bash
# watches your files and uses livereload by default run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
$ npm start
# prod build, will output the production application in `dist`
# the produced code can be deployed (rsynced) to a remote server
$ npm run build
```
