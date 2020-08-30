# README

* Ruby version\
2.7.1

* System dependencies
  - PostgreSQL on Docker\
    To create the container:\
    ` $ docker run --name semaphore_postgres -e POSTGRES_PASSWORD=<mysecretpassword> -d -p 5433:5432 postgres `\

    To run the container:\
    ` $ docker start semaphore_postgres `\

* Database creation\
  ` $ rake db:create `

* Database initialization\
  ` $ rake db:migrate `

* How to run the test suite\
  ` $ bundle exec cucumber `\
  ` $ bundle exec rspec `
