# spring-boot-practice

:toc:

Created a "hello world" RESTful web service with Spring.

== What you'll build

A service that will accept HTTP GET requests at:

....
http://localhost:8080/greeting
....

and respond with a JSON representation of a greeting:

[source,json]
----
{"id":1,"content":"Hello, World!"}
----

Custom greeting with an optional `name` parameter in the query string:

----
http://localhost:8080/greeting?name=User
----

The `name` parameter value overrides the default value of "World" and is reflected in the response:

[source,json]
----
{"id":1,"content":"Hello, User!"}
----
