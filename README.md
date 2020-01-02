## Unify Application - Java Application
This starter provides a project template for building applications using Unify Framework that will run as a Java executable in a JVM. Runs on Java 7, 8, 9 and 10. An embedded Jetty server is used to handle all HTTP requests.

Uses in-memory HSQLDB as application database and utilizes port 8080 and 8081 for HTTP by default. You can change database and port settings in ...\WEB-INF\conf\unify.xml.

## Build the Project

```
mvn clean package
```

### Quick Run
* Download an already assembled runnable package here.
* Extract downloaded package to a suitable folder and run startup.bat or startup.sh in folder ..\bin
* Open a browser and enter http://localhost:8080/unify into address the bar.