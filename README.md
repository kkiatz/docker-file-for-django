# docker-file-for-django

Docker django file for development

Required to create the volumes for postgres by running 

```docker volume create pgdata```

To run the application 

```docker-compose up```

To run the django shell or command 

```docker-compose run web python manage.py shell```

To access with bash

```docker-compose run web bash```
