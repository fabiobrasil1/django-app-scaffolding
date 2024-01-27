## Para executar o App run

```
docker-compose up --build

```

## Para executar makemigrations

```
docker-compose run djangoapp python manage.py makemigrations

```
## Para executar migrations

```
docker-compose run djangoapp python manage.py migrate

```

## criar super user

```
docker-compose run djangoapp python manage.py createsuperuser

```