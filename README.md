# ASP.Net-AL-BE-Project-2-EF-Part-C-Change

####  CREATE MIGRATIONS
```
dotnet ef migrations add V3AddYearOfEnrollmentAndRemoveSectionCol --project Student-API.csproj
```


#### List Unapplied Migrations
```
 dotnet ef migrations  list --project Student-API.csproj
```
#### Reflect Migrations in Db
```
dotnet ef database update V3AddYearOfEnrollmentAndRemoveSectionCol --project Student-API.csproj
``` 
```
For default value approach used is- manually added default value in migration V3AddYearOfEnrollmentAndRemoveSectionCol
```


#### Remove Migration
```
 dotnet ef migrations remove
```
####  DOCKER-POSTGRES CONTAINER CREATE/UP
```
docker-compose up
```
