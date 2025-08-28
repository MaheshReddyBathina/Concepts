# REST Architecture


## What is REST
- REST stands for Representational State Transfer. It's an architectural style for designing network applications.REST is used to build RESTful web services that communicate using standard HTTP methods like GET,POST,PUT,DELETE and return data in formats of JSON. 

## Key Principles
- Client-Server :  The Client and Server are seperate.Client is   responsible for User interface,while the server handles the data storage and business logic.  
- Stateless :  Each request from the client to the server must contain all the information but the server does not store any client context or session state between requests. This makes the system more scalable.his we called Stateless. 
- Cacheable : The server responses must be able to define whether it can be cacheable or not. 
- Uniform Interface : Standard methods (GET,POST,PUT,DELETE).  
- Layered System : Clients may not know if they are talking to end server or an intermediary.   

## HTTP Methods
- There are Five types of HTTP Methods
1. GET: Primary purpose of GET is used to read the data or retrive the data.  
2. POST: is used to Create new resource on the server.
3. PUT: is used to Update existing resource. 
4. DELETE: is used to Remove the resource.
5. PATCH: Partial update the existing resource.  

## Advantages
- Simple and lightweight  
- Scalable due to statelessness  
- Works well with web standards (HTTP,JSON). 

## My Takeaways
- REST makes APIs simple and scalable  
- Best for CRUD operations over HTTP  
- Understanding principles helps in designing clean APIs  

## References 
- https://developer.mozilla.org/en-US/docs/Glossary/REST
- https://www.youtube.com/watch?v=7YcW25PHnAA
