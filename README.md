# Travel Salmon

This is the code for the [Travel Salmon](http://travelsalmon.com) demo site. It's mostly static files, but a couple of things require further documentation:

## Building CSS

The CSS is built from SASS using the included npm scripts. To run them all at once, which creates a production ready CSS file, run `npm run build:css`.

## Building JS

Some of the JavaScript is included within the pages themselves, but some of it needs to be obscured because of....reasons. For the obscured code, modify the `js/index.js` file, and then run `npm run build:js` to bundle it all up to be loaded on the page.

## Dev Mode

Run `npm start` to initiate a server for local development. This will watch for SASS changes and update in real time.