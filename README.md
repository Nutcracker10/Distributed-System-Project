# comp30220-online-shopping

Group project for COMP30220 Distributed Systems.

This version of the project has all unit tests and has not been dockerised yet.

The Master branch has the video demonstration and project report.

View the docker branch to run the dockerised project.

To run without Docker, enter the project root and do the following:
1. mvn clean compile
2. mvn install
3. mvn spring-boot:run -pl eureka
4. mvn spring-boot:run -pl aggregator
5. Then, start the other services in any order using the same steps as above, but naming the
other services instead.
