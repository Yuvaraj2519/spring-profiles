# spring-profiles
+ Adding profile switch in simple spring boot app

## running the application
+ I have added 3 prop file in app with simple eureka server code
+ That three consisits of default, test and prod.
+ I have defined test as an acttive profile in `application.yml` file

## alternate method
provide `-Dspring.profiles.active=profile-name` that profile name could be prod, test or default
