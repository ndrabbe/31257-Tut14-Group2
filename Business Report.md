#### Students Contributing to this report
1. Nathan
2. Ayush 
3. Nafisul 
4.Jianmu Huang
### Assumptions

- We will have to assume what the criteria is for likelihood on a person buying the product. (e.g. purchase history) 
- Is the profiler tool an assumption? 
- Employees answer their questionnaire truthfully
- Company have a high-end computer to ensure the normal operation of the system during peak hours
- The system has a secure firewall to ensure the safety of customer and employee information.
- CMC's skill score scoring standard should also refer to RM's purchase desire of customers to score. For example: if some customers have a short phone call for consultation, but they have a desire to buy.


###Define the problem: 

The main problem is that this large travel company needs to develop an information system to improve the operation of its internal call management center (CMC). The new system will allow end customers to be well matched with well-informed account managers with appropriate knowledge about the destination and its traditions. In addition, RM's personal files and skill matrix are obtained and entered into the system through a 10-minute questionnaire survey by employees. On the other hand, when the system uses outgoing calls to target potential buyers, the system will automatically dial the number based on the customer target list generated by the system. For inbound calls, CMC has its own dedicated automatic branch exchange to route calls. In this regard, the new system will be able to evaluate the customer's skill scores to achieve the highest score will get the inbound call service first. The skill score is calculated based on the call duration and personal data before RM. Finally, the new system will be able to direct inbound customers to interactive voice response units during peak hours.

##### User 

People who are interested on travelling and want to use ‘major travel company’. 

##### Need 

To find out about the different holiday packages on offer for their destination 

##### Insight 

It is hard to know where to go and what to do in destinations you have not been before. 


### Stakeholders

- Relationship Managers 
- Customers 
- Developers of the system 

### Objectives of the system

- The system will adjust the call flow rate to suitable Relationship Managers (RM) 
- To provide improved call routing and dynamic call flow control for both inbound and outbound calls 
- To improve the call flow rate is to match customers based on RM performance and product knowledge 
- Matching end-customers to well informed RMs with appropriate knowledge about the destination and its traditions 
- Be able to use the customer profiles created from the Profiler Tool ( looks at age, sex, culture, language proficiency, experience and product knowledge) to match users with appropriate RM, to improve sales. 
- The system will adjust the RMs profile according to subsequent performance in selling packages and in serving customers effectively and efficiently. 
- With outbound calls, the system dials numbers automatically according to a customer target list generated by the system 
- The system retrieves customers details from a database. It then displays the details and provides the RM with guidelines and a script to help in providing an improved service 
- The system will create a target list for each RM based on their skills and profile. A target list is a list of tuples in the format <potential customer, product proposed> 
- A skill score is calculated based on the RM’s previous call duration and profile. (do they mean customer here?) 
- A score from 1-10 based on the likelihood to purchase the product is given to a customer according to some preloaded criteria 
- During busy times, inbound customers can be directed to an Interactive Voice Response (IVP)
- The IVP will prompt users for options, and may even ask for call reasons in a few words and then redirect the call to an Automatic Call Distributor routing the call to the first available appropriate RM. 

### Analysis and design

By reading the text, we can understand the emotions and beliefs of a major travel company. The company hopes to develop an information system to improve the operation of its internal call management center (CMC). The company hopes that the new system will adjust the call flow rate to the appropriate customer relationship manager (RM). In this way, accurate and efficient service can be achieved to match the information between the RM and the customer so that the customer can successfully purchase the travel package. In contrast, the company now does not have this new system so that the information between RM and customers can not be similarly matched, resulting in less sales of travel packages. Customers can not truly understand the true response of the content of the travel package area they want to purchase. RM can not provide timely and true feedback to customers regarding the content of travel packages. It can also be seen from the article that in the traditional system, CMC does not give customers priority call distribution services based on skill scores. On the other hand, the company's old system also did not include directing inbound customers to the interactive voice response unit when it encountered a busy period. This will enable the customer to have a response when making a call and wait, so that the customer will not feeling of being unable to make a call all the time. As a result, customers give up calling the company's sales hotline.