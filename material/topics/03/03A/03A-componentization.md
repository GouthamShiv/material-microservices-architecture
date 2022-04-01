> # <mark>`Microservices Architecture`</mark>

# Microservices Architecture

> 1.  ### Componentization via services

-   Modular design is always a good idea
-   Components are the parts that together compose the software
-   Modularity can be achieved using:
    1.  `Libraries:`
        -   External code files that are called directly within the process,
            usually after declaring them using the keywords such as `import, require or using`.
        -   The libraries are executed within our systems process, share the same compute resources.
        -   They do not need any kind of mediation, such as `serializer or network` in order to be used.
        -   One of the benefits of using libraries is great performance.
    1.  `Services:`
        -   These are out of process components and are called using out-of-process mechanisms such as `Web API, RPC`.
        -   Modern systems mainly use modern Web APIs such as `REST`.
-   In Microservices, we prefer to implement the modular design using services (not libraries) for the componentization.
-   The componentization, which is a process of separating the software into different components, thus making it modular
    is preferably done using services and not libraries.
-   Libraries can and should be used inside the services, but in this case, they are part of the service and do not represent the whole componentization of the software, just the service itself.
