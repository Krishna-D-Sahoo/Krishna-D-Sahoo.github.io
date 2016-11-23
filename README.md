# Web optimization

**Task** - To optimize pages for good user experience.

## Methods applied
---
1. **Web workers are awesome.** In W3schools, the web worker has been defined as a JavaScript running in the background, without affecting the performance of the page. We have transferred some code to a worker.js file. The work done on worker thread doesn't affect the work done in the function thread. The Udacity forums are a great help.  Here is a link about the web workers - [Web worker] (https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers)  Well, there can be issues while using web workers in chrome on windows. We can overcome those hurdles by using command prompt. Using command prompt, we will go to the directory where the .exe of chrome browser is and type - `chrome.exe --allow-file-access-from-files`. I have used web worker for the slider in the pizza.html. The slider is resizing the pizzas.

2. Another way to optimize the index.html page was to inline the css that were present in the style.css file. Well, the file exists but we have delinked the style.css from the index.html file. This is the best option because the images and the design are pretty much static. So it was safe to inline the css in the index.html file.

3. **Remove the render blocking css.** The `print.css` was render blocking. We labelled it as `media="print"` and it no more blocked the rendering of the index.html. :)

4. Changes have been made in the `main.js` inside the `view` folder. This has removed the janky animations.



To see the initial structure of the whole project go to this [link](https://github.com/udacity/frontend-nanodegree-mobile-portfolio). 
