docker-compose ps

docker-compose run --rm client

docker-compose exec mysql-dev mysql -uroot -ppassword blogapp

docker-compose exec postgres-dev psql -U root -W blogapp

docker run -it --rm --link some-postgres:postgres postgres psql -h postgres -U postgres

