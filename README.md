# Testing Boilerplate

- [Testing Boilerplate](#testing-boilerplate)
  - [Introduction](#introduction)
    - [Dependencies](#dependencies)
  - [How to install](#how-to-install)
  - [How to build](#how-to-build)
  - [How to test](#how-to-test)

## Introduction

This is a basic boilerplate for web projects using TypeScript. The project is bundled using Webpack. Webpack has been set up to include all the configuration which I would normally use when starting a fresh web project including:

- SCSS
- TypeScript
- PostCSS
- HTML Loader
- File Loader (Copies files from assets into the distribution folder)

Testing is built in to the boilerplate using Karma and Jasmine.

I have built this so that I have an easy to use starting point for my projects.

### Technologies

This boilerplate uses the following technologies:

- Typescript
- Webpack
- SCSS
- PostCSS
- Karma
- Jasmine
- ts-node

## How to install

To install this boilerplate, simply clone this repository `git clone`, navigate to the directory and run `npm install`.

## How to build

Use `npm run build:dev` to build the project. Files will be outputted to `/dist`. Running `npm run build:prod` will build the project for a production environment. `npm run watch` can be used to rebuild the project on save.

## How to test

Testing is set up to use Chrome. To create tests, name your files like `*.spec.ts`. To run the tests, use `npm test`.
