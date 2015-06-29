## A template project for TDD workshop in JavaScript

This template project uses [Jasmine](http://jasmine.github.io/) and [Karma](http://karma-runner.github.io/)

## Getting started with Jasmine tests
- Clone the repository
- Run `git checkout base-jasmine`

## Getting started with Karma
- Install `Node.js`. This is required because we want to use `npm` to install `karma` packages. Please refer to [this link](https://docs.npmjs.com/getting-started/installing-node) for help
- Clone the repository
- Run `git checkout base-karma`
- Run `npm install karma karma-jasmine karma-chrome-launcher karma-firefox-launcher --save-dev`
- Run `npm install -g karma-cli`
- Run `karma start`

## Stories
Following are the stories we can use for the workshop

- As a driver, I want to park my car, So that I can catch my flight
- As a driver, I want to find my car, So that I can go home
- As a driver, I want to unpark my car, So that I can go home
- As a parking lot owner, I want to know when the lot is full, So that I can put out the full sign
- As a parking lot owner, I want to know when the parking lot has space again, So that I can take in the full sign
- As a parking lot owner, I want a parking attendant to park cars, So that I can make decisions on where to park the cars
