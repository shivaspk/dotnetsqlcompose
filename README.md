# dotnetsqlcompose
This is a sample dotnet with sqlserver docker project

### Run the docker for MSSQL 

$ docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=1p@sswordY' -e 'MSSQL_DB=postcommentdb' -e 'MSSQL_USER=postcommentdb_app' -e 'MSSQL_PASSWORD=1p@sswordY' -p 1433:1433 -v sqlvolume:/var/opt/mssql -d mcmoe/mssqldocker:v2017.CU12.1

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
