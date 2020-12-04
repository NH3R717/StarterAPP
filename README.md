# Web Application Template

## General info

Personal project starter template for a React (or Vue) web framework application connected to an ExpressJS server/database API.

## Technology

### Core Tech

- web framework – React
- server – NodeJS
- server framework – Express
- database – Postgre
- ORM – Sequelize
- CI – Circle CI

### Test

- test runner – Jest

### Code Style & Linting

- linter – ESLint
- style guide – airbnb

### API

Services hosted on this api are:

- data access and processing
- access authorization

## Installation

Install the most recent software packages from npm for this app by running the following commands

1.

```
$ cd StarterAPP
$ npm init -y && npm i concurrently && npm i nodemon
$ npm i --save-dev eslint && nmp i --save-dev eslint-config-airbnb-base

```

1.

```
$ cd api
$ npm init -y && npm i express && npm i axios && npm i uuid
$ npm i --save-dev dredd
```

2.

```
$ cd ../web
$ npm init -y && npm i react
$ nmp i --save-dev
```
