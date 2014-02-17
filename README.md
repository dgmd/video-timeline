Project 1: Developing a Project Container
=========

In this project, we're going to develop the skeleton of for a single-page app/site which will serve as an evolving template for course projects, inspired by [Apple's recent treatment of their new Mac Pro](https://www.apple.com/mac-pro/).

### In class

In class, we're going to talk through the rough outline of how the skeleton is put together before turning to you to ask you to implement a few, additional features and add your own touches to it.  This means you'll need to [fork](https://help.github.com/articles/fork-a-repo) this repository (using the [github app](http://mac.github.com)), make changes, and push them to your fork so we can see what you've done.

As far as the specific changes we'd like you to make. . .

![Tweaks to make to the skeleton app](http://cl.ly/image/2J0g1J190Y2g/download/Screen%20Shot%202014-02-06%20at%2011.31.48%20AM.png)

+ Animate the white waypoint buttons when you hover over them.

+ Record your own video and pull it into to replace [Beyoncé's "Countdown"](https://www.youtube.com/watch?v=2XY3AvVgDns).

+ Animate the entry of the detail panels--perhaps flying in or fading in or. . .--_a la_ [the Mac Pro example](https://www.apple.com/mac-pro/).

+ At the bottom of the page, you should notice a black arrow.  Make that arrow proceed between waypoints.

#### Addendum, posted 7 February 2014

> ##### add :hover to the side navigation bar for Project-1
> 
> You'll notice that there are a number of effects on the Apple site which don't yet exist on our Project-1.  We'd like you to try exploring add some of this functionality.  In rough order of increasing complexity:
>
> 1. Shoot your own video and replace the one in Project-1
> 2. Head over to Google Fonts and select a new font to change the Header/Footer text to.
> 3. Add the functionality for the down triangle to switch between waypoints.
> 4. Dynamically place text as you scroll; perhaps add a timing element/delay to the panel effects so that when you switch to a waypoint, there's a delay before, say a panel slides in or some text appears or. . .
> 5. Change the behavior of scrolling so that rather than the video seeking in time to a different point each time you scroll, create something more like Apple's site, where scrolling triggers transitions or cutscenes.  i.e. At some point, your script should basically be saying, "When I've scrolled this far, play that scene of the video."
> 6. Animate the emergence/arrival of the `.detail` panels-- either via fade-in, slide-in, or a mechanism of your choice.
> 7. Similarly, animate the bottom panel sliding up when you've scrolled a certain amount.
> 8. Set up the nav bar so that when you hover over a waypoint, some text appears next to the waypoint.  This means you'll need to insert a `div` with a description in the right place depending on what you're hovering over.