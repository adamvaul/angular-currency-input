angular-currency-input
======================

An Angular html input directive.  You edit the value as a number, see it as a currency, just like excel.
```html
    <input angular-currency-input type="text" ng-model="MyValue"></input>
```
angularCurrencyInput is an [Angular.js](http://angularjs.org/) input directive that creates an input like an excel spreadsheet cell that is formatted like a currency.  You see the number as a currency, but when editing it reverts to a simple number

## To use

Include the angular-currency-input.js in your project 
Add a script reference in your index.html page like so
```html
    <script src="js/angular-currency-input.js"></script>
```
Add the 'angular-currency-input' module to your application dependencies like so.
```javascript
    var app = angular.module("myApp", ["angularCurrencyInput"])
```
Use it in your html pages.
```html
    <input angular-currency-input type="text" ng-model="MyValue"></input>
```


