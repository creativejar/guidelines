---
layout: content
pre-heading: Improving our quality of code through
heading: Guidelines
menu-label: Home
permalink: /
weight: 0
---

## Introduction

Guidelines define best practice. They are not necessarily mandatory, but should be followed unless there are very good reasons not to. These guidelines are designed to help developers working on projects of varying complexity and size produce CSS that employs a consistent style and is:

* predictable
* reusable
* maintainable
* scalable

Recommended reading:

* Nicole Sullivan, [OOCSS](https://github.com/stubbornella/oocss/wiki)
* Jonathan Snook, [SMACSS](http://smacss.com/)
* Harry Roberts, [CSS Guidelines](http://cssguidelin.es/) 

### Predictable
Predictable CSS means your rules behave as you’d expect. When you add or update a rule, it shouldn’t affect parts of your site that you didn’t intend. On small sites that rarely change, this isn’t as important, but on large sites with tens or hundreds of pages, predictable CSS is a must.

### Reusable
CSS rules should be abstract and decoupled enough that you can build new components quickly from existing parts without having to recode patterns and problems you’ve already solved.

### Maintainable
When new components and features need to be added, updated or rearranged on your site, doing so shouldn’t require refactoring existing CSS. Adding component X to the page shouldn’t break component Y by its mere presence.

### Scalable
As your site grows in size and complexity it usually requires more developers to maintain. Scalable CSS means it can be easily managed by a single person or a large engineering team. It also means your site’s CSS architecture is easily approachable without requiring an enormous learning curve. Just because you’re the only developer touching the CSS today doesn’t mean that will always be the case.

## Boilerplate
A boilerplate project has been created which follows the guidelines outlined in this documentation. It is advised that each project is started with taking a copy of this project and will ensure that these guidelines and standards are adhered to.

The boilerplate can be found and maintained on [Github](https://github.com/creativejar/boilerplate).

## QA
To ensure that projects are developed to meet these standards, regular checks of the code will be carried out my senior members of the team. 

To automate this process in parts, [SCSS Linting](https://github.com/brigade/scss-lint) is included in our standard boilerplate through Gulp to highlight areas where your code can be improved.

Our rules are defined with the [.scss-lint.yml](https://github.com/creativejar/boilerplate/blob/master/.scss-lint.yml) file in our boilerplate. For explanation of these rules, please see the [Linters documentation](https://github.com/brigade/scss-lint/blob/master/lib/scss_lint/linter/README.md).

Please ensure that your code passes these tests.

## Table of contents
* [Project Structure](/guidelines/project-structure/)
	* [Introduction](/guidelines/project-structure/#structure)
	* [CSS & Sass](/guidelines/project-structure/#css-sass)
	* [Images](/guidelines/project-structure/#images)
	* [JavaScript](/guidelines/project-structure/#javascript)
	* [Styleguide](/guidelines/project-structure/#styleguide)
* [HTML](/guidelines/html/)
	* [Syntax](/guidelines/html/#syntax)
	* [Whitespace](/guidelines/html/#whitespace)
	* [HTML5 Doctype](/guidelines/html#html5-doctype)
	* [Language attribute](/guidelines/html/#language-attribute)
	* [Character encoding](/guidelines/html/#character-encoding)
	* [IE Compatibility mode](/guidelines/html/#ie-compatibility-mode)
	* [CSS & JavaScript includes](/guidelines/html/#css-javascript-includes)
	* [Boolean attributes](/guidelines/html/#boolean-attributes)
	* [Semantics](/guidelines/html/#semantics)
	* [Reducing markup](/guidelines/html/#reducing-markup)
	* [JavaScript generated markup](/guidelines/html/#javascript-generated-markup)
	* [General guidelines](/guidelines/html/#general)
* [CSS](/guidelines/css/)
	* [Structure](/guidelines/css/#structure)
	* [Documentation](/guidelines/css/#documentation)
	* [Reset](/guidelines/css/#reset)
	* [Syntax](/guidelines/css/#syntax)
	* [Nesting & Specificity](/guidelines/css/#nesting-and-specificity)
	* [Naming Conventions](/guidelines/css/#naming-conventions)
	* [Variables](/guidelines/css/#variables)
	* [Colours](/guidelines/css/#colours)
	* [Units](/guidelines/css/#units)
	* [Grids](/guidelines/css/#grids)
	* [Media Queries](/guidelines/css/#media-queries)
	* [Icons](/guidelines/css/#icons)
* [Testing](/guidelines/testing/)
	* [Introduction](/guidelines/testing/#introduction)
	* [Testing](/guidelines/testing/#testing-and-checklist)
	* [Desktop Browser Support](/guidelines/testing/#desktop-browser-support)
	* [Mobile/Tablet Device Support](/guidelines/testing/#mobile-tablet-device-support)