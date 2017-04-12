**Provider**

`gradle clean build && java -jar build/libs/gs-actuator-service-0.1.0.jar`

`curl http://localhost:8080/hello-world`


**Consumer**

`./gradlew test`

**Provider Again**

`./gradlew pactVerify`