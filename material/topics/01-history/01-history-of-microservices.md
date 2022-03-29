# `Microservices Architecture`

# History of Microservices

`Microservices are a result of problems with two architecture paradigms:`

-   **Monolith**
-   **SOA**

> ## Monolith Architecture

-   The original architecture, the ancestor of all the other architectures we have today.
-   There are a lot of applications that are still in monolith architecture.
    -   This is not a bad thing, because some scenarios are best suited for monolith architecture.
-   All software components are executed in a single process.
    -   All the components share the same memory, compute power and no distribution of any kind.
-   Strong coupling between all classes
    -   The code pieces being tightly coupled, there is nothing that separates them from one another.
-   Usually implemented as Silo
    -   It's a standalone application, that does not share anything with other applications [data, functionality or API].
-   Example:

    -   `HR App`

        ![HR App Monolith](./img/hr-app-monolith.svg)

    -   Here, the HR app is a single process, comprising of all the components of the application.
    -   Thus making the app a monolith without any distribution.
    -   A monolith application may not always have one and only one process. Quite often they have a database, which is usually another process unless it's a in-memory database.
    -   And, in cases of web-applications, the user interface is also usually running on a separate machine, that has separate process.
    -   Yet, this is called a monolith as the core of the application involved is a single process.
    -   Consider a similar monolith called **Purchasing App** that has to be integrated with **HR App**

        -   Unfortunately, this is not possible because monoliths are often silos and do not expose ways to share data and functionality (Could be achieved, but not an easy process)

        ![Integrating Monoliths](./img/purchase-app-monolith.svg)

> ## Monolith Architecture Pros

-   Easier to design
    -   No network-hops, messaging mechanisms / queues, no cross-process dividing
-   Performance
    -   No network-hops, no serialization & de-serialization layers
