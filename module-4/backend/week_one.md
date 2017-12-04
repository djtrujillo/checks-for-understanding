## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
    * I think learning how files communicate with each other was very helpful. (Having to import and export files)
2. What are some tools to help debug JavaScript code?
    * Console.log, debugger, devtools
3. What are some tools you need in order to unit test your JavaScript?
    * Mocha with Chai.
4. What is the syntax for invoking a function?
    * function();
5. What is CORS?
    * Cross Origin Resource Sharing
6. How do we enable CORS?
    * 1. Open IIS manager, right click the site and go to properties, change to http headers tab, click add in custom http headers section and click add, enter access-control-allow-origin as the header name, enter * as the header value, click OK twice.
7. What's `this` in JavaScript?
    * THis is an object that references the current context of where it is invoked.
8. What is Webpack and why is it useful?
    * Webpack is way to organize assets and minify them so a browser can get the information that it needs. 
9. When/why do you want to use event delegation?
    * Setting an event listener on a parent object so as to not set one for every child element
10. What's `npm` and what do we use it for?
    * npm is a package manager that allows you to install js libraries and code to help with development

#### Review  
11. What's the MVC design pattern? Describe each part of MVC.
    * MVC stands for model, view, control and describes how data is retrieved through models and displayed through the views all directed by the controllers. 
12. What are a few ways to optimize a Rails application?
    * with Gems that use prewritten code to help with development
13. What's a background worker? When would we want to use a background worker?
    * a background worker is an operation that can be runnning in the background while other tasks are being completed. 
