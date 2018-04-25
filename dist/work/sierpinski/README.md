# Sierpinski's Triangle Generator: Probability Exercise

I got the idea for this program from a math textbook called Discovering Algebra. In one of the activities, students are encouraged to draw a triangle, associate each triangle with two of the numbers of a die, and then perform a simple algorithm to draw dots on the triangle. The algorithm requires students to 1) pick a random point on the triangle, 2) role a die, then 3) mark the midpoint of the previously drawn point and the triangle vertex corresponding to the number on the die, repeating steps 2 and 3 over and over.

I did it with JavaScript instead.

## Run live

Run it live at http://sierpinski.grantiverson.me

### How it works

This is more of an exercise in the usefulness of computers in probability than a game or application, as it is not very interactive. The only interactivity is that the vertices of the big triangle can be dragged around to change its shape. Notice that the programming regenerates the pattern using the algorithm described above.

This fractal pattern of recurring triangles is known as [Sierpinski's Triangle](https://en.wikipedia.org/wiki/Sierpinski_triangle).

## Download

These instructions will allow you to get a copy of the project that runs on your local machine.

### Prerequisites

* [Git](https://git-scm.com/downloads)
* Browser

### Installing

Instructions to clone and run the project:
1. Clone the git project using `$ git clone https://github.com/grantiverson/sierpinski.git`
2. Navigate to the root directory for the project
3. Open index.html in your favorite browser

## Built with

* [Atom](https://atom.io) - Text Editor
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Programming Language
* [Google Chrome](https://www.google.com/chrome/) - Browser and Debugging Tool
* [Khan Academy](https://www.khanacademy.org/computer-programming/new/pjs) - Browser-based JavaScript programming environment
* [Processing.js](http://processingjs.org) - Visual programming language, designed for the web

## Author

* **Grant Iverson** - [GitHub](https://github.com/grantiverson)

### Acknowledgements

* [Discovering Algebra 2nd Ed.](https://k12.kendallhunt.com/program/discovering-algebra-third-edition) - Textbook I got the idea from (ISBN: 1559537639)
