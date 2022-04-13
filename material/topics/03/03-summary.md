> # <mark>`Microservices Architecture`</mark>

# Microservices Architecture - Summary

`Some things to note`

-   These 9 characteristics are guidelines and not mandatory instructions.
-   They should not be followed blindly everything that is described here.
-   Rather, take a close look at each and every attribute and adopt only what works for you.
-   Some attributes might not be relevant and it's completely legitimate to decide not to follow them.
-   Microservices world is rapidly changing and the concepts that were thought two years ago are not considered obsolete today.
    -   So, it important to follow new APIs, new monitoring tools, new cloud services and more.
    -   In fact, even in this section, we discussed some attributes that shouldn't be followed blindly and are replaced by newer, better ones.
        -   We said that about APIs, where REST are not the only option nowadays.
        -   Also the communication patterns between the services, for which we concluded that there are better options than direct communication between services.

## Most Important Characteristics

1.  `Componentization`
    -   You should try as much as possible to make your components services.
    -   The modularity of your system should be done using out of process components also known as services.
    -   The ease of deployment and maintenance of the system that its components are out of process services is really unmatched.
1.  `Organized around business capabilities`
    -   The importance of this attribute is that it forces the team, including you, the architect to think long and hard about the boundaries of the service.
    -   With microservice we can't just say 'Let's begin with a small API and see where it goes'. We can't change the API at will because it will make other services work with it incompatible and will make a lot of other team rework.
    -   By designing a well bounded service we make the system more modular, the service more independent of other services and our maintenance much easier.
1.  `Decentralized governance`
    -   This is one of the most popular attributes because it lets the teams to use the technology best suited of the services needs.
    -   No more do we have a service handling document with slow and incompatible relational database.
    -   And, no more we need to use slow and legacy technology when what we really need is a lite and fast one.
    -   By implementing this attribute, the teams can really use the best tools for the task and that will make the team satisfied, and as a result, the other services and the end users too.
1.  `Decentralized data management (when possible)`
    -   Decentralized data management is also one of the most important attributes.
    -   True, that there were some reservations about it and it's still the most controversial attribute, but still when possible it's definitely a great idea to use a separate database for each service.
    -   It makes the service more autonomous and less dependant on other external mechanisms.
1.  `Infrastructure automation`
    -   This is definitely something that you shouldn't compromise on.
    -   Building a microservices architecture without automation in place will probably result in a system slow to test and deploy. And the client will start to question the effectiveness of it all.
    -   So, before embarking on microservices journey, talk to the IT and Dev guys to make sure automation tools are part of the plan.

---

[PREV](./03I/03I-evolutionary-design.md) <span style="margin-left:85vw"></span> [NEXT](./03-summary.md)
