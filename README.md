# Responsive React multistep form component
## React 15.4.2 - Babel 6.23.0 - Browserify 14.1.0 
### [Working demo](http://srdjan.github.io/react-multistep/)

##### (Webpack version is here: https://github.com/Srdjan/react-multistep-with-webpack)

[![NPM](https://nodei.co/npm/react-multistep.png?downloads=true&stars=true)](https://nodei.co/rnpm/react-multistep/)

<img src="https://raw.githubusercontent.com/srdjan/react-multistep/master/assets/react-multistep.png"/>

[List of forks] 
(https://github.com/srdjan/react-multistep/network/members)

## Instructions

To install this module run:
```sh
npm install react-multistep
```
next, require it inside of your app:
```sh
var Multistep = require('react-multistep').Multistep
```
### Configuration:
```
showNavigation 
type: boolean (default = true)
```
```
steps 
type: array of objects pointing to React components
```
### Example:
```javascript
const steps = [
              {name: 'StepOne', component: <StepOne/>},
              {name: 'StepTwo', component: <StepTwo/>},
              {name: 'StepThree', component: <StepThree/>},
              {name: 'StepFour', component: <StepFour/>}
            ];
<Multistep showNavigation={true} steps={steps}/>
```

To build included example:
```sh
npm run build
```
Now open ./example/index.html in your favorite browser


## Dev instructions

First clone the repository and then run:
```sh
npm install
```

To test run:
```sh
npm test
```
