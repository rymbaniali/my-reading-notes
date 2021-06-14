1.What does REST stand for?
	To designing web services

2.REST APIs are designed around a ____.
	Resources.


3.What is an identifer of a resource? Give an example.
	It is a URI that uniquely identifies that resource- https://adventure-works.com/orders/1 .

4.What are the most common HTTP verbs?
	POST - GET - PUT - DELETE - PATCH 

5.What should the URIs be based on?
	Resources.

6.Give an example of a good URI.
	/customers/1/orders/99/products

7.What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
	"chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request. Retrieving large objects can increase the latency of a request and incur additional bandwidth costs so it is bad thing.

8.What status code does a successful GET request return?
	Returns HTTP status code 200 (OK).
	
9.What status code does an unsuccessful GET request return?
	404 (Not Found).

10.What status code does a successful POST request return?
	It returns HTTP status code 201 (Created).

11.What status code does a successful DELETE request return?
	 The web server should respond with HTTP status code 204.