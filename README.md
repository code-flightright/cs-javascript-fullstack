# Javascript Fullstack Exercise

## The server side
Design and implement a backend service that `GET` data from [randomuser.me](https://randomuser.me/api/?results=300&nat=de,dk,fr,gb&inc=id,gender,name,location,email,dob,picture,nat&seed=flightright). Group the results by `nat` and expose the new object as `/nat` endpoint so it can be used by a frontend application. 
 
    https://randomuser.me/api/?results=300&nat=de,dk,fr,gb&inc=id,gender,name,location,email,dob,picture,nat&seed=flightright


## The client site
Design and implement an application that reads data from the `/nat` endpoint. Display the results grouped by nat with the given information.

As an out put of this exercise we expect to see a minimum of the following:

- display nr of entries for each country
- display a random picture of a citinsen
- display a vote button for each coutry


The objective of this exercise is to have you walk us through a solution you have created. Do as much or as little as you would like.

## ReadMe

Please include:

-   a readme file that explains your thinking
-   a flow model showing your design, explain why you designed the db and include the DDL used to generate the tables in your database
-   how to run and set up your project
-   if you have tests, include instructions on how to run them
-   a description of:
    -   enhancements you might make
    -   additional features you have added to help or that you found interesting
-   questions you have
-   recommendations for us

## Additional Info:

-   we expect that this will take you a few hours to complete
-   use any framework or library you are comfortable with (we love Next.js)

-   Bonus points for setting up a db (for a hypothecial country vote function)
-   Bonus points for security, specs, etc.
-   Bonus points for deployment
-   Bonus points for Dockerized solution
-   Do as little or as much as you like.

Ideally commit your code into a repo. Show your work and process through those commits. If you're not be able to commit your code, send us the files via email.
