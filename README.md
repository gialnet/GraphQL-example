# Book details example 


This is the source code for the "Getting started with GraphQL Java and Spring Boot" which 
is available here: https://www.graphql-java.com/tutorials/getting-started-with-spring-boot/

>install Firefox plugin
Altair GraphQL Client

query example:
```
{
  bookById(id: "book-1"){
    id
    name
    pageCount
    author{
      firstName
      lastName
    }
  }
} 
```
