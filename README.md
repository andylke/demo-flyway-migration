# Demo Application for Flyway Migration

## To Create project using Spring Initializr
```
curl https://start.spring.io/starter.tgz ^
  -d dependencies=flyway,h2 ^
  -d packageName=com.github.andylke.demo ^
  -d groupId=com.github.andylke.demo ^
  -d artifactId=demo-flyway-migration ^
  -d bootVersion=2.3.8.RELEASE ^
  -d baseDir=demo-flyway-migration ^
  | tar -xzvf -
```
