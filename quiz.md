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
   Exposing the existing function on the network
        - it is a web service that managed code that can be remotely invoked using HTTP.
   Interoperability
        - It is the web services allowing various applications to talk to each other and sharing data among themselves.
   Stardardized Protocol
        - It is use for standardized industry-standard protocol for communications.
   Low Cost Communication
        - It is a web services use for SOAP over HTTP protocol, so we can use our existing  low-cost internet for implementing web services.
   
8. List and discuss the characteristics of Web Services.
   XML-Based
       - It is a web services use for XML at data representation and data transportation layers.
   Loosely Coupled
       - It is a web service is not tied to that web service directly.
   Coarse-Grained
       - It is an invdividual method to find an operation to provide any useful capability at a corporate level.
   Ability to be Synchronous or Asynchronous
       - It is synchronicity refers to the binding of the client to the execution of the service.
    Supports Remote Procedure Calls
       - It allows clients to invoke procedures, functions, and methods on remote objects using and XML-based protocol.

9. List and discuss the distinct roles in Web Services Architecture.
    - There are three roles in architecture of a web service: Service provider, service requester, and the service registry.

    - The service provider as I understand this is the services that are hosted by the platform. It produces a web service and makes it accessible to client applications.

    - The service requester this is a program the one searching for, calling upon, or starting a conversation with a service.

    - The service registry it is a services that are being developed, service requestors locate the service and acquire binding information.
    
10. List and discuss the Web Services Components.
    SOAP
        - It is a communication protocol that communicates between applications. It is also a platform and language independent.
    WSDL
        - It is an XML-based language for describing web services and how to access them. It is used for describing the web services and the process of accessing them.
    UDDI
        - It is also an XML-based standard for describing, publising, and finding web services. It is an open framework and platform-independent.
    
