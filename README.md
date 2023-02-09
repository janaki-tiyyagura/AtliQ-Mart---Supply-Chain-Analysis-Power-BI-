
# AtliQ Mart - Supply Chain Analysis

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

Get the datasets here: https://codebasics.io/event/sectionMedia/971

## Task
Peter Pandey is the data analyst in the supply chain team who joined AtliQ Mart recently. He has been briefed about the the task in the stakeholder business review meeting. Now imagine yourself as Peter Pandey and play the role of the new data analyst who is excited to build this dashboard and perform the following task:
* Create the metrics according to the metrics list.
* Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in comic form.
* Create relevant insights not provided in the metric list/stakeholder meeting.


## Business Knowledge | Supply Chain
### Orders and Lines: 
* Orders are nothing but a unique request placed by a customer on a given date.
* Within an order, a customer could request multiple items. Each of these items requested within the order is called an order line.
Example: Let's say you order 4 notebooks and 2 pens at Amazon. A unique order ID is
generated for all these items. Notebook and Pen is an order line.

### Measuring Line Fill Rate & Volume Fill Rate: 
* Line Fill Rate is an important metric for the supply planning team to understand how many lines they shipped out of the total lines ordered. This metric does not consider the delivery time of the order.
* Volume fill rate or case fill rate is a similar metric useful for the supply planning team to understand the total quantity they are able to ship for a customer per order or for a given period of time.
Example: In above example let's say Amazon is able to ship you 4 notebooks and 1 pen. 

The line item pen is failed because you requested 2 nos. So Line Fill Rate for Amazon for your order is order lines fulfilled / lines ordered => 1/2 => 50 %. Volume Fill rate will be total quantity shipped / total quantity ordered => 5/6 => 83 %.

### Measuring On Time delivery %:
* Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered as per the agreed time with the customer.
* This metric is important for the warehouse & distribution team.
* An order is On Time only when all the line items inside the order is delivered on time.

### Measuring In Full delivery %:
* Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered in full as per the requested quantity by the customer.
* This metric is important for the supply planning team.
* An order is In Full only when all the line items inside the order are delivered In Full.

### Measuring On Time In Full (OTIF) %:
* Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered BOTH in full and On Time as per the customer order request.
* This metric is important for all the sub functions in the supply chain team.
* An order is OTIF only when all the line items inside the order are delivered In Full and ON Time. This is a hard metric which measures the reliability of an order from customer's point of view.


## Data Model

![datamodel](https://user-images.githubusercontent.com/98509940/217880436-c3ba0d4f-4b9a-4c89-9d28-db333bbad68e.PNG)


## Dashboard

![dashboard-1](https://user-images.githubusercontent.com/98509940/217882045-a609b67a-6306-487b-a160-3e8ab2797441.png)
![dashboard-2](https://user-images.githubusercontent.com/98509940/217882060-ca33f06f-37e9-407a-a31c-bdd89d4bf02d.png)




