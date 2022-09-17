## Referenced link
https://blog.logrocket.com/how-to-build-a-rest-api-with-golang-using-gin-and-gorm/


A fantastic open-source project called Gin.
This framework is lightweight, well-documented, and, of course, extremely fast.

```sh
go mod init gin_gorm
go get github.com/gin-gonic/gin github.com/jinzhu/gorm
```
Get Sqlite3
```sh
go get github.com/jinzhu/gorm/dialects/sqlite@v1.9.16
```


## How to run
```sh
go run main.go
```

By building this project from scratch, I hope you gained a basic understanding of how to develop a RESTful API with Gin and Gorm, how they work together, and how to implement the CRUD features. There is still plenty of room for improvement, such as authenticating users with JWT, implementing unit testing, containerizing your app with Docker, and a lot of other cool stuff you can mess around with if you want to dig deeper.