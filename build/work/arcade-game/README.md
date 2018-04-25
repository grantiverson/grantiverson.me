# Front-End Nanodegree Arcade Game

I made this game as a project for my Front-End Web Development Nanodegree from Udacity. It is a modern variation of Frogger, a classic arcade game, developed using the HTML5 Canvas element and Object Oriented JavaScript.

## Run live

Run it live at [arcade-game.grantiverson.me](http://arcade-game.grantiverson.me)

### How to play

Use the direction keys on your keyboard to move your character up, down, left, or right. Make it to the water without getting hit by the ladybugs and you get a point! See how many points you can get before you lose all three of your lives!

## Download

These instructions will allow you to get a copy of the project that runs on your local machine.

### Prerequisites

* [Git](https://git-scm.com/downloads)
* Browser

### Installing

Instructions to clone and run the project:
1. Clone the git project using `$ git clone https://github.com/grantiverson/arcade-game.git`.
2. Navigate to the root directory for the project.
3. Open index.html in your favorite browser.

## Built with

* [Atom](https://atom.io) - Text Editor
* [JavaScript ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Programming Language
* [Google Chrome](https://www.google.com/chrome/) - Browser and Debugging Tool

### How I made this app

I was given the JavaScript files `js/resources.js` and `js/engine.js` that preload and store the necessary resources and loop through the draw function necessary for the game to run.

I wrote the code in `js/app.js`. This code creates the constructor functions that player and enemy objects inherit properties from. I made use of `this` to reference the properties and create methods that control keyboard input, character movement, speed, collisions, and win/loss conditions.

## Author

* **Grant Iverson** - [GitHub](https://github.com/grantiverson)

### Acknowledgements

`index.html`, `css/style.css`, `js/resources.js`, and `js/engine.js` were provided as part of [Udacity's Front-End Web Development Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001?gclid=CjwKCAjwq_vWBRACEiwAEReprL6RuGAkBbe7XRljOzu9GYr_zQ70LKtonUz_Qev-z0rf07jmNrZNMRoCF9sQAvD_BwE).
