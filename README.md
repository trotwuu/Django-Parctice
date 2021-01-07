# Django-Parctice

### Run Server
```sh
$ docker-compose up
```

```sh
$ docker-compose up -d
```

### clost server
$ docker-compose down

### Django
If you want to `makemigrations` or `migrate`
First we have to activate the Django_env

```sh
$ source ./Django_env/bin/activate
```

```sh
$ python3 manage.py makemigrations
$ python3 manage.py migrate
```

###

開啟 docker 後進去 docker 的 terminal 的方法
docker exec -it django-container bash
為了open python shell 要用的
還有 python manage.py createsuperuser
