# Heroku Skeleton Application

__Global Requires__
Skeleton application which solves global `require` locally and on Heroku.  Using a  `node_modules` directory in `./app/` we can make global path requires.

__Backbone/Marionette/Browserify__ 

Ensure we have dependencies between Backbone & Marionette configured properly for Browserify so when it builds it will all work. _Assigning these libs and more to `window` on `entry.js` file_ so they are globally available thorughout our application runtime. This way we don't have to define the dependecy at the start of every file, cause we'd have to do that  __alot__.

__Pay attention to versions, they are extremely important to get this to work right.__

## Client 

### Backbone

[Backbone 1.1.1](http://backbonejs.org/)

__*Backbone must be at `1.1.1` because, [insanity](https://github.com/jashkenas/backbone/issues/2997)__

also @see https://github.com/jashkenas/backbone/issues/3291


### Marionette

- [Marionette](http://marionettejs.com/)


- [Underscore]
- [jQuery]
- [Handlebars]


---

## Server 

### iojs

- [io.js]()

### express

- [Express]()



---

## Database

### Mongoose

- [Mongoose]()




---

## Build


### Browserify

- [Browserify]()


### Npm Scripts


---

# Tests



---

## Configs

### editorconfig

[editorconfig]()


#### No Semicolons
