# README

* Create *.env* file with following variables
	COMPOSE_PROJECT_NAME=small_app
	PGDB_HOST=postgres
	POSTGRES_USER=<your_pg_user>
	POSTGRES_PASSWORD=<your_pg_password>
	RAILS_ENV=development

* *docker-compose build*

* *docker-compose up*

* Database creation
	*docker-compose run web rake db:create*
