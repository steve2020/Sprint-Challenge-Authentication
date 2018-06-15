<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
middleware: functions or other software between the database or server and the client. 
sessions: a place to store data (generally either in a cookie stored in the client's browser, or stored in the database) to asociate disparate actions of one user across a website

2.  What does bcrypt do in order to prevent attacks?
hashes a password by using a "salt" (random data) as opposed to simply storing a password as plain text

3.  What are the three parts of the JSON Web Token?
header (algorithm and token type), payload(data), secret