1. How do we make flash messages display on a page?
    * We call the flash hash like flash[:notice] for example

2. Where is cart information/temporary information usually stored?
    * The cart is stored in the session hash in the browser cache

3. What might be some reasons not to store cart in our database? Are there any reasons why we would want to persist that information?
    * We wouldn't want to make that many calls to a database. Also, their generally isn't a "visitor" database and we would want to carry
    that person's cart as they log in. 

4. What is the purpose of the asset pipeline?
    * The asset pipeline concatenates and minifies our assets.
5. Why do we precompile our assets?
    * This packages them up to increase effiecny when they are utilized

6. What do each of the following tags do?

```ruby 
<%= stylesheet_link_tag "application" %>
    * This links our stylesheet into our html
<%= javascript_include_tag "application" %>
    * This links our javascript files into our html
<%= image_tag "rails.png" %>
    * This adds an image into our html 
```

7. What are some of the elements of a great read me? What are some of the benefits of taking the time to update a readme for our project?
   * Some elements of a great readme include good examples, use cases, detailed description, contributors. Without updating the readme it 
   is possible that people won't be able to fully utilize the benefits of the program. 

8. What are the top four accessibility issues that we as developers should be aware of?
   * Developers should be aware of the need to supply accessibitity to those with disabilities such as being those who aren't able to visually interact with the site as well as those who aren't able to physically use the mouse to navigate. Other issues that affect accessibiilty are cognitive and color blindness. 

9. `before_save` is an example of a what? Where in our Rails application would we find a `before_save`?
    * A Before save is a callback that would be found in the model of a rails application.

10. Given the following object, how would we create a scope for all users who are active?

```ruby 
User.create(name: "Happy", active: true)
```
    * scope :active, -> {where(active: true)} ??

11. What is the difference between a scope and a class method?

    * A class method searches all instances of the object found in the database.
