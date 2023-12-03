## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
    - Software development that permits the reusability of services is known as service-oriented architecture, or SOA. More applications of SOA include applications that require services from other active services, and these services will interact with one another to function as a team. A method known as "loose coupling" is used to remove dependencies between components in a system or network so that they can communicate with one another and handle business operations.

2. List and discuss the characteristics of SOA.
    - Standardized Service Contracts - takes guarantee that contracts in a service inventory are uniform and clearly state their capabilities and goals.

    •Loose Coupling - Given the elimination of component dependencies, the client application shouldn't be severely impacted or crash as a result of a service functionality failure.

    •Interoperability - As I understand this principle, it establishes guidelines for services, guarantees their usability for subscribers, and upholds interoperability for effective data exchange. It adheres to standards that let different clients or customers make use of the service.

    •Abstraction - In here from what I understand, for the protection of the client, the customer, and the business, the workings of the service should remain hidden from the public. Allows for the introduction of agility, the breaking of dependencies, and the definition of technology within a business process.

    •Autonomy - For runtime execution, services have extensive control over their underlying environment. Allows consumers the flexibility and control to make decisions without seeking approval or involvement.

    •Discoverability - Services are added by leveraging communicative meta-information that can be found and translated successfully.

    •Reusability - This is a method of reducing duplication and waste by utilizing current services whenever possible or developing new services that can serve many functions.

    •Statelessness - Based on my understanding, the client application should be in charge of ensuring that data is not retained between states in this situation.

3. Define Microservices.
    - Like SOA, microservices are used to develop separate applications in a way that improves robustness and scalability. It is made up of tiny, separate parts that, when put together, form larger applications that put services together and treat the whole thing as a whole.

4. List and discuss the benefits of using Microservices.
    - Improved productivity - When a program is separated into smaller, independent sections, it is easier to build and maintain.

    •Increased scalability - Services can also be distributed over multiple servers, reducing the impact of more demanding components on performance.

    •Right Tool for the Job - Microservices enable flexibility by allowing each service to use its own language and framework, which simplifies communication with the chosen application.

5. List and discuss the similarities and differences of SOA and Microservices.
    - Similarities:

    •Both emphasize the importance of checking for existing services before developing new ones, whereas microservices emphasize code reuse through copying and accepting data duplication.

    •Communication - SOA relies on an ESB (Enterprise Service Bus) and can become a single point of failure, whereas microservices use independent communication protocols and simpler messaging methods such as APIs.

    •Interoperability - SOA defines service standards, whereas microservices facilitate the sharing and usage of information across systems.

    •Speed - Although SOA facilitates development and troubleshooting, it may be slower than microservices. Microservices enable the rapid deployment and testing of discrete application components without disrupting the overall program.

6. Define Web Services.
    - It is a web services that the class of internet software are made available for use by clients or other web-based programs from the web server of an application service provider.

7. List and discuss the benefits of using Web Services.
    - The benefits of using web services it decreased time needed to integrate apps and it leads to increased efficiency. The capacity to create new application far more quickly than in the past.

8. List and discuss the characteristics of Web Services.
    - The modularity of web services, as I understand it is calling lower-layer web services from a web service implementation or by employing workflow techniques, simple web services can be combined to form a more complex ones. 
    - Web services can be connected to each other to carry out more complex in business tasks. This allows for implementations and reduces development time.

9. List and discuss the distinct roles in Web Services Architecture.
    - There are three roles in architecture of a web service: Service provider, service requester, and the service registry.

    - The service provider as I understand this is the services that are hosted by the platform. It produces a web service and makes it accessible to client applications.

    - The service requester this is a program the one searching for, calling upon, or starting a conversation with a service.

    - The service registry it is a services that are being developed, service requestors locate the service and acquire binding information.
    
10. List and discuss the Web Services Components.
    Uses of web services:
    - it is reachable by all users via the internet. While there are many uses for web services, code reuse and program connectivity are the most popular uses. Web services can be used to link data between different platforms. Developers can use this technique to break down applications into components that can be reused and used for different purposes.
