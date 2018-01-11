# Interview questions

I was asked all of those questions in late 2017 while trying to get job as a Java developer.

- SOLID principles
- what's the output?

```
String s = 1 + 2 + "3" + 4 + 5;
System.out.println(s);
```

- difference between StringBuffer and StringBuilder
- how to use notify() and wait()?
- what's the contract between hashCode() and equals()?
- ACID vs BASE and eventual consistency
- write simple SQL queries based on given tables
- what design patterns do you know?
- what is immutability and why it's importand with threads?
- dependency injection methods and it's drawbacks? (constructor/field/setter)
- how to write a simple HTTP or socket server? how many threads to use? describe it's architecture
- what is connection pooling and when to use it? what problems does it solve on TCP level?
- TCP vs UDP, when you can safely use UDP?
- what is garbage collector? what is gc pause?
- HTTP client timeout types, how to configure timeouts in microservices architecture
- circuit breaker
- how to approach new feature implementation? case study based on shop basket example
- write REST webapp that will access github REST API and will present it's data in different way
- how to find nearest neighbour of a point given millions points with (x, y) coords?
- given object containing unique id and unique name fields, write a collection class that will allow lookup by id or name (hint: synchronized is good, but ReadWriteLock is better)
- do you have any pet project?
- given monolith application, how would you approach it's rewrite into microservices?
- how to approach writing transactional checkout in an online shop while using REST API for payment?
- application monitoring, profiling, logging - describe your experience with those
- live coding fizzbuzz
- live coding fibonnaci (iterative vs recursive versions, space and time complexity)
- types of joins in SQL, what mathematical operations they represent?
- is this class immutable? what should we do to make it immutable?
- is this threading code alright? can it deadlock? what to do to avoid deadlock here?
- how to unit test time related code?
- how to unit test legacy code with calls to System.currentTimeMillis() inside?
- java.util.concurrent, what classes are inside this package? name a few and describe how to use them
- what is single responsibility principle?
- what is a 'clean code' for you?
- can u instantiate abstract class? (hint: you can if it's anonymous)
- what is a functional interface?
- what are the main features added in java 8?
- describe scrum artifacts
- what is idempotency?
- is POST or PUT idempotent? what does it mean in practice? (hint: docs says one of those is, why does Stripe API use 'Idempotency-Key' then?)

