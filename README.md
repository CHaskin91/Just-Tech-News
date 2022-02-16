# Just-Tech-News

## Lesson 1
* Set up the application to use Sequelize to manage SQL data.
* Used environment variables to protect the sensitive data.
* Created a user table using Sequelize models.
* Created all of the server endpoints using RESTful API standards to work with the user model's data.

## Lesson 2
* Secure user passwords stored in a database with hashing.
* Add Sequelize hooks (lifecycle events) at key junctures in the application workflow to process important tasks.
* Use `async` and `await` keywords to handle asynchronous functionality to increase legibility.
* Create user authentication that enables identity verification with a hashed password.

## Lesson 3
* We used an ORM to translate the object model into a relational data model using associations.
* When defining the `Post` model, we included references to the primary key and then defined the foreign key relationship with the model associations.
* When defining the routes for the `post` table, we used key properties like `include` in the database requests, to add fields from associated tables like the post's `username`.

## Lesson 4
* Created a new Vote model to store data about who's voting on which posts.
* Implemented a many-to-many model association using Sequelize.
* Created a route allowing a user to vote on a post.
* Queried for related data to see who has voted on which posts.
* Cleaned up some of the code with a custom static Sequelize model method.