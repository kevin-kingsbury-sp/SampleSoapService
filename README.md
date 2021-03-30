# SampleSoapService

This project uses maven to create a Sample Soap Web Service that is 
packaged as a war file and can be deployed to an application server.  
In my testing I used a Tomcat application server to run the service.

To compile the war file:

`mvn clean package`

The war file and the service wsdl file will be available in the **target**
subdirectory.
