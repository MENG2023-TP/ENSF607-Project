###Functional Requirements

1. Administrators can add and manage repair experts to the system.
2. Customers can sign up for support services.
3. Customers can submit and manage problem tickets through the Best Appliance website.
4. Customers are notified by email or SMS when a repair expert is on their way.
5. Customers can complete satisfaction surveys.
6. The system automatically bills the customer’s credit card on an annual basis.
7. The system automatically assigns the best suited repair expert.
8. The system automatically emails a survey link to customers when their ticket is completed.
9. Repair experts are notified by SMS when they have been assigned to a new ticket.
10. Repair experts can retrieve and update the ticket information they are assigned to using their phone.
11. Repair experts can access and update the knowledge database using their phone.

Assumptions:

- The administrator verifies the credential of each repair expert.
- The Best Appliance website is intuitive, and customers are comfortable using the internet to submit problem tickets.
- Customers and repair experts keep their information up to date.
- The repair experts will find the knowledge database useful and will actively contribute to it.
- Customers like to provide feedback after their service.

###Non-Functional Requirements

1. The ticket assignment algorithm must accurately and dynamically match problem tickets with the appropriate repair expert.
2. The system must seamlessly and quickly integrate with constant changes in the ticket assignment algorithm without affecting other parts of the system.
3. The system must immediately route assigned tickets to repair experts.
4. The system must immediately handle ticket routing failures by reassigning the ticket to a new expert until the routing is successful.
5. The system must keep track of each ticket status until completion and have a backup mechanism to ensure ticket processing integrity.
6. The system must incorporate real-time monitoring for stability and errors, and scheduled maintenance to ensure operational reliability.
7. The Best Appliance website must always be running and accessible to customers.
8. The system's resources must be capable of continious expansion to match the expected increase in website traffic.
9. The system must protect sensitive customer data like name, address, and credit card information.

Assumptions:

- The automatic ticket assignment is a highly complex task and because of that, it relies on algorithms that change frequently to fine-tune the process. 
- The immediate routing of assigned tickets is a priority to provide the best customer service.
- The risk of ticket routing failure is high.
- Keeping track of the ticket’s status and implementing backup mechanisms prevent ticket loss.
