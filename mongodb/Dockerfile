# # This is official MongoDB image pull from Docker Hub. We are using version 5 of MongoDB.
FROM mongo:5 
# We are copying all the .js files from the current directory to the /docker-entrypoint-initdb.d/ directory in the container. This is a special directory in MongoDB image where we can place our initialization scripts. These scripts will be executed when the container is started for the first time and the database is initialized.
COPY *.js /docker-entrypoint-initdb.d/  
