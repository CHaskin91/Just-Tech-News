# Just-Tech-News

## Module 13 - Lesson 1
* Set up the application to use Sequelize to manage SQL data.
* Used environment variables to protect the sensitive data.
* Created a user table using Sequelize models.
* Created all of the server endpoints using RESTful API standards to work with the user model's data.

## Module 13 - Lesson 2
* Secure user passwords stored in a database with hashing.
* Add Sequelize hooks (lifecycle events) at key junctures in the application workflow to process important tasks.
* Use `async` and `await` keywords to handle asynchronous functionality to increase legibility.
* Create user authentication that enables identity verification with a hashed password.

## Module 13 - Lesson 3
* We used an ORM to translate the object model into a relational data model using associations.
* When defining the `Post` model, we included references to the primary key and then defined the foreign key relationship with the model associations.
* When defining the routes for the `post` table, we used key properties like `include` in the database requests, to add fields from associated tables like the post's `username`.

## Module 13 - Lesson 4
* Created a new Vote model to store data about who's voting on which posts.
* Implemented a many-to-many model association using Sequelize.
* Created a route allowing a user to vote on a post.
* Queried for related data to see who has voted on which posts.
* Cleaned up some of the code with a custom static Sequelize model method.

## Module 13 - Lesson 5
* Created a new `Comment` model that stored user id's and post id's.
* Established multiple `belongsTo` and `hasMany` relationships.
* Created routes that allow for getting, creating, and deleting comments.
* Updated existing routes to include additional models.
* Deployed a MySQL app to Heroku using the JawsDB add-on.

## Module 14 - Lesson 1
* Use proper code organization paradigms in a full-stack app.
* Use a template engine to deliver front-end files.

## Module 14 - Lesson 2 
* Used Express.js and Sequelize to implement sessions.
* Managed front-end JavaScript logic in an MVC app.

## Module 14 - Lesson 3 
* Use session data within a template.
* Write conditionals to change a template's layout.