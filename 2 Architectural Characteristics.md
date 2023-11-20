### Drive out which architectural characteristics would apply and why. (Justify).

**Architectural Characteristics:**

1. Decomposition into Services (Microservices Architecture)

  Justification: 
  Based on the monolithic nature of the current system, decomposing it into microservices will address the need for independent scaling,
  ease of updating individual components, and reducing the blast radius of changes. This aligns with the requirements for accurate and
  dynamic ticket assignment and the need for continuous expansion to handle increased traffic.

2. Resilience and Fault Tolerance
   
  Justification: 
  Considering the high risk of ticket routing failure and the critical nature of immediate routing, the system should be 
  designed to be resilient with fallback mechanisms such as retry logic or circuit breakers, ensuring high availability and reliability.

3. Data Security and Compliance
   
  Justification: 
  Protecting sensitive customer data is a non-negotiable requirement. The architecture must include secure data handling,
  encryption, and compliance with data protection regulations.

4. Continuous Integration/Continuous Deployment (CI/CD)

  Justification: Due to the complexity and frequency of changes in the ticket assignment algorithm, a CI/CD pipeline will allow for faster, 
  safer deployments, and quicker rollback if needed.

5. User Experience Design

  Justification: With the assumption that customers are comfortable using the internet to submit tickets, the system must provide an intuitive
  user interface that is easy to navigate and reliable, ensuring customer satisfaction.

6. Backup and Recovery

  Justification: Given the importance of ticket integrity and the non-functional requirement to ensure processing integrity, the architecture
  must include robust backup and recovery solutions.

7. Automated Billing System

  Justification: The system must have an automated billing mechanism that securely handles transactions and can scale to process an increasing
  number of payments as the customer base grows.

8. Scalability

  Justification: With an expected increase in website traffic and system load, the architecture must support both horizontal and vertical scaling
  strategies to handle load increases without service degradation.

9. Real-time Data Processing and Monitoring

  Justification: Real-time processing is required for immediate ticket assignment and routing. Monitoring is crucial for maintaining system stability
  and identifying errors, as outlined in the non-functional requirements.

10. Data Analytics and Knowledge Management

  Justification: To improve service and the knowledge database's utility, data analytics can provide insights into common issues and solutions, while
  knowledge management can facilitate information sharing among repair experts.
