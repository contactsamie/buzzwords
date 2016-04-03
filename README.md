# buzzwords
buzz....

API
REST
The Richardson Maturity Model Level 0 (one url for all, details of exec is in message body, aka swamp of pox [plain old xml]. no use of http construct)
The Richardson Maturity Model Level 1 (different uri for different types of resource. details still contain how exec will happen)
The Richardson Maturity Model Level 2 (http methods are used, as well as http status codes etc)
The Richardson Maturity Model Level 3 (HATEOAS)
HATEOAS


typical webapp concerns = Consistency + Concurrency + Synchronous Queries + Data Entry + Asynchronous Notification

At most once delivery (which is default for most actor frameworks) 
at least once delivery (which is available using akka persistence)

Indempotent
Immutable
