## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service-Oriented Architecture, or SOA, structures software as a set of services. It contains units of functionality that perform tasks that can be accessed by other software components. SOA's goal is to promote sustainability and flexibility in software development.

2. List and discuss the characteristics of SOA.
- Reusability: One good thing about SOA is that it's reusable in other applications to reduce effort and be more efficient.

  Services:A self-contained functional unit is called a service in SOA. It is an independent task that can be called upon. Because of their modular design, services can be combined to create applications with greater complexity. 

  Discoverability:In SOA, a service registry or directory with a list and description of services is frequently used. This facilitates the process for developers to find and comprehend pre-existing services that are suitable for reuse.

  Standardized Communication: SOA uses a standard communication protocol to enable easier communication between services.

3. Define Microservices.
- Another one of the architectural styles is microservices, it also structures an application as a collection of small, independent deployable services that are focused on a specific business capability. In a microservices architecture, the application consists of loosely coupled services that communicate with each other through well-defined APIs.

4. List and discuss the benefits of using Microservices.
The following are the benefits of using microservices:

1.Modularity and Scalability- By separating an application into smaller, independent modules, microservices facilitate the scalability of individual services in response to demand. Teams can scale and implement particular services independently of one another due to this modular structure, which results in more effective resource use.

2.Independent development and deployment- Individual services can be created and used independently through the use of microservices. This means that teams can work on multiple services at once, release updates to particular services without impacting the application as a whole, and deploy changes without causing system-wide disruptions.

3. Technology Diversity- Programming languages and technologies can be used differently for different services because of microservices. Teams can choose the best tools for the unique needs of each service because of to this flexibility, which could speed up development and enhance system performance as a whole.

4. Improved Development Speed- Teams may collaborate on multiple services simultaneously because of microservices' independent nature, which speeds up the development process. Teams are able to react to shifting business requirements more quickly by releasing features and updates more quickly.


5. List and discuss the similarities and differences of SOA and Microservices.

Similarities

Service Based: Software is divided into services that each offer a particular set of business functionalities in service-based architectures, such as SOA and Microservices.

Interoperability:The goal of microservices and SOA is interoperability amongst services. To facilitate smooth communication and collaboration among services, they often use common communication protocols.

Modularity: Both architectures place an enormous value on modularity, which splits a system into more manageable, smaller parts. Software development, testing, and maintenance are made easier through this modularity.

Differences
- In data management SOA is a centralized data model that is capable for sharing a database, while microservices is decentralized and have their own database.

- In communication protocols, SOA uses a standard communication protocol like the simple object access protocol. While microservices use light-weight communication protocols like representational state transfer for efficiency,

- In development teams, SOA doesn't prescribe the size or structure of development teams. While microservices are associated with smaller, cross-functional teams that are responsible for developing and maintaining a specific microservice,
