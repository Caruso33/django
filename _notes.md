### building

docker build .

docker-compose build

### set up project

docker-compose run app sh -c "django-admin.py startproject app ."
docker-compose run app sh -c "./manage.py startapp core"
docker-compose run app sh -c "./manage.py test"
docker-compose run app sh -c "./manage.py test && flake8"