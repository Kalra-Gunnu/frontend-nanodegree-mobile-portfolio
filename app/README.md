## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

Instructions to run site:

1. Fork & Clone the repository.
2. [Install npm](https://github.com/npm/npm).
3. [Install gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md).
4. Run `npm install` in the app directory.
5. Build and run with `gulp serve`.

#### Part 1: Optimize PageSpeed Insights score for index.html

My Solution:

1. Removed `<link href="//fonts.googleapis.com/css?family=Open+Sans:400,700" rel="stylesheet">`. It takes a lot of time to load.
2. Compressed and Resized images.
3. Moved all the scripts at the last of `<body>...</body>`.   


#### Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).

My Solution:
1. Brougth declaration of variables outside the `for` loops(as mentioned in `main.js` in comments).
2. Created a new `for` loop to assign style calculations and preventing the browser from rendering and painting so much.

#### More Customisation

1. One can [add Social media icons](http://weloveiconfonts.com/).
2. Customise the whole layout using different [frameworks](https://colorlib.com/wp/html5-frameworks/).