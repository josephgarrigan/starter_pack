# Python, HTTP, and the Requests library

Sending requests then parsing the response for important information is a most needed skill. 

Python has a great library for making sending requests over http much easier. This is the [requests](https://requests.readthedocs.io/en/latest/) library and with it we can create an abstract pattern to reuse against different api endpoints. 

## Topics to read first: 

- [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) is the protocol upon which most communication occurs. This is one of the most critical concepts to understand as it will provide context to future topics. 
- [API](https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces) This is an acronym that will be thrown around a lot. Having a real understanding of what it means vs using it wrong will really help 
- [CRUD](https://rapidapi.com/blog/api-glossary/crud/) is another acronym that will be mentioned often. Nothing too serious just be aware 
- [JSON](https://docs.python.org/3/library/json.html) will be the primary data structure being worked with. Understanding how to work with JSON is critical

The very first task will be to create a script that uses endpoints from [FOAAS](https://www.foaas.com/?ref=apilist.fun) to fulfill the following requirements: 

- Print a message about every group member using a different endpoint
