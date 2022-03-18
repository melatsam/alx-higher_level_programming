0x11-python-network_1

urlibrequest is python modules for fetching URLS  (uniform Resource Locators).IF offers a 
very simple interface in the form of the urlopen funcion.

HTTP is based on request and response - THE client makes request and service
send respones urlib,request mirrors this with request object whcih represent
the HTTP request you are making .IN this simplest from you create a request
object that specifies the URL you want to fetch. calling urlopen with this
request object returns a respones object for the URL REQUEST . this response 
is a file like object, which means you can for examples call read() on the response.

IN case of HTTP, there are two extra things that Request object allow you to do:

first, you can pass data to be sent to the server.

second , you can pass extra information("metadata") about the 
data or about the request it self, to the server. this information
is sent as HTTPS "headers"

fetch is the retrieval of data by software program,script or hardware device.

