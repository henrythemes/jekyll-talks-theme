# Jekyll Talks Theme

A jekyll theme for talks. Layouts include:

- [S6 slideshow templates / machinery / kit](http://slidekit.github.io) w/ blank 'n' blank5 styles
- [Bespoke.js](https://github.com/bespokejs) w/ cube styles


## How-to Add Your Own talks

Step 1: Fork this repo

Step 2: Add your talks to the `_talks/` folder

Replace all sample text files in the `_talks/` folder with your own.

That's it :-)


## Live Demo

See a live demo @ [`henrythemes.github.io/jekyll-talks-theme` »](http://henrythemes.github.io/jekyll-talks-theme)

Sample talks include:

_Using S6 / Slidekit_

- Dr Jekyll and Mr Hyde - Build Static (Web) Sites w/ Ruby - [(Slides)](https://henrythemes.github.io/jekyll-talks-theme/talks/drjekyll.html), [(Source: `drjekyll.md`)](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/drjekyll.md)
- Stay Static - Jekyll vs Middleman - Build Static (Web) Sites w/ Ruby - [(Slides)](https://henrythemes.github.io/jekyll-talks-theme/talks/jekyll_vs_middleman.html), [(Source: `jekyll_vs_middleman.md`)](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/jekyll_vs_middleman.md)

<!-- break -->

- Starter Sample (Blank Theme) - Habits - [(Slides)](https://henrythemes.github.io/jekyll-talks-theme/talks/starter.html), [(Source: `starter.md`)](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/starter.md)
- Starter Sample (Blank5 Theme) - Habits - [(Slides)](https://henrythemes.github.io/jekyll-talks-theme/talks/starter5.html), [(Source: `starter5.md`)](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/starter5.md)

<!-- break -->

_Using Bespoke.js_

- A Bespoke Ecosystem (Cube Theme) - [(Slides)](https://henrythemes.github.io/jekyll-talks-theme/talks/bespoke.html), [(Source: `bespoke.md`)](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/bespoke.md)



## Talk Themes

The [S6 slideshow templates / machinery / kit](http://slidekit.github.io)
lets you theme your talks.
Built-in themes include:


### Blank

Use heading 1 (e.g. `#`) for slide breaks or
use the `<!-- @SLIDE -->` directive for slide breaks without titles
(e.g. for slides with images only). Example:

```
---
title:     Starter Sample (Blank Theme) - Habits
author:    John Doe
date:      March 22, 2017
---

# In the morning
{:.fullscreen}


# Getting up

- Turn off alarm
- Get out of bed


# Breakfast

- Eat eggs
- Drink coffee


# In the evening
{:.fullscreen}


# Dinner

- Eat spaghetti
- Drink wine
- Browse slide show


<!-- @SLIDE -->

![](../i/slideshow.png)


# Going to sleep

- Get in bed
- Count sheep
```

(Source: [`_talks/starter.md`](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/starter.md))


To change the colors, typography, etc.
see the styles in `css/blank.scss`.


### Blank5

Use heading 1 (e.g. `#`) for the title (note: gets auto-added :-) from the front matter),
use heading 2 for section breaks and
use heading 3 for slide breaks or
use the `<!-- @SLIDE -->` directive for slide breaks without titles
(e.g. for slides with images only). Example:

```
---
title:     Starter Sample (Blank5 Theme) - Habits
author:    John Doe
date:      March 22, 2017
---

## In the morning

### Getting up

- Turn off alarm
- Get out of bed

### Breakfast

- Eat eggs
- Drink coffee


## In the evening

### Dinner

- Eat spaghetti
- Drink wine
- Browse slide show


<!-- @SLIDE -->

![](../i/slideshow.png)


### Going to sleep

- Get in bed
- Count sheep
```

(Source: [`_talks/starter5.md`](https://github.com/henrythemes/jekyll-talks-theme/blob/master/_talks/starter5.md))

To change the colors, typography, etc.
see the styles in `css/blank5.scss`.



## Alternatives

For alternative Jekyll-compatible talk templates (e.g. reveal.js, deck.js, impress.js, shower, etc.)
see the [Slide Show (S9) templates](https://github.com/slideshow-templates).


## License

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The slide show (S6) scripts and templates are dedicated
to the public domain. Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to
the [wwwmake forum/mailing list](http://groups.google.com/group/wwwmake).
Thanks!
