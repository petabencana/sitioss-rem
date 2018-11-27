# cognicity-rem-v3
Cognicity REM Web Client v3
[![Build Status](https://travis-ci.org/urbanriskmap/cognicity-rem.svg?branch=master)](https://travis-ci.org/urbanriskmap/cognicity-rem)


### Machine setup:
* Install Aurelia CLI
  * `npm install aurelia-cli -g`

### Application setup
* Install the project dependencies
  * `npm install`

### Auth0
* Configure callback, logout, CORS
* Add a rule with content from [auth0-rule.js](auth0-rule.js)

### To Build
* To generate a production build
    * Run `ENV=prod npm run build`
