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

These architectural concepts are explained very well on the Appfolio Engineering blog:

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

## Table of contents
* [Project Structure](/project-structure/)
	* [Introduction](/project-structure/#structure)
	* [CSS & Sass](/project-structure/#css-sass)
	* [Images](/project-structure/#images)
	* [JavaScript](/project-structure/#javascript)
	* [Styleguide](/project-structure/#styleguide)
* [HTML](/html/)
	* [Syntax](/html/#syntax)
	* [Whitespace](/html/#whitespace)
	* [HTML5 Doctype](/html#html5-doctype)
	* [Language attribute](/html/#language-attribute)
	* [Character encoding](/html/#character-encoding)
	* [IE Compatibility mode](/html/#ie-compatibility-mode)
	* [CSS & JavaScript includes](/html/#css-javascript-includes)
	* [Attribute order](/html/#attribute-order)
	* [Naming components](/html/#naming-components)
	* [Boolean attributes](/html/#boolean-attributes)
	* [Semantics](/html/#semantics)
	* [Reducing markup](/html/#reducing-markup)
	* [JavaScript generated markup](/html/#javascript-generated-markup)
	* [General guidelines](/html/#general)
* [CSS](/css/)
	* [Structure](/css/#structure)
	* [Documentation](/css/#documentation)
	* [Reset](/css/#reset)
	* [Syntax](/css/#syntax)
	* [Nesting & Specificity](/css/#nesting-and-specificity)
	* [Naming Conventions](/css/#naming-conventions)
	* [Variables](/css/#variables)
	* [Colours](/css/#colours)
	* [Units](/css/#units)
	* [Grids](/css/#grids)
	* [Media Queries](/css/#media-queries)
	* [Icons](/css/#icons)
* [Testing](/testing/)
	* [Introduction](/testing/#introduction)
	* [Testing](/testing/#testing-and-checklist)
	* [Desktop Browser Support](/testing/#desktop-browser-support)
	* [Mobile/Tablet Device Support](/testing/#mobile-tablet-device-support)