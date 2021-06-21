1.In your own words, describe what each group of status code represents:
100’s = informational status codes.
200’s = success codes, the request met all validation requirements at the time of sending.
300’s = redirection codes, the resource they are requesting isn’t available at the expected location anymore.
400’s = client error codes, They are all about invalid requests a client sent to a server.
500’s = server error codes. overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.


2.What is a status code 202?

	It is intentionally non-committal. Its purpose is to allow a server to accept a request for some other process (perhaps a batch-oriented process that is only run once per day) without requiring that the user agent's connection to the server persist until the process is completed.

3.What is a status code 308?
	supose to use another URL to access the resource.

4.What code would you use if an update didn’t return data to a client?
	Code 204 No Content.
	
5.What code would you use if a resource used to exist but no longer does?
	414 Request-URI Too Long.

6.What is the ‘Forbidden’ status code?
	403 Forbidden.
