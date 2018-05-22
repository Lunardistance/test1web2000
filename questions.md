1-How do we measure the length of the critical rendering path? (10 pts)


Taking into account all of the things that must happen for the page to render--for example, running the CSS, js, etc.  Also taken into account is how many times the server needs to request information for the page to render.

2-What are the events in the Timeline pane which show the DOM being built, the CSSOM being built, and the render tree being built? (10 pts)



3-What is the render tree? (10 pts)

The DOM and CSSOM are each separate trees and together known as the render tree. This structure contains all the elements of the DOM and CSSOM in the order they render according to the structure of the code. This exists as input instructions for the browser to render the page correctly.

4-What are three things you can do in order to speed up a website's load time? (10 pts)
1. Make the code efficient ex. remove unnecesarry styles
2. Minify the Javascript so that the code runs faster ex. bundle
3. Cache the files

5-What is the name of the Google tool you can use to see a list of things you can do to improve your page's load speed? (10 pts)

google page speed insights

6-What is the purpose of including multiple <source> elements within a single <video> element?

So that different browsers can play the video


7-Use webpack to bundle all the files in the following project: https://github.com/Swolebrain/connect4
Setup Steps:

Fork the project by going to the above link and clicking "Fork" near the top right of the screen
The project will now have a copy in your own github page. Clone it from there.
In your computer, initialize this folder as a node project.
Install webpack, webpack dev server, and make sure they are saved as development dependencies in package.json
Split out the code from the createTable function and the isLegitEdge function into separate files. Make sure each function has its own file.
**js**This loooks like it was already done?**js**
Back in your main file, require/import the contents of your two new files
Create an npm script to use webpack to fire the dev server and create a javascript bundle (one single file containing all your JS).
Do anything else you need to do in order to get the bundle working and test your site.
Before submitting, ensure your code is bundled into one file.
Commit and push to github
Upload the game to yourname.fvi-grad.com


8-Bonus points: Produce a minified bundle for the exercise above using an uglify plugin.