# "Class 07" Reading Notes 📖

1. What does REST stand for?
   - Representational State Transfer
2. REST APIs are designed around a ____.
   - resources
3. What is an identifier of a resource? Give an example.
   - A URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
     - `https://adventure-works.com/orders/1`
4. What are the most common HTTP verbs?
   - GET, POST, PUT, PATCH, and DELETE
5. What should the URIs be based on?
   - On nouns (the resource)
6. Give an example of a good URI.
   - Organize URIs for collections and items into a hierarchy. For example, /customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5. This approach helps to keep the web API intuitive.
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
   - To many web requests, it is not good, try to avoid it.  
8. What status code does a successful GET request return?
   - 200(OK)
9. What status code does an unsuccessful GET request return?
   - 404 (Not Found)
10. What status code does a successful POST request return?

- Status 201

1. What status code does a successful DELETE request return?

- Status 204

## Things I want to know more about

Using the common HHTP verbs, in demo.

## References

- [API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
