# Javascript Fullstack Exercise

## The server side

Design and implement a backend service that `GET` data from [randomuser.me](https://randomuser.me/api/?results=300&nat=de,dk,fr,gb&inc=id,gender,name,location,email,dob,picture,nat&seed=flightright). Group the results by the `nat` (nationality) field and expose the new object via a `/nat` endpoint so it can be used by a frontend application.

    https://randomuser.me/api/?results=300&nat=de,dk,fr,gb&inc=id,gender,name,location,email,dob,picture,nat&seed=flightright

## The client side

Design and implement an application that reads data from the `/nat` endpoint. Display the results grouped by `nat`.

As an output of this exercise we expect to see a minimum of the following:

- display the number of entries for each country
- display a random picture of a citizen
- display a vote button for each coutry

## Readme

Please include:

- a readme file that explains your thinking
- if you included database functionality, explain how you designed the database and include any DDL used to generate the tables in your database
- how to run and set up your project
- if you have tests, include instructions on how to run them
- a description of:
  - enhancements you might make
  - additional features you have added to help or that you found interesting
- questions you have
- recommendations for us

## Additional Info:

- we expect that this will take you a few hours to complete
- use any framework or library you are comfortable with (we love Next.js)
- Bonus points for setting up a db (for a hypothetical country vote function)
- Bonus points for security, specs, etc.
- Bonus points for deployment
- Bonus points for Dockerized solution
- Do as little or as much as you like.

Ideally commit your code into a repo. Show your work and process through those commits. If you're not be able to commit your code, send us the files via email.
