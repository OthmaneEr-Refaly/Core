### Your answer

> its a standard way that computers use to communicate, and its basically a set of rules that we call "Rest constraints", if we follow this rules we can get a safe and scalable rest api

## Score

**8/10**

You're on the right track, but there are two misconceptions.

REST is **not** "how computers communicate."

HTTP is the communication protocol.

REST is **an architectural style** for designing APIs that use HTTP.

Think of it like this:

- HTTP = the language
- REST = the grammar and writing style

---

### Interview-ready answer

> REST (Representational State Transfer) is an architectural style used to design web APIs. It defines a set of constraints that make APIs simple, scalable, and maintainable. REST APIs typically expose resources through URLs and manipulate them using standard HTTP methods such as GET, POST, PUT, PATCH, and DELETE.


## REST Constraints

- Client-Server
- Stateless
- Cacheable
- Uniform Interface
- Layered System
- (Optional) Code on Demand

## Related

- [[API]]
- [[HTTP]]
- [[Resources vs Actions]]
- [[Idempotency]]