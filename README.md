# template-application-lifecycle
project will serve as template and documentation on the lifecycle of application from creating requirement to deploying to each environment. With recommendations of technologies to use

# Application Requirements

1.    **Documenation** (Attlasian Confluence): will offer more high level documenation on application. Remember application may have many different repositoris to make up the entire application so having a single space for more high level documentation is key 
2.    **Task Management** (Attlasian JIRA): assigned unit of work represented in a ticket that will track state is in work flow (eg To-Do, In-Progress, Code Complete, Verification, Done). Each ticket will be attached to a feature,bug,etc being worked on. 
3.    **Version Control System & Repository** (Git & GitHub): along with storing code on repository, will help segment out changes of code base as to allow for different version that can be decided to be deployed to different environments.   
4.    **Continous Integration** (Jenkins): scripts out different actions to automate workflows within the deployment process
5.    **Container** (Docker): will bundle up all the system requirements for application, so can easily install and run application on different computers
6 .   **Container Orchestration** (Kubernetes): will hand lifecycle, management, and deployment of manh containers. In microservices, will need to deploy multiple instances our appications in order to scale and handle load

# Technologies
1.    **Database** (Postgres): will allow to store and query data efficently and scalably. Will store the core application data
2.    **Cache** (Redis or Memcached): simple scalable key value store largely. Highly helpful in caching webapi results
3.    **Message Broker** (RabbitMQ): will store messages that other apps can use to act on. Useful to make database etls event based
