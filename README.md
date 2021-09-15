# docker-file-for-django

Docker django file for development

Update the postgres DB name, username and password on docker-compose.yml file.

Required to create the volumes for postgresql by running command

```docker volume create pgdata```

# commands
To run the application 

```docker-compose up```

To run the django shell or command 

```docker-compose exec web python manage.py shell```

To access with bash

```docker-compose exec web bash```

To access postgresql

``` docker exec -it <container name> psql -h <host> -U <username> -d <dbname>```

```docker-compose exec <container name> psql -U <username> -d <dbname>```

rebuild image
```docker-compose build web```

Remove unused images
```docker images prune -a```
