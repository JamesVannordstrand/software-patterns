# Software Patterns
Software patterns represent recurring solutions to common problems in software design. They encapsulate best practices and provide a shared vocabulary for developers. There are several categories of software patterns, each addressing different levels and aspects of software development:


## Design Patterns
These deal with object creation, composition, and interaction within the design of software. They can further be categorized as:

- Creational: Concerned with the process of object creation.
- Structural: Focus on the composition of classes or objects.
- Behavioral: Deal with object collaboration and responsibilities.


## Architectural Patterns
These patterns provide a structure for the major parts of software systems. They define a pattern for the architecture of a system. Examples include:

- MVC (Model-View-Controller)
- Layered Architecture
- Microservices
- Event-Driven Architecture
- Monolithic Architecture
- Serverless Architecture
- Peer-to-Peer Architecture
- Hexagonal (or Ports and Adapters)


## Concurrency Patterns
Address multi-threading and parallel computing problems. Examples include:

- Lock
- Monitor
- Active Object
- Scheduler
- Double-Checked Locking
- Producer/Consumer


## Enterprise Patterns
These patterns are used to identify and specify abstractions of common enterprise-level solutions. Martin Fowler's book "Patterns of Enterprise Application Architecture" is a great resource on this. Examples include:

- Unit of Work
- Repository
- Data Mapper
- Service Layer
- Domain Model


## Integration Patterns
Deal with the communication between different systems. Gregor Hohpe and Bobby Woolf's book "Enterprise Integration Patterns" covers this extensively. Examples include:

- Message Channel
- Message Translator
- Message Endpoint
- Publish/Subscribe
- Request-Reply


## Presentation Patterns
Focus on handling user interfaces and their interactions. Examples include:

- Model-View-Presenter (MVP)
- Model-View-ViewModel (MVVM)
- Composite View


## Idioms
These are low-level, language-specific patterns. They aren't universally applicable across different programming languages, but rather are particular to specific ones.


## Anti-Patterns
These describe common pitfalls in software development. They are the "what not to do" of software patterns, highlighting bad practices and their solutions. Examples include:

- Singleton Abuse
- Golden Hammer
- Cargo Cult Programming