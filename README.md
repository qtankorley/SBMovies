# SBMovies
A REST movie catalog that allows you create, read, update and delete records of movies. Each movie record entry may have the movie name, the movie director and it's rating.This application is written with Java 8 and the Spring Boot module of the Spring Framework. SBMovie is built on top of a relational database management system.

REQUIREMENTS

	In order to use access data from this service you must first acquire a authentication token. The token is required to perform all CRUD actions.
  You may acquire a token by calling the /login endpoint and supplying the providing your username and password.
  
  
CURRENT FUNCTIONALITY
  This application supports GET, PUT, POST, and DELETE to perform CRUD actions on the movie catalog.
  Given a director name SBMovies will return all movie records associated to the provided director name.
  You can also search movies where the rating is above a provided rating.
  
  
