## Website Performance Optimization portfolio project
-----------------------------------------------------
# Optimized WebPage : https://aravindbj.github.io/weboptimization/.

##How to test Pagespeed
-----------------------
1. Open the link https://developers.google.com/speed/pagespeed/insights/ in any browser.

2. Enter the url https://aravindbj.github.io/weboptimization/. in the text box for url and click on Analyze button.

3. It then displays the Pagescore of the web page in both desktop and mobile.

##How to check the time to resize pizza
---------------------------------------
1. Open the project by opening the index.html file in google chrome.

2. Click the pizza link.

3. Open the dev tool by pressing Ctrl/Cmd + I and click on Console.

4. By default the pizza slider is in the middle position showing the medium pizzas.

5. Move the pizza slider to left end and then towards the right end to generate small and larger pizzas.

6. The time to resize pizzas will now be displayed in the console.

##Steps taken for Optimizing
1. Added media query for the render blocking print.css

2. High Resolution images are compressed using online websites

            **www.optimizilla.com**

3. Inlined the render blocking Google font css using web font loader.

4. Minified style.css, print.css and perfmatters.js.

5. Added async tag to analytics.js and perfmatters.js

6. Removed queries from for loops in changePizzaSize()

7. Changed updatePosition() functions

## Score
94/100 - Mobile

93/100 - Desktop**Attached Screenshots in page speed results folder**
