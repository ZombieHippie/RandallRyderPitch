# Randall Ryder Pitch

Documents:
 * [Gameplay Mechanics](https://docs.google.com/document/d/1vlS1MlH119EY5btTJeoGPgkzjx5Ad_cfgJnp3hCTXZM/edit?usp=sharing)

## Technologies to be used

> GitHub is our collaboration tool for this project, to get up to speed on
Git and GitHub utilize this [GitHub Guides tutorials page](https://guides.github.com/).

## Client interface (HTML5 Game)

### Polymer Web Components

 * Used to separate HTML DOM components that are used in multiple places in
the game page.
 * Polymer allows us to reuse HTML5 Web components effectively in an extremely
modular way.
 * Suggested by Nick Jaross of O'Reilly, who described it as the successor of
AngularJS.

**Polymer Resources**

 * [Polymer/polymer project](https://github.com/Polymer/polymer)
   * Read Polymer in 1 minute!
 * [Curated list of apps using Polymer](http://builtwithpolymer.org/)
 * [Web components information](http://webcomponents.org/)


### ES6 / BabelScript

 * Used for the browser-side logic of communicating with the server and
displaying data through DOM manipulation.
 * EcmaScript 6; version of JavaScript supporting classes and inheritence.
 * Vanilla JavaScript is very complicated to declare classes (prototyping
methods).
 * Will be used to back Web Components scripting.
 * Compiled before serving by [Webpack](https://webpack.github.io/docs/).

**ES6 / BabelScript Resources**

 * [Module syntax, how modules work (!important)](http://www.2ality.com/2014/09/es6-modules-final.html)
 * [Overview of EcmaScript2015](https://babeljs.io/docs/learn-es2015/)
(Recommend reviewing JavaScript tutorials before this)

## Server Interface

### Node.js

Node.js will serve all the HTML, CSS, and JavaScript files and handle storing
session data using Apache Cassandra.

Please learn some basics of Node.js, you may try [NodeSchool tutorials](http://nodeschool.io/#workshoppers).


*As always, if you want to learn more try Googling it and looking at a tutorial
before looking at the documentation*
