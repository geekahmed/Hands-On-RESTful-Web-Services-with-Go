
# Hands On RESTful Web Services with Go
This is my summary of the Hands On RESTful Web Services with Go by Naren Yellavula.
Contributions: Issues, comments and pull requests are super welcome 😃

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
# Table of Contents
- [Table of Contents](#table-of-contents)
- [Chapter 1. Getting Started with REST API Development](#Chapter-1-Getting-Started-with-REST-API-Development)
<!-- /TOC -->

# Chapter 1. Getting Started with REST API Development
- A web service is a communication mechanism defined between various computer systems.
- A web service is a software system designed to support interoperable machine-to-machine interaction over a network, as defined by the World Wide Web Consortium (W3C).
- Types of web services:
	- Simple Object Access Protocol (SOAP)
		- The main drawback of SOAP is that it is too complex for implementing web services and is a heavyweight framework.
	- Universal Description, Discovery, and Integration (UDDI)
	- Web Services Description Language (WSDL)
	- Representational State Transfer (REST)
- Characteristics of REST services:
	- Client-server based architecture
	- Stateless
	- Cacheable
	- Representation of resources
	- Implementation freedom
- REST verbs specify an action to be performed on a specific resource or a collection of resources.
- A trivial REST API URI looks like the following: http://HostName/APIEndpoint/?key=value(optional)
- A GET method fetches the given resource from the server. To specify a resource, GET uses a few types of URI queries:
	- Query parameters
		- Query parameters are intended to add detailed information to identify a resource from the server. 
	- Path-based parameters
- Use Path parameters for a single resource and Query parameters for multiple resources in a GET request.
- The POST method is used to create a resource on the server.
- The PUT is used to replace the resource that already exists.
- The PATCH method is similar to PUT, except it won't replace the whole record.
- The DELETE API method is used to delete a resource from the database.
- The OPTIONS API method is the most underrated in API development. 
	- Given the resource, this method tries to find all possible methods (GET, POST, and so on) defined on the server.

