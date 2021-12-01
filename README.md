# GinApiGorm
Gin+Api+Gorm+login qq

#Create data base
```sql
DBName:   "my_db",
```

#For start project

```go
go run main.go
```

#Create new user `POST`
###Here, we will create two users simultaneously.
```
http://localhost:8080/user-api/user
```
![This is an image](https://miro.medium.com/max/3000/1*3CdGUAEzwGn8s0_4J6Hp7g.png)

#Get all users `GET`
###Get all the available users in our database.
```
http://localhost:8080/user-api/user
```
![This is an image](https://miro.medium.com/max/3000/1*OnJDrpLSg3u9K7Ot8E_IBw.png)

#Get user by id `GET`
###Get the user information for the user having Id=1.
```
http://localhost:8080/user-api/user/1
```
![This is an image](https://miro.medium.com/max/3000/1*fYKgG909hwR6vZaGRZpKyw.png)

#Update the user `PUT`
###Update the user information for the user having Id=1.
```
http://localhost:8080/user-api/user/1
```
![This is an image](https://miro.medium.com/max/3000/1*E142tFPr3nU_9NAHeb58dw.png)

#Delete the user `DELETE`
###Delete the user having Id=2.
```
http://localhost:8080/user-api/user/2
```
![This is an image](https://miro.medium.com/max/3000/1*E142tFPr3nU_9NAHeb58dw.png)


#JSON

```
{"name":"Sudeep Orochy","email":"yura333619@gmail.com","phone":"+380982476223","address":"New Road"}
{"name":"Maxym Mat","email":"maxymmat@gmail.com","phone":"+380982726593","address":"New Varash"}
```
