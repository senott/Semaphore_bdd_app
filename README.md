# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies
  - PostgreSQL on Docker\
    To create the container:\
    ` $ docker run --name semaphore_postgres -e POSTGRES_PASSWORD=<mysecretpassword> -d -p 5433:5432 postgres `\
\
    To run the container:\
    ` $ docker start semaphore_postgres `\
\
* Configuration

* Database creation\
  ` $ rake db:create `

* Database initialization\
  ` $ rake db:migrate `

* How to run the test suite\
  ` $ bundle exec cucumber `

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
