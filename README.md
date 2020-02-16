# 60227230-camel-servlet-example
Made as an answer for [this StackOverflow question](https://stackoverflow.com/questions/60227230/how-can-you-make-a-java-dsl-servlet-using-camel-in-war-format-that-can-deployed) 

Based on Apache [Camel 2.25.x example collection](https://github.com/apache/camel/tree/camel-2.25.x/examples/camel-example-servlet-tomcat-no-spring/src/main) 


--
* Clone the repo
* Build with `mvn clean package`
* Run with `mvn jetty:run`
* Access the service will be available at [http://localhost:8080/camel-example-servlet/camel/hello](http://localhost:8080/camel-example-servlet/camel/hello)
