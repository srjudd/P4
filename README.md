<h1>Website Performance Optimization portfolio project</h1>
<p>This project from the Udacity Website Performance Optmization course. Link: <a href="https://www.udacity.com/course/ud884" target="_blank">https://www.udacity.com/course/ud884</a> and submitted to the Udacity Frontend Nanodegree program, cohort 1, for Project 4.</p>
<p>All files for the project wrere downloaded from Link: <a href="http://cameronwp.github.io/udportfolio/" target="_blank">http://cameronwp.github.io/udportfolio/.</a></p>
<h2>How to Play</h2>
<h3>Page Speed Game</h3>
<ul>
	<li>Load the page by going to <a href="http://srjudd.github.io/P4/" target="_blank">http://srjudd.github.io/P4/</a>.</li>
	<li>To check the page speed, go to <a href="https://developers.google.com/speed/pagespeed/insights/" target="_blank">https://developers.google.com/speed/pagespeed/insights/</a>. Paste the URL above into the input field and click "analyze".</li>
	<li>You can investigate Cameron's contributed portfolio by clicking the links on the index page.</li>
</ul>
<h3>Frame Rate Game</h3>
<ul>
	<li>From the index page above, click "Cam's Pizzeria", or go directly to <a href="http://srjudd.github.io/P4/views/pizza.html" target="_blank">http://srjudd.github.io/P4/views/pizza.html</a>.</li>
	<li>Scroll the page to read the amusing random pizzas that have been generated. Watch little pizzas move as you scroll.</li>
	<li>A bit below the page fold, find the size slider. Use it to choose the size of your pizza, and watch the non-moving pizzas change thier size acordingly.</li>
	<li>Use the js console and/or Chrome Dev tools while doing these things to see how frame rate is affected.</li>
</ul>
<h2>Project Approach</h2>
<p>The following strategies were used with index.html to optimize page loading.</p>
<ul>
	<li>Replacing the small pizzeria image with a thumbnail and optimizing profile pic, and using them both as gifs.</li>
	<li>The external style.css style sheet was removed. Most of the css needed for the page was in-lined; some style sheet elements, such as the link styles, were moved into a style declaration in the head.</li>
	<li>Javascript in the head was made asynchronous except for a Google Analytics script that Google recommended not to make async.</li>
	<li>A script at the end of the html page was used to load the Google font stylesheet.</li>
</ul>
<p>To improve the frame rate of pizza.html, Changes were made to main.js in order improve the frame rate in both scrolling of pizza.html and re-sizing pizzas with the slider. The number of pizzas was knocked down to 100. Calculations and document query look-ups that did not need to be repeated in loops were moved out of loops and/or concretized in declared variables of local or global scope, according to their use.</p>
<h2>Resources</h2>
<ul>
	<li>Source files were provided at <a href="https://www.udacity.com/course/ud884" target="_blank">https://www.udacity.com/course/ud884</a>.</li>
	<li>Udacity Course 884 Website Performance Optimization</li>
	<li>Sublime Text v3 was used in editing index.html and views/js/main.js and this Read-Me page.</li>
	<li>Adobe Fireworks CS6 and <a href="http://www.jpegmini.com" target="_blank">http://www.jpegmini.com</a> were used to optimize images.</li>
	<li>Google Developers "Optimizing Performance" was used, along with PageSpeed Insights (below). 
	<a href="https://developers.google.com/web/fundamentals/performance/" target="_blank">https://developers.google.com/web/fundamentals/performance/</a></li>
	<li>Google Developers Pageesped Insights was used to analyze and optimize inde.html. <a href="https://developers.google.com/speed/pagespeed/insights/" target="_blank">https://developers.google.com/speed/pagespeed/insights/</a></li>
	<li>Code to load css asychronously from Javascript was found at <a href="http://stackoverflow.com/questions/574944/how-to-load-up-css-files-using-javascript" target="_blank">http://stackoverflow.com/questions/574944/how-to-load-up-css-files-using-javascript</a> and used with little modification.
	</li>
	<li>Chrome Developer Tools were used to analyze the framerate of pizza.html.</li>
	<li>Udacity Coach Susan recommended the use of randomPizzaContainer.</li>
	<li>jslint was used to check a section of code that did not wind up in the final project.</li>
	<li>A minified version of the css in the head tag of pizza.html was produced by <a href="http://cssminifier.com" target="_blank">http://cssminifier.com</a>.</li>
	<li>A minified version of main.js was produced by <a href="http://jscompress.com" target="_blank">http://jscompress.com</a>.</li>
</ul>
<h2>Honor Code Statement</h2>
<p>I hereby confirm that all project submissions consist of my own work. Accordingly, I will document and cite the origins of any part(s) of my project submissions that were taken from websites, books, forums, blog posts, github repositories, or any other source and explain why I used them for any part of my submission. I understand that I may be asked to explain my work in a video call with a Udacity Coach before my Nanodegree is conferred.</p>

