# helloworld-rs: Hello World JAX-RS RESTful Web Service


## Technologies

JAX-RS
CDI
Wildfly



## Requirements

Wildfly Server
Maven


## Steps

###### Start a Wildfly Server:

For Linux:   WILDFLY_HOME/bin/standalone.sh  
For Windows: WILDFLY_HOME\bin\standalone.bat


###### Build and Deploy the Webservice:

*mvn clean install wildfly:deploy*


###### Access the Application:

http://localhost:8080/helloworld-rs/


###### Undeploy Webservice:

*mvn wildfly:undeploy*


## original source
<https://github.com/wildfly/quickstart/>