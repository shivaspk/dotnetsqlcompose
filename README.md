# dotnetsqlcompose
This is a sample dotnet with sqlserver docker project

### Creating Docker Containers With Docker Compose

#### In the same  folder
$ docker-compose up -d 

#### Parsing file as parameter 
$ docker-compose -f [File Path Here] up -d 

#### Forcing container recreation 
$ docker-compose up -d --force-recreate 

## Testing the application 

After all it is easy to access the application and the data base created.

http://localhost:8080/swagger/index.html