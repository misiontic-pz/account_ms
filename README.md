
###Run application
mvn spring-boot:run
___

###Local server
http://localhost:8080/
___

###Add new models -> Modify order
1. repositories
2. models
3. exceptions
4. controllers
___

###Deploy
1. mvn package
2. heroku container:login
3. heroku create "appName"
4. heroku container:push web --app "appName"
5. heroku container:release web --app "appName"

BD connection
src/main/resources/application.properties