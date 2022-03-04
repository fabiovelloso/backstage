# Microservice Template
Minimal microservice template project, based on Onion/DDD.

* Helidon MP 2.2
* Deltaspike 1.9.4
* MySQL 8.0.21
* JUnit 5.7.0 
* ArchUnit 0.15.0
* Flywaydb 7.4.0
* Docker

## Clone the repository
```bash
git clone https://fabiovelloso@bitbucket.org/fabiovelloso/archetype-jpa-microservice.git
```

## Go to archetype directory
```bash
cd archetype-jpa-microservice
```## Install the archetype
```bash
mvn install
```

# Generate the first microservice from the template

Run the Maven archetype
```bash
mvn archetype:generate -DinteractiveMode=false \ 
     -DarchetypeGroupId=org.flvs.microservices.archetypes \
     -DarchetypeArtifactId=microservices.template \
     -DarchetypeVersion=1.0-SNAPSHOT \
     -DgroupId=org.flvs.microservices \
     -DartifactId=hello-service \
     -Dpersistence=hello \
     -Dpackage=org.flvs -Ddatabase=teste
```


