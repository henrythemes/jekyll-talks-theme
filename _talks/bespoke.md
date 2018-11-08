---
###  adapted version from jade
###    see https://github.com/markdalgleish/presentation-a-bespoke-ecosystem/blob/master/src/index.jade for source
###

title:     SDG Ecosystem
subtitle:  Sustainable Development Goals _and your opensourcecode_
author:    Roy Leon
date:      November 9, 2018
layout:    bespoke
---


## UP20 <br /> "Your social program marketplace"

## UP20 boldly facing the uncanny-rift <br /> ...of the Digital-Divide 
 - (remember it's finite)

## By promiting open-source best-practices in the social realms
- (remember it's infinite)

## JOIN us as contirbutors and start-up this _funky_ community

## CSR | Corporate Social Responsibility
 ![So you're telling me...](http://www.quickmeme.com/img/03/03bdfeb0940d49b4e2321e5f63df38cb376e59289cb1a25fffa38ee303a4c2cc.jpg)
 
## Greenwashing
  ![Greenwash](http://www.theglobalbeauty.com/wp-content/uploads/2016/10/image221-washed.jpeg)

## What the SDG is all about?
[UNDP | Sustainable Development Goals](http://www.undp.org/content/undp/en/home/sustainable-development-goals.html)
 - 193 countries signed 
 - Specific 17 *Goals*, each w/ *Targets* and ~340 *Indicators*
 - Each goal has set of specific parameters (aka. KPI)
 - 2-step _'Deadlines:'_ 2020, 2030


## They're Setting the course for the next decade
 - Adopting SDG means: *Duty of SDG Reporting (country)*
 - Corporates and Countries have to work together
 - Parameters are presets of specific best-practices


## SDG features over time:

- Manages state
- Handles country input
- Country handles NGO input
- Adds KPI to exising programs
- Acquire and run programs


## Plugin first design

``` pseudo-code
social.from('#mySocialProgram', [
  country()
  goals(),
  keys(),
  actors(),
  outlets('NGO, GOV, COM, CS-JV'),
  media('THIS IS IMPORTANT!'),
  instance('Penguin-August-2018')
  etc...
]);
```


## Every instance is a separate module

``` js
var index  = require('SDG-index'),
    classes  = require('SDG-classes'),
    keys     = require('SDG-keys'),
    oss      = require('SDG-repositories'),
    outlets  = require('SDG-bullets'),
    etc...
```


## Social Programs _have_ functions

``` pseudo-code
social.module.exports = function(options) {
  return function(deck) {
    deck.next();
    deck.prev();
    // etc...
  };
};
```


## An API to track KPI's
![SDG Index](https://dashboards.sdgindex.org/#/)
- Using it teaches you how it works
- Driven by Open-data. Powered by research institute
- Actors are encouraged to create source-code and APIs
* [Bonus: F18 Authoring API](https://18f.gsa.gov/)

## Authoring experience?
UP20 Aims at *Bridging the Digital Divide*
we encourage...
   - Definitions, Policy, Content
   - Professional community for social innovation
   - open-source SHARING content via repositories
=> Marketplace for Social Innovation (!)


## Perfect for collaborating<br />"no perfect solution"


## Repos provide a safe space for your crazy experiments
*Best-Practices:* 
 - development process
 - open-data ^ open-source
 - versions
 - collaborators

## Managing reports and collaborations simplified across the globe


## Great for maintenance mode

- Communication-Bugs are minimised
- Mistaken reports are minimised
- Your NGO reports tend to go to the right place
- You get to keep your sanity


## To be continued...

