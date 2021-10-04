## **Statement of purpose**

This project is focused to creating a web application that allows students to buy or sell or rent books. Universities tend to distribute textbooks to students for their courses every year.  In case of shortage or damaged or  other reasons, the university tends to ask students to purchase textbooks from other sources. At the end of the year, most of these books are sold on other websites after usage  or students tend to recycle them. This project focuses on allowing students to sell these books to the university for a certain percentage of the actual retail price. So that universities can reuse those books instead of buying it from other sources.

## **Overview**

The overview of the project is to develop an application that allows students to check the books they want to buy, rent, or sell from the institution. They will be given an appointment at their university library after filling out a form, where they will bring their book and sell it to the institution. These books will be displayed as a catalog. The students need to fill a form for selling the books and make an appointment where the admin can accept or reject the appointment based on the availability of the book in the library.

* At first, we would have a login page where an existing user can log-in or a user can create an account.
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

* As admin/user, they should be able to view the Home page and login page.
* As user, they should be able to see the catelog of books. 
* As user, they should be able to singup to the portal.
* As user, they are able to Buy/Sell/Rent books.

* Admin can approve/reject appointments 
* As admin, we should be able to view the admin layout 
* As admin, They should be able to see the availability of books and the ability to change the information about the database.
 
## Acceptance criteria checklist

* Home screen URL should be loaded in user-friendly format irrespective of the gadget its being used on.
* when Registration/login for the portal is registered/logged-in then it should be accessible for authorized admin and users.
* When View/buy/rent/sell options are clicked then only there respective actions must be performed.
* When admin clicks on View/Edit/Delete respective operations occur

## Schedule

![Screenshot (122)](https://user-images.githubusercontent.com/77799896/135661242-b1f5aef1-5f11-45ce-bb10-4040a7bae0d6.png)


## User interface sketches 
 #### Website Map
 ![interface Sketch](https://user-images.githubusercontent.com/77645775/135176134-8c275dc5-5484-41a6-813b-6da5033621ed.png) 
 
 ![Screenshot (35)](https://user-images.githubusercontent.com/77645775/135179577-4f8f88a6-d468-4c18-9370-a0862e014186.png)

![Screenshot (120)](https://user-images.githubusercontent.com/77799896/135568122-a7d16001-6188-40fd-b000-ec137492881f.png)


## Technology stack descriptions

### ASP.Net Core & C#
We are going to use Microsoft Visual Studio 2019 (Community verson). We are going to use ASP.Net Core and C# to write the middleware of the application. Also we will be using Razor pages for routing.

### Bootstrap
We are going to use bootstrap to create a responisve design for the application . We are also going to use Jquery, HTML , CSS to the pages .

### Microsoft SQL Server & Azure Cloud SQL database
We are going to use Entity framework SQL server to create and maintain the database on local machines. Then we are going to configure it to Azure SQL database.

### Azure Cloud Hosting
We are going to use Azure Cloud Hosting services to host the application and be able to run it on all devices.


## ER- Diagram 
![Blank diagram (3)](https://user-images.githubusercontent.com/77645775/135532612-521c4fac-633e-4939-8eda-2115c9cbb34b.png)


## Consistent Set of Sample Data
### BOOK

![image](https://user-images.githubusercontent.com/77765092/135659848-1411d43f-7c00-4613-bfe0-3cb4442abc90.png)

### User

![image](https://user-images.githubusercontent.com/77765092/135582300-1ca3d81b-55eb-4c88-aa93-17a3985dc419.png)

### Appointment

![image](https://user-images.githubusercontent.com/77765092/135582435-6144ecd3-b582-4a1c-87bc-510f2fb6c281.png)

### Purchase

![image](https://user-images.githubusercontent.com/77765092/135582525-51f2b071-18d4-4245-b6bd-55fabf8799f4.png)

### Rent Book

![image](https://user-images.githubusercontent.com/77765092/135582615-8421671a-154b-434d-8372-32630dae38d7.png)

 ### Sales 

![image](https://user-images.githubusercontent.com/77765092/135582684-3e3c5630-95f8-4aea-9074-00c6450b05ed.png)







 
## **Risks**

* Students can only sell selected books which are required by the university.
* University may not have all the books the student may require.
* If the student took rent for a particular period, they need to return the book on time.

## **Assumptions**

* Students can buy books from the library.
* Students can sell books to the library.
* Students can take books for rent from the library.
* Students can access all the above information within the application.
