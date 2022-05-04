# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Un peu de freestyle :
1) Movie.create(..)

2) movie_1 = Movie.find(1)
   movie_1.update(allocine_rating: 4.7)

3) movie_2 = Movie.find(2)
   movie_2.update(genre: "Comédie")

4)  movies = Movie.where(already_seen: true)
    movies.all

5)      

d) Le seed aux BDD bien créées, la valeur n'attend point le nombre des années
