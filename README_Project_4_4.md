# P4: Website Optimisation

This project will tackle a number of optimization- and performance-related issues, to s a target PageSpeed score and runs at 60 frames per second.

## Version

1.0

## Getting Started

Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

Check out the repository
To inspect the site on your phone, you can run a local server

$> cd /path/to/your-project-folder

$> python -m SimpleHTTPServer 8080

Open a browser and visit localhost:8080

Download and install ngrok to make your local server accessible remotely.

$> cd /path/to/your-project-folder

$> ngrok 8080

Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: More on integrating ngrok, Grunt and PageSpeed.

Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js.

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: Chrome Dev Tools tips-and-tricks.

## Important Files

The project optimises the critical rendering path by inlining css and enhancing functions in JavaScript. The two important files are:

*index.html - This file contains the structure of the profile site, and the changes made particularly in css to optimise the critical rendering path.

*main.js - This file contains the functionality of one of the profile - Cam's Pizza. Changes have been made to the functions to enhance it performance, so that it achieves 60fps.

License
----

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



