[![Angular Logo](./logo-angular.jpg)](https://angular.io/) [![Electron Logo](./logo-electron.jpg)](https://electronjs.org/)

# Introduction

Bootstrap your project with Angular 7 and Electron (Typescript + CSS)

Currently runs with:
- Angular v7.2.14
- Angular CLI v7.3.8
- Electron v4.0.0

## Getting Started

Clone this repository locally:

``` bash
git clone https://github.com/kamit15/electron-angular.git
```

Install dependencies with npm dependency manager :

``` bash
npm install
```


## To build for development

**in a terminal window** -> npm start
**in another terminal window** -> npm run electron

The code for this is managed at `main.js`. In this sample, the app runs with a simple Electron window.
By default, Developer tools is opened. You can deactivate it by uncommenting `win.webContents.openDevTools();` in `main.js`.

## To build for production

npm run build
npm run electron dist