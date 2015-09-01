## LTH Forum - Great Neighborhood Restaurants (GnR)

Application deployed on Heroku: http://lthforum-gnr.herokuapp.com/

### background
"The Great Neighborhood Restaurants and Resources are a crazy mish-mash of great places, nominated by members of LTHForum.com and chosen by all of us. They started as an answer to the one question we always get – “Can you tell us what places you love?” and have grown to become a full list of spots we love and are happy to recommend to anyone. These are destinations all over Chicagoland, restaurants to try if you want to get a true sense of the depth and breadth of the food scene in our city."

<br>
-LTH Forum <br>
http://www.lthforum.com/2013/03/gnr/

### Overview
A RESTful API built on Rails with a database of Great Neighborhood Restaurants off of the LTH Forum website.  Currently, the GNR list is managed on the forum and it can be somewhat difficult to navigate the list.  This API was created to better manage the data on the site and to allow developers to build out applications using the database of restaurants on the list.  As a bonus feature, I added a random restaurant 'roulette' button on the home page.

### Project Scope
* Use Ruby & Sinatra OR Rails to build an API.
* Create a RESTful API using at least one model.
* Include all major CRUD functions in a RESTful API that will work using CocoaREST, Postman, or any client of your choosing.
* Consume your own API by making your front-end with HTML, Javascript, & jQuery, and Backbone.js.
* Add support in your API for Backbone. Do not neglect support for standardized API access as well.
* Add authentication to your API to restrict access to appropriate users. This can be done using API keys, user accounts, or any other form of authenication except OAuth (because we'll cover that soon).
* Craft thoughtful user stories to explain your API.
* Manage your source code using a standard Git flow on Github.
* Layout and style your front-end with clean & well-formatted CSS and make it Responsive. Bootstrap, Skeleton, Foundation, and other front-end CSS frameworks are all welcome here!
* Deploy your application online so it's publicly accessible. For Sinatra, use Digital Ocean. For Rails, use Heroku.

### Technologies used
* HTML5/CSS
* SASS
* Bootstrap
* Ruby on Rails
* Backbone.js
* jQuery
* underscore.js
* Postgres

### Deployment
* Clone down the application.
* Bundle the Gems
* Launch PSQL
* Build the database - rake db:create db:create db:seed
* Lauch the app in the console > rails s
* Open the browser and point it to http://localhost/3000

### Requesting an API Key
* As of now, there's one API key for the application.  Future iterations of the application will include a role based key for updates.
