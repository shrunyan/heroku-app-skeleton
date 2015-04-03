# Heroku Skeleton Application

__Getting Started:__

- `npm install`
- `npm start`


__Global Requires__
Skeleton application which solves global `require` locally and on Heroku.  Using a  `node_modules` directory in `./app/` we can make global path requires.

__Backbone/Marionette/Browserify__

Ensure we have dependencies between Backbone & Marionette configured properly for Browserify so when it builds it will all work. _Assigning these libs and more to the `window` object in the `entry.js` file_ so they are globally available throughout our application runtime. This way we don't have to define the dependency at the start of every file, cause we'd have to do that __alot__.

__Pay attention to versions, they are extremely important to get this to work right.__

## Client

### Backbone

[Backbone 1.1.1](http://backbonejs.org/)

__*Backbone must be at `1.1.1` because, [insanity](https://github.com/jashkenas/backbone/issues/2997)__. Also @see https://github.com/jashkenas/backbone/issues/3291


### Marionette

- [Marionette](http://marionettejs.com/)


- [Underscore](underscorejs.org)
- [jQuery](jquery.com)
- [Handlebars](handlebarsjs.com)


---

## Server

### iojs

- [io.js](https://iojs.org)

### express

- [Express](expressjs.com)



---

## Database

### Mongoose

- [Mongoose](http://mongoosejs.com/)




---

## Build

Using __[Npm Scripts](https://docs.npmjs.com/misc/scripts)__ to handle the build. Check out `package.json` to see what's available.



---

# Tests



---

## Configs

### editorconfig

[editorconfig](http://editorconfig.org/)


#### No Semicolons
