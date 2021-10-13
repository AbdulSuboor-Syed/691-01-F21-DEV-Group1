## **Statement of purpose**

This project is focused to creating a web application that allows students to buy or sell or rent books. Universities tend to distribute textbooks to students for their courses every year.  In case of shortage or damaged or  other reasons, the university tends to ask students to purchase textbooks from other sources. At the end of the year, most of these books are sold on other websites after usage  or students tend to recycle them. This project focuses on allowing students to sell these books to the university for a certain percentage of the actual retail price. So that universities can reuse those books instead of buying it from other sources.

## **Overview**

The overview of the project is to develop an application that allows students to check the books they want to buy, rent, or sell from the institution. They will be given an appointment at their university library after filling out a form, where they will bring their book and sell it to the institution. These books will be displayed as a catalog. The students need to fill a form for selling the books and make an appointment where the admin can accept or reject the appointment based on the availability of the book in the library.

* At first, we would have a login page where an existing user can log-in or a sign up page where a user can create an account.
* After they have created an account . They can look  at the catelog of books to buy or rent.
* They can also sell books which they acquired from other sources and if they wish to do so they can set up an appointment which the admin can accept or reject based on the availability of the book.
* The user who is selling the book should fill out a form which gives general details about the book.
* An admin has the capacity to check the number of books available and update the database.
* The admin can also edit information about the books. 

## **Benefits**
* Students can buy or rent books easily in the library.
* This also allows the university to buy newer addition of textbooks in a short time span.
* Students who require these books for a short time period can get access easily.
 
## Epics / User Stories / Tasks
### Epics:
* Login and Authentication
* Sign Up (Personal and Gmail)
* Catelog Management
* Buy Order
* Sell Order
* Rent Order
* Appointment

### User Stories:
* As admin/user, they should be able to view the Home page and login page.
#### User Capabilities:
* As user, they should be able to see the catelog of books. 
* As user, they should be able to singup to the portal.
* As user, they are able to Buy/Rent books.
* As user, they should be able to send a request for selling a book with information.
#### Admin Capabilities:
* Admin can approve/reject appointments 
* As admin, we should be able to view the admin layout 
* As admin, They should be able to see the availability of books and the ability to change the information on database easily.
 
## Acceptance criteria checklist:

* Home screen URL should be loaded in user-friendly format irrespective of the gadget its being used on.
* when Registration/login for the portal is registered/logged-in then it should be accessible for authorized admin and users.
* When View/buy/rent is clicked then respective pages and request must respond.
* When admin clicks on View/Edit/Delete operations occur respectively.
* Buy Order or Sell Order or Rent Order must be displayed.

## Functional Requirment:
* The project should support data manupilation from the website.
* The project should be able to create unique id for every user that signs up.
* The project should display Buy order or Sell order or Rent order.
* The project should be able to display the catelog and any changes made should be implemented immediately.
* The project should have User Authentication which is secure and locks out users if they input wrong information multiple time. 

## Performance Requirement:
![Screenshot (38)](https://user-images.githubusercontent.com/77645775/136893857-8a6059cc-7d7d-4fe9-8f46-2d0183c86d1e.png)
This image shows the avergae processing speed to process request on the Azure website and avialable space for the Azure database

## Other Requrement:
* User layouts should be displayed for Users.
* Admin layouts should be displayed for Admin users.
* The project should be able to support Gmail login.
* Sell order must have a form that user must be filled out before it is displayed.




## User interface sketches 
 #### Website Map
 ![interface Sketch](https://user-images.githubusercontent.com/77645775/135176134-8c275dc5-5484-41a6-813b-6da5033621ed.png) 
 
 ![Screenshot (35)](https://user-images.githubusercontent.com/77645775/135179577-4f8f88a6-d468-4c18-9370-a0862e014186.png)

![Screenshot (120)](https://user-images.githubusercontent.com/77799896/135568122-a7d16001-6188-40fd-b000-ec137492881f.png)


## Technology stack descriptions

### ASP.Net Core(.NET 5) & C#
We are going to use Microsoft Visual Studio 2019 (Community verson). We are going to use ASP.Net Core and C# to write the middleware of the application. Also we will be using Razor pages for routing.

### Bootstrap ("twitter-bootstrap@5.1.1") & Jquery ("jquery@3.6.0")
We are going to use bootstrap to create a responisve design for the application . We are also going to use Jquery, HTML , CSS to the pages .

### Microsoft SQL Server(2018) & Azure Cloud SQL database
We are going to use Entity framework SQL server to create and maintain the database on local machines. Then we are going to configure it to Azure SQL database.

### Azure Cloud Hosting
We are going to use Azure Cloud Hosting services to host the application and be able to run it on all devices.


## ER- Diagram 

![Blank diagram (5)](https://user-images.githubusercontent.com/77645775/135913080-4ad70c23-6fcc-49cb-ab8f-31fc8b0fb152.png)



## Consistent Set of Sample Data
### BOOK

![image](https://user-images.githubusercontent.com/77765092/135946296-7f75e997-8a18-45fb-953b-d3fd449370c7.png)

### User

![image](https://user-images.githubusercontent.com/77765092/135946345-9feb2044-5a3b-40be-9208-d61e87a83ca9.png)

### Appointment

![image](https://user-images.githubusercontent.com/77765092/135946365-b57a5eb3-5d70-4929-a427-a48dffdf844c.png)

### Buying Order

![image](https://user-images.githubusercontent.com/77765092/135946430-b214b5dc-8052-4ece-ba97-5f4b51ff25df.png)

### Sale Order

![image](https://user-images.githubusercontent.com/77765092/135946500-b40014b3-c362-49a4-a8be-8e3b64b0253d.png)

### Renting Order 

![image](https://user-images.githubusercontent.com/77765092/135946536-40ddd42f-08d0-4019-8957-61bb1022e9bf.png)
 
## **Risks**

* Students can only sell selected books which are required by the university.
* University may not have all the books the student may require.
* If the student took rent for a particular period, they need to return the book on time.

## **Assumptions**

* Students can buy books from the library.
* Students can sell books to the library.
* Students can take books for rent from the library.
* Students can access all the above information within the application.


## 	Deliverable artifacts


## 	Scope:
This project has the capacity to reach a wide range of audience. This will help university to reachout to students who don't have time to come to the library and reserve the book they need. Even if they are unable to get the book from the university they could buy it from other vendors and have a chance to get a return on the retail price.

## Milestones
1. User Interfact and Web Design (User Layout & Admin Layout)
2. Routing and Request pipelining
3. Database Creation and Connection
4. Security and Error handeling
5. Testing and depolying

## Schedule
![Screenshot (122)](https://user-images.githubusercontent.com/77799896/135661242-b1f5aef1-5f11-45ce-bb10-4040a7bae0d6.png)

## Budget (as time)
| S. No. | Name                                                            | Role               | Hours/ Week | Estimated Cost/ Week |
|------|--------------------------------------------------------------------|--------------------| ------------- | ---------- |
| 1    | [Abdul Suboor syed ](https://github.com/AbdulSuboor-Syed)           |  Developer  | 9 - 15 |  $415 - $550 |
| 2    | [Hema Sree Rathnam Machha](https://github.com/HemaSreeRathnamMachha)                   |  Team Lead | 9 - 15 | $415 - $550 |
| 3    | [Himaja Parachuri](https://github.com/HimajaParachuri)                   |  Developer | 9 - 15 | $415 - $550 |
| 4    | [Chandra Bhanu Tata](https://github.com/tata1141)                   |  Tester | 9 - 15 | $415 - $550 |
|    |               |   | Material Resources  | $1500 |
|    |               |   | Total  | $3160 - $3700 |


## Test plan with requirements

## Test Deliverables before testing phase

* Test plans document.
* Test cases documents.
* Test Design specifications.

## Test deliverables are provided during the testing

* Test Scripts
* Test Data
* Test Traceability Matrix
* Error logs and execution logs.

## Test deliverables are provided after the testing cycles is over.

* Test Results/reports
* Defect Report
* Installation/ Test procedures guidelines
* Release notes
