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
**in another terminal window** -> npm run electron:serve

The code for this is managed at `main.js`. In this sample, the app runs with a simple Electron window.
By default, Developer tools is opened. You can deactivate it by uncommenting `win.webContents.openDevTools();` in `main.js`.

## To build for production

- npm run electron:dist

You can find your built files in the /dist directory.

## Included Commands
- `npm run electron:linux` - builds your application and creates an app consumable on linux systems.
- `npm run electron:windows` - On a Windows OS, builds your application and creates an app consumable in windows 32/64 bit systems.
- `npm run electron:mac` - On a MAC OS, builds your application and generates a `.app` file of your application that can be run on mac.

**Your executable is optimised. There are only the files of /dist directory in the executable generated.**