# Product Review code challenge 
## Description
- E-Commerce Product Reviews System .This is a Ruby on Rails project that simulates a system for product reviews in an e-commerce domain. The project has three main models: User, Review, and Product.

- For the purpose of this project, a Product has many Users, a User has many Products, and a Review belongs to a User and to a Product. Product-User is a many-to-many relationship.


## Getting started
-In order for you to use the content in this repo ensure you have the following:
-  Linux
- Mac Os
-To use this repo on your machine you need to clone by either using:
- terminal
- forking directly from the repo.
### Cloning using button labelled forking
click on the the fork button in the top most rigt corner of the github to fork the repo to your own account.

## Running and testing
Running the application is very straight forward. You can use the following steps to run the app.

This application is interactive on the terminal.

Run the command below to install ruby gems;

          bundle  install 
Then run the command below to migrate the tables;

           rake db:migrate
Then run the command below to add data into your database

    bundle exec rake db:seed:replant
Then run the command 
        
        ruby bin/run
to start your files.

## Author
contributed by:

<b>Amina Hagi<b>

## License
                           Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/