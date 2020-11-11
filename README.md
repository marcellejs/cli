# Marcelle CLI

[![npm version](https://img.shields.io/npm/v/@marcellejs/cli)](https://www.npmjs.com/package/@marcellejs/cli)
![Status](https://img.shields.io/badge/status-active-success.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

A command line interface for Marcelle applications

## Installation

```bash
npm install -g @marcellejs/cli
```

## Usage

```
$ mkdir myproject

$ cd myproject

$ marcelle help

  Usage: marcelle generate [type]


  Options:

    -V, --version  output the version number
    -h, --help     output usage information


  Commands:

    generate|g [type]  Run a generator. Type can be
    	• app - Create a new Marcelle application in the current folder
    	• module - Generate a new module for an existing application
    	• backend - Add a server-side backend for your application's data

    *

$ marcelle generate app

$ npm run dev
```

## About

Marcelle CLI's generators are provided by [generator-marcelle](https://github.com/marcellejs/generator-marcelle).

## ✍️ Authors

- [@JulesFrancoise](https://github.com/JulesFrancoise/)
- [@bcaramiaux](https://github.com/bcaramiaux/)

## 🎉 Acknowledgements

- [Feathers CLI](https://github.com/feathersjs/cli)
- [Yeoman](https://yeoman.io/)
