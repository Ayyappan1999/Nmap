### What is HTTP and how it works?

  HTTP stands for Hypertext Transfer Protocol, which is a protocol used for communication between web servers and clients. It is the foundation of data communication on the World Wide Web (WWW).

  When you enter a URL (Uniform Resource Locator) into a web browser, it sends an HTTP request to the web server hosting the website you want to access. The server responds with an HTTP response, which includes the requested webpage and any associated resources (such as images, videos, and style sheets).

  HTTP works on a client-server model, where the client (usually a web browser) sends a request to the server and the server responds with the requested information. The client and server communicate over a TCP/IP (Transmission Control Protocol/Internet Protocol) network.

  HTTP requests and responses consist of headers and a body. The headers contain metadata about the request or response, such as the type of content being sent, the size of the content, and other information. The body contains the actual data being transferred, such as the HTML content of a webpage.

  HTTP is a stateless protocol, which means that each request/response pair is independent and does not depend on any previous requests or responses. However, web applications often require maintaining state between requests, and to do this, they use cookies, sessions, and other mechanisms.


### Basics of HTTP

  1. HTTP is a protocol: HTTP stands for Hypertext Transfer Protocol, which is a protocol used for communication between web servers and clients.

  2. HTTP uses a client-server model: The client (usually a web browser) sends a request to the server and the server responds with the requested information.

  3. HTTP is a stateless protocol: Each request/response pair is independent and does not depend on any previous requests or responses. However, web applications often require maintaining state between requests, and to do this, they use cookies, sessions, and other mechanisms.

  4. HTTP requests and responses consist of headers and a body: The headers contain metadata about the request or response, such as the type of content being sent, the size of the content, and other information. The body contains the actual data being transferred, such as the HTML content of a webpage.

  5. HTTP uses a request/response model: The client sends a request to the server and the server responds with the requested information.

  6. HTTP uses methods to specify the type of request: The most common methods are GET (to retrieve a resource), POST (to submit data to a resource), PUT (to update a resource), and DELETE (to delete a resource).

  7. HTTP uses status codes to indicate the status of a request: The most common status codes are 2xx (successful), 3xx (redirect), 4xx (client error), and 5xx (server error).


### HTTP request / response

HTTP request/response is the fundamental mechanism of communication between a client and a server in the HTTP protocol. When a client wants to retrieve information from a server, it sends an HTTP request, which includes a method (such as GET, POST, PUT, DELETE), a URL (Uniform Resource Locator), and headers (optional metadata).

The server then processes the request and generates an HTTP response, which includes a status code, headers (optional metadata), and a response body (the requested information). The status code indicates the success or failure of the request, such as 200 (OK), 404 (Not Found), or 500 (Internal Server Error).

HTTP requests and responses can contain additional information in the headers, such as authentication credentials, cookies, caching information, and more. The request and response headers can be used to control caching, encryption, and compression of the data being transferred.

HTTP requests and responses can also include content types, such as HTML, JSON, XML, and others, which indicate the format of the data being transferred. This enables web servers and clients to understand the content being transferred and process it accordingly.
