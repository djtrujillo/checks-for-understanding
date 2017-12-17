## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
    * Node is a server side framework allowing you to write server-side Javascript. 
2. What is Express? What is Express similar to in the Ruby world?
    * Express is a framework that sits on top of Node that allows the creation of web applications using Node.js. It is simliar to Sinatra.
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
    * A route is created in the Server.js file that directs specific endpoints to other functions within the application
    * app.get('/api/v1/meals', function(request, response) { Meals.getMeals(request, response) })
4. What do we use Knex for?
    * Knex is used to access the database within a Node appplication. It is similar to ActiveRecord in Rails.
5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?
    * To mimic an MVC pattern in QS, the routes are all set in the server.js file, those routes are directed to appropriate controllers, that redirect to requests to models that access the data from the db and return that data to the controllers. 
6. How do you execute raw SQL in node?
    * by Using the Knex function .raw()
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
    * An advantage would be making adjustments to your front end that would not affect the back end. Another advantage is you can use different technologies on your front end that may not exist in your backend framework. Disadvantages could be the difficulty in getting them working together(configuration). Also the speed in which an app could be developed may be slowed. 

#### Review  

8. Describe DNS.
    * a Domain Name Server takes a URL and finds it's appropriate IP address. 
9. What does writing clean code mean to you?
    * Clean code is easily changed without breaking other parts of the application. It also easily readable by other people who are new to the codebase. 
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?
    * A hotel would have many classes. You would have a hotel class(different hotels), room class (with room-type attribute, vacancy attribute) 
