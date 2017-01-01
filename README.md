## Website Performance Optimization portfolio project

In this challenge, I have to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques that I have picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

open index.html to launch this project.

####Part 1: Optimize PageSpeed Insights score for index.html

1. Moved analytics code at the bottom page.
2. Include all the style on the page.
3. Loaded google font in more optimised way.
4. Added media print seperately.
5. Compressed and resize all the images.
6. Loading scripts asynchronously.

####Part 2: Optimize Frames per Second in pizza.html

1. Used more performant DOM element selectors getElementsbyClassName.
2. Removed unwanted calculation from the changePizzaSizes loop.
3. Removed determineDx function and optimized calculation.
4. Moved Repeated Calculation outside the loop in updatePositions function.
5. Added a scroll function to use the requestAnimationFrame API to optimize concurrent animations.
6. moved variable intialization before loop to improve performance.
7. Calculated number of pizzas which should be displayed on screen dynamically.

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>


