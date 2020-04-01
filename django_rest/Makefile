run_tests: 
	docker-compose run --rm app sh -c "./manage.py test && flake8"
run_dev: 
	docker-compose up
make_migrations: 
	docker-compose run --rm app sh -c "./manage.py makemigrations"
run_cmd: 
	docker-compose run --rm app sh -c "$(cmd)"