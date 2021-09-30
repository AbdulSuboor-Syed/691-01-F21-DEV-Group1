## **Statement of purpose**

This project is focused to creating a web application that allows students to buy or sell or rent books. Universities tend to distribute textbooks to students for their courses every year.  In case of shortage of books or damaged books or for other reasons, the university tends to ask students to purchase textbooks from other sources. At the end of the year, most of these books are sold on other websites after usage where students tend to recycle them. This project focuses on allowing students to sell these books to the university for a certain percentage of the actual retail price. So that universities can reuse those books instead of buying it from other sources.

## **Overview**

The overview of the project is to develop an application that allows students to check the books they want to buy, rent, or sell them to the institution. They will be given an appointment at their university library after filling out a form, where they will bring their book and sell it to the institution. These books can be looked up based on the student details in a catalog. The students need to fill a form for selling the books and make an appointment where the admin can accept or reject the appointment based on the availability of the book in the library.
At first, we would have a login page where an existing user can log-in or a user can create an account.

* After they have created an account with their desired userID and password. They can look up books to buy/rent/checkout.

* They can also sell books they have bought from other vendors and if they wish to do so they can set up an appointment which the admin can accept or reject based on the availability of the book.

* The user who is selling the book should fill out a form which gives general details about the book.

* A user can look up books based on the name / subject / semester by year. This will be a drop-down box which would display all the books based on selected values.

## **Benefits**

* Students can buy books easily in the library.
* This also allows the university to buy newer addition of textbooks in a short time span.
* It allows students to buy or rent books easily.
* Students who require these books for a short time period can get access easily.
 
## Epics / User Stories / Tasks

* As a admin, we want to know the count of books available so that we can rent more books. 
* As a user, we should be able to signup by entering the username,password and email so that user can be able to login to the portal to Buy/Sell/Rent.
* As a user, we should be able to book an appointment so that user can Buy/Sell/Rent a book.
* As a admin, Should be able to approve/reject/reschedule appointment.
 
## Acceptance criteria checklist

* Registration and login for the portal should be accessible for admin and users.
* Users can purchase, sell and rent the books. 
* Provision for managing the appointment with the library employees for purchasing, selling or renting the books.
* Application should be user-friendly for the user.
 
## Schedule

![image](https://user-images.githubusercontent.com/77799896/135207341-93d202c4-8655-43ac-b8e7-313f4bbe482a.png)



## User interface sketches 
 #### Website Map
 ![interface Sketch](https://user-images.githubusercontent.com/77645775/135176134-8c275dc5-5484-41a6-813b-6da5033621ed.png) 
 
 ![Screenshot (35)](https://user-images.githubusercontent.com/77645775/135179577-4f8f88a6-d468-4c18-9370-a0862e014186.png)

 
![Screenshot (36)](https://user-images.githubusercontent.com/77645775/135179590-18f4d5b2-342f-4382-8365-16f73e758654.png)



## Technology stack descriptions

### ASP.Net Core & C#
We are going to use Microsoft Visual Studio 2019 (Community verson). We are going to use ASP.Net Core and C# to write the middleware of the application. We will be using Razor pages which are going to be routed using ASP.net Core and display all operations on it.

### Bootstrap
We are going to use bootstrap to create a responisve design for the application . We are also going to have Jquery, HTML , CSS to the pages .

### Microsoft SQL Server
We are going to use Microsoft SQl server to create and maintain a database for the application.

### Azure Cloud Hosting
We are going to use Azure Cloud Hosting services to host the application and be able to run it on all devices.


## ER- Diagram 
![Blank diagram (3)](https://user-images.githubusercontent.com/77645775/135532612-521c4fac-633e-4939-8eda-2115c9cbb34b.png)


## Consistent Set of Sample Data
BOOK

![image](https://user-images.githubusercontent.com/77765092/135327732-cb642ce3-46b7-4d04-8979-620649b91e61.png)

User

![image](https://user-images.githubusercontent.com/77765092/135327852-0feec287-d54b-4f31-ae40-4745649c5f5f.png)




 
## **Risks**

* Students can only sell selected books which are required by the university.
* University may not have all the books the student may require.
* If the student took rent for a particular period, they need to return the book on time.

## **Assumptions**

* Students can buy books from the library.
* Students can sell books to the library.
* Students can take books for rent from the library.
* Students can access all the above information within the application.
