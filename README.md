# FIGGIF

FIGGIF is a GIF Database REST API.

Graphics Interchange Format. GIFs are image files that are compressed to reduce transfer time. The proper pronounciation of the acronym is a soft "g" sound: like JIF. 

Each GIF handled by FIGGIF has an unique ID, a description, tags, reactions and number of downloads.

FIGGIF allows to search GIFs by tag, by reaction and by description.

Default response format must be JSON.

## API

* Create an endpoint to create GIF.
* Create an endpoint to return one GIF with all data related (ID, description, reactions, tags, number of downloads) given an ID.
* Create an endpoint to update a GIF given an ID.
* Create an endpoint to delete a GIF given an ID.
* Create an endpoint to download GIF file.
* Create an endpoint to create Tag.
* Create an endpoint to list Tags.
* Create an endpoint to delete Tag.
* Create an endpoint to create Reaction.
* Create an endpoint to list Reactions.
* Create an endpoint to delete Reaction.
* Create an endpoint to search GIFs by description.
* Create an endpoint to search GIFs by tag.
* Create an endpoint to serach GIFs by reaction.
* Create an endpoint to list all the GIFs that have the same tags as a given GIF

## Optional Tasks

* [Optional] Create one integration test.
* [Optional] Create one unit test.
* [Optional] Health checks
* [Optional] Run with Docker

## SETUP

* Java 8
* Spring-Boot
* H2 or HSQLDB database
* Maven
* [Optional] Docker image

# Good Practices

1. Use good practices for REST APIs (http://www.restapitutorial.com/lessons/restquicktips.html).
2. Implement clean code (https://blog.goyello.com/2013/01/21/top-9-principles-clean-code/).
3. Develop by functionality instead of by layer. Choose a verb, and implement it completely. from API to repository. 
4. The application MUST compile and run from Maven, independently from the IDE you use for development.
5. Use good practices for Spring-Boot Applications (https://spring.io/guides/gs/spring-boot/).
6. Consider using Actuator or any other Spring-Boot starter for development or deployment (http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/).
