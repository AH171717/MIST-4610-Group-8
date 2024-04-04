
# Team Name:
21482 Group 8
# Team Members:
1. Matteo Garza
2. Andrew Hayes
3. Collin Ladina
4. Abe Michael
# Problem Description:
The primary objective of this project is to design and develop a comprehensive relational database to underpin the operations of our micro-loan provision service. To achieve our mission of financial inclusion, our database must efficiently manage loan application processing, customer information, loan disbursement, and payment tracking. It will also support our risk assessment models and manage user accounts for customers while having assigned employees to help manage the accounts, ensuring the secure handling of financial transactions.
# Data Model 

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/128336029/660149f2-a4b0-4f5e-b85f-23ed492ca786)



# Data Dictionary 
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/742cbf36-f9aa-4cf6-b4df-2b10b25650db)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/4d7b1603-c33b-4790-b12c-b628477b67e1)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/ef8c9820-beea-4000-8daa-a8d22fb844e6)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/c1e81154-1fc8-4359-af8a-8d94fcbd254b)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/0f80763f-77aa-424a-806b-0570a5fe44e5)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/1f87cab5-44f9-4559-b888-cadafa7d92f0)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/a82883a0-2a17-4375-ade6-728063e74694)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/9e933aee-8c99-4552-93db-49842ff559df)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/edbea620-00e8-4bf0-9943-518fbdcf7c69)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/1c9d70c6-25a7-45b3-923b-7711bd994045)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/420529fe-e3ce-4709-95ce-40df43f55589)
![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/e91b9962-393d-45c2-af0e-b68b44a16ba3)

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/e4bd0ade-6042-47a5-a8e3-14eded50fda6)
Description: This query identifies customers who have raised support tickets
Justification: Managers can use this query to monitor customer satisfaction and identify areas for service improvement. It helps in addressing customer inquiries promptly and enhancing overall customer experience.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/3335ddf8-3504-4bfa-9693-1754ac36e81f)
Description: This query identifies customers with high-risk assessment scores.
Justification: Managers can use this query to proactively manage credit risk and apply appropriate risk mitigation measures. It helps in preventing potential defaults and preserving the financial health of the company.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/5b801d00-c2e7-4d3a-9c0e-40be20b964cd)
Description: This query identifies the employees with the most approved loan applications.
Justification: Managers can use this query to recognize top-performing employees in loan approval processes. It helps in incentivizing high productivity and identifying best practices to improve overall efficiency.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/5b08c3b3-6f2b-47cb-847a-1869edc7c260)
Description: This query calculates the average payment amount made by each customer. It uses the Payment table and calculates the average amount for each customer.
Justification: Managers can use this query to assess the payment behavior of individual customers. It helps in identifying customers who consistently make larger or smaller payments, which can inform decision-making regarding credit limits, loan approvals, or targeted marketing strategies.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/b89b2473-5c23-49b9-a45f-5aae2662e86e)
Description: This query calculates the percentage of customers who raised support ticket requests assigned to each employee. It involves joining the Employee and SupportTicket tables to determine the count of distinct customers for each employee and calculates the percentage of customers who raised a support ticket regarding their EmployeeID. 
Justification: Managers can use this query to evaluate the effectiveness of employees in handling customer support issues. It helps in identifying employees who receive a high volume of support tickets, indicating potential areas for additional training or support.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/aef6cac2-7bbf-4042-a6c8-851e15528212)
Description: This query calculates the average time taken by each employee to approve loans.
Justification: Managers can use this query to evaluate the efficiency of employees in processing loan applications. It helps in identifying bottlenecks, optimizing workflows, and improving overall operational efficiency.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/b0ee2457-0fdc-4cfb-9c68-21302c4b23bd)
Description: This query counts the number of active loans with due dates in the future.
Justification: Managers can use this query to monitor the current loan portfolio and assess the company's exposure to credit risk. It helps in ensuring that loan repayments are on track and managing liquidity effectively.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/bb3283ab-ed49-47c4-abcf-16fe9e9c15a6)
Description: This query counts the number of loan applications that are pending approval.
Justification: Managers can use this query to track the workload of loan approvers and assess the efficiency of the approval process. It helps in ensuring timely processing of applications and maintaining high levels of customer satisfaction.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/7f5dcdf0-ea6d-49f1-96bf-f0686a706a6a)
Description: This query calculates the average payment amount for each payment method used by customers.
Justification: Managers can use this query to analyze payment trends across different methods. It provides insights into customer preferences and can inform decisions regarding payment processing optimization and service enhancements.

![image](https://github.com/AH171717/MIST-4610-Group-8/assets/163201574/02f429c9-dd96-4146-91be-1bce4fc32605)
Description: This query identifies the top  customers with the highest total loan amounts.
Justification: Managers can use this query to identify high-value customers who contribute significantly to the loan portfolio. It helps in prioritizing customer relationship management efforts and offering tailored financial solutions to meet their needs.

