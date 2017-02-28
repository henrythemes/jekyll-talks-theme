---
###  adapted version from jade
###    see https://github.com/markdalgleish/presentation-a-bespoke-ecosystem/blob/master/src/index.jade for source
###

title:     A Bespoke Ecosystem
author:    Mark Dalgleish
date:      July 31, 2014
layout:    bespoke
---


# A Bespoke Ecosystem

## On front-end modularity



# Why Bespoke?


# Bespoke.js is a blank canvas


# Most frameworks are<br />busy **adding** features


# Bespoke features over time:

- Manages deck state
- Handles keyboard input
- Handles touch input
- Adds CSS classes
- Allows plugins


# Plugin first design


``` js
bespoke.from('#presentation', [
              classes(),
              keys(),
              touch(),
              bullets('li, .bullet'),
              etc&hellip;
            ]);
```


# Every plugin is a separate module

``` js
            var bespoke = require('bespoke'),
                classes = require('bespoke-classes'),
                keys = require('bespoke-keys'),
                touch = require('bespoke-touch'),
                bullets = require('bespoke-bullets');
```


# Plugins are just functions

``` js
            module.exports = function(options) {
              return function(deck) {
                deck.next();
                deck.prev();
                // etc&hellip;
              };
            };
```


# The API is inherently modular

- Using it teaches you how it works
- No black box, small approachable modules
- Users are encouraged to view source


# Authoring experience?


# Perfect for fighting<br />"fear of the imperfect solution"


# Plugins provide a safe space for your crazy experiments


# Managing versions is simplified


# Great for maintenance mode

- Bugs are minimised
- Mistaken bug reports are also minimised
- Bug reports tend to go to the right place
- You get to keep your sanity


# To be continued
