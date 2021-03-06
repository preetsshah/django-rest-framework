# django-rest-framework

Complete source code for [Django Rest Framework](https://www.django-rest-framework.org/) which implements basic CRUD functionality in a blog API.

## Local Setup

```
$ git clone  https://github.com/preetsshah/django-rest-framework.git
$ cd django-rest-framework
$ pipenv install
$ pipenv shell
(api) $ ./manage.py runserver
```

Navigate to the list view at [http://127.0.0.1:8000/api/](http://127.0.0.1:8000/api/) and detail view at [http://127.0.0.1:8000/api/1](http://127.0.0.1:8000/api/1).

![Blog list view](screenshots/blog-list.png)

![Blog detail view](screenshots/blog-crud.png)
