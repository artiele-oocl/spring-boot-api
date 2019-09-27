# spring-boot-api

**Greeting**
This POJO is created for the structure of the Greeting object.

**GreetingController**
This controller is created to handle mapping of requests depending on HTTP method used.
In our case, it uses the GET method which essentially just requesting data from an endpoint, "/greeting".
A controller intercepts requests and maps it specific endpoints depending on the HTTP method. 
For the annotations, @RestController is used to create RESTful web services. It marks the class as a controller.
On the other hand, @RequestMapping is used to map requests to certain controller methods. This annotation can have two parameters:
method or the HTTP verb, and path or the webservice endpoint.
In our example, we have controller method greeting() of type Greeting. Controller methods use the @RequestParam to extract query parameters
or form parameters.

**Application**
Annotation @SpringBootApplication is essentially the starting point of the application which scans all sub-packages and boots up
the application.