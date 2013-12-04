dropwizard-tutorial
===================

Some code from the dropwizard site

# Running the sample
    mvn package;java -jar -Ddw.http.port=9090 target/dropwizard-0.0.1-SNAPSHOT.jar server src/main/resources/hello-world.yml 


# Testing the sample
Visit:
* http://localhost:9090/hello-world
* http://localhost:9090/hello-world?name=joe

