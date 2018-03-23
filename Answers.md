<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
  - Middleware a layer of software that lies between two other pieces of software, for example, it can be used in authentication by requiring the request to pass through the middleware before reaching the target. I also feel like I remember the simplest definition of middleware being a function that return another function, but I would like clarification on that.
2.  What does bcrypt do in order to prevent attacks?
  - Bcrypt hashes passwords and then hashes the potential passwords in order to compare them, this way, the actual password is never exposed.
3.  What are the three parts of the JSON Web Token?
  - The header, payload (which contains some user data), and the signature (which, being composed of the header, payload, secret, and algorithm given in the header, ensures that nothing was changed along the way).