# FEND Project 4 -- Website Performance Optimization

This project is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

Click [here](http://guanxiaomin.github.io/FEND-project-4-web-opt/) to view page.

##Part 1: Optimize PageSpeed Insights score for index.html
Modify index.html to get PageSpeed score 90 or higher.

* Inline CSS to html file.
* Asynchronously load Google Analytics script and move it to the bottom.
* Add Cache Control as public.
* Add `media` to the print css.
* Move google font to the bottom.



##Part 2: Optimize Frames per Second in pizza.html

Modify views/js/main.js until frames per second rate is 60 fps or higher. 

* Refactoring `changePizzaSizes()` function which changes widths of pizza elements.
* Assign constant variables outside of the loop instead of calculating them in every iteration.
* Reduce the number of sliding pizzas to improve performance.


