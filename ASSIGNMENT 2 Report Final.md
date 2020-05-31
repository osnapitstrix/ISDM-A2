# 31257 Information Systems Development Methodologies
## Assignment 2: Group Project Report
##### Date: 2 June 2020

Student Name|Student ID |
------------|---------- |
Amna Abbasi |13227297|
Patricia Ann Acosta | 13205669|
Areeba Khan | 13268608 |
Ishita Verghese|13209921 |

## Table of Contents
- [SECTION 1. Project Definition and Project Objectives](#section-1-project-definition-and-project-objectives)
- [SECTION 2: Stakeholders](#section-2-stakeholders)
- [SECTION 3: Approach from a Design Thinking Perspective](#section-3-approach-from-a-design-thinking-perspective)
	- [STEP 1.Empathise](#step-1empathise)
	- [STEP 2.Define](#step-2define)
	- [STEP 3. Ideate](#step-3-ideate)
		- [3.1.1 Stakeholder 1: Customer Empathy Diagram](#311-stakeholder-1-customer-empathy-diagram)
		- [3.1.2 Stakeholder 1: Customer How Might We Statement](#312-stakeholder-1-customer-how-might-we-statement)
		- [3.2.1 Stakeholder 2: Relationship Manager Empathy Diagram](#321-stakeholder-2-relationship-manager-empathy-diagram)
		- [3.2.2 Stakeholder 2: Relationship Manager How Might We Statement](#322-stakeholder-2-relationship-manager-how-might-we-statement)
		- [3.3.1 Stakeholder 3: Travel Company Owner Empathy Diagram](#331-stakeholder-3-travel-company-owner-empathy-diagram)
		- [3.3.2 Stakeholder 3: Travel Company Owner How Might We Statement](#332-stakeholder-3-travel-company-owner-how-might-we-statement)
	- [STEP 4. Prototype](#step-4-prototype)
	- [STEP 5. Testing](#step-5-testing)
	- [3.1 Reflections](#31-reflections)
- [SECTION 4. Agile Methodology: Scrum](#section-4-agile-methodology-scrum)
	- [STEP 1: CREATE SCRUM ARTIFACT 1: PRIORTISED PRODUCT/PROJECT BACKLOG](#step-1-create-scrum-artifact-1-priortised-productproject-backlog)
		- [4.1.1  Stakeholder 1: Customer Product Backlog](#411--stakeholder-1-customer-product-backlog)
		- [4.1.2 Stakeholder 2: Relationship Manager Product Backlog](#412-stakeholder-2-relationship-manager-product-backlog)
		- [4.1.3 Travel Company Owner Product Backlog](#413-travel-company-owner-product-backlog)
	- [STEP 2:  SPRINT PLANNING AND CREATING SCRUM ARTIFACT 2: SPRINT BACKLOG](#step-2--sprint-planning-and-creating-scrum-artifact-2-sprint-backlog)
		- [SPRINT 1 BACKLOG:](#sprint-1-backlog)
		- [SPRINT 2 BACKLOG:](#sprint-2-backlog)
	- [STEP 3: SCRUM MEETINGS](#step-3-scrum-meetings)
	- [STEP 4: SPRINT REVIEW and SPRINT RETROSPECTIVE](#step-4-sprint-review-and-sprint-retrospective)
- [SECTION 5: System Analysis Assumptions](#section-5-system-analysis-assumptions)
	- [5.1 Assumptions about the Current System:](#51-assumptions-about-the-current-system)
	- [5.2 Assumptions about the Enhanced System:](#52-assumptions-about-the-enhanced-system)
- [SECTION 6: Proposed Workproducts and Models](#section-6-proposed-workproducts-and-models)
	- [6.1 Use Case Diagram](#61-use-case-diagram)
	- [6.2 Activity Diagram](#62-activity-diagram)
	- [6.3 Class Diagram](#63-class-diagram)
	- [6.4 Collaborative Diagram](#64-collaborative-diagram)
		- [6.4.1 Outbound Call](#641-outbound-call)
		- [6.4.2 Inbound Call](#642-inbound-call)
- [SECTION 7: Competitive Advantages and Adverse Effects to Business if Project Fails](#section-7-competitive-advantages-and-adverse-effects-to-business-if-project-fails)


## SECTION 1. Project Definition and Project Objectives

The project involves developing an information system to improve the operations of a major travel company's Call Management Centre (CMC). At current state there, the lack of an information system means that a lot of the functions are done manually and at an ad-hoc pace affecting the call flow rate. 

This proposal will uncover how an improved call routing and dynamic call flow system can better be used to achieve CMC's business goals by streamlining business processes to increase overall efficiency. The report will examine the five phases of design thinking principles to develop and test the system, the illustration of agile methodology and the assumptions required to develop the system prototype. Furthermore, a critical evaluation will be completed to provide a comparison highlighting competitive advantages that will accompany the implementation of the new information system. 

The main project objective is to create an information system that meets the following criteria: 
* improves the operations of the in-house call management centre
* has the capability to adjust the call flow rate to suitable relationship managers (RM)
* improves call routing and dynamic flow for both inbound and outbound calls
* directs customers to appropriate Relationship Managers (RM) by matching customers to a relationship manager based on performance, product knowledge and customer profiles
* reduces customer's waiting time with the Automatic Call Distributor routing the call to a relationship manager that best matches and has the appropriate skill levels.
* targets potential buyers with outbound calls through automatically dialling numbers according to a customer target list generated by the system. This will allow the travel company to gain potential customers.
* has repeat customers that are satisfied with their experience with the CMC system

## SECTION 2: Stakeholders
There are three main stakeholders that have been identified. 
1. Customer: We have identified customers as a stakeholder as they are one of the most important stakeholders of any business, without them the business does not run as our main purpose is to serve our clients to the best of our ability. They become stakeholders of the company as they are interested in the service we provide and are directly impacted by the quality and value of our service. 

2. Relationship Manager: We have identified a Relationship Manager (RM) as a stakeholder as they are one of the main employees within this company. They are the ones directly providing the service to the customers through communication. They have a direct stake within the company as their interest lies in providing the best service to the customers, and through earning an income to support themselves through the company, therefore they have an effect on the effort put into the service as well as being affected by the company. 

3. Travel Company Owner: We have identified the Travel Company Owner as a stakeholder as they are the most critical stakeholder as they control the business. They are in charge of and control all the management, finances and strategy in regards to the company, making them liable for the impacts of the company. Their interest as stakeholders lies in the significant decisions they make within the company regarding both internal and external stakeholders, making their role as owner and stakeholder one of extreme importance. 


## SECTION 3: Approach from a Design Thinking Perspective

Each phase of design thinking will be analysed carefully to provide a better understanding of how the individual phases assist in reducing and resolving issues related to developing the CMC information system.  

### STEP 1.Empathise 
Allows for the understanding of the user's pain points and potential improvements that will be required to be developed to enhance the user experience. A method for approaching this phase involves the need for interacting with users and considering their viewpoint on the issue. From the interviews conducted, an empathy map was created to provide visualisation of the user's, i.e. customers as well as other stakeholders attitude and behaviours. This will assist the UX team in revealing any in the current user data and support the greater understanding of end-users. 

### STEP 2.Define 
From the data gathered, it will allow for better exploration and understanding of the core problems identified by users. The overall problem definition consists of – "A major travel company would like to develop an information system to improve the operation
of their in-house call management centre (CMC)". With these details, the system designers/developers can envision the functions, features and other elements of the system, which will assist in solving the defined problem. 

### STEP 3. Ideate
This stage is the most fundamental to the creative development associated with design thinking. By the utilisation of ideation techniques, i.e. asking "How Might We..." questions, allows for the expansion and further breakdown of the problem space and stimulates free thinking. Furthermore, the added understanding of a potential customer or other stakeholders pains and gains, the project team are able to look for alternative ways to view the problem. Additionally, the empathy maps developed in stage 1 illustrate the interviewees' pains and gains on the potential change. 

The interviewees' perspectives from the empathy map can be used as a guideline for developing "how might we" ("HMW") statements to kick start brainstorming or further ideation sessions for the project team. 

#### 3.1.1 Stakeholder 1: Customer Empathy Diagram
![image](https://user-images.githubusercontent.com/62224079/83110213-11e02780-a106-11ea-9484-20b7b202f3ee.png)

#### 3.1.2 Stakeholder 1: Customer How Might We Statement
1. How might we get the best travel package possible with minimal time/effort? 
2. How might we be serviced by someone who can meet our needs? 
3. How might we complete this booking in a timely fashion?

#### 3.2.1 Stakeholder 2: Relationship Manager Empathy Diagram
![image](https://user-images.githubusercontent.com/62224079/83110481-7d29f980-a106-11ea-9582-12c24dafbaeb.png)

#### 3.2.2 Stakeholder 2: Relationship Manager How Might We Statement
1. How might we improve our own skills to serve customers effectively and efficiently?
2. How might we improve the customers' likelihood score to purchase a product/package?
3. How might we upskill in a way that we are tracking to our performance goals? 
4. How might we improve the operation during busy times?
5. How might we improve the way we approach the customers?
6. How might we improve the operation during times of low levels of customers?
7. How might we ensure that we're able to fulfil all customers orders?
8. How might we improve the overall customer experience?

#### 3.3.1 Stakeholder 3: Travel Company Owner Empathy Diagram
![image](https://user-images.githubusercontent.com/62224079/83110323-3dfba880-a106-11ea-8e78-463981ffe38b.png)

#### 3.3.2 Stakeholder 3: Travel Company Owner How Might We Statement
1. How might we improve the operation of the the CMC?
2. How might we improve the skills of the relationship managers to serve customers effectively and efficiently?
3. How might we improve the packages available to customers? 
4. How might we ensure we have the best packages available in comparison to our competitors? 
5. How might we improve the way the relationship managers are matched with the customers?
6. How might we improve the operation during busy times?
7. How might we improve the operation during times of low levels of customers?
8. How might we ensure that we're able to fulfil all customers orders?
9. How might we improve the overall customer experience?

### STEP 4. Prototype
The prototyping stage will involve the system developers producing inexpensive, scaled-down versions of the proposed application, capturing all required features. This will be done in an iterative process by continuous check-ins with the Travel Company owner and other stakeholders to ensure the system is meeting their needs. The prototype will be tested/used by the staff of CMC to identify whether the system achieves the best possible solution for the issues acknowledged in the previous stages of this process. The system solutions which will increase efficiency by streamlining the interactions process will be highlighted within the prototype. 

### STEP 5. Testing
During the testing phase, system testers will test against user acceptance tests to ensure full functionality of the system. Future users of the system/other stakeholders will also experiment with the developed prototype. The results, driven from this stage, will allow for redefining the issue if needed and derive a full understanding of the user experience along with their conditions of use.  

### Reflections Based on Design Thinking Approach

Using the empathy maps we have as a team been able to evaluate the customer and their relationship with the RM, which allowed us to attain different perceptions of the customer and the RM. It allowed us to understand how the customer may feel and their needs and wants regarding this experience. We concluded that the customer going into this experience does not have any knowledge and is merely a curious client wanting to be given all the knowledge possible in regards to travel packages. The customer will continue to extract more information to increase their understanding and knowledge about the travel packages and what will work best for them. We have also identified the three key stakeholders within this company as being the Relationship Manager (RM), the customer and the Manager of the RM's/Company as we believe these are the main roles involved and that hold sufficient interest within the company. In regards to the prototype, we as a team will decide which possible prototype design we feel will succeed and provide us as the most breakthrough solution. Through some further brainstorming, we concluded that some solutions we could implement are collaborating with other airlines and developing sale and inventory system application.

## SECTION 4. Agile Methodology: Scrum
Agile models refers to a group of software development methodologies based on iterative development. The agile methodology that will be useful for the travel company is Scrum. ‘Scrum is an agile process that allows us to focus on delivering the business value in the shortest time.’ (Chandran 2020).  Scrum also involves a self-organising team of product owner, scrum master and development team roles. This team must adapt to changing business and technology needs and ‘accomplish the work without depending on others’. (Chandran 2020)

Through thorough consideration, each group member was assigned one of the three main roles for Scrum: 
1. Product Owner - Areeba
2. Scrum Master - Amna
3. Development Team - Patricia Ann and Ishita

After the team roles were assigned, the team followed the sequence of steps for the scrum methodology in the image below.

<p align="center">
<img src="https://user-images.githubusercontent.com/49214046/82641970-81f73500-9c50-11ea-811b-05b12c700198.png" width="800" height="400"  />
 </p>

### STEP 1: CREATE SCRUM ARTIFACT 1: PRIORTISED PRODUCT/PROJECT BACKLOG

This product backlog was made by product owner and contains user stories for each of the identified stakeholders.

#### 4.1.1  Stakeholder 1: Customer Product Backlog

Use Case ID|User | Need | Insight | Priority | Estimation |
--------|----- | ----| --------| ---------| ---------  |
C001 | Customer | I want to book a holiday| So that I travel abroad to my desired destination | High | 2 |
C002 | Customer | I want to talk to a knowledgeable Relationship Manager | So that my queries are answered  | High | 2
C003 | Customer | I want to quickly contact a Relationship Manager | So that I can know a range of holiday options available| High | 1
C004 | Customer | I want to ensure I will not miss any promotional package deals and purchase the most cost effective package | So that I can get the best package at a lower price | High | 3
C005 | Customer | I want to be purchase a package that has the shortest travel time| So that I can get more time at my destination and save travel time| High | 2
C006 | Customer | I want to have a high likelihood purchase score | So that I can be matched to the next available Relationship Manager that also has a high skill score | High | 2
C007 | Customer | I want a smooth experience from Relationship Manager | So that I can give good feedback and increase the RM skill score | Medium | 2
C008 | Customer | I want to ensure the company stores my data in a secure location | So that I do not need to worry about data breaches | Medium | 2
COO9 | Customer | I want to be matched with a relationship manager twho has the same culture as me | So that they can understand my culture and social area | Medium | 2

#### 4.1.2 Stakeholder 2: Relationship Manager Product Backlog
Use Case ID|User | Need | Insight | Priority | Estimation |
--------|----- | ----| --------| ---------| ---------  |
R001| Relationship Manager| I want to be prepared with the various packages available before discussing with customers | So that I can provide answers to customers if there are any queries | High | 2|
R002 | Relationship Manager |I want to provide correct and detailed information to the customer | So that I can sell a package | High | 1 |
R003 | Relationship Manager | I want to sell many packages as possible and serve customers effectively and efficiently | So that my performance in the skill matrix gets adjusted  | High | 1
R004 | Relationship Manager | I want to target potential buyers with outbound call with the automatically dialing system | So that the the pool of customers gets expanded| High | 1
R005 | Relationship Manager | I want to reduce the call wait times for customers | So that the customers do not provide negative feedback | High | 1
R006 | Relationship Manager | I want to be connected to customers with higher scores first| So that I can encourage quick and repeat sales |Medium |3
R007 | Relationship Manager| I want my subsequent performance score not to go low | So that I can match with more customers and answer their queries| Medium | 2
R008 | Relationship Manager | I want to be matched with a customer who has the same culture as me | So that I can understand their social and culture area | Medium | 2 
R009| Relationship Manager | I want to maintain positive/professional attitude towards customers | So that customer satisfaction is kept | Medium | 2
R010 | Relationship Manager | I want to have more professional development training| So that I can improve the selling techniques and the system can increase my performance score | Medium | 2

#### 4.1.3 Travel Company Owner Product Backlog
Use Case ID|User | Need | Insight | Priority | Estimation |
--------|----- | ----| --------| ---------| ---------  |
M001 | Travel Company Owner| I want to analyse the customers preferences for packages | So that I can create or arrange more travel packages that satisfy customer needs | High | 1
M002| Travel Company Owner| I want to hire and train relationship managers | So that they can provide the best customer service and can attend to the customer needs | High | 1
M003 | Travel Company Owner |I want to ensure that the relationship manager know how to handle different situations | So that the customer's experience is smooth and improve their skill score | High | 1 |
M004 | Travel Company Owner| I want to ensure the relationship managers are achieving the desired number of sold packages and take corrective action if required| So that the business can meet their goals and it allows for more profit| Medium | 1
M005 | Travel Company Owner| I want to constantly improve the call handling of the CMC system | So that the business can gain competitive advantage and customers stay loyal to the company| Medium | 2
M006 | Travel Company Owner| I want to reward the relationship managers with high performance | So that the relationship managers are motivated and strive to do their best with the customers | Low | 2
M007 | Travel Company Owner| I want to regularly communicate with all relationship managers through the data analytics reports | So that the business can improve and maximise efficiency of business process | Low | 2

### STEP 2:  SPRINT PLANNING AND CREATING SCRUM ARTIFACT 2: SPRINT BACKLOG

Sprint Planning involves defining the requirements for each sprint and decide forecasts based on the product backlog. This sprint meetings are run by the Scrum Master and ensure that all team members agree with the objectives and goals provided by the product owner are achieved. The team also filtered which items in the product backlog were more important and the sequence to complete all tasks. The development team also clarifies misunderstandings and plan how they can or cannot deliver specific goals.

#### SPRINT 1 BACKLOG:
* Goals of the Sprint: 
1. To add more relationship managers for the call management system => When the new relationship managers fills in a questionnaire, the answers will formulate a performance score based on their skills set.
2. Develop the relationship managers' skill set to handle various types of customers
3. Improve the call handling of the CMC system
4. Analyse customers preferences to arrange/create more packages to sell
5. To create an information system and make the business processes more efficient

* Product Backlog Items that contribute to the goal: M001, M002, M003, M004, M005, R001, R002, R003, R004, R005, R006
* Estimated Timeframes: Run for 30 days and have a maximum of 1 day to complete the planning

#### SPRINT 2 BACKLOG:
* Goals of the Sprint: 
1. To focus on customers and ensuring they are satisfied with their experience
2. To make sure relationship managers are adaptable to any situation and provide all information required to the customers
3. Incentives for relationship managers that have high performance scores
4. Improve relationship manager skills even further

* Product Backlog Items that contribute to the goal: C001, C002, C003, C004, C005, C006, R007, M006, M007
* Estimated Timeframes: Run for 30 days and have a maximum of 1 day to complete the planning

The sprints were monitored through issues with the necessary tasks to be completed. These issues were created, opened and closing when the specific assigned task has been finished. Github provided the team version control and records of all the changes made in the document. It allows the team to see how the report has modified the report, compare to previous changes and revert changes if required. 

### STEP 3: SCRUM MEETINGS

Communication and meetings between team members were performed through online Zoom Meetings and through the group chat, which is not preferable. The current situation provided difficulties in meeting the team members face to face. However, the team was able to adapt to this situation and was able to discuss their progress on project tasks for the report.  

During each meeting, project tasks were assigned to each group member to help the team iteratively work on the project within the given deadline. Moreover, the weekly team meetings enabled the team to deepen their understanding of what tasks and activities are required and to tell what roadblocks team members experienced to complete a particular task. The other team members were able to contribute their ideas for potential solutions. The team was also able to discern and openly discuss what tasks and activities were proven to be more challenging.

### STEP 4: SPRINT REVIEW and SPRINT RETROSPECTIVE

Each sprint ends with a sprint review and sprint retrospective. In the sprint review, the team analyses the product backlog and modifies it if required and make sure that incremental progress is made for each sprint. In the sprint retrospective, the team discusses the results found and determine how to make the development process better. The team evaluates what went well and what could be improved for future iterations. 

## SECTION 5: System Analysis Assumptions

### 5.1 Assumptions about the Current System: 
* Part of the team on this project consists of system designers/developers, business analysts, systems architect, system tester and system administrator
* The technique which matches RM with customers requires improvement
* Customers experience long waiting times
* Customer is created through profiler tool
* Relationship Managers are hired based on the questionnaire answers 
* Relationship Managers and Customers are matched through a segmentation technique which matches them through social and cultural segments based on postcodes and surnames
* Calls can be made or received by the customer
* Calls can be made or received by the RM

### 5.2 Assumptions about the Enhanced System:
* The travel company owner will arrange packages relationship managers will use to sell to customers
* The questionnaire Relationship Manager fill out when they get hired consists of questions to build profile and skill matrix
* The details (answers and skill matrix) of the Relationship Manager will be stored in the Relationship Manager Profiler Tool
* The Relationship Manager also has a profile which is updated after every call or interaction with a customer -> - the system adjusts the score accordingly based on subsequent performances
* The Relationship Manager profile also includes product knowledge , their rate of success and how they manage their time during a call
* All Relationship Manager will perform at the quality we expect them to in regards to timeliness and quantity
* Each Relationship Manager will fulfill all the needs of the clients
* The Relationship Manager will maintain all the system constraints and tasks which are assigned to them
* Relationship Managers and Customers are matched through a segmentation technique which matches them through social and cultural segments based on postcodes and surnames
* The customer profile will consist of all their personal details, details regarding previous purchases and their likelihood to purchase the package score
* If a customer has not used the service before, the RM will ask for their details and the profile will be created in a profiler tool
* The Customer, RM and the travel company owner can view the customer profile 
* The customers profile updates whenever they finalise or book a trip
* The target list consists of customer profiles and proposed packages that would suit them
* The target list is only used for outbound calls
* The system goals included in the analysis do not conflict with the system goals that are excluded from the analysis
* An inbound call coming from the customer will go directly to their matched RM if the CMC is not busy
* If the CMC is busy, the customer will need to wait until the next available Relationship Manager is ready
* If the matched Relationship Manager is busy the customers inbound call will get transferred to the next eligible matched RM
* When the customer makes a payment that is also updated to their customer profile
* Customers will alert their Relationship Manager when their needs are not met
* Customers also do not need to create a profile until they are about to make a purchase since they might want to get a consultation first
* If the system redirects a call to the Relationship Manager, they have a choice to accept or decline the call



## SECTION 6: Proposed Workproducts and Models

### 6.1 Use Case Diagram

A Unified Modified Language Use Case Diagram is the main form of requirements model which depicts the interactions between a user and a system. It presents an outside view of the underdeveloped system by specifying the expected behaviours of the system. A use case diagram is never extremely detailed, just showing the flow of events through capturing the functionality of each use case and its interactions with the stakeholders and other scenarios. 

![travel company owner use case diagram](https://user-images.githubusercontent.com/62224150/83340662-51815c00-a31e-11ea-84f0-3bb832f91ae6.jpeg)

The following list summarises what is in the diagram:
- The Travel Company Owner hires an employee they deem fit for the role of RM 
- The Travel company then trains the RM in order to improve their selling techniques and ensure they provide the best customer service to all customers.  
- In relation with the RM, the travel company arranges travel packages for promotional advertising 
- The Travel Company also remains in constant contact with the RM, by communicating with them through the data analytics report

## 6.1.1 Use Case ID: Hire and Train RM

|Use Case ID| M002|
| --- | --- |
|User Story | I want to hire and train relationship managers |
|Goal | So that they can provide the best customer service and can attend to the customer needs |
|Priority| High |
|Actors| Travel Company Owner, Relatioship Manager (RM) |
|Pre Conditions| Employee is interested in a job at the company |
|Post Conditions| Travel Company Owner has hired and trained a RM, Employee now has a job as a RM |
|Trigger| Employee is interested in a job at the company |
|Main Flow| 1.Employee applies for the position of RM, 2.Travel Company Owner evaluates the employees documents, 3.Travel Company Owner hires the employee for the position of RM, 4. Employee now has a job as a RM in the company, 5.The Travel Company owner trains the employee in order to be the best RM possible and provide good customer service, 6. The RM is now well trained for their job |
|Exceptions| Employee does not get hired for the role of RM within the company |
|Includes/Excludes/Inherits| M003, M004 |
|Supporting Information| None |
|Non-Functional Requirements| None |
|No Alt Flow|

![Use Case Diagram for Customer](https://user-images.githubusercontent.com/49214046/83258097-03bf0380-a1f9-11ea-955d-4919792a5585.png)
The following list summarises what is in the diagram:
- The customer creates a profile with the help of the RM, through answering a questionnaire
- The customers wants to book a holiday in order to travel abroad to their desired destination. In order to do that they wish to speak to a knowledagble RM whom can answer all their queries and concerns. Through their interest and the RM's instructions they then create a profile. This profile is created through the questionnaire in which they answer a few questions about themself. This profile can now be viewed by the customer, RM and the Travel Company Manager. 
- Communication between the customer and RM is conducted through inbound and outbound calls which are either made or received by either one of them
- The customer also wishes to be aware of any promotional packages which the RM and Travel Company owner arrange. This is enabled by the RM utilising the target list to ensure the customer receives the promotional package details every time.
- the customer depends on the target list to ensure they receive promotional packages
- The customer pays the RM when booking a trip 

## 6.1.2 Use Case ID: Inbound Call

|Use Case ID| C002|
| --- | --- |
|User Story | I want to talk to a knowledgeable Relationship Manager|
|Goal | So that I can have all my queries answered |
|Priority| High |
|Actors| Customer, Relatioship Manager (RM) |
|Pre Conditions| Customer is interested in booking a holiday destination |
|Post Conditions| Customer can purchase or book a trip as well as have a profile created by then.The profile can be viewed by the customer, RM, and the travel company owner. |
|Trigger| Customer calls company due to their interest in booking a holiday |
|Main Flow| 1.	Customer calls RM as they are interested in wanting to book a holiday or have enquiries, 2.RM receives inbound call, 3.RM attends call from customer, 4.Customer expresses interest in booking a holiday, 5. RM conducts a questionnaire with the customer regarding their personal and purchase details, 6. Customer fills out questionnaire, 7. Customer profile is created, 8. Customer presents enquiries in regards to holiday bookings, 9. RM provides the customer with holiday destination options, 10. Customer wants to book holiday (Alt Flow 1), 11. Customer pays for holiday, 12. Customer profile is updated with holiday and payment details, 13. Customer greets the RM, 14. Customer ends the call |
|Exceptions| Call drops and customer is redirected to a different RM, Amount is zero or negative,Amount is more than the available balance in the account |
|Includes/Excludes/Inherits| C001, C003, C005, C006 |
|Supporting Information| None |
|Non-functional Requirements| 
|Alternate Flow 1| 11. Customer does not want to book holiday
|Trigger| Customer is not interest in preseted information |
|Steps| re-join at step 13
|Post Conditions|
|Exceptions| 

![Use Case Diagram for RM](https://user-images.githubusercontent.com/49214046/83258142-16d1d380-a1f9-11ea-999e-acda3e8f79c7.png)
The following list summarises what is in the diagram: 
- The RM is in direct contact with the customer and provides them with correct and detailled information in order to sell as many packages as possible and earn a high skill matrix scrore through their quality customer service and positive and professional attitude they provide to each individual customer
- The RM depends on the customer to pay them when they book a trip or when they make their official payment for the trip
- The RM is in charge of arranging promotional packages through arranging travel packges with the help of the Travel Company Owner
- The RM conducts a questionnaire which the customer depends on in order to create their profile
- The RM creates a target list in order to advertise promotional packages 

## 6.1.3 Use Case ID: Package Prep before Customer inbound call

|Use Case ID| R001 |
| --- | --- |
|User Story| I want to be prepared with the various packages available before discussing with customers |
|Goal| So that I can provide answers to customers if there are any queries |
|Priority| High |
|Actors| Relationship Manager (RM), Customer |
|Pre Conditions| RM is fully trained by the Travel Company owner |
|Post Conditions| Customer will have all their queries answered |
|Trigger| Training and communication with travel company owner |
|Main Flow| 
### 6.2 Activity Diagram
A Unified Model Language Activity Diagram is another important form of behavioural requirements model, that describes the dynamic aspects of the system. It details the interactions and behaviours between different processes and stakeholders, in achieving the final outcome. An activity diagram is slightly more detailed than a Use Case Diagram, as it highlights the steps taken to achieve certain tasks, but not as detailed as a Class or Collaborative Diagram, which extract qualities and types of relationships between stakeholders.


![Activity diagram inbound](https://user-images.githubusercontent.com/62224104/83344088-dfbd0880-a345-11ea-9603-23a819893d08.jpeg)
The following list summarises what is happening in the inbound call diagram:

- A customer calls the relationship manager (RM), to book a travel package
- There is an automatic profile search of the customer, using the number they are calling with, to determine whether the customer is already in the database of the company. 
- If they are not, they must create a profile, if they already have a profile, they will automatically be assigned an RM suitable to their needs
- The two parties then discuss the suitable packages and deals
- If a customer does not want to purchase, the call ends, if they do, the call also ends, however, payments and processes continue occurring online
- Forms and payments are finalised, and finally a receipt is provided to customers for their purchase

![Activity diagram Outbound](https://user-images.githubusercontent.com/62224104/83344119-1b57d280-a346-11ea-94e2-6e816274dba5.jpeg)
The following list summarises what is happening in the outbound call diagram:

- The RM receives new package deals
- They open their target list and apply filters that ensure customers who will be interested in the deal, can be contacted 
- Once the customer list is established, RM’s call customers whom they chat with
- If customers are not interested, call ends, if they are call still ends, however those with an interest receive an email containing the package information and chat log history, and information regarding how to book travels
- RM’s customer list is updated, and they can call the next customer

![Activity diagram TC](https://user-images.githubusercontent.com/62224104/83344129-2e6aa280-a346-11ea-835c-4f34258cb7bb.jpeg)
The following list summarises what is happening between an RM and the third-party Travel Company:

- The travel company hires and trains RMs, who then practice their skills
- They are then given a list of customer profiles, whom they can use to create their initial target list
- Once list is complete, RMs receive deals on packages, which they advertise to the customers
- The ‘Off- Page Link’ refers to the inbound call system activity diagram (located above).
- The RM then emails the details of their call to the Travel Company, who then arrange packages accordingly
- Afterwards, the RM’s rating is improved and they are upskilled. They are then paid a commission based on the package sold
- The RM’s target list is updated, which alerts the Travel Company, as they can provide information to more deals to this RM.

### 6.3 Class Diagram

Unified Modified Language Class diagrams provide general overview of the schematics of an application. In this case, the class diagram help model the information system used for the project and features nine attributes namely: TravelCompanyOwner, RelationshipManager, Customer, Call, TargetList, TravelPackage, SaleItem, Match and Questionnaire. In addition, the class diagram shows the association name, aggregation and composition relationships with their respective associations multiplicity (1 to 1, 1 to 0..* and 1 to 1..*).

<img align="center">
<img src="https://user-images.githubusercontent.com/49214046/82742268-5040b400-9d9f-11ea-9640-454210e5a0e0.jpg" width="900" height="750"  />
  
 The following list summarises what is in the diagram: 
 1. Travel Company Owner hires 1 or more Relationship Manager/Relationship Managers
 2. Travel Company Owner arranges 1 or more Travel Package/Packages
 3. Relationship Manager sells 1 or more Travel Package/Packages
 4. Customer purchases 1 or more Travel Package/Packages
 5. Relationship Manager completes Questionnaire (used to create skill matrix)
 6. Relationship Manager uses TargetList (Outbound Call)
 7. Target List is composed of  1 or more Customer/Customers and  1 or more Travel Package/Packages 
 8. Customer and Relationship Manager make and receive calls (caters for Inbound/Outbound calls)
 9. Customer and Relationship Manager are matched with each other (regardless if Inbound or Outbound Call)
 10. Relationship Manager makes 0 and more Sale Item/Items
 11. Sale Item is composed of 1 or more Travel Package/Packages

### 6.4 Collaborative Diagram
Collaborative Diagrams include Object Name, Actors, Links and Messages. They are used to show how object interact and their relationships. The following diagrams represents the system during an outbound and inbound call

#### 6.4.1 Outbound Call

![Collaborative Diagram-Outbound](https://user-images.githubusercontent.com/49214046/83226959-6c40bd00-a1c6-11ea-96ad-184fea2f0e84.png)

The following list summarises the steps from the diagram:
1. The CMC system dials numbers automatically according to a customer target list generated by the system.

2.1 The system retrieves customers details from the Customer Profiler Tool Database.

2.2. The Customer Profiler Tool Database provides the requested customer details to the target list generator.

3.1  In the meantime, the system also retrieves Relationship Manager details based on skills and profile from the Relationship Manager Profiler Tool Database.

3.2  The Relationship Manager Profiler Tool Database provides the requested relationship manager details to the target list generator.

4. The target list is generated based on customer details.
5. The system displays the details 

6.1. The system also provides the Relationship Manager with guidelines and a script to help in providing an improved service to the end-customer. 

6.2 The Relationship Manager retrieves the script/guidelines and proceeds to Step 7.

7. The Relationship Manaager calls the target customer and try to sell a travel package.

#### 6.4.2 Inbound Call
![Collaborative Diagram-Inbound](https://user-images.githubusercontent.com/49214046/83257299-6f07d600-a1f7-11ea-908e-aec5c4b35088.png)

The customer calls the CMC. There are two things that happen when a customer calls using inbound method.
1. If the CMC is busy, the customer will be redirected to the Interactive Voice Response. This Interactive Voice Response will ask the customer reasons why they are calling the CMC. The customer will respond to the question. Based on the response, the Interactive Voice Response will redirect the customer to the automatic call distributor. When the customer is at this stage, they wait until there is an available Relationship Manager to attend to their needs.
2. If the CMC is not busy, the customer and relationship manager profiles are retrieved from their profiler tools. They are matched based on the segmentation technique. After, the system requests for customer likelihood purchase score and relationship manager skill score which is calculated as they are matched. The customer with very high likelihood purchase scores are redirected to the next available Relationship Manager. The Relationship Manager will attend to their needs and try to sell the travel packages.


## SECTION 7: Competitive Advantages and Adverse Effects to Business if Project Fails

Advantages:
 1. Successfully differentiating service
 
One of many competitive advantages the new information system can bring to the company is greater market share, by providing differentiated services. Reducing wait times for customers contacting a Relationship Manager (RM) and increasing the accuracy of RMs correctly matching to customers, current and potential consumers would deviate towards this company, instead of others. By capitalising on the unique feature of relationship marketing via phone, this company can reach successful milestones in the future such as company expansions and greater profits. 

 2. Reduce costs and achieve economies of scale
 
The new information system will also encourage the company to achieve economies of scales in the long run, by serving the maximum number of customers, with the lowest production costs. Pain points, such as long wait times between RM and customer allocations, and the outbound call process of RMs contacting customers, is leading to loss of productivity and profits. Improving the efficiency of the system by reducing wait times to a maximum of two minutes, will ensure customers have minimal interaction with the Interactive Voice Response Unit, which research has proven, ‘frustrates’ customers (Bitner, M.J., 2011, p.10), whilst maintaining productivity and sales. The efficient system will also reduce costs associated with electricity and specialised software and programs, as RMs will be aware of frequent travellers, who are responsive to outbound calls. 

 3. Increased shareholders profits for R&D
 
Another advantage the new system would bring to the company is greater shareholder interest and funding. A successful system would be able to generate increased profits for the company, resulting in support from shareholders, who will receive a greater dividend in return. Recognition from shareholders is vital for the company if it wants research and development to improve the current new system in the future. By consistently updating the system, the company ensures they remain at the top the industry.

Disadvantages:
 1. If the new project fails in its differentiation, there is an increased risk of losing both potentials and repeat clients. The standout feature in this company is their call management centre (CMC), which can allocate RMs to customers, based on their travel needs and purchase history. If the vital component of the new system fails, it would cause frustration amongst customers and decrease an RMs selling streak. Eventually, the longevity of the company will be compromised.

 2. Lack of economies of scale can reduce current and future potential
The failure of a new system can have a detrimental impact on the company’s cost structures and overall profits. The level of productivity the company can achieve, will not be unlocked, leading to the loss of labour and customers, as both groups divert to the competition. Attaining economies of scale is essential; otherwise, the company will struggle to reach cover costs and maintain adequate profits.

 3. Decreased shareholder trust for future projects
If the new system cannot function, there will be reduced shareholder interest and diminished certainty for the company, to regain the lost interest. Shareholders would be hesitant to reinvest in the company due to fear of loss, significantly impacting the company’s available funds. In the long term, this can negatively impact funding for research and development.

References:
1. Bitner, M.J. 2011, ‘Self- service technologies: what do customers expect?’, American Marketing Association, vol. 10, no.1, p.10.
2. Chandran, D. 2020, 'Lecture 5: Agile Scrum', UTS Online Subject 31257, lecture notes, UTS, Sydney, viewed 15 May 2020,<https://online.uts.edu.au/webapps/blackboard/content/listContent.jsp?course_id=_41893_1&content_id=_3756258_1>.

