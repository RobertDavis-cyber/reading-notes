## Class 7 Reading Notes My Reading Journal for seattle-code-301d92

## Readings: Readings: APIs

## API Design Best Practices

1. What does REST stand for?--*Representational State Transfer (REST) is a software architecture that imposes conditions on how an API should work.*

2. REST APIs are designed around a ____. *resources*

3. What is an identifier of a resource? Give an example.--*REST API resource can be accessed by using a Uniform Resource Identifier (URI). The URI must contain the correct connection information to successfully call the API.*

4. What are the most common HTTP verbs?--*POST, GET, PUT, PATCH, and DELETE.*

5. What should the URIs be based on?--*Uniform Resource Identifier is a sequence of characters that distinguishes one resource from another. For example, foo://example.com:8042/over/there?name=ferret#nose is a URI containing a scheme name, authority, path, query and fragment.*

6. Give an example of a good URI.*foo://example.com:8042/over/there?name=ferret#nose*

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?--*Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. BAD*

8. What status code does a successful GET request return?--*The 200 OK status code means that the request was successful, but the meaning of success depends on the request method used: GET: The requested resource has been fetched and transmitted to the message body.*

9. What status code does an unsuccessful GET request return?--*If not valid, 400 Bad Request is returned.*

10. What status code does a successful POST request return?--*The 200 OK status code means that the request was successful, but the meaning of success depends on the request method used: GET*

11. What status code does a successful DELETE request return?--*HTTP 200 or HTTP 204 should imply resource deleted successfully.*

## Bookmark and Review

RegExr - Pay particular attention to the cheatsheet
(https://regexr.com/)
Regex Tutorial
(https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
Regex 101
(https://regex101.com/)

## Things I want to know more about...

*Using JSON as the Format for Sending and Receiving Data for REST API best design practice meaning?*
