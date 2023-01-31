# 0x00-ES6_basic

![](../readme_assets/is_this_this.png)

JavaScript ES6 (also known as ECMAScript 2015 or ECMAScript 6) is the newer version of JavaScript that was introduced in 2015.
  
[EMCAScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources) is the standard that JavaScript programming language uses. ECMAScript provides the specification on how JavaScript programming language should work.  
  
A list of all of the changes from the ES6 update can be found [here](https://www.javascripttutorial.net/es6/), but for this project we will only focus on the following learning objectives.

---

## Learning Objectives

* What ES6 is
* New features introduced in ES6
* The difference between a constant and a variable
* Block-scoped variables
* Arrow functions and function parameters default to them
* Rest and spread function parameters
* String templating in ES6
* Object creation and their properties in ES6
* Iterators and for-of loops

---

## Resources

* [ECMAScript 6 - ECMAScript 2015](https://www.w3schools.com/js/js_es6.asp "ECMAScript 6 - ECMAScript 2015")
* [Statements and declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements "Statements and declarations")
* [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions "Arrow functions")
* [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters "Default parameters")
* [Rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters "Rest parameter")
* [Javascript ES6 — Iterables and Iterators](https://towardsdatascience.com/javascript-es6-iterables-and-iterators-de18b54f4d4 "Javascript ES6 — Iterables and Iterators")

---

## Setup

### Install NodeJS 12.11.x
(In your home directory)

```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

```
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```

### Install Jest, Babel, and ESLint
(In your project directory)

* Install Jest using: npm install --save-dev jest
* Install Babel using: npm install --save-dev babel-jest @babel/core @babel/preset-env
* Install ESLint using: npm install --save-dev eslint
