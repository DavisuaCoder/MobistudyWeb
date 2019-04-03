# Mobistudy Web

This repository contains the frontend of the Mobistudy web server.
The frontend is developed as a single-page app using the [quasar framework](https://quasar-framework.org/).

## Pre requisites

You need to install the following on your system:

- nodejs
- the [quasar command line tool](https://quasar-framework.org/guide/quasar-cli.html)

Install all other dependencies with `npm install`.

## Run it

To start the interface, run `quasar dev`.
You will need the MobistudyAPI running in parallel (see MobistudyAPI docs).

## Develop it

The code is written mostly in ES6 and uses ES6 modules, please be consistent.


## Deploy it

Run `quasar build`. This will generate the material UI interfaces and make it available under `./dist/`
