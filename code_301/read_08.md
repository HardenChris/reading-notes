# API's

## API Design Best Practices

1. What does REST stand for?

    *  Representational State Transfer

2. REST APIs are designed around a ____.

    * >REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

3. What is an identifier of a resource? Give an example.

    * >A resource has an identifier, which is a URI that uniquely identifies that resource.
    * Ex: https://adventure-works.com/orders/1 

4. What are the most common HTTP verbs?

    * GET, POST, PATCH, PUT, and DELETE.

5. What should the URIs be based on?

    * >  When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

6. Give an example of a good URI.

    * > https://adventure-works.com/orders 

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    * chatty APIs are to be avoided since they give off a little data each time and end up resulting in multiple requests instead of a larger singular request which would be slower but require fewer hits.

8. What status code does a successful GET request return?

    * code 200 (ok)

9. What status code does an unsuccessful GET request return?

    * code 404 (not found)

10. What status code does a successful POST request return?

    * code 201(created)

11. What status code does a successful DELETE request return?

    * code 204(no content)


"RESTful web API design" docs.Microsoft, <https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design>

All definitions and information came from the above-listed publication(s).

[<===Back>](README.md)
