# Blank module template

This is a template for JavaScript module projects.

## Repo structure

- dist: Production-ready files
- src: Uncompiled source
- test: Unit tests
- examples: Demos of plugin in action

## Building dist folder

- Install [Node and npm](https://nodejs.org) and [Grunt](http://gruntjs.com)
- Run `npm install`
- Run `grunt`

## Running tests

- Build dist folder
- Run `grunt test`





## Options (* = required)

- source * (file or media URL)
- startpoint (number, seconds)
- skipTime (number, seconds)
- speedIncrement (number, seconds)
- container*: element (eg. grabbed using querySelector)
- buttons (selectors or elements)
    - playPause
    - speedSlider
    
- onReady: function
- onChange: function(argument: name of function which called it)
- onDisableSpeedChange: function
- rewindOnPlay: boolean

## Methods

- reset
- remove (same as reset)
- playPause
- play
- pause
- skipTo: number (seconds)
- skip
    - 'backwards'
    - 'forwards'
- speed
    - 'up'
    - 'down'
    - 'reset'
    - number (eg. 0.5, 1, 2)
- getTime
- setTime (same as skipTo)
- getDuration
- parseYoutubeURL (don't need to initialise a new object to use)


## Read-only properties

- progressBar (progressor instance)
- speedChangeDisabled
- paused


