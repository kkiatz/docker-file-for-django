# docker-file-for-django

Docker django file for development

Update the postgres DB name, username and password on docker-compose.yml file.

Required to create the volumes for postgresql by running command

```docker volume create pgdata```

# commands
To run the application 

```docker-compose up```

To run the django shell or command 

```docker-compose run web python manage.py shell```

To access with bash

```docker-compose run web bash```
