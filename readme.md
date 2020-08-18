## Spring-boot application with H2 in local/client mode with web console

Running your own properties:
	
	java -Dspring.config.location=/c/tmp/application.properties -jar h2-console-0.0.1-SNAPSHOT.jar
	
	or
	
	java -Dspring.config.location=application.yml -jar h2-console-0.0.1-SNAPSHOT.jar
	
	
TCP server is available [here](https://github.com/etlapa/h2-tcp-server)