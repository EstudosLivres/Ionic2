# ionic2 study
Studying ionic2, angular2 & typescript


## Set it up

It is a ionic project, which means a node project, so start installing dependencies by npm install & restore plugins 

1. Install NPM dependencies
```shell
    $ npm install
```

2. Install ionic cordova dependencies
```shell
    $ ionic state restore
```


## Executing

Start it just like a server to run in browser
```shell
  $ ionic serve
```


## PUG

PUG is a HTML pre-compiler, which means that it have a specific semantic to generate the final HTML files.
[Check it Documentation](https://pugjs.org)

## ionic tutorial

#### files & structure

* __app.module.ts__: def the app settings (config)
* __app.component.ts__: basic the same as ng-app/app.js in ionic1 (bootstrap/launch)
* __app.html__: main/initial content loader. the __ion-nav__ root set the initial page

