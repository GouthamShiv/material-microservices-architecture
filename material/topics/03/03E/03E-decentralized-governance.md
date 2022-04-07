> # <mark>`Microservices Architecture`</mark>

# Microservices Architecture

> 5.  ### Decentralized governance

-   `In traditional projects there is a standard for almost anything:`
    -   Which dev platform to use.
    -   Which database to use.
    -   How logs are created.
-   `There is no place for various teams to make decisions.`
-   `With microservices each take makes its own decisions:`
    -   Which dev platform to use.
    -   Which database to use.
    -   How logs are created.
    -   The team has authority to make its own decisions and implement them in the services.
    -   Each team is fully responsible for the service it developes.
    -   Service is something the team works on together and tries to make it the best possible.
    -   Since the team is united around the services success, it will make the optimal decision for it, mainly technological decisions.
        -   Sometimes that means it's better to use NoSQL database instead of the more traditional relational database.
        -   And sometimes it means it's better to use NodeJS instead of Java.
            What ever the case is, this independence is always a good idea in the microservice world.
        -   What's even better is that, this independence is enabled by the loosely coupled nature of the microservices.
        -   Where in, with monolith, changing the underlying development platform of a component, which is a library in the case of monolith,
            will immediately affect the rest of the monolith and all the other components libraries have to align themselves to the new platform.
        -   This is not the case with microservices. Since microservices are loosely coupled by definition, a change in one of them will have exactly zero effect on the other services. In fact, the other teams will probable not even know something has changed. This is a great advantage of this architecture style.
    -   Using multiple development platform in one system is called `polyglot`.

> **Motivation:**

-   `Technological decisions:`
    -   By employing decentralized governance, we enable the team to make the optimal technological decisions for the specific service.
    -   Since these decisions can't fit an scenario, it's great that specific technology can be used for specific service, thus making it more efficient and develop quickly.

---

[PREV](../03D/03D-smart-endpoints-and-dump-pipes.md) <span style="margin-left:85vw"></span> [NEXT](../03F/03F-decentralized-data-management.md)
